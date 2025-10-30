# Ujian Tengah Semester – Training Model Machine Learning

Proyek ini merupakan tugas UTS untuk melatih model machine learning menggunakan Python. Dikembangkan di **Google Colab** dan didokumentasikan di GitHub.

## Deskripsi Proyek
Model ini dibuat untuk [jelaskan tujuan model, contoh: memprediksi harga rumah / mengklasifikasi gambar / memprediksi churn pelanggan, dll].  
Dataset yang digunakan: [dataset_properti.csv"].

## Library yang Digunakan
- `pandas` – manipulasi data
- `numpy` – komputasi numerik
- `scikit-learn` – training dan evaluasi model
- `matplotlib` / `seaborn` – visualisasi 


> Daftar lengkap ada di file `requirements.txt`.

## 📂 Struktur Proyek

real_estate_price_prediction/
├── data/
│ ├── raw/
│ │ └── dataset_properti.csv
│ ├── processed/
│ │ └── property_prices_synthetic.csv
│ └── predictions/
│ └── new_samples_predictions.csv
│
├── models/
│ ├── final_best_model.pkl
│ ├── best_model.pkl
│ ├── sample_model_ridge_deg2.pkl
│ └── scaler.pkl
│
├── notebooks/
│ └── (file-file notebook analysis)
│
├── src/
│ ├── init.py
│ ├── data_preprocessing.py
│ ├── feature_engineering.py
│ ├── model_training.py
│ └── utils.py
│
├── results/
│ ├── visualizations/
│ │ ├── correlation_matrix.png
│ │ ├── histograms.png
│ │ ├── pred_vs_actual.png
│ │ ├── residuals_plot.png
│ │ ├── ridge_lasso_alpha_vs_r2.png
│ │ └── scatter_features_vs_price.png
│ │
│ ├── metrics/
│ │ ├── cv_results_summary.csv
│ │ ├── model_comparison_metrics.csv
│ │ └── top_coefficients.csv
│ │
│ └── models/
│ └── scaler_standard.pkl
│
├── docs/
│ └── README.md
│
├── requirements.txt


## Cara Menjalankan
1. Buka file `uts.ipynb` di [Google Colab](https://colab.research.google.com/drive/1nUyvDJis76a2iYJeKxJmMhxs0wdF4T0w?usp=sharing).
2. Jalankan semua cell secara berurutan.
3. Pastikan semua dependensi terinstal (Colab biasanya sudah punya library dasar).

> Jika dijalankan di lokal:
> ```bash
> pip install -r requirements.txt
> jupyter notebook
> ```

## Catatan
- Proyek ini dibuat sebagai bagian dari UTS mata kuliah [Machine Learning].
  
## Dibuat oleh
[Sang Putu Murtiyasa Wiguna]  
[2201020027]
