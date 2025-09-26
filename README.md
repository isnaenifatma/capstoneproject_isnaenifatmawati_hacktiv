💤 Sleep Disorder Classification using IBM Granite Models

📌 Project Overview
Gangguan tidur seperti Insomnia dan Sleep Apnea merupakan masalah kesehatan yang berdampak pada kualitas hidup, produktivitas, serta risiko penyakit kronis. Capstone Project untuk Hacktiv8 – Analisis dan Prediksi Sleep Disorder menggunakan Machine Learning. Proyek ini mencakup data preprocessing, eksplorasi data, visualisasi insight, penerapan beberapa algoritma klasifikasi (Logistic Regression, Random Forest, Naive Bayes, SVM, KNN), serta evaluasi performa model.

Dalam project ini, dilakukan analisis dataset kesehatan tidur untuk:
- Mengidentifikasi faktor-faktor yang memengaruhi gangguan tidur.
- Mengklasifikasikan jenis gangguan tidur menggunakan Machine Learning.
- Mengeksplorasi potensi penggunaan IBM Granite Model (Watsonx.ai) dalam mendukung prediksi berbasis AI.
- Tujuan utama project ini adalah memberikan insight berbasis data yang dapat membantu pemahaman risiko gangguan tidur serta perbandingan performa model prediksi.

📂 Dataset 
Dataset yang digunakan: Sleep Health and Lifestyle Dataset
Sumber: Kaggle – Sleep Health and Lifestyle Dataset (https://www.kaggle.com/datasets/caymansmith/sleep-health-and-lifestyle-data-set-part-2)
Jumlah data: 374 baris × 13 kolom
Variabel penting: Age, Gender, Sleep Duration, Quality of Sleep, Stress Level, BMI Category, Blood Pressure, Heart Rate, Daily Steps, dan Sleep Disorder.

📊 Insights & Findings
1. Distribusi Gangguan Tidur:
47% Normal Sleep
33% Insomnia
20% Sleep Apnea

2. Faktor Dominan:
Durasi tidur < 6 jam → sangat berkorelasi dengan Insomnia.
Tekanan darah tinggi → berhubungan dengan Sleep Apnea.
Langkah harian rendah (< 4000) → berasosiasi dengan gangguan tidur.

3. Performa Model Klasifikasi:
- Model	Akurasi	Precision	Recall	F1-Score
- Logistic Regression	86%	0.85	0.84	0.84
- Random Forest	92%	0.91	0.92	0.91
- Naive Bayes	78%	0.77	0.76	0.76
- SVM	88%	0.87	0.86	0.87
- KNN	81%	0.80	0.79	0.79

🔎 Kesimpulan: Random Forest menghasilkan performa terbaik dengan akurasi 92%.

🤖 AI Support Explanation (IBM Granite Watsonx)

Dalam project ini, selain implementasi Machine Learning tradisional di Python, penulis juga memanfaatkan IBM Watsonx.ai dengan Granite Models untuk mendukung:
- Eksperimen prediksi berbasis LLM (Large Language Model): memberikan insight tambahan dari dataset.
- Generasi penjelasan otomatis (AI-assisted reporting): membantu membuat interpretasi hasil analisis lebih mudah dipahami.
- Validasi insight: membandingkan hasil model lokal (skikit-learn) dengan rekomendasi AI Watsonx.
Dengan pendekatan hybrid ini, project tidak hanya fokus pada implementasi algoritma klasik, tetapi juga menunjukkan bagaimana AI generatif modern bisa memperkuat workflow data science.
