# ADS_9_RA
# Nama Anggota Kelompok 9 ra :
1. Queenta Thifaal Nabila_124450059
2. Elsa Sitorus_124450088
3. Afriza Azmi_124450110
4. Djofy Prianda Banu_124450117

# Cara Menjalankan Script :
1. Simpan file dataset dengan nama "Copy of Dataset Tugas Besar ADS 2025 - Karakteristik Mahasiswa (3).csv" di direktori kerja yang sama dengan script R
2. jalankan script secara berurutan dari awal hingga akhir
3. Pastikan semua package yang diperlukan sudah terinstal

# Paket R yang Digunakan :
1. readr - untuk membaca file CSV
2. dplyr - untuk manipulasi data
3. car - untuk uji Levene (homogenitas varians)
4. knitr - untuk membuat tabel yang rapi
5. broom - untuk merapikan output uji statistik

# Penjelasan Singkat Dataset :
1. Dataset berisi karakteristik mahasiswa dengan fokus pada:
2. IPK (Indeks Prestasi Kumulatif) sebagai variabel numerik
3. Status Pekerjaan sebagai variabel kategorikal dengan tiga kategori:
- Tidak Bekerja
- Paruh Waktu
- Penuh Waktu

# Struktur :
 tugas_besar_ads_2025/
 │
 ├── 01_raw_data/
 │   └── Copy of Dataset Tugas Besar ADS 2025 - Karakteristik Mahasiswa (3).csv
 │
 ├── 02_data_cleaning/
 │   ├── data_cleaning.ipynb                 # Jupyter Notebook untuk cleaning
 │   ├── data_cleaning.R                     # Script R untuk cleaning  
 │   └── cleaning_report.html                # Laporan hasil cleaning
 │
 ├── 03_cleaned_data/
 │   ├── dataset_cleaned.csv                 # Data yang sudah dibersihkan
 │   └── data_dictionary.csv                 # Dokumentasi variabel
 │
 ├── 04_analysis_scripts/
 │   ├── exploratory_analysis.R              # EDA dan statistik deskriptif
 │   ├── hypothesis_testing.R                # Uji hipotesis
 │   └── data_visualization.R                # Visualisasi
 │
 ├── 05_output_results/
 │   ├── tables/
 │   │   ├── descriptive_statistics.csv
 │   │   ├── normality_test_results.csv
 │   │   ├── t_test_results.csv
 │   │   └── mann_whitney_results.csv
 │   │
 │   ├── figures/
 │   │   ├── boxplot_ipk_pekerjaan.png
 │   │   ├── histogram_ipk.png
 │   │   ├── histogram_by_employment.png
 │   │   └── qq_plot_normalitas.png
 │   │
 │   └── reports/
 │       └── final_analysis_report.html
 │
 ├── 06_documentation/
 │   ├── README.md
 │   ├── project_structure.md
 │   └── methodology_explanation.md
 │
 └── run_analysis.R                         # Script utama untuk menjalankan semua analisis
