# Basics of Computer Vision

This mini-project demonstrates the **fundamentals of image processing** using Python and OpenCV. The goal is to understand how images can be loaded, converted into different color scales, and visualized using `matplotlib`.

## 📷 Project Objective

- Load and display an image.
- Convert the image into grayscale.
- Extract and display individual color channels: Red, Green, and Blue.
- Display combinations of color channels for visual understanding.

## 🛠️ Technologies Used

- Python 3.x
- OpenCV (`cv2`)
- NumPy
- Matplotlib

## 📁 Files

- `Basics_of_Computer_Vision.py` — Contains the image processing and visualization code.
- `README.md` — Project documentation.

## 🖼️ Features

### 1. Load and Display Image
- Read the original image using `cv2.imread()`.
- Convert from BGR to RGB for correct color rendering in `matplotlib`.

### 2. Grayscale Conversion
- Use OpenCV flag `0` to convert the image to grayscale.

### 3. Channel Separations

#### 🔴 Red Scale
- Retain only the red channel.
- Set green and blue channels to zero.

#### 🟢 Green Scale
- Retain only the green channel.
- Set red and blue channels to zero.

#### 🔵 Blue Scale
- Retain only the blue channel.
- Set red and green channels to zero.

### 4. Channel Combinations

#### 🟣 Red + Blue
- Remove the green channel.

#### 🟡 Red + Green
- Remove the blue channel.

#### 🔵🟢 Green + Blue
- Remove the red channel.

## Install the required libraries:
   ```bash
   pip install opencv-python matplotlib numpy
