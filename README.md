# Analisis Sentimen Ulasan Mobile JKN

Proyek Dicoding oleh Ilham Jaya Saputra. Proyek ini menganalisis sentimen dalam ulasan Mobile JKN di Google Play. Pengambilan ulasan dan analisis dipisah ke dua notebook sehingga tahapan pengolahan teks bisa dibaca tanpa mengambil ulang data.

## Bagian proyek

- [Notebook pengambilan ulasan](Dicoding_Code_Scraping_Data_Mobile_JKN.ipynb) memakai `google-play-scraper` dan menyimpan hasil ke CSV.
- [Notebook analisis sentimen](Dicoding_Proyek_Analisis_Sentimen.ipynb) membersihkan teks berbahasa Indonesia, memberi label sentimen dengan leksikon InSet, serta mengeksplorasi kata dan frasa yang sering muncul lewat word cloud dan n-gram. TF-IDF dipakai untuk merepresentasikan teks pada tahap pemodelan.
- [`requirements.txt`](requirements.txt) berisi dependensi Python.

Jika sudah memiliki CSV ulasan, langsung buka notebook analisis dan sesuaikan lokasi berkas pada sel pemuatan data. Label InSet berasal dari pencocokan kata, bukan anotasi manual. Sarkasme dan penggunaan kata dalam konteks yang tidak biasa perlu ditafsirkan dengan hati-hati.

[Proyek Mobile JKN di portofolio Ilham Jaya Saputra](https://www.ilhamjayas.my.id/#pc-sentiment)
