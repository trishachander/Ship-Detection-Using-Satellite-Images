# 🚢 Airbus Ship Detection - ML Course Project

A CNN-based solution using the Airbus Ship Detection dataset that processes satellite imagery for ship detection, achieving 88.54% accuracy.

# 🎯 Project Overview
Academic project (19CSE305 Machine Learning course) focused on:
- 🛥️ Ship detection in satellite imagery
- 🔍 Feature extraction techniques
- 🧠 CNN architecture implementation
- 📊 Binary image classification

# 🔑 Key Features
- 📊 Mean pixel value extraction from RGB layers
- ⚖️ Otsu threshold masking
- 🔄 Hu Moments for shape characterization
- 🧮 CNN with BatchNormalization
- 🎯 88.54% accuracy achievement

# 🛠️ Technical Stack
- Python
- TensorFlow/Keras
- OpenCV
- NumPy
- Pandas
- Matplotlib

# 🏗️ Model Architecture
- Input shape: 256x256x3 (RGB)
- Convolutional layers with 32 filters
- ReLU activation
- MaxPooling with 2x2 pool size
- 25% dropout rate
- Batch normalization

# 📈 Feature Extraction Process
1. Mean Pixel Value
  - Reduces 3 RGB layers to 1 layer
  - Calculates mean of R, G, B values per pixel
2. Otsu Threshold Masking
  - Calculates threshold per image
  - Binary output (0, 255)
3. Hu Moments
  - Shape characterization
  - Ship feature extraction

# 📚 References
- [1] Analytics Vidhya - Feature Extraction Techniques
- [2] Otsu's Method - Wikipedia
- [3] Hu Moments - CV Explained
