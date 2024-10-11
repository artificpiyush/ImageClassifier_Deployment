# Image Classification Web

This Flask web application classifies images into one of ten categories from the CIFAR dataset using a pre-trained Convolutional Neural Network (CNN) model. Users can upload images and receive classification results in real time, along with the confidence percentage for each category.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Directory Structure](#directory-structure)
- [License](#license)

## Features

- Upload an image for classification.
- Displays the predicted category with the confidence percentage for each of the ten classes.
- User-friendly web interface built with HTML and CSS,Flask.

## Technologies Used

- Python
- Flask
- TensorFlow
- HTML/CSS
- Bootstrap (optional for styling)

project-folder/
│
├── app.py                  
├── requirements.txt        
├── static/                 
│   └── style.css           
└── templates/              
    ├── home.html          
    └── result.html        

## Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd <repository-folder>
