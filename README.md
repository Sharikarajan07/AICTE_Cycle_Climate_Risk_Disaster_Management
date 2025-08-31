# 🌍 AICTE Cycle 3 (2025) - Climate Risk & Disaster Management

## 📌 Project: AI-Powered Climate Risk Prediction & Disaster Management

### 📖 Overview

This project develops an **AI/ML-based climate risk and disaster management system** to **predict, monitor, and mitigate natural disasters** such as floods, cyclones, and droughts.
The system uses **historical climate data, satellite imagery, and weather patterns** to provide **early warning systems** and **decision support** for communities and authorities.

### 📂 Dataset

* **Sources**:

  * IMD (Indian Meteorological Department) data
  * NASA Earth Data / NOAA Climate Data
  * Kaggle Disaster Management datasets
* **Data Types**:

  * Weather time-series (temperature, rainfall, humidity, wind speed)
  * Satellite/remote sensing imagery
  * Past disaster event records (floods, droughts, cyclones, landslides)

📊 **Size**: \~20,000+ records (structured + unstructured data)

### ✅ Week 1 Progress (30% Completed)

* ✔️ Data collection from multiple open-source climate & disaster datasets
* ✔️ Preprocessing of time-series (handling missing values, normalization, trend analysis)
* ✔️ Satellite imagery preprocessing (resizing, normalization, noise reduction)
* ✔️ Initial exploratory data analysis (heatmaps, seasonal patterns, extreme event distribution)
* ✔️ Train-test split for predictive modeling (time-series forecasting + classification tasks)

📊 **Outcome:** Dataset is **structured, cleaned, and prepared** for predictive model training (Week 2).

### 🛠️ Technologies Used

* **Python 3.x**
* **Pandas / NumPy** → Data Handling
* **Matplotlib / Seaborn / Plotly** → Visualization & Analytics
* **Scikit-learn** → ML Preprocessing & Utilities
* **TensorFlow / PyTorch** → Deep Learning Models (forecasting & classification)
* **OpenCV / Rasterio** → Satellite Image Processing

### 📂 Project Structure

```
├── week1.ipynb                        # Week 1: Data Cleaning & EDA
├── Climate_Data/                      # Raw + Processed Datasets
├── .gitignore                         # Ignore unnecessary files
└── README.md                          # Project Documentation
```

### 🚀 How to Run

1. Clone this repository:

   ```bash
   git clone <your-repo-link>.git
   cd <repo-name>
   ```

2. Install dependencies:

   ```bash
   pip install numpy pandas matplotlib seaborn plotly scikit-learn tensorflow opencv-python rasterio
   ```

3. Download the **climate & disaster datasets** and place them inside `Climate_Data/`.

4. Run the notebook:

   ```bash
   jupyter notebook week1_data_preprocessing.ipynb
   ```

### 📅 Next Phases

* **Week 2 (40–60%)** → Predictive Model Development (time-series forecasting + classification)
* **Week 3 (60–80%)** → Model Optimization, Multi-modal Integration (climate + satellite data)
* **Week 4 (80–100%)** → Deployment (early warning system prototype + documentation)

