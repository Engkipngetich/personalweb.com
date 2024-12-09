# Shopping List Application

## Overview
This is a simple shopping list application that allows users to add, mark as purchased, edit, and clear items from a shopping list.
The application also persists the list items using local storage, so the list remains intact even after the page is refreshed.

## Features
- Add new items to the shopping list.
- Mark items as purchased, which visually updates the item.
- Clear the entire list.
- Edit existing list items.
- Persistent storage using local storage.

## HTML Structure
The HTML file should include:
- An input field for adding items.
- Buttons for "Add", "Mark Purchased", and "Clear List".
- An unordered list (`<ul>`) to display the items.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shopping List</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>Shopping List</h1>
        <input type="text" id="itemInput" placeholder="Add a new item">
        <button id="addItemButton" class="btn-add">Add</button>
        <button id="markPurchasedButton" class="btn-purchased">Mark Purchased</button>
        <button id="clearListButton" class="btn-clear">Clear List</button>
        <ul id="itemList"></ul>
    </div>
    <script src="app.js"></script>
</body>
</html>
