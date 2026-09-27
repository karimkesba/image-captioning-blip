# Image Captioning with BLIP

An image captioning application using the pretrained BLIP vision-language model and Gradio.

## Overview

This project takes an image as input and generates a natural-language caption describing the image.

## Pipeline

```text
Image
  ↓
BLIP Processor
  ↓
Pretrained BLIP Model
  ↓
Generated Tokens
  ↓
Decoded Caption
```

## Technologies

* Python
* PyTorch
* Hugging Face Transformers
* BLIP
* Gradio

## Model

`Salesforce/blip-image-captioning-base`

The project uses a pretrained BLIP model for image captioning without training a model from scratch.

## Gradio Interface

The final application uses Gradio and provides two ways to provide an image:

* Upload an image
* Enter an image URL

The generated caption is displayed in the interface.

## How to Run

1. Install the required libraries.
2. Open `image-captioning-blip.ipynb`.
3. Run the notebook cells.
4. Launch the Gradio interface.
5. Upload an image or provide an image URL.

## Project Structure

```text
image-captioning-blip/
├── image-captioning-blip.ipynb
└── README.md
```
