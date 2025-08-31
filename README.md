# 🐱🧬 CatCRISPR: Predicting sgRNA Efficiency with CatBoost  

This project focuses on predicting **sgRNA efficiency scores** using **CatBoost**, a gradient boosting algorithm on decision trees, with **one-hot encoded sequence features**.  

## 📋 Project Overview  

Designing efficient sgRNAs is essential for accurate **CRISPR-Cas9** genome editing.  
**CatCRISPR** applies machine learning to predict sgRNA efficiency by:  

- Encoding sequences into **one-hot vectors**  
- Training a **CatBoost regression model**  
- Evaluating performance with **cross-validation** and regression metrics  

## 📁 Project Structure  

- `Code/` – Source code for preprocessing, fine tunning, and training  
- `Data/` – Input datasets of sgRNA sequences and labels  
 

## 🚀 Key Features  

1. 🐱 **CatBoost regression** for sgRNA efficiency prediction  
2. 🔡 **One-hot encoding** of sgRNA sequences  
3. 🔄 **5-fold cross-validation** for robust evaluation  
4. 📉 Regression metrics: Spearman, Pearson correlation  
5. 📊 Feature importance analysis to understand sequence influence  

## 💻 Installation  

Clone the repository and install dependencies:  

```bash
git clone https://github.com/Sizerta/CatCrispr
cd CatCRISPR
pip install -r requirements.txt
