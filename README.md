## Description
A deep learning-based system designed to detect tomato leaf diseases such as Early Blight, Late Blight, and Mosaic Virus using images uploaded by users. This project aims to assist farmers in diagnosing diseases early, ensuring healthier crops and improved yield.

## Features
- Image-based tomato leaf disease detection.
- Supports multiple disease classifications.
- User-friendly interface for uploading and analyzing images.
- Generates actionable insights for users.

## Tech Stack
- **Programming Language:** Python
- **Frameworks and Libraries:** TensorFlow/Keras, OpenCV, NumPy, Pandas
- **Frontend:** Streamlit
- **Visualization:** Matplotlib, Seaborn

## Dataset
- The model is trained on a curated dataset of tomato leaf images, containing healthy and diseased samples.
- The dataset includes images for Early Blight, Late Blight, Mosaic Virus, and healthy leaves.

## How It Works
1. **Image Upload:** Users upload an image of a tomato leaf.
2. **Preprocessing:** The image is resized, normalized, and preprocessed using OpenCV.
3. **Prediction:** The deep learning model (CNN) analyzes the image and classifies the disease.
4. **Results Display:** The system provides the disease name and confidence score
