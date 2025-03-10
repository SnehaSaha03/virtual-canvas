# Virtual Painter

## Overview

This project implements a virtual painter using OpenCV, allowing users to draw on the screen using a colored marker. The application detects a colored object (e.g., a pen cap) and uses its movement to draw on a virtual canvas. Users can select different colors from a palette displayed on the screen and clear the canvas with a designated button.

## Features

*   **Color Detection:** Uses HSV color space and trackbars to detect the specified marker color.
*   **Virtual Canvas:** Creates a separate window where the drawing is displayed.
*   **Color Palette:** Presents a color palette on the screen for users to select drawing colors.
*   **Clear Functionality:** Allows users to clear the entire canvas with a dedicated button.
*   **Real-time Drawing:** Draws lines on both the live video feed and the virtual canvas based on the marker's movement.

## Dependencies

*   Python 3.x
*   OpenCV (`cv2`)
*   NumPy (`numpy`)
*   collections (`deque`)
