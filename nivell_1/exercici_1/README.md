# Exercise 1: Unified Responsive Layout

This exercise has been upgraded to a fully responsive "all-in-one" solution. It uses a single stylesheet to adapt the layout across Mobile, Tablet, and Desktop devices.

## Features
* **Mobile-First:** Base styles are optimized for small screens using Flexbox.
* **Tablet View:** A media query at `700px` activates a CSS Grid layout for the articles.
* **Desktop View:** A media query at `1120px` switches the main structure to a horizontal layout with a `1200px` max-width constraint.
* **UI Cleanliness:** Includes cross-browser CSS rules to hide scrollbars for a cleaner aesthetic.

## Technical Stack
* **HTML5** (Semantic structure)
* **CSS3** (Flexbox & CSS Grid)
* **JavaScript** (Width-check utility for testing)
