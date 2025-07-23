# 🍏 Apple Leaf Disease Prediction using CNN

[![Python](https://img.shields.io/badge/Python-3.9-blue)](https://www.python.org/)
[![Model](https://img.shields.io/badge/Model-CNN-green)]()
[![Status](https://img.shields.io/badge/Status-Completed-brightgreen)]()
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

<img src="https://media.giphy.com/media/kH5k2G7Dz5iF2/giphy.gif" alt="Leaf" width="100%"/>

---

## 📌 Project Overview

This project detects diseases in **apple leaves** using a **Convolutional Neural Network (CNN)**. It classifies leaf images into multiple disease categories and helps in early detection to reduce crop loss.

> 🔍 Built using Python, TensorFlow, and Streamlit.

---

## 🧠 Model Details

- **Model**: CNN (Convolutional Neural Network)
- **Framework**: TensorFlow / Keras
- **Input Image Size**: 224x224
- **Accuracy Achieved**: ~97%
- **Output**: Leaf classified into one of 4 categories

---

## 🗂️ Dataset

- Source: [PlantVillage Dataset on Kaggle](https://www.kaggle.com/datasets/emmarex/plantdisease)
- Total Images: 6,000+
- Classes:
  - Apple Scab 🍂
  - Black Rot 🖤
  - Cedar Apple Rust 🍁
  - Healthy 🌿

---

## 💻 Project Structure

```
apple-leaf-disease-prediction/
├── dataset/                  # Images (train/test)
├── model/                    # Saved .h5 or .tflite model
├── app.py                    # Web UI (Streamlit)
├── main.py                   # Training and prediction logic
├── requirements.txt
├── README.md
└── assets/                   # Screenshots and GIFs
```

---

## 🚀 How to Use

### ▶️ Local Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/apple-leaf-disease-prediction.git
   cd apple-leaf-disease-prediction
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the app**
   ```bash
   streamlit run app.py
   ```

---

## 🌐 Web App Preview

> Powered by **Streamlit** for real-time prediction.

<img src="assets/app_demo.gif" width="100%" alt="App Preview"/>

---

## 📈 Model Performance

| Metric     | Score  |
|------------|--------|
| Accuracy   | 97.5%  |
| Precision  | 96.8%  |
| Recall     | 96.2%  |
| F1-Score   | 96.5%  |

---

## 📤 Deployment Options

- 🔗 [Streamlit Cloud](https://streamlit.io/)
- ☁️ [Render.com](https://render.com/)
- 🤗 [Hugging Face Spaces](https://huggingface.co/spaces)

---

## 👨‍💻 Author

**Ajeet Rawat**  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?logo=linkedin)](https://www.linkedin.com/in/ajeet-rawat-8a4b91251/)  
[![GitHub](https://img.shields.io/badge/GitHub-grey?logo=github)](https://github.com/ajeetrawat-dev)

---

## 📃 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

> ⭐ Star this repository if you found it helpful!
