# Deep_learning_models

# 🧠 Deep Learning Projects

This repository contains my hands‑on Deep Learning projects built using **TensorFlow/Keras**.  
Each project is organized in its own folder with code, datasets (or links), and saved models.

---

## 📂 Projects Included

### 1️⃣ Cats vs Dogs Classifier (CNN)
- **Type:** Image Classification
- **Description:** A Convolutional Neural Network (CNN) trained to classify images as cats 🐱 or dogs 🐶.
- **Dataset:** [Kaggle - Dogs vs Cats](https://www.kaggle.com/c/dogs-vs-cats/data)
- **Key Features:**
  - Image preprocessing with `ImageDataGenerator`
  - Multiple `Conv2D` + `MaxPooling2D` layers
  - Dropout for regularization
  - Model evaluation and prediction on new images
- **Saved Model:** `.h5` format in the project folder.

---

### 2️⃣ Diabetes Prediction Model (DL)
- **Type:** Tabular Data Classification
- **Description:** Fully connected Deep Neural Network (DNN) to predict diabetes based on medical features.
- **Dataset:** [PIMA Indians Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- **Key Features:**
  - Data normalization
  - Dense layers with ReLU activation
  - Binary classification output
  - Evaluation metrics for accuracy

---

## ⚙️ Installation & Usage

## ⚙️ Setup & Usage

```bash
# 1️⃣ Clone the repo
git clone https://github.com/Arun-cat/Deep_Learning.git
cd Deep_Learning

# 2️⃣ (Optional) Create & activate virtual environment
python -m venv .venv
# Mac/Linux
source .venv/bin/activate
# Windows
.venv\Scripts\activate

# 3️⃣ Install dependencies
pip install -r requirements.txt

# 4️⃣ Run a project
cd "Cats_vs_Dogs"
python cnn_cats_dogs.py

