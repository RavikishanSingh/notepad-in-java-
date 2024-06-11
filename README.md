# Simple Notepad Application

## Overview
This is a simple notepad application implemented in Java using Swing for the GUI components. It supports basic file operations such as creating a new file, opening an existing file, saving the current file, and saving the file with a new name.

## Features
- **New File**: Clears the text area for a new document.
- **Open File**: Opens and reads a file, displaying its content in the text area.
- **Save File**: Saves the current text to a file.
- **Save As**: Saves the current text to a new file.

## Requirements
- Java Development Kit (JDK) 8 or later.

## Installation
1. Ensure you have JDK 8 or later installed on your machine.
2. Download the `notepad.java` source file to your local directory.

## How to Run
1. Open a terminal or command prompt.
2. Navigate to the directory where the `notepad.java` file is located.
3. Compile the Java file using the following command:
    ```bash
    javac notepad.java
    ```
4. Run the compiled Java program using:
    ```bash
    java notepad
    ```

## Usage
### New File
- Click on `File` in the menu bar.
- Select `New` to clear the text area for a new document.

### Open File
- Click on `File` in the menu bar.
- Select `Open` to open a file chooser dialog.
- Choose the file you want to open. The content of the file will be displayed in the text area.

### Save File
- Click on `File` in the menu bar.
- Select `Save` to open a file chooser dialog.
- Choose the location and name of the file to save the current text.

### Save As
- Click on `File` in the menu bar.
- Select `Save As` to open a file chooser dialog.
- Choose the location and name of the new file to save the current text.

## Code Structure
- **Main Class**: `notepad`
  - Initializes the GUI components.
  - Sets up action listeners for menu items.
  - Defines the main frame and its components.

### Key Components
- **JFrame**: The main window.
- **JTextArea**: The text area where the content is written.
- **JMenuBar**: The menu bar containing the file menu.
- **JMenu**: The file menu.
- **JMenuItem**: Menu items for new, open, save, and save as actions.
- **JFileChooser**: Used for file operations (open, save).

## Contributing
If you find any issues or have suggestions for improvements, please create a pull request or submit an issue on the repository.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

**Note**: The application is intended for educational purposes and may not cover all edge cases or handle errors extensively. Use and modify it as needed.
