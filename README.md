# Pulmonary Fibrosis Classification


## Description
This project focuses on the **classification of pulmonary fibrosis** using **Vision Transformers** as the primary evaluation model, along with **VGG16** and **CNN** models for comparison.  

The goal of this project is to review the **CT diagnostic criteria** for some of the most frequent interstitial lung diseases (ILDs), including:

- **Organizing Pneumonia (OP)**  
- **Pulmonary Histiocytosis (PHS)**  
- **Pneumoconiosis (PINS)**  
- **Usual Interstitial Pneumonia (UIP)**  

Each of these types has distinct characteristics, making it essential to differentiate between them accurately.  

## Dataset
The project uses **CT scan images** with a total of **6,122 images**, divided as follows:

- **Training set:** 4,522 images  
- **Testing set:** 1,600 images  

These images were used to train and evaluate the classification models.  

## Tools & Technologies
- **Environment:** Google Colab  
- **Programming Language:** Python  
- **Libraries & Frameworks:** TensorFlow, Keras, PyTorch, Torchvision, Matplotlib  

---

## Evaluation Metrics
The models are evaluated using:
- Confusion Matrix  
- Accuracy  
- Precision  
- F1-Score  
- Recall  


## Optimizers
The following optimizers were tested:

- Adam (Adaptive Moment Estimation)  
- AdamW  
- Stochastic Gradient Descent (SGD)  


## Note
The **source code is confidential** and is not publicly shared. This repository contains only project documentation and example images.  

## Vision Transformer Architecture

![Vision Transformer Model Architecture](images/vision Transformer architecture.png)