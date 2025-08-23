
# 🖊️ Multi-Language Handwritten Digit Recognition Using Deep Learning

This project is a multilingual handwritten digit recognition system capable of identifying digits written in **English**, **Hindi**, and **Kannada**. It uses a combination of **Convolutional Neural Networks (CNNs)**, **Artificial Neural Networks (ANNs)**, and **Random Forest (RF)** classifiers. The models are deployed in an interactive **Streamlit** web application that allows users to draw digits or upload images for real-time prediction.


## 📌 Project Highlights

 Supports **three languages**: English (MNIST), Hindi (Devanagari), Kannada
 Implements **9 models** (3 per language: CNN, ANN, RF)
 Interactive **Streamlit** web interface for digit prediction
 Input via **drawing canvas** or **image upload**
 Real-time inference with dynamic preprocessing based on the selected model


##  Models Implemented

| Model Type | Description | Accuracy |
|------------|-------------|----------|
| CNN        | Best performing deep learning model using spatial feature extraction | 96–99% |
| ANN        | Lightweight deep learning model with dense layers | 90–94% |
| RF         | Classical ML model using decision trees | 85–88% |


## Datasets Used

1. **English (MNIST)** – Standard 28x28 grayscale digit dataset.
2. **Hindi (Devanagari)** – MNIST-like dataset adapted for Hindi digits.
3. **Kannada** – CSV-based dataset with 28x28 grayscale pixel values.

## Tech Stack

- **Language**: Python 3.12
- **Libraries**:
  - Deep Learning: `TensorFlow`, `Keras`
  - Machine Learning: `scikit-learn`, `joblib`
  - Visualization: `matplotlib`, `seaborn`
  - UI & Deployment: `Streamlit`, `streamlit-drawable-canvas`
  - Data Handling: `NumPy`, `Pandas`
  - Image Processing: `PIL`
- **Tools**: Jupyter Notebook, Google Drive (for model hosting), GitHub
---
## Features of the Web App

- Language selection: `English`, `Hindi`, `Kannada`
- Model selection: `CNN`, `ANN`, `RF`
- Input options:
  -  Draw a digit on canvas
  -  Upload a digit image
- Real-time prediction with output display
- Error handling for invalid inputs

## 🚀 Live Demo
[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://handwritten-digit-recognition-using-deep-learning.streamlit.app/)

![WhatsApp Image 2025-08-01 at 5 14 45 PM](https://github.com/user-attachments/assets/f850f9c0-48e1-444c-ae2b-9f92fd919666)


## Challenges Faced

- Dataset format inconsistencies across languages
- Handling variability in hand-drawn inputs
- File size limitations for model uploads (CNN .h5 files)
- Dynamic preprocessing for different model types

---

## References

- [TensorFlow Documentation](https://www.tensorflow.org/)
- [Keras Documentation](https://keras.io/)
- [scikit-learn](https://scikit-learn.org/)
- [MNIST Dataset](http://yann.lecun.com/exdb/mnist/)
- [Streamlit Docs](https://docs.streamlit.io/)

