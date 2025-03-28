# Face Recognition System

## Description
This project implements a face recognition system using OpenCV. It allows users to capture and store facial images, train a model using OpenCV's face recognition algorithms, and recognize faces in real-time.

## Features
- Capture facial images and create a dataset
- Train a model using OpenCV's LBPHFaceRecognizer
- Recognize and label faces in real-time using a webcam

## Installation
### Prerequisites
Ensure you have Python installed along with the required libraries:

```sh
pip install opencv-contrib-python numpy jupyter
```

## Usage
### 1. Open Jupyter Notebook
Run the following command to launch Jupyter Notebook:
```sh
jupyter notebook
```

### 2. Open the Notebook
Navigate to the project directory and open `FaceRecognition.ipynb`.

### 3. Execute the Cells
Run each cell in sequence to:
1. Generate a dataset
2. Train the model
3. Recognize faces in real-time

## Dependencies
- Python
- OpenCV
- NumPy
- Jupyter Notebook

## Notes
- Ensure Haar Cascade XML files are available in the working directory.
- Modify the notebook to support multiple users by assigning unique IDs.

## License
This project is open-source and available for modification and distribution.

