# 🩺 Skin Disease Classification with Explainable AI

This project uses machine learning and deep learning to classify skin diseases, and applies **Explainable AI (XAI)** techniques to make the model's predictions easier to understand and trust.

---

## 📁 Repository Contents

| File | Description |
|------|-------------|
| `Data.zip` | The skin disease image dataset used to train and evaluate the models (~169 MB, stored with Git LFS). |
| `Skin Disease Classification_Clinical.ipynb` | Clinical evaluation of the classification model. |
| `Skin Disease Classification_K fold.ipynb` | K-Fold cross-validation to check how well the model generalizes across different data splits. |
| `Skin Disease Classification_Grad-CAM.ipynb` | Grad-CAM visualizations that highlight the regions of the skin image the model focuses on when making a prediction (stored with Git LFS). |
| `Skin Disease Classification_Lime.ipynb` | LIME explanations for individual predictions. |
| `Skin Disease Classification_SHAP.ipynb` | SHAP analysis showing how each feature contributes to the model's output. |

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- TensorFlow / Keras
- Grad-CAM
- LIME
- SHAP

---

## 📦 Dataset and Git LFS

`Data.zip` and `Skin Disease Classification_Grad-CAM.ipynb` are large files, so they are stored using **Git Large File Storage (Git LFS)**.

You need Git LFS installed to download the actual files. Without it, you will only get small pointer files instead of the real data.

---

## 🚀 Getting Started

### 1. Install Git LFS

Download and install it from [git-lfs.com](https://git-lfs.com). It is already included with Git for Windows.

Then run this once:

```bash
git lfs install
```

### 2. Clone the repository

```bash
git clone https://github.com/Zeeshan467/Skin-disease-classification.git
cd Skin-disease-classification
```

> If you already cloned the repo before installing Git LFS, run `git lfs pull` inside the folder to download the full files.

### 3. Extract the dataset

Unzip `Data.zip` inside the project folder.

### 4. Install the required libraries

```bash
pip install jupyter tensorflow numpy pandas matplotlib scikit-learn opencv-python lime shap
```

### 5. Run the notebooks

```bash
jupyter notebook
```

Open any notebook and run the cells from top to bottom.

---

## ⚠️ Disclaimer

This project is for **educational and research purposes only**. It is not a medical diagnosis tool and should not be used in place of advice from a qualified dermatologist or healthcare professional.

---

## 👤 Author

**Zeeshan** – [GitHub](https://github.com/Zeeshan467)
