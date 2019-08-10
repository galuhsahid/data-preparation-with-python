# Data Preparation with Python
Materi-materi yang digunakan pada DQLab Meetup #11: Data Preparation with Python, 3 Agustus 2019.

- [Slides](https://speakerdeck.com/galuhsahid/data-preparation-with-python)
- Sumber data (dengan modifikasi untuk pembelajaran):
    - `angka_partisipasi_sekolah.csv`: [Satu Data Indonesia](https://data.go.id/dataset/angka-partisipasi-sekolah)
    - `penduduk_telepon_seluler_pedesaan.csv`: [Satu Data Indonesia](https://data.go.id/dataset/proporsi-penduduk-yang-memiliki-telepon-seluler-di-daerah-perdesaan)
    - `world_gdp.tsv`: [World Bank](https://data.worldbank.org/indicator/ny.gdp.mktp.kd.zg)
    - `world_population.csv`: [World Bank](https://data.worldbank.org/indicator/SP.POP.TOTL?view=chart)

## 📖 Daftar Isi
Materi untuk Data Preparation with Python tersedia dalam bentuk Jupyter *notebook* (ekstensi .ipynb). Sejauh ini, materi berfokus pada penggunaan *library* [pandas](https://github.com/pandas-dev/pandas). Tidak menutup kemungkinan bahwa materi-materi ini akan dikembangkan lebih lanjut lagi ke depannya. Terdapat 3 *notebook* berbeda, yaitu:
1. Membaca, mengakses, dan mengeksplor data
2. Memodifikasi data (menghapus, mengubah nama kolom, meng-handle *missing values*, menangani duplikasi)
3. Mengubah bentuk data, menggabungkan data dari berbagai sumber, serta meringkas data (*groupby*, agregasi)

Masing-masing *notebook* juga dilengkapi dengan beberapa latihan beserta masing-masing solusinya.

## ⚙️ Instalasi
### Instalasi Python
Python sudah ter-*install* di Mac OS dan Linux secara *default*. Para pengguna Windows dapat mengunduh Python melalui *link* [ini](https://www.python.org/downloads/).

### Instalasi Jupyter notebook
Jupyter notebook adalah aplikasi berbasis web, di mana kita dapat menulis dan mengeksekusi kode Python di ​*web browser*​. Dengan Jupyter notebook, kita dapat mengeksekusi kode Python per bagian/per blok dalam satu waktu.

Apabila Anda telah meng-*install* Python 3:
```
python3 -m pip install --upgrade pip
python3 -m pip install jupyter
```

Apabila Anda memiliki Python 2:
```
python -m pip install --upgrade pip
python -m pip install jupyter
```

Anda telah meng-*install* Jupyter Notebook. Untuk dapat menjalankan *notebook*, jalankan perintah di bawah ini baik di Terminal (Mac/Linux) atau Command Prompt (Windows) Anda.
```
jupyter notebook
```

Penjelasan lebih lengkap terkait instalasi Jupyter notebook dapat dilihat di [tautan ini](https://jupyter.org/install).

## 💭 Isu dan Kontribusi
Apabila Anda menemukan isu atau ingin membantu memperbaiki modul ini, Anda bisa langsung [membuka isu](https://github.com/galuhsahid/data-preparation-with-python/issues/new) atau [membuat *pull request*](https://github.com/galuhsahid/data-preparation-with-python/compare). 🙏

## ⚖️ Lisensi
Karya ini dilisensi dengan <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)</a>. Untuk melihat salinan dari lisensi tersebut, kunjungi http://creativecommons.org/licenses/by-nc-sa/4.0/.

<a rel="license" href="https://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a>