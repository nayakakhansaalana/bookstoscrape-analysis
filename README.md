# 📚 Book Scraper & Data Visualization
Web scraping dan visualisasi data dari situs Books to Scrape.

## 🔍 Deskripsi Proyek
Proyek ini menggunakan Python untuk men-scrape data buku (judul, harga, ketersediaan) dari seluruh halaman website Books to Scrape. Data kemudian dibersihkan dan divisualisasikan dalam bentuk grafik menggunakan Seaborn dan Matplotlib. Output disimpan dalam file Excel dan PNG.

## 🛠️ Tools dan Library
### requests – Mengambil halaman HTML
### BeautifulSoup – Parsing HTML
### pandas – Manipulasi data
### re – Pembersihan data teks
### matplotlib & seaborn – Visualisasi data

## 📈 Visualisasi
### Jumlah buku tersedia vs tidak tersedia
### Top 10 buku dengan harga tertinggi

## 📁 Output
### books_allpages.xlsx – Data buku hasil scraping semua halaman
### books_page1.xlsx – Data buku hasil scraping halaman 1
### availability_page1.png – Grafik ketersediaan buku halaman 1
### availability_chart.png – Grafik ketersediaan buku semua halaman
### top5_prices_page1.png – Grafik buku termahal halaman 1
### top10_prices.png – Grafik buku termahal semua halaman

## 🚀 Cara Menjalankan
pip install requests beautifulsoup4 pandas matplotlib seaborn openpyxl

## 📄 Lisensi
Proyek ini hanya untuk tujuan edukasi. Data diambil dari situs publik Books to Scrape yang memang disediakan untuk keperluan latihan web scraping.
