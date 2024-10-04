# Proyek Analisis Data dengan Streamlit

## Deskripsi
Proyek ini adalah aplikasi analisis data yang dibangun menggunakan Streamlit. Aplikasi ini memungkinkan pengguna untuk menganalisis dan memvisualisasikan data dari file CSV yang berisi informasi tentang pesanan dan ulasan pelanggan. Tujuannya adalah untuk memberikan wawasan yang lebih baik tentang kinerja penjualan dan kepuasan pelanggan.

## Fitur
- Memuat data dari file CSV.
- Menampilkan statistik dasar tentang data.
- Visualisasi grafik berdasarkan data pesanan dan ulasan.
- Mengubah format tanggal dari kolom yang relevan.

## Prasyarat
Sebelum menjalankan aplikasi ini, pastikan Anda memiliki:
- Python 3.x terinstal di sistem Anda.
- Pip untuk mengelola paket Python.
- File `all_data.csv` yang berisi data yang akan dianalisis.

## Instalasi
1. Clone repositori ini ke komputer Anda:
   ```bash
   git clone https://github.com/username/repository-name.git
   cd repository-name
2. Buat dan aktifkan virtual environment (opsional tetapi disarankan):
   python -m venv venv
   ```bash
    Aktifkan virtual environment
    Windows
    .\venv\Scripts\activate
    Linux/macOS
    source venv/bin/activate
3. Install dependensi yang diperlukan:
   ```bash
   pip install -r requirements.txt
## Penggunaan
1. Pastikan file all_data.csv berada di direktori yang sama dengan skrip aplikasi.
2. Jalankan aplikasi Streamlit:
   ```bash
   streamlit run dashboard.py
3. Aplikasi akan terbuka di browser Anda di http://localhost:8501.
