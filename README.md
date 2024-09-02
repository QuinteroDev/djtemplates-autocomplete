# DJTemplates-Autocomplete

## Description

**DJTemplates-Autocomplete** is a Visual Studio Code extension that provides autocomplete for common Django template tags and filters. This extension is designed for developers working with Django, making it faster and easier to write template code.

## Features

- Snippets for Django blocks like `{% block %}`, `{% endblock %}`.
- Autocomplete for conditional statements like `{% if %}`, `{% else %}`, `{% endif %}`.
- For loop autocomplete for `{% for %}`, `{% endfor %}`.
- Autocomplete for tags like `{% url %}`, `{% static %}`, `{% include %}`.
- Easy to use in any `.html` or `.djhtml` file containing Django templates.

## Installation

1. **From the Visual Studio Code Marketplace**:
   - Open Visual Studio Code./
   - Go to the Extensions view (`Cmd + Shift + X` on Mac).
   - Search for "DJTemplates-Autocomplete" and install it directly from the Marketplace.

2. **Install from a `.vsix` file** (Local):
   - If you have the `.vsix` file, you can install it directly in VSCode:
     - Open VSCode.
     - Go to the Extensions view.
     - Click on the three dots (`...`) and select **Install from VSIX...**.
     - Select the `.vsix` file for DJTemplates-Autocomplete.

## Usage

After installing the extension, simply open any `.html` or `.djhtml` file in VSCode. The following snippets will be available:

### Available Snippets

- **Django Block (`{% block %}`)**:
  - **Prefix**: `djblock`
  - **Description**: Creates a Django block.
  
- **If Statement (`{% if %}`)**:
  - **Prefix**: `djif`
  - **Description**: Creates a Django `if` statement.
  
- **If-Else Statement (`{% if-else %}`)**:
  - **Prefix**: `djifelse`
  - **Description**: Creates a Django `if-else` statement.
  
- **For Loop (`{% for %}`)**:
  - **Prefix**: `djfor`
  - **Description**: Creates a Django `for` loop.
  
- **URL Tag (`{% url %}`)**:
  - **Prefix**: `djurl`
  - **Description**: Creates a Django `url` tag.
  
- **Static Tag (`{% static %}`)**:
  - **Prefix**: `djstatic`
  - **Description**: Creates a Django `static` tag.
  
- **Include Template (`{% include %}`)**:
  - **Prefix**: `djinclude`
  - **Description**: Includes another template in Django.

- **Load Static (`{% load static %}`)**:
  - **Prefix**: `djloadstatic`
  - **Description**: Loads static files in Django.

- **Extends Template (`{% extends %}`)**:
  - **Prefix**: `djextends`
  - **Description**: Extends a base template in Django.

- **Comment (`{% comment %}`)**:
  - **Prefix**: `djcomment`
  - **Description**: Adds a comment block in Django.

- **Load Custom Tags (`{% load custom tags %}`)**:
  - **Prefix**: `djloadcustom`
  - **Description**: Loads custom template tags in Django.

## Contributions

Contributions are welcome! If you have ideas for improving the extension or want to add more snippets, feel free to open an issue or submit a pull request on [GitHub](https://github.com/QuinteroDev/djtemplates-autocomplete).

## License

This extension is licensed under the MIT License. For more details, see the `LICENSE` file.

---

Thank you for using **DJTemplates-Autocomplete**! I hope this extension helps you be more productive in your Django development.