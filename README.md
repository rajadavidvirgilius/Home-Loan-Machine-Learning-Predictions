# Machine Learning untuk Prediksi Pinjaman Bank

## Deskripsi
Proyek ini bertujuan untuk memprediksi apakah aplikasi pinjaman rumah akan disetujui atau tidak berdasarkan berbagai fitur seperti pendapatan pemohon, jumlah tanggungan, jumlah pinjaman, dan lainnya. Model machine learning menggunakan dataset yang terdiri dari berbagai fitur tersebut untuk melakukan prediksi.

## Data
Data yang digunakan dalam proyek ini tersedia dalam format CSV dan terdiri dari berbagai kolom, yakni:
- Loan_ID: ID peminjam (unique code)
- Gender: jenis kelamin peminjam (Male/Female)
- Dependents: jumlah tanggungan peminjam
- ApplicantIncome: pendapatan peminjam
- CoapplicantIncome: pendapatan pasangan dari peminjam
- LoanAmount : jumlah pinjaman yang diminta
- Loan_Amount_Term : jangka waktu pinjaman dalam bulan
- Loan_Status: status persetujuan pinjaman

## Model Machine Learning
Model machine learning yang digunakan untuk memprediksi status pinjaman adalah regresi logistik (LogisticRegression) dengan features ApplicantIncome, CoapplicantIncome, LoanAmount, dan Loan_Amount_Term terhadap target yakni Loan_Status. LogisticRegression adalah algoritma klasifikasi yang umum digunakan untuk memodelkan probabilitas bahwa suatu insance data masuk ke dalam kelas tertentu

## Penggunaan
1. Clone repositori ini ke local Anda:
2. Masuk ke direktori proyek
3. Pastikan Anda memiliki Python yang sesuai dengan depedensi yang diperlukan
