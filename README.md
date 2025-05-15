# 🍅 Tomato Leaf Disease Classification System

A deep learning-powered web application that classifies tomato leaf diseases such as **Early Blight**, **Late Blight**, and **Mosaic Virus** using uploaded images. This tool is designed to help farmers and agriculturists identify plant health issues early, enabling better crop management and yield.

## 🚀 Features

- 📸 Image-based tomato leaf disease classification
- 🧠 Trained deep learning model using Convolutional Neural Networks (CNNs)
- 🌱 Supports multiple disease categories: Early Blight, Late Blight, Mosaic Virus, and Healthy
- 🖼️ Interactive UI for uploading and analyzing images
- 📊 Displays classification result with confidence score
- 💡 Provides insights and visual feedback to the user

---

## 🛠️ Tech Stack

| Category         | Tools/Technologies                          |
|------------------|---------------------------------------------|
| Programming      | Python                                      |
| Deep Learning    | TensorFlow, Keras                           |
| Image Processing | OpenCV, NumPy                               |
| Data Handling    | Pandas                                      |
| Visualization    | Matplotlib, Seaborn                         |
| Frontend         | Streamlit                                   |

---

## 📂 Dataset

Dataset contains 18,345 training and 4,585 validation images across 10 disease classes from the **New Plant Diseases Dataset (Augmented)**.




---

## ⚙️ How It Works

1. **Image Upload**  
   Users upload an image of a tomato leaf via a simple Streamlit interface.

2. **Preprocessing**  
   The uploaded image is:
   - Resized to a standard input size
   - Normalized
   - Converted to array and processed using OpenCV

3. **Prediction**  
   The preprocessed image is fed into a CNN model trained to classify diseases.

4. **Result Display**  
   The app:
   - Shows the predicted disease label
   - Displays a confidence percentage
   - Optionally visualizes the input and prediction result

---

## 🖥️ Running the Project Locally

```bash
# Step 1: Clone the repository
git clone https://github.com/your-username/tomato-leaf-disease-classification.git
cd tomato-leaf-disease-classification

# Step 2: Create virtual environment and activate it
python -m venv venv
source venv/bin/activate  # For Linux/macOS
venv\Scripts\activate     # For Windows

# Step 3: Install dependencies
pip install -r requirements.txt

# Step 4: Run the app
streamlit run app.py

