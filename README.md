# CSCI323_Group30
An automatic Sudoku Solver utilising Computer Vision to identify the Sudoku grid, and CSP to solve it.
FT30 Automatic Sudoku Solver

This project focuses on developing an automated Sudoku solver that integrates image recognition with algorithmic reasoning. The system takes an image of an unsolved Sudoku puzzle, processes it to detect and recognize digits, and applies a backtracking algorithm to generate a valid completed grid.

Presentation Slides  Presentation Video

Objective

The project aims to create an end-to-end AI system capable of:

Extracting and segmenting Sudoku grids from input images.
Recognizing digits using a trained Convolutional Neural Network (CNN) model.
Solving the puzzle logically through a CSP-based backtracking algorithm.
This pipeline demonstrates how image recognition and search algorithms can work together to solve structured reasoning tasks.

Getting Started

Built using:

Python
Packages used:

Numpy
OpenCV
Tensorflow
Matplotlib.
Environment:

Python virtual environment
Algorithm applied:

Basic Backtracking
Minimum Remaining Value
Foward Checking
Degree Hueristic
Least Constraining Value.
Clone the Repository

git clone https://github.com/cyuanjun/CSCI323_Group30.git
cd CSCI323_Group30
Setup Virtual Environment

python -m venv .venv
# For Windows
.\.venv\Scripts\activate
# For Mac/Linux
source .venv/bin/activate
Install Dependencies

pip install numpy opencv-python tensorflow matplotlib
Running the Sudoku Solver

Run main.py:
python FINAL_SUBMISSION/main.py
Input Sudoku image path:
Enter path of sudoku image to be solved or (N) to end:
# enter your image path e.g Images/img1.png
After the outputs for each stage (image preprocessing and Sudoku solving) are displayed, press any key to proceed to the next step.
Files

Image Recognition

FINAL_image_processing.py
FINAL_digit_recognition.py
Solving

DegMRVFV_sudoku_solver.py
IcvDegMrvFc_sudoku_solver.py
MRV_sudoku_solver.py
MRVFC_sudoku_solver.py
sudoku_metrics.py
sudoku_solver.py
Main

main.py
Models

printed_digits_cnn.keras
Dataset

Dataset and web sources we used for the development of our model.

Kaggle: Printed Digits Dataset
Testing Images 1
Testing Images 2
Authors

Group name: FT30

Project number: 13

Members:

Lee Haeeun
Chia Yuan Jun
Lee Jinseo
Nadon Panwong
