# Flask Cat and Dog Image Classification Application

This is a Flask web application that allows users to upload images and get predictions on whether the image is of a cat or a dog. The predictions are made using a pre-trained model (h5 format), and the application is containerized using Docker.

## Docker Deployment
Build Docker image : docker build -t my-flask-app .
Run the Docker container : docker run -p 5000:5000 my-flask-app
Access the app at http://127.0.0.1:5000/upload

## Installation

To get started with this project, clone the repository and install the required dependencies.

## Usage
Upload an image using the web form.

The app will predict whether the image contains a cat or not.

## Demo Video



https://github.com/saiyesh1th/Cat-Dog-Classification-Using-Docker/assets/169977151/9622878f-a490-4828-9935-d7dc4bbbe415

## Acknowledgement and Links
DockerHub Link: https://hub.docker.com/repository/docker/yeshme/flask_docker/general

Model Download link: https://huggingface.co/spaces/Sa-m/Dogs-vs-Cats/blob/main/best_model.h5
