# Advanced Lane Detection

This project implements an advanced lane detection system using Python and OpenCV. The system identifies lane lines on the road, measures lane curvature, and provides real-time feedback on vehicle position relative to the lane center.

## Key Features

- **Camera Calibration:**
  - Corrects image distortion using chessboard images to compute camera matrix and distortion coefficients.
- **Perspective Transformation:**
  - Transforms road images to a bird’s-eye view to simplify lane detection.
- **Thresholding:**
  - Applies gradient and color thresholding to create binary images highlighting lane lines.
- **Lane Line Detection:**
  - Uses histogram and sliding window methods to detect lane pixels and fits polynomial curves to the lane lines.
- **Curvature Measurement:**
  - Calculates lane curvature and vehicle position relative to the lane center.
- **Debug Mode:**
  - Visualizes each step of the lane detection process for development and troubleshooting.

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/Legedrid10/advanced-lane-detection.git
   cd advanced-lane-detection
