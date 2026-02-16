# Object Shape Enhancement Using Morphological Operations

## DCIT407 -- Digital Image Processing

**University of Ghana, Legon**\
**Group 15 Project**

------------------------------------------------------------------------

## Overview

This project demonstrates the use of mathematical morphology to enhance
object shapes in binary and grayscale images. Specifically, it focuses
on two fundamental morphological operations:

-   Opening -- removes small bright noise and smooths object boundaries\
-   Closing -- fills gaps, holes, and connects broken object parts

The implementation uses Python, OpenCV, and NumPy, and includes
experiments on both synthetic and real-world images.

------------------------------------------------------------------------

## Project Objectives

The main objectives of this project are:

-   Implement erosion, dilation, opening, and closing using OpenCV\
-   Demonstrate noise removal and gap filling using morphological
    operations\
-   Analyze the effect of structuring element size and shape\
-   Apply operations to real-world images such as text, coins, and
    biological structures\
-   Provide reusable functions for morphological image processing

------------------------------------------------------------------------

## Files in the Repository

### 1. Main Project Notebook / Script

Contains:

-   MorphologicalOperations class implementation\
-   Functions for erosion, dilation, opening, closing, gradient, top-hat
    and black-hat transforms\
-   Experiments on noise removal, gap filling, combined enhancement,
    real-world images, and kernel comparison

### 2. Demonstration Script

Contains:

-   morph_opening() function\
-   morph_closing() function\
-   Test cases on noisy binary blobs and shapes with intentional gaps\
-   Visualization of results using matplotlib

------------------------------------------------------------------------

## Technologies Used

-   Python 3.x\
-   OpenCV\
-   NumPy\
-   Matplotlib\
-   scikit-image

------------------------------------------------------------------------

## Installation

Install required dependencies:

``` bash
pip install opencv-python numpy matplotlib scikit-image scipy pillow tqdm
```

------------------------------------------------------------------------

## How to Run

### Option 1: Run the Notebook

Open the .ipynb file in:

-   VS Code, or\
-   Jupyter Notebook

Run all cells.

### Option 2: Run the Python Script

``` bash
python your_script_name.py
```

------------------------------------------------------------------------

## Example Results

The project demonstrates:

-   Removal of salt-and-pepper noise\
-   Filling of holes and gaps in objects\
-   Enhancement of document text\
-   Enhancement of biological and industrial images

Results are saved in:

images/processed/

------------------------------------------------------------------------

## Applications

Morphological operations are widely used in:

-   Medical image analysis\
-   Document processing and OCR\
-   Industrial inspection\
-   Biometrics\
-   Autonomous vehicle vision\
-   Satellite image analysis

------------------------------------------------------------------------

## Project Team -- Group 15

  Name                          Student ID
  ----------------------------- ------------
  Emelia Ampofo                 11288825
  Sonia Selassie Dean-Snowden   11120331
  Samson Gyampoh                11257581
  Nyamekye Korsah               11353306
  Desmond Opoku Anane           11126586
  Reuben Addo                   11019527
  Joy Owusu Ansah               11341365
  Nyarko Rudolf                 11297285
  Michael Adadey                11283519
------------------------------------------------------------------------

## Conclusion

This project successfully demonstrates how morphological opening and
closing can enhance object shapes by removing noise and filling gaps
while preserving structural integrity. The implementation is modular,
efficient, and applicable to real-world image processing tasks.
