# Embracing Responsive Design: Media Queries and More

In the evolving landscape of web development, one principle remains crucial: a website must provide an optimal viewing experience across a wide array of devices. This principle is the foundation of responsive web design.

## Required YouTube Videos
- [Master Media Queries And Responsive CSS Web Design Like a Chameleon!](https://www.youtube.com/watch?v=K24lUqcT0Ms)
- [The secret to mastering CSS layouts](https://www.youtube.com/watch?v=vHuSz4fRM88)

## Responsive Web Design

Responsive web design is the approach that suggests design and development should respond to the user's behavior and environment based on screen size, platform, and orientation. Essentially, it wraps together flexible layouts, images, CSS media queries, and sometimes also flexbox and grid layouts. 

In the given project, we have used a combination of flexible grids (using Flexbox and CSS Grid), media queries, and CSS variables to create a layout that works well on a variety of screen sizes.

## Media Queries

Media queries are a cornerstone of responsive design. They allow CSS to apply styles based on various parameters, such as viewport width, screen resolution, or device orientation. In essence, media queries let us adapt the presentation of web content for different devices.

### Media Queries for Narrow Screens

In our project, we have used media queries to adjust the layout for narrow screens. Below is an example:

```css
@media (max-width: 768px) {
    body {
        background: none;
    }
    
    .container {
        flex-direction: column;
        margin: 0 auto;
        padding: 0;
        width: 100%;
    }

    .sidebar {
        order: -1;
        height: 100vh;
        overflow-y: auto;
    }

    .main-content {
        padding-top: 1rem;
    }
}
```

The `@media` rule is followed by the condition `(max-width: 768px)`. This means that the enclosed styles will apply when the width of the viewport is 768 pixels or less.

In this particular case, when the viewport width drops below 768 pixels, the layout shifts from a row to a column layout (`flex-direction: column`), and the sidebar moves to the bottom (`order: -1`). These adjustments make the layout more suitable for narrower screens, like on mobile devices.

### Media Queries for Print

Media queries can also target printed documents. This is beneficial when you want to style a document specifically for printing. For instance, you may want to change the font sizes, hide certain elements, or alter the color scheme to be more print-friendly.

Here's an example from the project:

```css
@media print {
    /* Reset */
    *,
    *::before,
    *::after {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }

    body {
        font-family: "Times New Roman", serif;
        color: #333;
    }

    .container {
        flex-direction: column;
        margin: 0.1rem;
    }

    /* other styles omitted for brevity */

    .links,
    h1,
    .portrait {
        display: none;
    }
}
```

In this media query, the condition is `print`, which means the enclosed styles will be applied when the document is being printed. Among other adjustments, the font is changed to a more print-friendly font, certain elements are hidden to save ink (`display: none`), and the layout is optimized for a print format.
