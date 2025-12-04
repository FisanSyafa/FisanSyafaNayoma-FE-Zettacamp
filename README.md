# Zettabyte Front End Developer Coding Challenge

This repository contains the source code submission for the Zettabyte Front End Developer technical assessment. The project involves recreating a specific "Simple Pricing" User Interface using HTML and CSS, adhering to the visual design and functional requirements provided in the challenge description.

## Project Description

The objective of this project was to convert a static design reference into a functional web page. The solution focuses on accurate layout structure, proper CSS styling, and interactivity using vanilla JavaScript.

## Features implemented

Based on the requirements, the following features have been implemented:

1.  **UI Reproduction**
    The pricing layout has been recreated to match the reference image, including typography, colors, and the specific negative margin layout where cards overlap the header section.

2.  **Card Hover Effect**
    Hovering over any pricing card triggers a zoom transformation (scale effect) to provide visual feedback to the user.

3.  **Buy Now Interaction**
    Clicking the "BUY NOW" button triggers a browser alert with a success message, preventing the click event from bubbling up to the card container.

4.  **Selection Logic**
    Clicking anywhere on a pricing card toggles its state to "Selected". Visual indicators (border highlighting) are applied to the currently selected card, while ensuring only one card can be selected at a time.

## Technologies Used

* **HTML5:** Semantic markup structure.
* **CSS3:** Styling, layout (Flexbox), and transitions/animations.
* **JavaScript:** DOM manipulation for handling click events and state management.

## Installation and Usage

Since this project uses static web technologies, no build process or package manager is required.

1.  Clone the repository:
    ```bash
    git clone [https://github.com/FisanSyafa/FisanSyafaNayoma-FE-Zettacamp.git](https://github.com/FisanSyafa/FisanSyafaNayoma-FE-Zettacamp.git)
    ```

2.  Navigate to the project directory.

3.  Open the `index.html` file directly in any modern web browser (Chrome, Firefox, Edge, Safari) to view the result.

## File Structure

* `index.html`: The main entry point containing the HTML structure and necessary JavaScript logic.
* `style.css`: The stylesheet containing all visual styles, responsive rules, and animation definitions.

## Author

Fisan Syafa Nayoma
