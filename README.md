# What needs to be done

You need to convert the index.html to use reactJS

![](https://github.com/triosky/react-starterify/blob/master/assets/screen1.png)

![](https://github.com/triosky/react-starterify/blob/master/assets/screen2.png)

##Data Formats.

The predefined data is available at ***data.json***

## general requirements

* when click on edit on top left, the form (contains title, descriptions, etc) should appear.
* by default edit form for each row of expense should be hidden.
* show the edit form for expense when user hover over the row and click on edit.
* like on Send on comment textbox should trigger a POST call to /tasks/task_id/comments
* the new comment should appear at the comment thread bottom.
* user needs to be able to set save PUT request to /tasks/task_id
* saved data doesn't need to include ***form*** attribute

##form attribute

it defines how the form will look like.


##final page layout by component.

```
├── /form.jsx                     # the main form body
├── /fields/                      # directory to hold different form fields
│   ├── /expense.jsx              # the components for "field_type": "expense"
```
