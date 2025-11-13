# 🛒 Retail Demand Forecasting App  


<img width="1915" height="794" alt="Screenshot 2025-10-25 130915" src="https://github.com/user-attachments/assets/0aa9c93d-c3ee-4826-98ae-d315d9036511" />

---

![Python](https://img.shields.io/badge/Python-3.10%2B-blue.svg)
![Streamlit](https://img.shields.io/badge/Framework-Streamlit-red.svg)
![XGBoost](https://img.shields.io/badge/Model-XGBoost-orange.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Status](https://img.shields.io/badge/Status-Active-success.svg)

---

## 🧩 Overview  

The **Retail Demand Forecasting App** is a modern, AI-powered Streamlit application that predicts retail demand using advanced machine learning models like **XGBoost**, **Transformer Networks**, and **scaling pipelines**.

Designed for data-driven retail management, it empowers users to:
- 📊 Analyze historical data patterns  
- ⚙️ Predict future demand accurately  
- 📦 Optimize inventory and logistics  
- 💡 Visualize forecast insights interactively  

---


## ⚙️ Tech Stack  

| Category | Technology Used |
|-----------|----------------|
| **Frontend / UI** | Streamlit |
| **Backend / ML** | Python, XGBoost, Transformer (Keras/TensorFlow) |
| **Data Handling** | Pandas, NumPy, Scikit-learn |
| **Visualization** | Matplotlib, Seabor
---

## 🚀 Quick Start  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/sarthakmaggo/retail-demand-forecasting.git
cd Retail-Demand-Forecasting-Streamlit-App
```
### 2️⃣ Create and Activate Virtual Environment
```bash
python -m venv venv
source venv/bin/activate     # On Windows: venv\Scripts\activate
```
### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt

## 📈 Output

<img width="1835" height="387" alt="Screenshot 2025-10-25 130938" src="https://github.com/user-attachments/assets/12b11c53-ef6c-4570-b8e8-dd73125eb62b" />
<img width="1810" height="685" alt="Screenshot 2025-10-25 130956" src="https://github.com/user-attachments/assets/fce316f9-bb53-4a6c-ab6a-89a554b974fd" />
<img width="1788" height="698" alt="Screenshot 2025-10-25 131008" src="https://github.com/user-attachments/assets/de806421-eb41-4995-b7f0-5a43f55d16d5" />
<img width="1761" height="643" alt="Screenshot 2025-10-25 131024" src="https://github.com/user-attachments/assets/568c0702-fc2e-4218-af10-84aa9608ef37" />

---
## 📈 Features

✅ **Hybrid ML Forecasting** — Combines XGBoost and Transformer models for optimal results  
✅ **Dynamic MAPE Calculation** — Real-time performance feedback on uploaded test CSVs  
✅ **Custom CSV Uploads** — Forecast on your own data instantly  
✅ **Interactive Plots** — Demand trends, comparison charts, and error distributions  
✅ **Clean UI/UX** — Aesthetic, dark-mode friendly dashboard

---

## 🧠 Model Workflow

| Step | Description |
|------|-------------|
| **Preprocessing** | Feature engineering, scaling, and encoding handled via `utils/preprocessing.py` |
| **Model Prediction** | Hybrid inference using `xgb_model.pkl` and `transformer_model.keras` |
| **Post-Processing** | Inverse scaling and accuracy metrics (MAPE/SMAPE) |
| **Visualization** | Interactive plots displayed in Streamlit dashboard |

---

## 📊 Example Output

| Date       | Product    | Actual Demand | Predicted Demand | Error (%) |
|------------|-----------|---------------|-----------------|-----------|
| 2025-10-20 | Product A | 102           | 98              | 3.9       |
| 2025-10-21 | Product B | 205           | 198             | 3.4       |
| 2025-10-22 | Product C | 78            | 81              | 3.8       |

⚡ **Average MAPE across test data:** ≈ 3%

---

## 🧰 Utilities

| File                    | Functionality |
|-------------------------|---------------|
| `preprocessing.py`      | Cleans data, scales features, encodes categorical columns |
| `metrics.py` (optional) | Contains MAPE, SMAPE, RMSE calculation functions |
| `visualization.py` (optional) | Generates performance plots and trend visuals |

 

## 🌟 Support

If you found this project useful, consider giving it a ⭐ on GitHub!



