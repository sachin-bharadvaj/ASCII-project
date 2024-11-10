# Donut ASCII

This project generates an animated spinning donut in the terminal using C. It utilizes trigonometric functions, buffer management, and simple graphics rendering techniques to create a real-time animation.

## Description

This code creates an ASCII art animation of a spinning donut. It performs the following steps:
1. **Initial Setup**: Initializes trigonometric variables and clears the screen.
2. **Buffer Management**: Uses two buffers to store characters and depth information.
3. **Trigonometric Calculations**: Calculates the positions and depths of points on a torus (donut shape).
4. **Graphics Rendering**: Uses ASCII characters to render the torus based on calculated positions and depths.
5. **Infinite Loop**: Continuously updates the screen to create the animation effect.

## How to Run

To compile and run the donut animation code, follow these steps:

- To Compile
  ```Sh
  gcc -o donut donut.c -lm
  ```
  
- To Run
  ```Sh
  ./donut
  ```

## Explanation
- A and B are angles for rotation.
- i and j are loop variables for generating the torus points.
- c, d, e, f, g, h, D, l, m, n, t are trigonometric intermediate variables.
- x and y are screen coordinates.
- o is the offset into the buffers.
- N is the ASCII character index based on depth.

