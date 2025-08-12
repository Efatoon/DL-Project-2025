# Deep Learning Project: BERT + Metadata for Review Score Prediction

## 📑 Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Evaluation Metrics](#evaluation-metrics)
- [Future Improvements](#-future-improvements)
---

## Project Overview
This project uses a hybrid deep learning model combining **BERT** for text review embeddings and **metadata features** to predict review scores.

---

## Dataset
Source: *[input_data.csv](https://github.com/user-attachments/files/21736627/input_data.csv)*
- Textual reviews + structured metadata  
- Preprocessing steps:
  - Tokenization with BERT tokenizer
  - Normalization of numerical features
  - One-hot encoding for categorical features

---

## Model Architecture
- **BERT** → Text embeddings  
- **Fully connected layers** → Metadata processing  
- **Concatenation** → Merged features  
- **Regression layer** → Final score prediction  

---

## Evaluation Metrics
- **RMSE** (Root Mean Squared Error)  
- **MAE** (Mean Absolute Error)  
- **R² Score**
---
## Future Improvements
Experiment with different pre-trained transformer models
- Hyperparameter tuning
- Incorporate more metadata features
- Use cross-validation for better evaluation

---
