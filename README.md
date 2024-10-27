# Automobile Price Prediction using Linear Regression

Proyek ini bertujuan untuk memprediksi harga mobil berdasarkan beberapa fitur seperti horsepower, weight, dan engine size menggunakan model regresi linear. Kami menggunakan Python dan pustaka populer seperti Pandas, Seaborn, dan Scikit-Learn untuk analisis, visualisasi, dan pemodelan data.

## Tabel Isi

- [Deskripsi Proyek](#deskripsi-proyek)
- [Struktur Dataset](#struktur-dataset)
- [Instalasi](#instalasi)
- [Langkah-Langkah Analisis dan Pemodelan](#langkah-langkah-analisis-dan-pemodelan)
  - [1. Mengimpor Pustaka](#1-mengimpor-pustaka)
  - [2. Memuat Dataset](#2-memuat-dataset)
  - [3. Eksplorasi Data Awal](#3-eksplorasi-data-awal)
  - [4. Preprocessing Data](#4-preprocessing-data)
  - [5. Visualisasi Data](#5-visualisasi-data)
  - [6. Membangun Model](#6-membangun-model)
  - [7. Evaluasi Model](#7-evaluasi-model)
- [Contributing](#contributing)
- [License](#license)

---

## Deskripsi Proyek

Proyek ini adalah analisis harga mobil dengan menggunakan model regresi linear untuk memprediksi harga berdasarkan fitur-fitur tertentu. Dataset yang digunakan berisi informasi spesifikasi mobil, yang diproses dan divisualisasikan untuk memahami hubungan antar-fitur sebelum membangun model prediktif.

## Struktur Dataset

Dataset berisi beberapa kolom, termasuk:

- **symboling**: Indikator risiko asuransi (integer)
- **normalized_losses**: Rata-rata kerugian yang dinormalisasi
- **make**: Merek mobil
- **fuel_type**: Jenis bahan bakar
- **aspiration**: Tipe aspirasi mesin (turbo atau standar)
- **engine_size**: Ukuran mesin
- **horsepower**: Tenaga mesin
- **price**: Harga mobil (target)

## Instalasi

1. Pastikan Python 3.6+ sudah terinstal di sistem Anda.
2. Instal pustaka yang diperlukan:
   ```bash
   pip install -r requirements.txt
