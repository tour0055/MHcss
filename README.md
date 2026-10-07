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

After linking the framework, you can use NovaCSS classes directly in your HTML.

### Button Example

```html
<button class="btn btn-primary">Primary Button</button>
<button class="btn btn-secondary">Secondary Button</button>
```

### Text Example

```html
<p class="text-primary fw-bold">
  Welcome to NovaCSS!
</p>
```

### Spacing and Border Example

```html
<div class="p-3 m-2 border rounded">
  Example using spacing and border utilities.
</div>
```

## Customization

NovaCSS uses Sass variables to make the framework easy to customize.

The variables can be changed inside:

```text
scss/_variables.scss
```

For example:

```scss
$primary: #6c63ff;
$secondary: #6c757d;
$font-family: Arial, Helvetica, sans-serif;
$border-radius: 8px;
```

Change these values to customize the colors, typography, and appearance of the framework.

After changing the variables, compile `main.scss` again to generate an updated compiled CSS file.

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

The Sass partials separate the framework into different components to keep the code organized and easy to maintain.

## Compiled CSS

The compiled version of the NovaCSS framework is located at:

```text
css/framework.css
```

This file can be linked directly to an HTML project without requiring Sass.

## Utility Classes

NovaCSS provides utility classes for common styling needs, including:

- Text colors
- Background colors
- Font weight
- Font size
- Margin
- Padding
- Borders
- Border radius
- Text alignment

Example:

```html
<div class="bg-primary text-white p-3 m-2 rounded">
  Styled with NovaCSS utility classes.
</div>
```

## Demo

The `index.html` file provides examples of NovaCSS components and utilities, including typography, lists, buttons, colors, forms, tables, spacing, and borders.

## Team Members

- Hiba Bouzid
- Mamadou Toure

## Technologies Used

- HTML5
- CSS3
- Sass
- Git
- GitHub
