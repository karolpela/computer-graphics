# Computer Graphics

A collection of university assignments exploring core computer graphics concepts, built with [p5.js](https://p5js.org/) and [Blender](https://www.blender.org/).

## Projects

### 1 - Introduction

Fundamentals of pixel-level rendering using the p5.js canvas API.

- **Pixel filling** - fill the canvas pixel-by-pixel with a solid color
- **Gradient rendering** - generate a horizontal grayscale gradient
- **Radial color mapping** - compute per-pixel color based on distance from the canvas center
- **Scene composition** - draw a simple house scene (roof, walls, grass with random flowers) entirely through pixel manipulation
- **Sierpinski triangle** - render the fractal via the chaos game algorithm (30,000 iterations)

---

### 2 - Colors and Histograms

Image processing and color space operations on a sample image (NASA astronaut photo).

- **RGB channel decomposition** - split an image into its red, green, and blue channels and recompose them using additive blending
- **RGB to HSV conversion** - manually convert pixel data from RGB to the HSV color model, visualizing hue, saturation, and value as separate grayscale images
- **Grayscale histogram** - compute and render the brightness distribution of a grayscale-converted image

---

### 3 - Drawing Algorithms

Implementation of line-drawing algorithms from scratch using direct pixel manipulation.

- **Naive line drawing** - draw lines using the slope-intercept equation (`y = ax + b`)
- **Bresenham's line algorithm (basic)** - integer-only line rasterization for the first octant
- **Bresenham's line algorithm (full)** - generalized implementation handling all octants and directions via axis swapping

---

### 4 - Affine Transformations

Interactive 2D transformation playground with real-time matrix composition.

- **Freehand drawing with vectors** - draw on a canvas using homogeneous coordinate vectors
- **Transformation matrix display** - view and compose the current 3x3 transformation matrix
- **Translation, scaling, rotation, and shearing** - apply affine transformations individually or compose them via matrix multiplication, with the transformed drawing rendered on a second canvas in real time

---

### 5 - 3D Graphics

3D scene modeling in Blender.

- **Blender scene** - a 3D scene created and rendered in Blender

---

## Tech Stack

- **p5.js** - JavaScript library for creative coding and canvas-based rendering
- **Blender** - open-source 3D modeling and rendering software
- **ESLint** - linting with the p5.js ESLint configuration
