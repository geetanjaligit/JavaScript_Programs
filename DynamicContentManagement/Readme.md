Dynamic Content Management
Overview
This project is a simple shopping list application that allows users to add items with a name and quantity, edit existing items, and remove items from the list. The application uses JavaScript to manipulate the DOM to achieve these functionalities.

Files
index.html: Contains the HTML structure for the shopping list application.
styles.css: Provides basic styling for the elements.
script.js: Contains the JavaScript code to handle adding, editing, and removing items from the shopping list.
HTML Structure
The HTML structure includes:

An input field for the item name.
An input field for the item quantity.
An "Add Item" button to add items to the list.
A list (unordered list) to display the shopping items.
JavaScript Code
The JavaScript file performs the following actions:

Add New Item:
Retrieves values from the input fields and adds a new item to the shopping list. Each item includes "Edit" and "Remove" buttons.
Edit Existing Item:
Allows users to modify the item's name and quantity using prompt dialogs. Updates the item's text in the list if valid data is provided.
Remove Item:
Deletes an item from the list when the "Remove" button is clicked.
Instructions
Open index.html in a web browser.
Ensure script.js and styles.css are in the same directory as index.html.
Use the input fields to add items to the shopping list.
Click "Edit" next to an item to modify its details.
Click "Remove" next to an item to delete it from the list.
JavaScript Code Explanation
addItem():
Validates input values and adds a new list item with the provided name and quantity. Creates "Edit" and "Remove" buttons for each item.
editItem(button):
Allows the user to edit the selected item's name and quantity through prompts. Updates the item in the list if new values are valid.
removeItem(button):
Removes the selected item from the list when the "Remove" button is clicked.
Usage
Adding Items:

Enter the item name and quantity in the input fields and click "Add Item" to add it to the list.
Editing Items:

Click "Edit" next to an item to change its name and quantity.
Removing Items:

Click "Remove" next to an item to delete it from the list.