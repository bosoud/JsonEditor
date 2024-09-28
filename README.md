# JSON Editor

This is a simple web-based JSON editor that allows users to load, view, edit, and save JSON files. It provides an intuitive tree structure for navigation and a separate editor for modifying the JSON data. Additionally, the tool allows users to copy the entire JSON data to the clipboard.

## Features

- Load JSON files into a navigable tree structure.
- Edit JSON data in a user-friendly interface.
- Save modified JSON files with proper data types (string, number).
- Copy the entire JSON content to the clipboard.
- Shows notifications/messages for actions like saving and copying.

## Installation and Setup

No installation is required. Simply download the files and open `DashboardJSON.html` in your web browser.

### Steps:

1. Clone or download the project.
2. Open the `DashboardJSON.html` file in any modern web browser (Chrome, Firefox, Safari, Edge).

## Usage

### Loading a JSON File

1. Click the **Choose File** button in the "شجرة JSON" (JSON Tree) section.
2. Select a valid `.json` file from your computer.
3. The JSON file's content will be displayed as a tree in the sidebar.

### Editing JSON Data

1. Click on any item in the JSON tree to display its properties in the editor on the right.
2. For each editable field:
    - Edit the text in the provided `textarea`.
    - Use the dropdown next to the field to specify whether the value is a string or a number.
3. Once you're done editing, click the **حفظ التعديلات** (Save Changes) button.
4. A link will appear allowing you to download the updated JSON file.

### Copying the Entire JSON

1. Click the **نسخ كل JSON** (Copy All JSON) button.
2. A message will confirm that the entire JSON data has been copied to the clipboard.

## Notes

- The tool supports string and number data types. When editing, you can specify whether the value should be treated as a number or text.
- The tool automatically limits the description field to 50 characters in the tree view for better readability.
- Messages for successful save or copy operations will appear on the page and disappear after a few seconds.

## License

This project is open-source and free to use. Feel free to modify it to suit your needs.

## Contributions

Contributions are welcome! If you'd like to add new features, report bugs, or improve the code, please submit a pull request or open an issue on the project's repository.

