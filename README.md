# 🌦️ Weather Recognition using SVM

<p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1PAGloXg0LQfPnMXMpakQl7ak6x0pQi_H" alt="Weather Recognition Poster" width="300"/>
</p>


This project is a machine learning application that classifies different weather conditions from images using **Support Vector Machines (SVM)**. The model is trained on a custom image dataset with various weather categories and achieves high accuracy through preprocessing, feature scaling, and PCA dimensionality reduction.

---

## 📁 Weather Categories
The model classifies images into the following 9 categories:

- Cloudy  
- Fog/Smog  
- Lightning  
- Rain  
- Rainbow  
- Sandstorm  
- Shine  
- Snow  
- Sunrise  

---

## 🧠 Algorithms and Techniques Used

- **Image Preprocessing:** Resize and flatten to 32×32 pixels  
- **Feature Scaling:** `StandardScaler` from scikit-learn  
- **Dimensionality Reduction:** `PCA` (95% variance retained)  
- **Classification Model:** Support Vector Machine (SVM) with RBF kernel  
- **Model Evaluation:** Accuracy, Confusion Matrix, F1 Score  
- **Visualization:** Matplotlib for displaying predictions and external image classification

---

## 📂 Dataset

The dataset contains folders for each weather category with images inside.  
Due to GitHub file size limits, it is hosted externally:

🔗 [Download Dataset from Google Drive](https://drive.google.com/drive/folders/1tvv-oGfF6CeiX7iLQzHhbSEWjnQ1d7H7?usp=sharing)

After downloading, extract it and place the dataset path in your notebook like this:
```python
data_dir = 'path/to/your/dataset'
