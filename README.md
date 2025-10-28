🧠 Klasifikasi ADHD Menggunakan Random Forest dan XGBoost

📋 Deskripsi Singkat
Proyek ini merupakan bagian dari skripsi yang bertujuan untuk mengklasifikasikan Attention Deficit Hyperactivity Disorder (ADHD) menggunakan algoritma Random Forest (RF) dan Extreme Gradient Boosting (XGBoost).
Penelitian ini memanfaatkan data dari National Survey of Children’s Health (NSCH) 2023 dan mengevaluasi performa kedua model dalam mendeteksi ADHD berdasarkan berbagai indikator kesehatan anak.

🎯 Latar Belakang
Attention Deficit Hyperactivity Disorder (ADHD) adalah gangguan neurologis yang memengaruhi kemampuan seseorang untuk memusatkan perhatian, mengendalikan impuls, dan mengatur aktivitas.
Diagnosis ADHD sering kali sulit karena gejalanya menyerupai gangguan lain. Dengan kemajuan machine learning, deteksi dini ADHD dapat dilakukan lebih efisien dan akurat.

🧩 Tujuan Penelitian
1. Melakukan klasifikasi ADHD menggunakan algoritma Random Forest dan XGBoost.
2. Membandingkan performa kedua algoritma berdasarkan metrik evaluasi.
3. Menangani ketidakseimbangan kelas (class imbalance) dengan teknik Random Undersampling (RUS).

🧮 Dataset
Sumber: National Survey of Children’s Health (NSCH) 2023
Jenis data: Tabular data
Target: Status ADHD (terdiagnosis / tidak terdiagnosis)
Teknik penanganan imbalance: Random Undersampling dengan rasio 0.3, 0.5, dan 0.7

⚙️ Metodologi
1. Preprocessing Data: Pembersihan data (handling missing values, encoding variabel kategorik), Pembagian data menjadi train, validation, dan test set
2. Modeling: Random Forest & XGBoost
3. Eksperimen dilakukan dengan tiga rasio undersampling
4. Evaluasi Model: Accuracy, Precision, Recall, F1-Score

🧾 Hasil Penelitian
Random Forest:	Akurasi 93%, F1-score	83%	(Stabil di semua rasio RUS)
XGBoost:	Akurasi 94%, F1-score	83%	(Performa terbaik secara keseluruhan)

💡 Kesimpulan:
XGBoost menunjukkan performa lebih unggul dibandingkan Random Forest, sehingga dapat menjadi pendekatan yang efektif untuk mendukung diagnosis dini ADHD dan membantu tenaga medis dalam menentukan intervensi yang tepat.
