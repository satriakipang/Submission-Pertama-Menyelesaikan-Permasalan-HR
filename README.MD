# Submission Pertama: Menyelesaikan Permasalahan Human Resources
Nama : Fransiskus Ricardo

Link Github : https://github.com/satriakipang/Submission-Pertama-Menyelesaikan-Permasalan-HR 

[Github](https://lookerstudio.google.com/reporting/6bb4df10-969c-4c7c-883a-bbfbb397e7fe)

[Rekaman](https://drive.google.com/file/d/1oT9eWwlTCMR7Wl4Vk-RDwoNjDuSObYQ_/view?usp=sharing)

## Business Understanding

### **Latar Belakang Bisnis**
Jaya Jaya Maju merupakan perusahaan multinasional yang telah berdiri sejak tahun 2000 dan kini memiliki lebih dari 1.000 karyawan yang tersebar di berbagai wilayah Indonesia. Meski telah menunjukkan pertumbuhan yang stabil dan ekspansi bisnis yang signifikan, perusahaan dihadapkan pada tantangan serius di bidang manajemen sumber daya manusia, terutama tingginya **attrition rate** (tingkat keluar karyawan) yang terus meningkat dalam beberapa tahun terakhir.
Tingginya tingkat attrition ini menimbulkan sejumlah konsekuensi strategis bagi perusahaan, antara lain:
* **Biaya tambahan untuk rekrutmen dan pelatihan karyawan baru**
* **Menurunnya produktivitas dan efektivitas kerja tim**
* **Hilangnya pengetahuan dan pengalaman organisasi (organizational knowledge)**
* **Penurunan semangat dan loyalitas karyawan yang tersisa**
Fenomena tersebut mengindikasikan adanya potensi masalah yang lebih mendalam, seperti rendahnya kepuasan kerja, beban kerja berlebih, ketidakseimbangan work-life balance, atau faktor eksternal seperti jarak tempat tinggal hingga kompensasi yang kurang kompetitif.

### Permasalahan Bisnis
Proyek ini bertujuan menjawab tantangan utama dalam pengelolaan SDM, yaitu:
1. **Mengungkap faktor utama penyebab karyawan keluar**, baik dari sisi demografi, kepuasan kerja, hingga kondisi finansial.
2. **Mengevaluasi tingkat kepuasan kerja** melalui indikator seperti *Job Satisfaction*, *Work-Life Balance*, dan *Environment Satisfaction*.
3. **Mendeteksi pola perilaku karyawan berisiko tinggi untuk resign**, seperti jarak rumah-kantor yang jauh, beban lembur berlebih, dan gaji rendah.
4. **Menyediakan dashboard interaktif** sebagai alat bantu pengambilan keputusan HR yang berbasis data, untuk memantau attrition secara real-time dan strategis.

### **Cakupan Proyek**
Proyek ini dirancang dengan cakupan:
1. **Eksplorasi dan Pemahaman Awal Data**
   Melakukan analisis awal terhadap dataset `employee_data.csv`.
2. **Persiapan dan Pembersihan Data**
   Melakukan proses data wrangling, termasuk pembersihan, transformasi, dan standarisasi data agar siap digunakan untuk analisis lanjutan.
3. **Analisis Penyebab Attrition**
   * Mengidentifikasi hubungan antara variabel kunci seperti gaji, frekuensi lembur, tingkat kepuasan kerja, dan jarak rumah ke kantor terhadap kemungkinan attrition.
   * Memvisualisasikan tren dan pola attrition berdasarkan departemen, jabatan, usia, serta kategori demografis lainnya.
4. **Pengembangan Dashboard Interaktif**
   Merancang dan membangun dashboard bisnis yang informatif dan user-friendly untuk membantu tim HR memonitor faktor-faktor penyebab attrition secara berkala dan proaktif.
5. **Penarikan Insight dan Rekomendasi Strategis**
   Menyusun temuan utama dari hasil analisis dan memberikan saran berbasis data untuk membantu perusahaan menurunkan tingkat attrition dan meningkatkan retensi karyawan.

---

### **Sumber Data**
Data yang digunakan dalam proyek ini berasal dari [Dataset Karyawan Jaya Jaya Maju](https://github.com/dicodingacademy/dicoding_dataset/tree/main/employee), sesuai dengan ketentuan dan arahan dari proyek submission yang ditetapkan.

### **Persiapan Lingkungan Kerja (Environment Setup)**
**Menjalankan Notebook Analisis (`notebook.ipynb`)**

   * Pastikan semua dependensi dan pustaka (libraries) yang dibutuhkan telah terinstal dengan benar. Daftar lengkap dependensi dapat dilihat pada file `requirements.txt`.
   * Jalankan seluruh sel dalam file `notebook.ipynb` menggunakan platform seperti Google Colab atau Jupyter Notebook untuk menampilkan hasil analisis, visualisasi data, serta insight yang dihasilkan dari proses eksplorasi.


### **Akses Dashboard**
Visualisasi interaktif dari hasil analisis dapat diakses melalui dashboard berikut:
🔗 [Dashboard HR](https://lookerstudio.google.com/reporting/6bb4df10-969c-4c7c-883a-bbfbb397e7fe)

Dashboard ini dirancang untuk membantu tim manajemen dan Human Resources memantau tren attrition serta memahami faktor-faktor kunci yang memengaruhi keputusan karyawan untuk keluar dari perusahaan.

---

### Fitur-fitur paling berpengaruh terhadap kemungkinan karyawan keluar:
1. **MonthlyIncome (0.1731)** — Gaji bulanan rendah cenderung meningkatkan risiko keluar.
2. **Age (0.1296)** — Usia muda cenderung lebih sering keluar.
3. **EnvironmentSatisfaction (0.1197)** — Kepuasan terhadap lingkungan kerja yang rendah mendorong attrition.
4. **TotalWorkingYears, DistanceFromHome, YearsAtCompany** — Menunjukkan bahwa pengalaman kerja dan jarak rumah berpengaruh terhadap keputusan keluar.


### **Kesimpulan untuk HR**
1. **Gaji rendah, jarak rumah jauh, dan pengalaman kerja sedikit adalah kombinasi utama yang mendorong karyawan keluar.**
2. **Usia muda dan status lajang** merupakan segmen yang lebih rentan.
3. **Lembur dan rendahnya kepuasan kerja/lingkungan kerja** sangat berkorelasi dengan attrition.
4. **Perlu perhatian khusus terhadap departemen Sales dan karyawan dengan intensitas perjalanan tinggi.**

---

### **Rekomendasi Strategis HR**
* **Revisi kompensasi**, khususnya untuk karyawan muda dan berpenghasilan rendah.
* **Program retensi dan engagement** untuk karyawan lajang dan baru.
* **Fleksibilitas kerja atau subsidi transportasi** untuk karyawan yang tinggal jauh dari kantor.
* **Kurangi lembur** dan **tingkatkan kepuasan kerja** melalui survei dan perbaikan lingkungan kerja.
* Fokus pengembangan SDM di departemen dan peran dengan tingkat attrition tinggi.