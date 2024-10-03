## Explainable AI for Image Classification using LIME

### Overview
This project implements **Local Interpretable Model-agnostic Explanations (LIME)** to provide interpretable insights into the predictions made by a deep learning image classification model (ResNet34). The goal is to visualize which regions of the image contribute the most to the model’s decisions, making the predictions more understandable and transparent.

Through a series of visualizations, the project demonstrates how LIME highlights critical superpixels that affect the model’s output, reveals potential biases in multi-class predictions, and identifies strengths and weaknesses in the interpretability of complex neural networks.

### Key Features
- **LIME Visualizations** for model interpretability.
- Analysis of **top-N class predictions** for the model’s outputs.
- **Superpixel Segmentation** to localize influential regions in the image.
- Comparison of **positive and negative feature contributions**.
- Clear visual overlays to pinpoint decision-making regions.

### Setup and Installation

#### Prerequisites
- Python 3.6+
- Jupyter Notebook or Google Colab
- The following libraries:
  - `numpy`
  - `matplotlib`
  - `torch`
  - `torchvision`
  - `scikit-image`
  - `lime`

#### Clone the Repository
```bash
https://github.com/aiyufan3/AIPI-XAI-Explainable-AI.git
cd 
