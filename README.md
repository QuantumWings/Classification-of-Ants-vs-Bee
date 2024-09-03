# Ant and bee image classification web application

## Introduction

This is a web-based image classification application designed to identify ants and bees. The application leverages deep learning models to provide a convenient tool for ecological research, education, and citizen science through a user-friendly interface.

Check out the demo [here](https://quantumwings.github.io/Classification-of-Ants-vs-Bee/).

## Main functions

- Instant image classification: identify ants or bees immediately after uploading the image
- Dynamic model loading: supports the upload and use of custom ONNX models
- Real-time visual feedback: displays classification results and confidence
- Responsive design: interface that adapts to various device sizes

## Installation and Setup Guide

### Environmental requirements

- Modern web browser (supports HTML5, WebAssembly and JavaScript ES6+)
- Internet connection (for initial loading)

### How to use

1. Clone or download this repository to your local machine
2. Use a web server (such as Python’s `http.server` or Node.js’ `http-server`) to host project files
3. Access the hosting address in your browser

## Instructions for use

### Operation steps

1. After opening the app, you will see two drag and drop areas
2. You can upload a customized ONNX model in the upper area (optional)
3. Upload the images to be classified in the area below
4. Wait a few seconds and the classification results will be automatically displayed.

### Example

Upload a picture of ants and the system will display:
```
Ant, confidence level 95.34%
```

## Project structure

- `index.html`: Contains all the necessary HTML, CSS and JavaScript code to build and display an interactive interface for image classification.

## Contribution Guidelines
If you would like to contribute to this project, please follow these steps:
1. Fork this repository and clone it to the local environment.
2. Create a new branch for development (git checkout -b feature-branch).
3. Commit your changes (git commit -m 'Add some feature').
4. Push the changes to your branch (git push origin feature-branch).
5. Submit a Pull Request.

## Authorization information
This project is licensed under the terms of [MIT](https://opensource.org/licenses/MIT).

## Contact Information
If you have any questions or suggestions, please contact the project maintainer: quantumwingslab@gmail.com

## Other information
This project uses ONNX Runtime Web for model inference, demonstrating how to implement efficient machine learning applications in the browser. Future plans include supporting the identification of more insect species, as well as adding data collection capabilities to further improve the model.
