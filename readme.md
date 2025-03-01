Flow of Execution – To-Do List

HTML Structure Initialization

The <!DOCTYPE html> declaration specifies that the document is an HTML5 file.
The <html> element contains the entire document structure.
The <head> section includes metadata, styles, and the title of the page.
The <body> section contains the UI elements required for the To-Do List.

CSS Styling (User Interface Design)

The .container class styles the to-do list box, including width, background color, and shadow effects.
The <input> field is styled for a clean and modern look.
The <button> elements have different styles for "Add Task" and "Delete" actions.
The <ul> list styles ensure the task items appear neatly with space and alignment.

JavaScript Execution (Dynamic Functionality)

The script waits for the Add Task button to be clicked.
When clicked:
Retrieves the text from the input field and trims any extra spaces.
If the input is not empty, a new <li> element (task item) is created.
A Delete button is appended to each new task.
The task is added to the <ul> list dynamically.
The input field is cleared after adding the task.
Each Delete button has an event listener that removes the corresponding task when clicked.
Error Handling & Edge Cases

The script prevents empty tasks from being added by checking if the input is empty.
When the delete button is clicked, only the corresponding task is removed.