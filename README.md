# City Skyline

This project is a simple HTML and CSS exercise that replicates a city skyline, based on a project from [freeCodeCamp.org](https://www.freecodecamp.org/). The skyline includes both background and foreground buildings of various shapes and sizes, with details such as windows and rooftops.

## Project Structure

### HTML

The `index.html` file contains the basic structure of the page. It is divided into two main sections:
- **Background buildings**: The buildings in the background.
- **Foreground buildings**: The buildings in the foreground.

### CSS

The `styles.css` file is responsible for styling the page. It uses CSS variables to define the colors of the buildings and windows, as well as to create different styles for each building.

### CSS Variables

- `--building-color1`: Color for the background buildings.
- `--building-color2`: Color for medium-sized buildings.
- `--building-color3`: Color for the foreground buildings.
- `--building-color4`: Color for rooftops and structural elements.
- `--window-color1`: Window color for buildings with `--building-color1`.
- `--window-color2`: Window color for buildings with `--building-color2`.
- `--window-color3`: Window color for buildings with `--building-color3`.
- `--window-color4`: Window color for buildings with `--building-color4`.

### Animation and Layout

- **Sky Background**: The background is styled with a radial gradient representing the sky, transitioning from a yellow hue to light blue, mimicking sunrise or sunset.
- **Background Buildings**: These are styled with lighter colors and simpler shapes to simulate distance.
- **Foreground Buildings**: These have darker colors and more complex details, appearing closer to the viewer.

### Media Queries

The project includes a media query for screens under 1000px wide, changing the color palette to shades of gray and black to simulate a nighttime scene.

## How to Run the Project

1. Clone or download this project.
2. Open the `index.html` file in a web browser.

## Contributions

Any contributions are welcome. Please fork the project and submit a pull request with your suggestions.

---

This project is part of the curriculum on [freeCodeCamp.org](https://www.freecodecamp.org/), designed to help learners practice HTML and CSS by building a simple and stylized city skyline.
