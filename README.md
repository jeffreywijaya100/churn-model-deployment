**Customer Churn Prediction — Machine Learning for Banking Retention Strategy**

Pada proyek ini, saya berperan sebagai Data Scientist di sebuah institusi perbankan dengan tanggung jawab untuk membangun sistem prediksi churn nasabah. Tujuan utama dari proyek ini adalah mendeteksi nasabah yang berpotensi meninggalkan layanan bank, sehingga manajemen dapat menerapkan strategi retensi secara proaktif dan tepat sasaran.

📌 Tahapan Pengerjaan
1. Machine Learning Modeling & Evaluation

    - Melakukan data pre-processing untuk memastikan kualitas input ke model:
    
      - Handling missing values
      
      - Encoding categorical variables
      
      - Scaling/normalization
    
      - Train–test split
    
    - Membangun dan melatih model klasifikasi menggunakan Random Forest dan XGBoost
    
    - Melakukan hyperparameter tuning untuk meningkatkan performa model
    
    - Mengevaluasi performa setiap model menggunakan classification report (precision, recall, F1-score, accuracy)
    
    - Memilih model terbaik berdasarkan performa pada test dataset dan menyimpan model dalam format .pkl menggunakan Pickle

2. Model OOP Conversion

  - Seluruh rangkaian proses training dari model terbaik diubah ke dalam bentuk Object-Oriented Programming
  
  - Implementasi kelas yang mencakup:

    - Data preprocessing
  
    - Training
      
    - Model evaluation
      
    - Model saving

3. Deployment Prediction Code

    Menyusun script inference untuk deployment yang memuat:
  
    - Load .pkl model
  
    - Preprocessing input pengguna secara otomatis
  
    - Fungsi prediksi churn untuk data baru

4. Deployment via Streamlit

    - Membangun UI sederhana pada Streamlit untuk memfasilitasi input data nasabah
  
    - Integrasi dengan prediction code untuk memberikan hasil prediksi secara real-time
  
    - Melakukan 2 pengujian test case untuk memverifikasi akurasi hasil prediksi dan stabilitas sistem


Testing with data:

- percobaan dengan data baris ke 0 : not churn

![image](https://github.com/user-attachments/assets/452e7401-f573-42bf-9d1b-ddf9bf3e476d)

- percobaan dengan data baris ke 21 :  churn

![image](https://github.com/user-attachments/assets/25316f63-8b26-4d3e-a478-4119edc3ee08)
