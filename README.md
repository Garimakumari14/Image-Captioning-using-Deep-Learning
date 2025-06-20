# Image-Captioning-using-Deep-Learning

# 🖼️ Image Captioning using Deep Learning

This project is an end-to-end image captioning system that combines **Convolutional Neural Networks (CNN)** and **Recurrent Neural Networks (RNN)** with an **attention mechanism** to generate human-like captions for images.

## 📌 Overview

- Used **InceptionV3** (CNN) to extract features from images.
- Used **LSTM** for sequence generation (caption).
- Integrated **Bahdanau Attention** to improve contextual understanding and caption quality.

## 🛠️ Tech Stack

- Python  
- TensorFlow & Keras  
- InceptionV3, LSTM  
- NumPy, Matplotlib  
- Jupyter Notebook / Google Colab

## 🗂️ Dataset

- Used **Flickr8k** (or a similar dataset) containing images with multiple human-written captions.

## 🧠 Model Workflow

1. Extract image features using InceptionV3 (excluding top layer).
2. Preprocess and tokenize captions.
3. Train an LSTM model with attention to learn image-to-text mapping.
4. Evaluate with BLEU Score and generate predictions.

## 📷 Sample Output

| Input Image | Predicted Caption |
|-------------|-------------------|
| ![sample](sample_images/dog.jpg) | "A dog is running on the grass" |

## 📈 Results

- Captions generated are context-aware and grammatically correct.
- Attention mechanism significantly improved the caption relevance.
- Evaluated using BLEU score.

## 💡 Future Improvements

- Use larger datasets like MS COCO for better generalization.
- Fine-tune CNN layers during training.
- Try transformer-based models (e.g., Vision Transformer + GPT).
