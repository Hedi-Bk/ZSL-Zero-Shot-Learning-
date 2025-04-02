# Vision Transformer (ViT) for Image Classification and Zero-Shot Learning

## Introduction

In the real world, traditional machine learning models require extensive labeled data to perform classification tasks effectively. However, in many cases, it is impractical or impossible to have labeled examples for every possible category. **Zero-Shot Learning (ZSL)** addresses this challenge by enabling models to recognize and classify new, unseen objects without explicit training on them. This is particularly useful in domains such as medical diagnosis, wildlife conservation, and autonomous driving, where new categories frequently emerge.

This project utilizes the **Vision Transformer (ViT)** and Hugging Face's `transformers` library to perform both standard and zero-shot image classification, as well as object detection.

## Project Structure

### Image Classification with Hugging Face

#### Task 1: Loading the Vision Transformer

- Load a pre-trained **ViT** model for image classification.

#### Task 2: Generating Features from an Image

- Extract meaningful feature representations from an input image.

#### Task 3: Making Predictions

- Perform classification on the extracted image features.

### Zero-Shot Image Classification

#### Task 4: Loading Models

- Load a pre-trained **CLIP** model for zero-shot classification.

#### Task 5: Preparing Inputs

- Process both images and text descriptions to make them compatible with the model.

#### Task 6: Generating Predictions

- Predict the most relevant label for an image without prior training on specific categories.

### Zero-Shot Object Detection

#### Task 7: Loading the Model

- Use the **Owl-ViT** model for object detection without predefined categories.

#### Task 8: Preparing Inputs for the Model

- Provide text-based queries alongside images for object detection.

#### Task 9: Visualizing the Results

- Draw bounding boxes around detected objects using textual descriptions.

## Installation

To run this project, install the required dependencies:

```bash
pip install torch torchvision transformers pillow matplotlib
```

## Acknowledgments

- [Hugging Face](https://huggingface.co/) for providing pre-trained transformer models.
- OpenAI's CLIP and Google’s Owl-ViT for zero-shot learning capabilities.

Feel free to contribute to this project and expand its functionalities! 🚀
