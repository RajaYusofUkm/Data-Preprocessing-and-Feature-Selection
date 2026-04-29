# Ridership KL Feature Selection

Projek ini membina model klasifikasi untuk meramal sama ada permintaan pengangkutan awam di Kuala Lumpur adalah tinggi atau tidak pada sesuatu hari.

Notebook utama menggabungkan beberapa sumber data, termasuk:

- data ridership harian
- data harga minyak
- data cuti umum Malaysia
- data cuaca Kuala Lumpur

## Objektif

- Membina target `high_demand` berdasarkan jumlah ridership harian.
- Menggabungkan data luaran yang boleh mempengaruhi permintaan pengangkutan awam.
- Membandingkan prestasi model selepas feature selection.

## Kaedah

Antara langkah yang digunakan dalam notebook ini ialah:

- pembersihan dan penyediaan data
- one-hot encoding untuk feature kategori
- standardization menggunakan `StandardScaler`
- train-test split secara kronologi supaya tiada data leakage
- feature selection menggunakan Mutual Information dan RFE
- dimensionality reduction menggunakan PCA
- penilaian model menggunakan Accuracy, Precision, Recall, dan F1 Score

## Fail Utama

- `Assignment1_Ridership_KL_Feature_Selection_REVISED.ipynb`

## Hasil

Hasil akhir projek disimpan dalam fail CSV seperti:

- `model_performance_results.csv`
- `mutual_information_feature_scores.csv`
- `rfe_feature_ranking.csv`

## Cara Jalankan

1. Buka notebook dalam Jupyter atau VS Code.
2. Pastikan semua library diperlukan dipasang.
3. Run semua cell dari atas ke bawah.

Jika mahu, anda boleh tambah bahagian ini kemudian:

- ringkasan dapatan penting
- limitasi kajian
- cadangan penambahbaikan
