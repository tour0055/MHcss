# MHcss
# NovaCSS

## Description

NovaCSS is a custom CSS framework created using Sass. It provides a simple, modern, and consistent design for standard HTML elements. The framework also includes utility classes that make it easier to style webpages without writing additional CSS.

## Features

NovaCSS includes styling for:

- Headings and paragraphs
- Links and lists
- Buttons
- Forms and inputs
- Tables
- Text and background colors
- Font sizes and font weights
- Margin and padding
- Borders

## Installation

1. Download or clone this GitHub repository.
2. Add the compiled `framework.css` file to your project.
3. Link the CSS file inside the `<head>` of your HTML page:

```html
<link rel="stylesheet" href="css/framework.css">
```

## Usage

After linking the framework, you can use NovaCSS classes in your HTML.

Example:

```html
<button class="btn btn-primary">Click Me</button>

<p class="text-primary fw-bold">
  Welcome to NovaCSS!
</p>

<div class="p-3 m-2 border">
  Example using spacing and border utilities.
</div>
```

## Customization

NovaCSS uses Sass variables to make the framework easy to customize.

Variables can be changed inside:

```text
scss/_variables.scss
```

For example:

```scss
$primary-color: #6c63ff;
$secondary-color: #333333;
$font-family: Arial, sans-serif;
$border-radius: 6px;
```

After changing the variables, compile `main.scss` again to generate the updated `framework.css`.

## Sass Structure

```text
scss/
├── main.scss
├── _variables.scss
├── _base.scss
├── _buttons.scss
├── _forms.scss
├── _tables.scss
└── _utilities.scss
```

## Team Members

- Hiba Bouzid
- Mamadou Toure

## Technologies Used

- HTML5
- CSS3
- Sass
- Git
- GitHub