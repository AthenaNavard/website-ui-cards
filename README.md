# CARDS - Responsive Gallery

A responsive, card-based gallery page created with HTML and CSS. The project presents six colorful cards with different layouts, images, icons, descriptions, and responsive behavior for mobile screens.

## Preview

The page includes a dark background, a centered `CARDS` heading, and a responsive grid of six visually distinct cards.

## Features

- Responsive card gallery layout
- CSS Grid layout for desktop screens
- Flexbox-based vertical layout on mobile screens
- Six cards with different colors, sizes, and visual styles
- Hover animation on cards
- Responsive `Read More` buttons on smaller screens
- Remix Icon integration through CDN
- Image-based card designs using local assets
- No JavaScript or build tools required

## Technologies

- HTML5
- CSS3
- CSS Grid
- Flexbox
- Remix Icon CDN

## Project Structure

```text
project-folder/
├── index.html
├── style.css
└── assets/
    ├── image/
    │   ├── Icon.png
    │   ├── Vector.png
    │   ├── Group.png
    │   └── hand.jpg
    └── css/
        └── style.css
```

> Make sure the paths used in `index.html` match the actual location of your CSS and image files. The current HTML references the stylesheet through `assets/css/style.css`.

## Getting Started

### 1. Clone or download the project

Download the project files or clone the repository from GitHub.

### 2. Check the file paths

Confirm that `index.html`, the CSS file, and the image assets are located according to the project structure above. If `style.css` is in the project root, update the stylesheet link in `index.html`:

```html
<link rel="stylesheet" href="style.css" />
```

### 3. Open the page

Open `index.html` directly in a web browser. No installation, server, or package manager is required.

For a better development workflow, open the project with VS Code and use the Live Server extension.

## Responsive Behavior

On screens wider than `768px`, the cards are displayed in a four-column CSS Grid layout.

On screens up to `768px` wide:

- The grid changes to a vertical layout.
- Card content is mostly centered.
- The cards are displayed one below another.
- The arrow links on cards 3 and 5 become `Read More` buttons.
- Images and text are resized for smaller screens.

## Card Layouts

- Cards 1 and 6: tall cards with large icons
- Cards 2 and 4: vertical image cards
- Cards 3 and 5: wide gradient cards with arrow links
- Cards use red, green, pink, white, yellow, and gradient color schemes

## External Dependency

The project uses Remix Icon from a CDN. An internet connection may be required for the icons to load:

```html
<link
  href="https://cdn.jsdelivr.net/npm/remixicon@..."
/><!-- Remix Icon CDN -->
```

## Learning Goals

This project was created to practice:

- Structuring a web page with semantic HTML
- Building responsive layouts with CSS Grid and Flexbox
- Styling reusable cards
- Using CSS hover effects and transitions
- Managing images and external icon libraries
- Creating a mobile-friendly interface

## Author

**Atena Razeghi**

Created as a front-end gallery project and HTML/CSS practice exercise.
