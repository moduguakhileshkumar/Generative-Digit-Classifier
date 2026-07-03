# Generative Digit Classifier

A Python implementation of Gaussian-based generative models for handwritten digit classification, image generation, and missing-data reconstruction on the **MNIST** dataset. This project was completed as part of **CS771: Introduction to Machine Learning** at **IIT Kanpur** under **Prof. Purushottam Kar**.

## Overview

This project explores probabilistic generative learning techniques by implementing Gaussian models from scratch. It demonstrates how generative models can not only classify handwritten digits but also generate realistic samples and reconstruct images with missing pixels.

The implementation covers:

- Single Gaussian Models
- Full-Covariance Gaussian Models
- Gaussian Mixture Models (GMM)
- Expectation-Maximization (EM) Algorithm
- Bayesian Generative Classification
- Missing Pixel Reconstruction using Conditional Gaussians

---

## Features

- Implemented the **Expectation-Maximization (EM)** algorithm from scratch.
- Built Gaussian Mixture Models for unsupervised handwritten digit modeling.
- Developed a multivariate Gaussian classifier for supervised digit recognition.
- Generated synthetic handwritten digits by sampling learned Gaussian distributions.
- Reconstructed censored images using Conditional Gaussian inference.
- Visualized learned covariance structures and generated samples.

---

## Results

- **85.7%** classification accuracy on the MNIST test dataset.
- Successfully reconstructed handwritten digits with **21% central pixels removed**.
- Achieved **78.6%** classification accuracy on censored test images.
- Demonstrated the importance of covariance modeling over simple spherical Gaussian assumptions.

---

## Technologies Used

- Python
- NumPy
- SciPy
- Matplotlib
- Jupyter Notebook

---

## Project Structure

```
.
├── my_generative_classification.ipynb
├── cs771/
│   ├── utils.py
│   ├── plotData.py
│   └── __init__.py
├── mnist/
│   ├── train-images
│   ├── train-labels
│   ├── test-images
│   └── test-labels
└── README.md
```

---

## Models Implemented

### Gaussian Models

- Identity Covariance Gaussian
- Full Covariance Gaussian

### Gaussian Mixture Models

- Expectation-Maximization (EM)
- K-Means++ Initialization
- Maximum Likelihood Estimation

### Classification

- Multivariate Gaussian Generative Classifier
- Bayesian Decision Rule
- Log-Likelihood Classification

### Missing Data Inference

- Conditional Gaussian Distribution
- Image Reconstruction
- Classification with Missing Pixels

---

## Dataset

The project uses the **MNIST Handwritten Digit Dataset**.

Download:
https://www.kaggle.com/datasets/hojjatk/mnist-dataset

Place the extracted files inside the `mnist/` directory before running the notebook.

---

## How to Run

Clone the repository

```bash
git clone https://github.com/moduguakhileshkumar/Generative-Digit-Classifier.git
```

Install the required packages

```bash
pip install numpy scipy matplotlib jupyter
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open

```
my_generative_classification.ipynb
```

and execute all cells.

---

## Learning Outcomes

This project provided hands-on experience with

- Probabilistic Machine Learning
- Gaussian Generative Models
- EM Algorithm
- Maximum Likelihood Estimation
- Covariance Modeling
- Bayesian Classification
- Image Reconstruction using Conditional Distributions

---

## Acknowledgement

Developed as a course project for **CS771: Introduction to Machine Learning** at **Indian Institute of Technology Kanpur** under the guidance of **Prof. Purushottam Kar**.
