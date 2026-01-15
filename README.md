# Telco Churn Prediction
Created by Rivaldo Nugradwiyanto

## Latar Belakang

Industri telekomunikasi memiliki tingkat persaingan yang tinggi sehingga churn pelanggan menjadi tantangan utama. Pelanggan dapat dengan mudah berpindah penyedia layanan akibat faktor harga, kontrak, maupun kualitas layanan. Oleh karena itu, perusahaan perlu memahami karakteristik pelanggan yang berpotensi churn agar dapat menerapkan strategi retensi yang tepat dan efektif.

## Dataset

Dataset Telco Customer Churn berisi informasi demografis pelanggan, jenis layanan yang digunakan, detail kontrak, dan metode pembayaran. Target variabel adalah status churn pelanggan (0: Tidak Churn, 1: Churn).

### Attribute Information

| Attribute | Data Type | Description |
| --- | --- | --- |
| Dependents | object | customer mempunyai tanggungan atau tidak |
| tenure | int | total sudah berapa bulan pelanggan berlangganan |
| OnlineSecurity | object | memiliki layanan online security atau tidak |
| OnlineBackup | object | memiliki layanan online backup atau tidak |
| InternetService | object | jenis layanan internet yang digunakan |
| DeviceProtection | object | memiliki layanan device protection atau tidak |
| TechSupport | object | memiliki layanan tech support atau tidak |
| Contract | object | jenis kontrak berdasarkan durasi |
| PaperlessBilling | object | apakah pelanggan menggunakan tagihan paperless |
| MonthlyCharges | float | jumlah biaya langganan setiap bulan |
| Churn | object | apakah pelanggan berhenti berlangganan atau tidak |

## Proses Analisis

Analisis dilakukan melalui EDA untuk memahami pola churn, dilanjutkan dengan preprocessing data dan pengembangan model klasifikasi. Evaluasi model memprioritaskan recall untuk meminimalkan pelanggan churn yang tidak terdeteksi, serta penyimpanan model ke dalam format pickle untuk penggunaan selanjutnya.
