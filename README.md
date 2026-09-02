# Blotly 🧬

A smart, browser-based tool for building clean Western blot figures faster.

⚠️ Note: This project is currently a prototype in active development and testing. Features, UI, and performance are subject to change as improvements are being made.

 ## 🎯 About The Project

Building Western blot figures for scientific publications is often a tedious process involving manual alignment, cropping, and labeling across multiple bloated software programs.

Blotly aims to simplify this workflow by providing a streamlined, web-based canvas dedicated specifically to arranging Western blot strips. It allows researchers to quickly upload raw images, crop them, assign molecular weights, and automatically align lanes and labels to create publication-ready figures.

## ✨ Features (Prototype)

In-Browser Image Editing: Crop, rotate freely, and adjust the contrast of your blot strips before adding them to the canvas.

Format Support: Drag and drop PNG, JPG, and natively unsupported TIFF/TIF files (handled via UTIF.js).

Smart Auto-Alignment: The canvas automatically stacks strips, calculates aspect ratios, and aligns lane headers based on your specific experiment parameters.

Global Lane Calibration: Use drag-and-drop handles to globally calibrate the first and last lanes across all your stacked strips.

Customizable Labels: Toggle target names, molecular weights, and dynamic lane group labels. Choose horizontal, diagonal, or vertical lane orientations.

High-Res Export: Export your finished figure as a clean, high-resolution PNG, ready for publication.

## 🛠️ Built With

- HTML5 / CSS3 / JavaScript - Vanilla web technologies for the core structure and styling.

- Konva.js - A 2D canvas framework used for drawing, dragging, and exporting the interactive figure.

- UTIF.js - A fast, advanced TIFF decoder to allow seamless .tif uploads across all modern browsers.
