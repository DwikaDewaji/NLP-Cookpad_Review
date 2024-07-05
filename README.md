# Analisis Sentimen NLP untuk Review Aplikasi Cookpad di Google Play Store

Proyek ini melakukan analisis sentimen terhadap ulasan-ulasan pengguna aplikasi Cookpad di Google Play Store menggunakan teknik Natural Language Processing (NLP).

## Daftar Isi
- [Pendahuluan](#pendahuluan)
- [Fitur](#fitur)
- [Instalasi](#instalasi)
- [Penggunaan](#penggunaan)
- [Struktur Proyek](#struktur-proyek)
- [Kontribusi](#kontribusi)
- [Lisensi](#lisensi)

## Pendahuluan
Proyek ini bertujuan untuk memahami bagaimana pengguna aplikasi Cookpad merespons aplikasi tersebut melalui ulasan yang mereka tinggalkan di Google Play Store. Dengan menggunakan teknik NLP, dapat diklasifikasikan ulasan-ulasan ini ke dalam kategori sentimen yang berbeda seperti positif atau negatif.

## Fitur
- **Pengumpulan Data**: Scraping ulasan pengguna dari Google Play Store.
- **Pra-pemrosesan Data**: Menghapus noise dan membersihkan data untuk analisis yang akurat.
- **Analisis Sentimen**: Menggunakan model NLP untuk menentukan sentimen ulasan.
- **Visualisasi Data**: Grafik dan plot untuk visualisasi distribusi sentimen.
- **Pelaporan**: Menyusun laporan tentang hasil analisis sentimen.


## Penggunaan
1. Jalankan skrip pengumpulan data untuk mendapatkan ulasan terbaru dari Google Play Store:
    ```sh
    python Scrap_data.ipynb
    ```
2. Jalankan skrip analisis sentimen untuk mengklasifikasikan ulasan:
    ```sh
    python Sentiment_Analysis_NLP.ipynb
    ```


## Struktur Proyek
- `ulasan_aplikasi_cookpad2.csv`: Folder untuk menyimpan data mentah dan hasil pengolahan.
- `Scrap_data.ipynbpy`: Mengambil data dari playstore
- `Sentiment_Analysis_NLP.ipynb`: Melakukan analisis sentimen.
- `requirements.txt`: Daftar dependencies yang diperlukan.

## Kontribusi
Kontribusi sangat diterima! Silakan fork repository ini dan buat pull request dengan perubahan yang Anda usulkan.

