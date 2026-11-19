# Skin Disease Classification Using Machine Learning and Explainable AI

## Overview

This project focuses on skin disease classification using machine learning and deep learning techniques. It explores automated skin disease recognition and incorporates Explainable Artificial Intelligence (XAI) methods to improve model interpretability and transparency.

The project includes clinical evaluation, K-Fold cross-validation, and explainability analysis using LIME and SHAP.

## Project Objectives

- Develop an automated approach for skin disease classification.
- Evaluate classification performance using clinical evaluation techniques.
- Apply K-Fold Cross-Validation to assess model generalization.
- Interpret model predictions using LIME.
- Analyze feature importance and model behaviour using SHAP.
- Explore the potential of explainable AI in healthcare applications.

## Repository Structure

```text
Skin-disease-classification/
│
├── Skin Disease Classification_Clinical.ipynb
├── Skin Disease Classification_K fold.ipynb
├── Skin Disease Classification_Lime.ipynb
├── Skin Disease Classification_SHAP.ipynb
│
└── README.md
```

## Notebooks Description

### 1. Clinical Evaluation
`Skin Disease Classification_Clinical.ipynb`

Contains the clinical evaluation and analysis of the skin disease classification approach.

### 2. K-Fold Cross-Validation
`Skin Disease Classification_K fold.ipynb`

Explores K-Fold Cross-Validation to evaluate model performance across multiple data splits and assess generalization.

### 3. LIME Explainability
`Skin Disease Classification_Lime.ipynb`

Uses Local Interpretable Model-Agnostic Explanations (LIME) to interpret individual model predictions.

### 4. SHAP Explainability
`Skin Disease Classification_SHAP.ipynb`

Uses SHapley Additive exPlanations (SHAP) to understand feature contributions and model behaviour.

## Technologies Used

- Python
- Jupyter Notebook
- Machine Learning / Deep Learning
- K-Fold Cross-Validation
- LIME
- SHAP
- Explainable Artificial Intelligence (XAI)

## Installation and Setup

1. Clone the repository:

```bash
git clone https://github.com/Zeeshan467/Skin-disease-classification.git
```

2. Navigate to the project directory:

```bash
cd Skin-disease-classification
```

3. Install Jupyter Notebook:

```bash
pip install notebook
```

4. Install the relevant Python libraries used in the notebooks.

5. Launch Jupyter Notebook:

```bash
jupyter notebook
```

6. Open the required notebook and execute the cells.

## Explainable Artificial Intelligence

This project incorporates two explainability techniques:

- **LIME:** Explains individual predictions by approximating the model locally.
- **SHAP:** Quantifies the contribution of input features to model predictions.

These techniques help investigate how the classification model generates its predictions.

## Applications

- Computer-aided skin disease classification research.
- Explainable AI in healthcare.
- Medical image classification research.
- Evaluation of machine learning models in clinical applications.

## Disclaimer

This project is intended for educational and research purposes only. It is not a substitute for professional medical diagnosis, clinical examination, or advice from qualified healthcare professionals.

## Author

**Zeeshan**

GitHub: [@Zeeshan467](https://github.com/Zeeshan467)

## Acknowledgements

This project explores the application of machine learning and Explainable AI techniques to healthcare-related classification problems.
