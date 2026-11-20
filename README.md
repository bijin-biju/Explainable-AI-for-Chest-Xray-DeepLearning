
# Explainable AI-Based Chest X-ray Classification

## Project Overview
This project uses Deep Learning and Explainable AI to classify chest X-ray images into two categories: **NORMAL** and **PNEUMONIA**. Grad-CAM is implemented to visualize the important regions influencing model predictions.

## Dataset
- **Source:** Kaggle – Chest X-Ray Images (Pneumonia)
- **Total Images:** 5,863
- **Classes:** NORMAL and PNEUMONIA
- **Image Size:** 224 × 224

## Technologies Used
- Python
- TensorFlow & Keras
- OpenCV
- NumPy & Pandas
- Matplotlib & Seaborn
- Scikit-learn
- Google Colab

## Models Implemented
1. Custom CNN
2. ResNet50
3. DenseNet121
4. EfficientNetB0

## Best Model Performance

**DenseNet121**
- Accuracy: 89.6%
- Precision: 88.6%
- Recall: 95.6%
- ROC-AUC: 0.957

Fine-tuned DenseNet121 achieved 89.9% accuracy and 0.964 ROC-AUC.

## Explainable AI
Grad-CAM (Gradient-weighted Class Activation Mapping) generates heatmaps to highlight important regions of chest X-ray images that influence the model's predictions.

## Key Features
- Medical image classification
- Deep learning model comparison
- Transfer learning and fine-tuning
- Performance evaluation
- Grad-CAM visualization
- Prediction error analysis

## How to Run
1. Clone the repository.
2. Open the Jupyter Notebook in Google Colab.
3. Download the dataset from Kaggle.
4. Configure Kaggle API authentication.
5. Run the notebook cells sequentially.

## Author
**Bijin Biju**

BCA Student | AI & ML Enthusiast | Python Developer

[GitHub](https://github.com/bijin-biju) | [LinkedIn](https://www.linkedin.com/in/bijinbiju/)

---
*This project is intended for educational and research purposes only, not for professional medical diagnosis.*
