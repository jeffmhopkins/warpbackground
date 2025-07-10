# Warp Starfield

A dynamic, interactive starfield simulation built with HTML5 Canvas and JavaScript. This project creates a visually engaging effect of stars moving towards the viewer, with customizable parameters such as speed, density, star size, color variation, and field of view. Users can toggle between point and tailed star shapes and adjust the perspective origin by clicking on the canvas.

Live at https://jeffmhopkins.github.io/warpbackground/

## Features

- **Interactive Controls**: Adjust speed, tail length, star density, base size, size variability, color shift, brightness variation, and field of view via sliders and a dropdown menu.
- **Dynamic Starfield**: Stars move towards the viewer with a 3D perspective effect, resetting when they reach the viewer.
- **Star Shape Options**: Choose between "Point (Circle)" and "Line (Tailed)" star shapes.
- **Customizable Origin**: Click anywhere on the canvas to set the perspective origin point.
- **Responsive Design**: Adapts to window resizing for a seamless experience across devices.
- **Hideable Menu**: Toggle the control menu to maximize viewing area.

## Getting Started

### Prerequisites

- A modern web browser (e.g., Chrome, Firefox, Safari, Edge).

### Installation

1. Clone or download the repository to your local machine.
2. Open the `index.html` file in a web browser.

No additional dependencies or setup are required, as the project runs entirely in the browser using vanilla JavaScript and HTML5 Canvas.

## Usage

1. Open `index.html` in a web browser.
2. Use the control panel to adjust:
   - **Speed**: Controls how fast stars move towards the viewer (0.1 to 15).
   - **Tail Length**: Sets the length of star tails (0 to 50, disabled for point stars).
   - **Density**: Number of stars displayed (50 to 5000).
   - **Base Size**: Base size of stars (0.05 to 5).
   - **Size Variability**: Variation in star sizes (0 to 2).
   - **Color Shift**: Variation in star colors (0 to 2).
   - **Brightness Variation**: Variation in star brightness (0.1 to 2).
   - **Field of View**: Perspective zoom level (0.1 to 3).
   - **Star Shape**: Select "Point (Circle)" or "Line (Tailed)" from the dropdown.
3. Click the canvas to set the perspective origin.
4. Click the "Hide Menu" button to toggle the visibility of the control panel.

## Limitations

- High density values (e.g., >2000) may impact performance on lower-end devices.
- The tail length slider is disabled when the "Point (Circle)" star shape is selected, as it does not apply.

## License

This project is licensed under the MIT License. Feel free to use, modify, and distribute it as needed.
