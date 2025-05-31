# 🌊 Flood Prediction System using Machine Learning

This project predicts flood probability using a machine learning model trained on environmental and socio-economic factors.

## 📊 Dataset

- Features include:
  - Monsoon Intensity
  - Urbanization
  - Wetland Loss
  - Encroachments
  - Deforestation
  - Drainage Systems
  - ...and more
- Target: `FloodProbability` (continuous value between 0 and 1)

## ⚙️ Model Used

- **Algorithm**: Random Forest Regressor (from `sklearn.ensemble`)
- **Performance**:
  - R² Score: 0.96
  - Mean Squared Error: 0.0043

## 🔍 Key Features Impacting Flood Risk

- Wetland Loss
- Urbanization
- Inadequate Planning
- Siltation
- Encroachments

## 🛠️ Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn
- Seaborn, Matplotlib
- Google Colab

## 🧠 Insights

The Random Forest model shows high accuracy, revealing that anthropogenic factors like poor planning and wetland degradation significantly increase flood risk.

## 🗂️ Files

- `flood_prediction.ipynb`: Main ML notebook
- `flood_data.csv`: Input dataset
- `README.md`: Project overview


