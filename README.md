# custom-bootstrap-components
A collection of HTML and CSS files that recreate common Bootstrap components with custom styles. 
# Custom Bootstrap Components

This project provides a collection of HTML and CSS files that recreate common Bootstrap components with custom styles. The goal is to offer a more modular and customizable approach by separating the structure (HTML) from the styling (CSS) for each component.

## Overview

Bootstrap is a popular framework that provides pre-styled components to help developers quickly build responsive and aesthetically pleasing web interfaces. However, sometimes you might want to customize these components beyond the default Bootstrap styles. This project addresses that need by providing standalone HTML and CSS files for common Bootstrap components, allowing for easier customization and modular use.

## Components

### Navbar
- **HTML:** `navbar/navbar.html`
- **CSS:** `navbar/navbar.css`

### Forms
- **HTML:** `form/form.html`
- **CSS:** `form/form.css`

## Usage

To use these components in your project, follow these steps:

1. **Download the Component Files:**
   - Navigate to the directory of the component you want to use (e.g., `navbar` or `form`).
   - Download the corresponding HTML and CSS files.

2. **Include the CSS File in Your HTML:**
   - Add a `<link>` tag in the `<head>` section of your HTML file to include the CSS file.

3. **Include the HTML Structure:**
   - Copy the HTML structure from the downloaded HTML file and paste it into the appropriate location within your HTML file.

### Example

Here's an example of how to include the custom Navbar component in your project:

1. **Download the `navbar/navbar.css` and `navbar/navbar.html` files.**

2. **Include the CSS file in the `<head>` section of your HTML file:**
   ```html
   <!DOCTYPE html>
   <html lang="en">
   <head>
       <meta charset="UTF-8">
       <meta name="viewport" content="width=device-width, initial-scale=1.0">
       <link rel="stylesheet" href="navbar/navbar.css">
       <title>My Project</title>
   </head>
   <body>




   custom-bootstrap-components/
│
├── navbar/
│   ├── navbar.html
│   └── navbar.css
│
├── form/
│   ├── form.html
│   └── form.css
│
└── README.md

