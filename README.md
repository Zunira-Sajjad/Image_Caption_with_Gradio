# Image_Caption_with_Gradio
This repository contains a web application built with Gradio and the BLIP (Bootstrapping Language-Image Pre-training) model for automatic image captioning. It allows users to upload an image and generates a descriptive caption using a pre-trained image-captioning model from the Hugging Face Transformers library.

## Features
1 - Pre-trained BLIP Model: Uses Salesforce’s blip-image-captioning-base model for generating accurate captions for any uploaded image.

2 - Simple Web Interface: Built with Gradio, providing an easy-to-use interface where users can upload images and get captions instantly.

3 - Base64 Conversion: Converts images to base64 strings to handle image processing.

4 - Customizable: Includes options for running locally and configuring the server port using environment variables.

## How It Works
1 - Users upload an image in the Gradio interface.

2 - The image is processed and passed through the BLIP model.

3 - The application returns a generated caption describing the image.

## Setup Instructions
1 - Clone this repository.

2 - Install the required dependencies mentioned in requirement.txt.

3 - Run the app with python app.py.

4 - Access the interface in your browser at localhost:7860 (or a custom port if set).

## Acknowledgments
This project uses the Hugging Face transformers library and Gradio for building the interface.
