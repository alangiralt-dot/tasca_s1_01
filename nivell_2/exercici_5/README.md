# Exercise 5: Japan Tourism Article Grid

This exercise builds upon the Japan Tourism theme, focusing on creating a dynamic and professional content area using CSS Grid and Flexbox. The goal was to transform basic placeholders into rich article cards.

## Objectives
*   Implement a responsive grid of article cards.
*   Use advanced CSS positioning for UI elements (dates over images).
*   Utilize modern CSS text layout properties (multi-column text).
*   Maintain a unified responsive design across mobile, tablet, and desktop viewports.

## Technical Features
- **Article Cards**: Each card is a structured container including an image, a category title, descriptive text, and a footer link.
- **Absolute Date Positioning**: Used `position: relative` on image containers and `position: absolute` on date tags to overlay metadata directly onto the graphics.
- **Multi-column Layout**: Implemented `column-count: 2` and `column-gap` in the article descriptions to mimic a professional editorial/magazine style.
- **Semantic HTML5**: Utilized descriptive class names and structured div nesting for better accessibility and SEO.
- **Color Palette Integration**: Applied a consistent color scheme (Light Coral, Light Grey, and Charcoal) to ensure visual harmony with the Exercise 4 header.

## Project Assets
- `sakura.jpg`: Culture article image.
- `comida.jpg`: Gastronomy article image.
- `fuji.jpg`: Tourism article image.
- `noche.jpg`: Nightlife article image.

## How to Run
1. Navigate to the `nivell_2/exercici_5/` directory.
2. Open `index.html` in your browser.
3. Observe how the grid adjusts from a single column (Mobile) to a complex layout (Desktop).
