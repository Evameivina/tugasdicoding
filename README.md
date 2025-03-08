# Dashboard Analisis Data E-Commerce

#### Proyek ini adalah dashboard interaktif untuk eksplorasi dan analisis data penjualan, review, dan pelanggan.

## Library yang Digunakan
- **Pandas:** Manipulasi dan analisis data  
- **NumPy:** Operasi numerik  
- **Matplotlib:** Visualisasi dasar  
- **Seaborn:** Visualisasi yang lebih estetik  
- **Streamlit:** Dashboard interaktif

- Sebelum menjalankan dashboard, pastikan telah menginstal:
- Python (versi 3.9 atau lebih baru)
- VSCode (Visual Studio Code)
- Streamlit
- Library pendukung lainnya: Pandas, Matplotlib, Seaborn, Plotly

#### 1. Setup Environment (Anaconda)
conda create --name dashboard-env python=3.9
conda activate dashboard-env
pip install -r requirements.txt


## Buat folder proyek (jika belum)
mkdir proyek_analisis_data
cd proyek_analisis_data

## Install environment menggunakan pipenv
pipenv install
pipenv shell

## Install semua library
pip install -r requirements.txt


# Menjalankan Dashboard

### Pastikan Anda berada di direktori proyek di VSCode atau terminal, lalu jalankan perintah berikut:

streamlit run dashboard.py

Setelah itu, dashboard akan terbuka secara otomatis di browser pada alamat seperti: http://localhost:8501/.

## Setup Environment - Anaconda

conda create --name main-ds python=3.9

conda activate main-ds

pip install -r requirements.txt

## Setup Environment - Shell/Terminal

mkdir proyek_analisis_data

cd proyek_analisis_data

pipenv install

pipenv shell

pip install -r requirements.txt

## Run steamlit app

streamlit run dashboard.py

