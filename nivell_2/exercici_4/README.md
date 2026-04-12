# Exercise 4: Japan Tourism Header

This project focuses on advanced CSS layout techniques and the integration of graphic resources to transform a basic responsive structure into a themed header for a Japan Tourism website.

## Objectives
*   Replace standard color blocks with high-quality graphic assets.
*   Implement a responsive header using Flexbox and background image properties.
*   Integrate inline SVG icons for navigation and social media.
*   Apply interactive hover states (roll-over effects).
*   Create a semi-transparent banner for key messaging.

## Technical Features
- **SVG Integration**: Inline SVGs are used for menu icons (Home, Routes, Hotels, etc.) and social media (Facebook, Twitter) to ensure high resolution and easy styling via CSS.
- **Interactive Links**: All clickable elements feature a smooth transition using the `:hover` pseudo-class, changing both text and SVG `fill` colors.
- **Graphic Banner**: A centered box with `rgba` background-color to create a semi-transparent "glass" effect over the background image.
- **Typography**: Implements specific font families (`Georgia` for the banner, `Arial` for navigation) as per the design requirements.

## Structure
- `index.html`: Contains the structural semantic HTML5 and inline SVG definitions.
- `style.css`: Manages the responsive layout, flexbox containers, and visual effects.
- `/images`: Contains the `torii_gate.png` background and the project favicon/logo.

## How to Run
1. Clone the repository.
2. Navigate to `nivell_2/exercici_4/`.
3. Open `index.html` in any modern web browser.
