# 🌦️ Weather Recognition using Convolutional Neural Networks (CNN)

<p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1PAGloXg0LQfPnMXMpakQl7ak6x0pQi_H" alt="Weather Recognition Poster" width="300"/>
</p>
## 📽️ Sample Output Video

<p align="center">
  <a href="https://drive.google.com/file/d/13MlzIB1xdw02E5LsLJg2_D0Vkn38NWeC/view?usp=sharing" target="_blank">
    <img src="https://img.youtube.com/vi/0yWZC3bH1Gc/0.jpg" alt="Sample Output Video" width="400"/>
    <br>
    🔗 Click here to watch the sample output video on Google Drive
  </a>
</p>

This project is a deep learning application that classifies different weather conditions from **images and videos** using a **Convolutional Neural Network (CNN)**. The model is trained on a curated dataset and achieves a test accuracy of **80%**.

---

## 📁 Weather Categories

The model classifies visuals into the following 9 categories:

- ☁️ Cloudy  
- 🌫️ Fog/Smog  
- ⚡ Lightning  
- 🌧️ Rain  
- 🌈 Rainbow  
- 🌪️ Sandstorm  
- ☀️ Shine  
- ❄️ Snow  
- 🌅 Sunrise  

---

## 🧠 Algorithms and Techniques Used

### 🖼️ Image Preprocessing

- Resized all images to **64×64 pixels**
- Normalized pixel values (`/255.0`)
- Removed **noisy and irrelevant images**
- Addressed **class imbalance** for better performance

### 🧱 CNN Architecture

- Multiple **Conv2D** layers with `ReLU` activation
- **MaxPooling2D** layers to reduce dimensions
- **Dropout** layers to prevent overfitting
- **Flatten** and **Dense** layers for classification
- Final **Softmax** layer with 9 output neurons

### 🧪 Evaluation

- ✅ **Test Accuracy:** 80%  
- 📊 **Confusion Matrix**, **F1 Score**

---

## 🔍 Prediction Capabilities

### 🖼️ Image Prediction

Predict weather conditions from static images:

```python
image_path = 'path/to/image.jpg'
# Preprocess, resize, normalize, predict
