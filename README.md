# EZ Ladder ST Extension for VS Code

Welcome to the **EZ Ladder Structured Text (ST) Extension** for Visual Studio Code! This extension provides syntax highlighting, IntelliSense, and other essential tools for working with EZ Ladder ST, which is based on Pascal but includes specific differences tailored for EZ Ladder programming. This extension will make writing, debugging, and navigating EZ Ladder code more efficient and enjoyable.

## Features

- **Syntax Highlighting**: Provides complete syntax highlighting for EZ Ladder ST, including:
  - Keywords (`IF`, `THEN`, `ELSE`, etc.)
  - Data Types (`BOOL`, `REAL`, `INT`, etc.)
  - Operators (`+`, `-`, `/`, `AND`, `OR`, etc.)
  - Assignment Operators (`:=`)
  - Built-in Functions (`ABS`, `MAX`, `MIN`, etc.)
  - Comments, Strings, Constants, and Custom Data Types

- **IntelliSense**: Autocomplete suggestions for common EZ Ladder keywords, functions, and data types, providing a more productive coding experience.

- **Custom Highlighting for Operators**: Special color highlighting for assignment (`:=`) operator to make code clearer and more readable.

- **Supports `.ezl` Files**: Automatically associates `.ezl` files with the EZ Ladder language mode for easy usage.

## Installation

To use this extension locally:

1. **Package the Extension**:
   - Run `vsce package` in your extension folder to create a `.vsix` file.

2. **Install the Extension**:
   - Open VS Code and go to the Extensions pane.
   - Click the three dots (`...`) in the top right and choose "Install from VSIX...".
   - Select the `.vsix` file to install.

## Usage

Once installed, open any `.ezl` file in VS Code to start using the extension. You will see:

- **Syntax Highlighting** for EZ Ladder ST code.
- **IntelliSense Suggestions** as you type keywords, functions, and other EZ Ladder-specific code elements.

## Language Support

This extension adds support for the following features:

- **Keywords**: Control flow statements like `IF`, `FOR`, `WHILE`, and more.
- **Data Types**: Native data types such as `BOOL`, `INT`, `REAL`, `STRING`, etc.
- **Built-in Functions**: Common functions such as `ABS`, `MIN`, `MAX`, `SIN`, etc.
- **Assignment Operator**: Custom coloring for the `:=` operator to help differentiate assignment from other operations.
- **Comments and Strings**: Proper highlighting for block comments (`(* ... *)`) and string literals.

## Contributing

Feel free to submit issues or pull requests on the [GitHub repository](#) to contribute to the development of the EZ Ladder ST extension.

### Development Setup

- Clone the repository.
- Run `npm install` to install dependencies.
- Make changes and use `vsce package` to generate the updated `.vsix` file.

### Known Issues

- Syntax coloring may conflict with certain VS Code themes, like Monokai. Consider customizing your theme's settings for the best experience.
- IntelliSense is currently limited to basic keywords and functions. Full language server support is planned for future releases.

## Release Notes

### 1.0.0
- Initial release with syntax highlighting and basic IntelliSense.
- Custom color highlighting for assignment operators.
- Support for `.ezl` file association.

### 1.1.0 (Planned)
- Enhanced IntelliSense with function argument hints.
- Basic error checking for common mistakes in EZ Ladder ST.

## Feedback

Your feedback is very valuable! Feel free to [open an issue](#) with your suggestions, bug reports, or feature requests.

## License

This extension is licensed under the [MIT License](#).

Enjoy coding with EZ Ladder ST!