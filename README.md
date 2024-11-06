# Object Detection YOLO Simplified

This repository provides a simplified object detection model inspired by YOLO, focusing on detecting basic geometric shapes in synthetic images. Key aspects include anchor box generation, classification and regression heads, and non-maximal suppression for filtering overlapping boxes.

## Project Structure

- **YOLO.ipynb** - Notebook containing the model architecture, training code, and visualization for the object detection model.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/manisha-goyal/object-detection-yolo.git
    cd object-detection-yolo
    ```

## Usage

Open the notebook in Jupyter or Google Colab and execute the cells to train, evaluate, and visualize object detection results.

## Key Components

- **Anchor Boxes**: Divides images into a grid of anchors with three different sizes, using offsets to refine the position and size.
- **Classification & Regression Heads**: Binary classification head for foreground/background detection, and a regression head for offset calculations.
- **Non-Maximal Suppression**: Filters overlapping boxes to retain the most relevant bounding boxes.
