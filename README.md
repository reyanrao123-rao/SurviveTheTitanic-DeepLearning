# 🚢 TitanicFatePredictor — Deep Learning Edition

![Python](https://img.shields.io/badge/Python-3.10-blue?style=flat-square&logo=python)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?style=flat-square&logo=tensorflow)
![Gradio](https://img.shields.io/badge/Web%20App-Gradio-purple?style=flat-square)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=flat-square)

> **Upgraded from Machine Learning → Deep Learning**
> Originally built with Logistic Regression. Now powered by ANN & CNN with a full interactive web app.

---

## 📌 About This Project

This project predicts whether a **Titanic passenger survived or not** using both traditional ML and modern Deep Learning techniques.

It was built as part of a Deep Learning course task to apply all core DL concepts on a real-world dataset, and compare the results with previously built ML models.

---

## 🧠 Deep Learning Concepts Applied

| Concept | How It's Used |
|---|---|
| **ANN** | Multi-layer fully connected neural network |
| **CNN (1D)** | Conv1D treats features as a sequence |
| **ReLU** | Activation function in all hidden layers |
| **Sigmoid** | Output layer for binary classification |
| **Tanh** | Compared against ReLU and Sigmoid |
| **Adam** | Main optimizer used |
| **SGD** | Compared in optimizer experiment |
| **RMSprop** | Compared in optimizer experiment |
| **Dropout** | 0.2–0.3 rate to prevent overfitting |
| **Batch Normalization** | After each hidden layer for stable training |
| **Early Stopping** | Stops training at best validation weights |
| **Binary Crossentropy** | Loss function for binary classification |

---

## 📊 Model Results

| Model | Type | Accuracy |
|---|---|---|
| Logistic Regression | ML (Baseline) | ~79% |
| Random Forest | ML | ~82% |
| ANN | ✨ Deep Learning | ~83% |
| 1D CNN | ✨ Deep Learning | ~82% |

---

## 📁 Project Files

```
SurviveTheTitanic/
│
├── Titanic_DeepLearning_Complete.ipynb   ← Main notebook (open in Colab)
├── Titanic-Dataset.csv                   ← Dataset
└── README.md                             ← This file
```

---

## ▶️ How to Run

### Option 1 — Google Colab (Recommended)
1. Click the notebook file above
2. Click **"Open in Colab"**
3. Click **Runtime → Run All**
4. Wait for all steps to finish
5. The web app launches at the end with a public link

### Option 2 — Local
```bash
pip install tensorflow gradio pandas numpy scikit-learn matplotlib seaborn
jupyter notebook Titanic_DeepLearning_Complete.ipynb
```

---

## 🗂️ Notebook Contents

| Step | What It Does |
|---|---|
| Step 1 | Install & import all libraries |
| Step 2 | Load dataset, clean missing values, encode features |
| Step 3 | ML Baseline — Logistic Regression & Random Forest |
| Step 4 | Build, train & evaluate ANN |
| Step 5 | Compare Adam vs SGD vs RMSprop optimizers |
| Step 6 | Compare ReLU vs Tanh vs Sigmoid activations |
| Step 7 | Build, train & evaluate 1D CNN |
| Step 8 | Final comparison — all 4 models side by side |
| Step 9 | Launch Gradio web app with all 4 models |

---

## 🖥️ Web App Features

- Select from **4 models**: Logistic Regression, Random Forest, ANN, CNN
- Enter passenger details via sliders and dropdowns
- Get instant **survival prediction with probability**
- Visual probability bar shows confidence level
- Works on mobile and desktop

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| Python | Core language |
| TensorFlow / Keras | ANN & CNN models |
| Scikit-learn | Logistic Regression, Random Forest, Scaler |
| Pandas / NumPy | Data processing |
| Matplotlib / Seaborn | Visualizations & plots |
| Gradio | Interactive web app |

---

## 📸 Outputs Generated

- `model_comparison.png` — Bar chart: ML vs DL accuracy
- `all_confusion_matrices.png` — All 4 models side by side
- `ann_training_history.png` — ANN accuracy & loss curves
- `cnn_training_history.png` — CNN accuracy & loss curves
- `optimizer_comparison.png` — Adam vs SGD vs RMSprop
- `activation_comparison.png` — ReLU vs Tanh vs Sigmoid

---

## 👨‍💻 Author

**Reyan Afzal**
App link: https://af3a33ae8e04a70694.gradio.live/
Deep Learning Course Project
*Upgraded from ML → Deep Learning*

---

> ⭐ If you found this helpful, give it a star!


