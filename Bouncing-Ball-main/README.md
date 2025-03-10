
# Bouncing-Ball
This repository contains the code for a simple animation of a bouncing ball inside a rectangular canvas.

### Features

* The ball bounces realistically off the edges of the canvas.
* The animation runs smoothly using `requestAnimationFrame`.

### Code Structure

* `index.html`: This file defines the basic HTML structure and includes the `animation.js` script.
* `animation.js`: This file contains the JavaScript code for animating the bouncing ball.

**Explanation**

The code utilizes the following concepts:
- **HTML:**
   - `<!DOCTYPE html>`: Declares the document type as HTML.
   - `<html>`: The root element of the HTML document.
   - `<head>`: Contains meta information about the document.
   - `<body>`: Contains the visible content of the web page.
   - `<canvas>`: Creates an element where the bouncing ball animation will be rendered.
   - `<script>`: Includes the animation script (`animation.js`).
 
- **JavaScript:**
* **Variables:**
    * `canvas`: Reference to the HTML canvas element.
    * `context`: 2D rendering context of the canvas.
    * `speed`: Defines the ball's movement speed (pixels per frame).
    * `position`: Tracks the ball's horizontal position on the canvas.
    * `moveSpeed`: Stores the ball's current movement direction (positive or negative).
    * `radius`: Defines the ball's radius.
* **Functions:**
    * `moveBall()`: Updates the ball's position based on its speed and checks for collisions with the canvas edges. It reverses the movement direction if the ball hits an edge.
    * `drawBall()`: Clears the canvas and then draws a circle representing the ball at its current position.
    * `animate()`: This function is called repeatedly by `requestAnimationFrame`. It calls `moveBall()` and `drawBall()` to update the animation and then schedules itself to be called again for the next animation frame.

### Running the Animation

1. Save the code as an HTML file (e.g., `bouncing_ball.html`).
2. Ensure the HTML file includes a canvas element with the id `my_canvas`.
3. Open the HTML file in a web browser to see the animation.
