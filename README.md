# 🖼️ Image Caption Generator using CNN + LSTM

This project implements a deep learning model that generates human-like captions for images using an encoder-decoder architecture. The encoder uses **InceptionV3** to extract image features, and the decoder leverages **LSTM** to generate textual descriptions. Trained on the **Flickr8k dataset**, the model can describe unseen images with contextually relevant captions.

---

## 📌 Objective

Automatically generate human-like captions for input images using a combination of Convolutional and Recurrent Neural Networks.

---

## 🔧 Tech Stack

- Python 3.x
- TensorFlow / Keras
- InceptionV3 (CNN Encoder)
- LSTM (Decoder)
- NumPy, Pandas, Matplotlib
- Flickr8k Dataset
- Beam Search (optional)
- Streamlit / Gradio (optional for UI)

---

## 🧠 Model Architecture

- **Encoder**: Pretrained **InceptionV3** (with the top classification layer removed) to extract image embeddings.
- **Decoder**: LSTM-based network trained on image-caption sequences.
- **Tokenizer**: Used for vocabulary creation and sequence padding.
- **Training**: Teacher forcing using image-caption pairs.
- **Inference**: Greedy or Beam Search to generate fluent captions.

---

## 🖼️ Example Output

> **Input**: A photo of a dog playing in the park  
> **Generated Caption**: *"A dog playing with a ball in the grass."*

---

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/Ramen4611/-Image-Caption-Generator.git
cd -Image-Caption-Generator
