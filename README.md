# AI Interpretability: MNIST & SHAP

## Mini Research Project (MRP) for Artificial Intelligence

### Project Overview
This project explores the **Explainability of AI Models**. By training a Convolutional Neural Network (CNN) on the MNIST dataset and applying **SHAP (SHapley Additive exPlanations)**, we visualize exactly which pixels contribute to the model's classification decisions.

### Contents
* **Presentation:** [[Link to your PDF](https://docs.google.com/presentation/d/1hYvRI_I33bxT1O_U2WwUgKOOyishlYOr126nwrzArF8/edit?usp=sharing)]
* **Code:** `MRP.ipynb`
* **Demo Video:** [[Link to YouTube](https://youtu.be/X2yhCKm-fOQ?si=E8R9aLRK9Fs__6bw)]

### Method
1. **Model:** Simple CNN (Conv2D + Dense Layers).
2. **Framework:** TensorFlow / Keras.
3. **Interpretability Tool:** SHAP (DeepExplainer).

### Results
The model achieves ~98% accuracy. The SHAP plots reveal that the model correctly identifies curvature and empty spaces to distinguish between digits (e.g., distinguishing a 3 from an 8).
