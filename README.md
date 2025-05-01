# fake-url-anf-fake-logo-detection-using-browser-extension
This project is a browser extension that helps in increasing security by detecting phishing emails which conThis extension integrates ulr scanning techniques to classify them as safe and unsafe and employes a Deep Learning model that compares the visible logos against the real brand logos and classifies them into real or fake.
Datasets
Genuine and Fake Logo Dataset: Used for training the ResNet-50 model to detect real vs. fake logos.

Threatening URLs Dataset: Used to detect phishing URLs (implicitly mentioned, integrated via Google Safe Browsing API).


Requirements
1. Software Requirements
Frontend: HTML, CSS, JavaScript, Python

Backend: Flask API

AI/ML Libraries:

pandas

torch

torchvision.models

torchvision.transforms

torch.utils.data.DataLoader

PIL.Image

cv2

os

2. Hardware Requirements
Processor: 64-bit, Core i5, 2.5 GHz minimum per core

RAM: 8 GB or more

HDD: 20 GB free space

Display: Dual XGA (1024 × 768) or higher

Standard keyboard


Metrics
Loss Function: Cross Entropy Loss

Optimizer: Adam Optimizer

Classification Accuracy: (Implied as the key performance metric for the model, though exact values are not listed)


Evaluation
Model Used: ResNet-50 (for logo classification)

Evaluation Stages (as part of Methodology):

Model Implementation

Model Evaluation

Classification

Comparison: Fake vs. real logos

Extension Test: On Gmail, scanning real email content for logos and URLs

Integration: Google Safe Browsing API for URL scanning
