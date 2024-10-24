# Pneumonia Prediction Using Chest X-Ray Images
This project aims to develop an automated system to predict the presence of pneumonia in patients using chest X-ray images. Given the importance of timely diagnosis, the goal of this system is to assist medical professionals by improving the accuracy and speed of pneumonia detection, especially in resource-limited settings where manual interpretation may be less reliable. 

The approach leverages a deep learning model based on the ResNet-50 architecture, using transfer learning to classify X-ray images as either "normal" or "pneumonia." The model was trained and evaluated on a publicly available dataset of chest X-rays from Kaggle.

The project demonstrates that a ResNet-50 based deep learning model can effectively detect pneumonia in chest X-ray images with an accuracy of 97.7%. The high accuracy and recall indicate the model's reliability in identifying pneumonia cases with minimal false negatives, which is critical for patient care. Additionally, the low false positive rate minimizes unnecessary treatments for patients without pneumonia.

Potential improvements and extensions to this work include addressing class imbalance by using techniques such as class weighting or oversampling, exploring other deep learning architectures to further improve performance, and integrating model explainability tools like Grad-CAM to help visualize which parts of the X-Ray influenced the model’s decision, aiding in verification by medical professionals.

<img alt="chest_XRay_pneumonia_prediction" src="https://github.com/user-attachments/assets/1e358491-301d-4987-aa0e-bde74860a2da">
