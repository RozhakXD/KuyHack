# KuyHack
![KuyHack](https://github.com/user-attachments/assets/86ffbcc3-c2a0-4ddf-a678-858afa0b0237)

**KuyHack** adalah tool penetration testing berbasis Python yang dirancang untuk menguji kerentanan pada platform [KuySocial](https://www.kuysocial.com/). Dengan menggunakan berbagai metode, termasuk brute force untuk akun yang memiliki kelemahan pada kata sandi, KuyHack memungkinkan pengguna untuk melakukan pencarian dan pengumpulan data pengguna. Selain itu, tool ini juga memberikan kemampuan untuk mengeksploitasi berbagai kelemahan yang ditemukan melalui fitur-fitur yang tersedia.

## ✨ Fitur Utama
- **Automasi**: Program otomatis untuk mengelola file hasil eksploitasi dengan pilihan pengaturan yang fleksibel.
- **Dump User**: Kumpulkan data pengguna dari berbagai sumber, seperti pencarian, pengikut, teman, komentar, hingga hashtag.
- **Desain Interaktif**: Tampilan yang menarik dengan elemen visual dari rich library untuk pengalaman pengguna yang lebih baik.
- **Brute Force**: Lakukan brute force pada akun dengan kelemahan password untuk menguji tingkat keamanan.
- **Pengelolaan Cookies**: Verifikasi dan kelola cookies untuk proses login yang mulus.

## 📚 Persyaratan
- Python 3.12
- Library:
    - `fake-useragent`
    - `requests`
    - `rich`
    - `bs4`
    - `futures`
- Device:
    - `64bit`

## Installation
**Termux** - [**Beta**](https://drive.google.com/file/d/1CX_vemkpcVR-NHnXw_Yx7q6b1TU_I22w/view?usp=drivesdk)
```
$ apt update -y && apt upgrade -y
$ pkg install git python-pip
$ git clone --depth 1 https://github.com/RozhakXD/KuyHack.git
$ cd "KuyHack"
$ pip install -r requirements.txt
$ chmod +x Run
$ ./Run
```

## 🚀 Cara Penggunaan
1. Pilih metode pengumpulan data yang diinginkan, seperti pencarian, pengikut, atau hashtag.
2. Ikuti petunjuk interaktif untuk memasukkan informasi yang dibutuhkan.
3. Jalankan brute force atau metode lain untuk menguji kerentanan.
4. Simpan hasil eksploitasi dengan mudah.

## 📷 Tangkapan Layar
![FunPic_20241021](https://github.com/user-attachments/assets/bc0617ab-7acf-447d-a94f-e133f5369e73)

## 🛠️ Troubleshooting
1. **Gagal Login**: Jika pengguna gagal login, berarti *cookies* sudah tidak valid. Anda diharapkan untuk mendapatkan *cookie* baru.
2. **Gagal Dump**: Jika proses dump gagal, kemungkinan ada kesalahan pada target atau *cookie* yang digunakan. Pastikan target benar dan *cookie* masih valid.
3. **Tidak Ada Hasil**: Jika tidak ada hasil, berarti target tidak memiliki *password* yang lemah. Coba target lain atau perbarui teknik yang digunakan.

## ⚠️ Disclaimer
KuyHack hanya boleh digunakan untuk tujuan pengujian keamanan yang sah dengan izin dari pemilik sistem. Penggunaan untuk tindakan ilegal atau tanpa izin dapat melanggar hukum setempat. Gunakan alat ini dengan bijak dan bertanggung jawab!

## 📜 Lisensi
Proyek ini dilisensikan di bawah [MIT License](https://github.com/RozhakXD/KuyHack/blob/main/LICENSE).
