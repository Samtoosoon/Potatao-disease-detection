# 🥔 Potato Leaf Disease Detection

## 🌟 Overview
This project aims to tackle the challenge of detecting plant diseases, specifically early and late blight in potato crops, using advanced deep learning techniques. Early and late blight, caused by **Alternaria solani** and **Phytophthora infestans** respectively, are significant threats to global agriculture. Accurate and timely detection of these diseases is crucial for minimizing crop yield loss.

## 🛠 Methodology
We developed a Convolutional Neural Network (CNN) model that achieves a 98.10% accuracy in detecting these diseases. The model was trained on a dataset of potato leaf images, and it demonstrated a 100% confidence in identifying early and late blight.

## ✨ Features
- **💡 Deep Learning Model**: A CNN model that accurately classifies potato leaf diseases.
- **🌐 Web Application**: A user-friendly interface built with FastAPI that allows users to drag and drop images for disease detection.
- **⚙️ TensorFlow Server**: Backend powered by TensorFlow, ensuring fast and reliable disease diagnostics.

## 🚀 Future Work
- **🔍 Integration with Vision Transformers (ViTs)**: Combining CNNs with ViTs to improve image processing and classification accuracy.
- **📱 Mobile Application**: Developing a React Native mobile app to provide farmers with on-the-go diagnostic tools.

## 🌍 Impact
This project highlights the potential of machine learning in plant disease diagnostics, offering a scalable and accessible solution for improving crop management and enhancing global food security.

## 📦 Installation and Usage
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/potato-disease-detection.git
    ```
2. Install the necessary dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the FastAPI server:
    ```bash
    uvicorn app.main:app --reload
    ```
4. Access the web application by navigating to `http://localhost:8000` in your web browser.

   ## 🚀 Try It Out on Google Colab
You can run the model and test it directly on Google Colab by following this [link](https://colab.research.google.com/drive/1Aok7p4P8kQ9-ecpiL029g1Q2CuOPbl4x?usp=sharing).


