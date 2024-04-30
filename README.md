# Fashion Product Recommendation System

This project involves building a recommendation system for fashion products using deep learning techniques.

## Introduction

The goal of this project is to recommend similar fashion products to users based on their preferences. This is achieved by leveraging deep learning models to generate embeddings for fashion product images and then using these embeddings to calculate similarities between products.

## Setup

1. **Install required libraries.**

    ```bash
    pip install -q kaggle swifter tensorflow==2.0.0
    ```

2. **Download and preprocess the dataset.**

    - Set up Kaggle API credentials by uploading the `kaggle.json` file.
    - Download the fashion product images dataset using the Kaggle API.
    - Extract the downloaded zip file.
    - Load and preprocess the dataset.

3. **Generate embeddings for fashion product images.**

    - Use a pre-trained ResNet50 model to extract embeddings for each image.
    - Calculate cosine similarity between embeddings to find similar products.

4. **Visualize the latent space of fashion products.**

    - Use t-SNE to reduce the dimensionality of embeddings for visualization.
    - Plot clusters of fashion products based on their embeddings.

## Dataset

The dataset used in this project is the [Fashion Product Images Dataset](https://www.kaggle.com/paramaggarwal/fashion-product-images-dataset) available on Kaggle.

## Scripts Included

- `fashion_product_recommendation.ipynb`: Jupyter Notebook containing Python code for dataset preprocessing, model building, and visualization.

## Results

The recommendation system generates recommendations for fashion products based on their embeddings, achieving a certain level of accuracy in suggesting similar items to users.

## Future Work

Future updates to this project may include fine-tuning the recommendation model, exploring different deep learning architectures for generating embeddings, and improving the visualization of the latent space of fashion products.
