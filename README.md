# NC2425 Final Assignment
This repository contains a Jupyter Notebook titled assignment_NC2425_final.ipynb, which serves as the final assignment submission for the NC2425 course. The notebook applies a variety of computer vision and image processing techniques using Python libraries to create a convolutional neural network that recognises and labels different food dishes.

## Contributors
Enzo Perk (s3894347)
Sem Broere (s3410552)
Bing Steens (s3901149)
Thijmen Bouman (s3543404)

## Repository Structure
.
├── assignment_NC2425_final.ipynb
├── report.pdf
├── best_model.pth
└── README.md

## Requirements
To execute the notebook, ensure the following Python packages are installed:

numpy
opencv-python
matplotlib
Pillow (optional, for image manipulation)
scikit-image (if used in specific parts of the notebook)
torch 2.6.0
torchvision
random
collections

## Training & Testing data
The user needs to add teir own train and test dataset to create the following directory structure:
.
├── assignment_NC2425_final.ipynb
├── report.pdf
├── best_model.pth
├── README.md
├── train
└── test

Where the train and test folders consist of folders, with the folder name as labels. Each labelled folder must consists of .jpg images.

## Jupyter notebook
In the browser interface, open the file assignment_NC2425_final.ipynb.

Execute each cell in order, or use Kernel > Restart & Run All to run the entire notebook.
This should start the training process of 50 epochs leading to a 62.36% accurate model. The training took about 2 hours on a NVIDIA GeForce RTX 3070 Laptop GPU using Torch 2.6.0 and CUDA 12.6

## Features
The notebook demonstrates:
Image loading and preprocessing
Image transformation

## Input Data
If the notebook requires image or video files, ensure they are located in the same directory as the notebook or update the file paths accordingly. 

## Upload own pictures
If you want to load your own 10 pictures, locate them in the test file under the appropriate label, and delete/move all other images.

## License
This project is intended for educational use only. No license is granted for commercial redistribution.
