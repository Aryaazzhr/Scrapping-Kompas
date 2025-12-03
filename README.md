# Analisis Clustering Berita Kompas.com

Proyek ini melakukan scraping berita dari indeks Kompas.com, membersihkan teks, dan mengelompokkan berita (Clustering) menggunakan algoritma K-Means.

## Fitur
- **Web Scraping**: Menggunakan `BeautifulSoup` & `Requests`.
- **NLP Cleaning**: Stopword removal menggunakan `Sastrawi`.
- **Clustering**: K-Means + TF-IDF.
- **Visualisasi**: WordCloud, PCA Scatter Plot, & Heatmap.

## Cara Menjalankan
1. Install library: `pip install -r requirements.txt`
2. Jalankan notebook `scraping_kompas.ipynb`
