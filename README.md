# Forecasting Nilai Tukar USD/IDR Menggunakan ARIMA

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge\&logo=python\&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge\&logo=pandas\&logoColor=white)
![ARIMA](https://img.shields.io/badge/Model-ARIMA-success?style=for-the-badge)
![Plotly](https://img.shields.io/badge/Dashboard-Plotly-blue?style=for-the-badge)

## 📌 Project Overview

Proyek ini bertujuan untuk menganalisis dan memprediksi pergerakan nilai tukar **USD terhadap Rupiah Indonesia (USD/IDR)** menggunakan metode **ARIMA (AutoRegressive Integrated Moving Average)**.

Analisis dilakukan pada data historis nilai tukar USD/IDR untuk memahami pola pergerakan kurs, mengidentifikasi tren jangka panjang, serta menghasilkan prediksi nilai tukar untuk 30 hari ke depan.

---

## 🚀 Key Results

| Hasil                 | Nilai             |
| --------------------- | ----------------- |
| Model Terbaik         | **ARIMA (5,1,4)** |
| Jumlah Observasi      | **1.676 data**    |
| AIC                   | **20,264.437**    |
| Nilai Aktual Terakhir | **18.031**        |
| Forecast Akhir        | **18.138**        |
| Perubahan Forecast    | **+0.59%**        |

> [!IMPORTANT]
> Hasil forecasting menunjukkan bahwa nilai tukar USD/IDR diperkirakan mengalami kenaikan secara bertahap dalam 30 hari ke depan dengan volatilitas yang relatif stabil.

---

## 📈 Forecast Result

<img width="1905" height="991" alt="image" src="https://github.com/user-attachments/assets/5b4f974d-a6f9-4ccb-80ae-c9ba682ceb3b" />

*Visualisasi data historis dan hasil forecasting USD/IDR.*

---

## 📂 Dataset

| Keterangan  | Informasi           |
| ----------- | ------------------- |
| Variabel    | Nilai Tukar USD/IDR |
| Periode     | 2020 – 2026         |
| Frekuensi   | Harian              |
| Jumlah Data | 1.676 Observasi     |
| Sumber Data | Yahoo Finance       |

---

## 🔄 Workflow

```text
Data Collection
      ↓
Data Cleaning
      ↓
Exploratory Data Analysis
      ↓
Stationarity Testing (ADF Test)
      ↓
Differencing
      ↓
Auto ARIMA Selection
      ↓
Model Evaluation
      ↓
Forecasting
      ↓
Dashboard Visualization
```

---

## 📊 Data Visualization

### Historical Exchange Rate

<img width="1158" height="451" alt="image" src="https://github.com/user-attachments/assets/e4ceeb41-ffc0-4ba4-a069-06f27369aba8" />

*Pergerakan historis nilai tukar USD/IDR.*

### Forecast Visualization

<img width="1178" height="547" alt="image" src="https://github.com/user-attachments/assets/8f9cc4cf-9628-48cf-b9de-4744d5868481" />

*Perbandingan data aktual dan hasil forecasting.*

---

## 🧮 Model Performance

### Model Terpilih

```text
ARIMA (5,1,4)
```

### Evaluasi Model

| Metric            | Value       |
| ----------------- | ----------- |
| AIC               | 20,264.437  |
| Log Likelihood    | -10,122.218 |
| Ljung-Box p-value | 0.78        |
| Observasi         | 1.676       |

> [!NOTE]
> Nilai p-value Ljung-Box sebesar 0.78 (> 0.05) menunjukkan bahwa residual model tidak memiliki autokorelasi yang signifikan sehingga model layak digunakan untuk forecasting.

---

## 📅 Forecasting Results

| Periode    | Prediksi USD/IDR |
| ---------- | ---------------- |
| Hari ke-1  | 18.093           |
| Hari ke-5  | 18.102           |
| Hari ke-10 | 18.109           |
| Hari ke-15 | 18.118           |
| Hari ke-20 | 18.126           |
| Hari ke-25 | 18.132           |
| Hari ke-30 | 18.138           |

### Trend Analysis

* USD/IDR diprediksi mengalami kenaikan secara bertahap.
* Tidak ditemukan lonjakan ekstrem selama periode peramalan.
* Nilai tukar diperkirakan meningkat sekitar 0.59% dalam 30 hari ke depan.
* Tren menunjukkan kecenderungan penguatan USD terhadap Rupiah dalam jangka pendek.

---

## 🎯 Key Findings

✅ Data nilai tukar USD/IDR menunjukkan pola yang dapat dimodelkan menggunakan pendekatan ARIMA.

✅ Auto ARIMA memilih model ARIMA (5,1,4) sebagai model terbaik berdasarkan nilai AIC minimum.

✅ Residual model tidak menunjukkan autokorelasi yang signifikan berdasarkan uji Ljung-Box.

✅ Forecast menunjukkan kecenderungan kenaikan USD/IDR secara bertahap dalam jangka pendek.

✅ Dashboard interaktif membantu memonitor pergerakan historis dan hasil forecasting secara visual.

---

## 🛠️ Tools & Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Plotly
* Statsmodels
* pmdarima
* Jupyter Notebook

---
