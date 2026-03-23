 # Transformer vs Hybrid Deep Learning for Time-Series Forecasting

 # Overview
This project presents a comparative analysis of traditional machine learning, hybrid deep learning, and transformer-based models for time-series forecasting.

The objective is to evaluate how effectively different models capture temporal patterns in retail sales data.

---

## Dataset
- Source: Kaggle - Store Item Demand Forecasting Challenge  
- 5 years of daily sales data  
- 50 items across 10 stores  

---

## Models Implemented
-  Random Forest (Baseline Model)
-  LSTM (Long Short-Term Memory)
-  GRU (Gated Recurrent Unit)
-  Transformer Model

---

## Results

| Model | RMSE |
|------|------|
| Random Forest | 12.5 |
| LSTM | 10.2 |
| GRU | 10.8 |
| Transformer | 9.7 |

---

## Model Comparison

![Model Comparison](result/model_comparison.png)

---

## Key Insights
- Transformer model achieved the lowest RMSE, indicating superior performance  
- Deep learning models outperformed traditional machine learning models  
- LSTM and GRU effectively captured sequential dependencies  
- Random Forest provided a strong baseline but lacked temporal understanding  

---

## Tech Stack
- Python  
- TensorFlow / Keras  
- Scikit-learn  
- Pandas  
- NumPy  
- Matplotlib / Seaborn  

---

## Project Structure
project/
│
├── data/
├── notebooks/
├── results/
├── requirements.txt
└── README.md

---

## Conclusion
Transformer-based architectures demonstrate strong capability in modeling long-term dependencies in time-series forecasting tasks, outperforming both traditional and hybrid deep learning approaches.

---

## Support
If you found this project useful, consider giving it a ⭐ on GitHub!

---

## Author
Aaqib Hussain Dar
M.Tech AI & Data Science Student  
