# CropIq - Soil-Based Crop Recommendation System
CropIq is a machine learning-based crop recommendation system designed to assist farmers and agricultural planners in selecting suitable crops based on soil characterstics derived from satellite images and user location.

The project leverages deep learning techniques to analyze soil image patterns and predicts the most appropriate crop for a given region. It aims to improve agricultural productivity by providing data-driven crop suggestions instead of relying solely on traditional farming methods.

Currently, the system focuses on model training, location fetching, and preparation for Android integration. The trained machine learning model has been successfully converted into TensorFlow Lite format for future deployment in a mobile application.

# Objectives
- To recommend suitable crops based on soil and regional features
- To use satellite imagery and machine learning for intelligent prediction
- To provide a farmer-friendly mobile-based solution
- To support location-based crop recommendation

# Current Features
- 📍 Fetches user location using GPS
- 🗺️ Redirects to satellite view using Google Maps
- 🤖 Machine learning model trained using satellite soil images
- 🔁 Model converted to TensorFlow Lite (.tflite) format
- 📊 Dataset prepared for 9 Indian states
- 🧪 Model evaluated and tested in desktop environment

# Machine Learning Details
- Model Architecture: EfficientNet
- Framework: TensorFlow and Keras
- Input: Satellite soil images
- Output: Recommended crop name
- Data Source: Sentinel Hub satellite images
- Dataset Size: ~1300 images

# Technology Stack
- Python
- TensorFlow / Keras
- OpenCV
- Flask (Web application)
- Google Maps API
- Android (Kotlin – upcoming)
- TensorFlow Lite

# Future Implementation
- 📱 Integrate TensorFlow Lite model into Android application
- 📸 Predict crop from mobile camera or satellite image
- ☁️ Cloud-based crop prediction API
- 🌐 Automatic satellite image retrieval using user location
- 📈 Improve model accuracy using a larger dataset
- 🌾 Multilingual and farmer-friendly Android UI
- 🗺️ State-wise and region-wise crop recommendation

## 🔄 Project Workflow
Satellite Images (Sentinel Hub)
            ↓
Image Preprocessing
            ↓
EfficientNet-B7 Model
            ↓
Soil Type Prediction
            ↓
Soil–Crop Mapping (CSV)
            ↓
Crop Recommendation Output
            ↓
Mobile App Display

-----
