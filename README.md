PM2.5 Prediction Using Machine Learning & Deep Learning  
(Rohtak • Hisar • Jhajjar — Hourly Data 2015–2025)

This project predicts **PM2.5 concentration levels** for three major Haryana cities using **hourly environmental data** collected over the past **10 years**.  
The dataset contains 60 attributes including weather, pollution, and atmospheric features.

Cities included  
- Rohtak  
- Hisar  
- Jhajjar  

The project uses Machine Learning and Deep Learning models like:  
✔ Naive Bayes  
✔ Support Vector Machine (SVM)  
✔ LSTM (Long Short-Term Memory)  
✔ GRU (Gated Recurrent Unit)

All steps—from **EDA to PCA to ML/DL modeling**—are implemented inside the main Jupyter notebook.

## 📂 Project Structure


For convenience, a small sample dataset is included in `data/sample/`.

---

## 📊 Exploratory Data Analysis (EDA)

The notebook includes:

- Hourly → Monthly → Yearly trends  
- Seasonal variation  
- Pollutant correlation heatmaps  
- Feature importance  
- PCA visualization  
- Missing value and outlier treatment  

---

## 🎛 Feature Engineering

- Standardization using **StandardScaler**  
- PCA dimensionality reduction (from ~60 → optimal components)  
- Sequence preparation for LSTM/GRU  
- Train-test split based on time-series format  

---

## 🤖 Models Implemented

### **1) Machine Learning Models**
- Naive Bayes  
- Support Vector Machine (SVM)

### **2) Deep Learning Models**
- LSTM  
- GRU  

Both DL models use:

- Sliding windows  
- Sequential time-series input  
- Stateful Keras layers  

---

## 📈 Performance Summary

| Model | Type | Notes |
|-------|------|-------|
| Naive Bayes | ML | Baseline, fast but limited |
| SVM | ML | Strong performance after PCA |
| LSTM | DL | Best long-term temporal accuracy |
| GRU | DL | Similar to LSTM but faster training |


---
