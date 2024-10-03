# AIPI-XAI-Explainable-AI
# LIME-Based Explainability for Image Classification Using ResNet34

This project demonstrates the use of Local Interpretable Model-Agnostic Explanations (LIME) to generate visual explanations for a pre-trained deep learning image classifier (ResNet34). The notebook provides a detailed analysis of how LIME can be used to interpret predictions for individual images, highlighting specific regions that contribute most to the model's decision-making process. The visualizations generated help build a better understanding of the model’s behavior and identify areas where the model might be confused or biased.

## **Project Overview**
The project consists of the following main components:
1. **Environment Setup**: Installation of necessary libraries and configuration of the runtime environment.
2. **Data Loading and Preprocessing**: Downloading and preparing a sample image to serve as input for the ResNet34 model.
3. **Model Loading and Prediction**: Using a pre-trained ResNet34 model to classify the input image and retrieve the top predicted class.
4. **LIME Explanations**: Generating local explanations for the predicted class using LIME.
5. **Visualizations**: Multiple visualizations are provided to illustrate LIME's explanations, including positive contributions, positive and negative contributions, and top-N superpixels.

## **Visualizations**
The project includes several visualization techniques to interpret the model's predictions effectively:

1. **Positive Contributions**: Shows regions that support the model's decision for the given class.
2. **Positive & Negative Contributions**: Highlights regions that both support and oppose the prediction.
3. **Top-N Contributing Regions**: Isolates the most influential superpixels for the prediction.
4. **Superpixel Segmentation**: Displays the segmented superpixels with their respective contribution values.
