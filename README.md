```markdown
# PowerPoint Material Maker using GPT

Bagian backend dari proyek web development yang menggunakan GPT untuk membuat materi presentasi PowerPoint. Aplikasi ini memungkinkan pengguna untuk menghasilkan presentasi, melihat riwayat presentasi, dan menghapus presentasi yang sudah tidak diperlukan.

## Fitur
- Membuat presentasi PowerPoint berdasarkan input pengguna.
- Mendownload presentasi yang telah dibuat.
- Menampilkan tabel riwayat pembuatan presentasi.
- Menghapus presentasi dari tabel riwayat.
- Mencari presentasi berdasarkan judul.
- Memilih untuk memperbarui atau membuat baru jika presentasi sudah pernah dibuat.

**Catatan: Proyek ini masih dalam pengembangan.**

## Prasyarat
Sebelum menjalankan aplikasi, pastikan Anda telah menginstal dependensi yang diperlukan dan memiliki API key dari OpenAI.

### 1. Instalasi Dependensi
1.1. Install dependensi yang dibutuhkan:
```bash
pip install openai
pip install python-pptx
pip install flask
pip install flask-sqlalchemy
pip install flask-cors
pip install pytz
```

1.2. Dapatkan API key dari OpenAI dan simpan untuk digunakan di aplikasi.

## Menjalankan Aplikasi Secara Lokal

### 2. Menyiapkan Proyek
2.1. Clone repositori ke lokal:
```bash
git clone https://github.com/infrasvc-magang/test-Internship-July2024.git
```

2.2. Pindah ke direktori proyek:
```bash
cd test-Internship-July2024/backend/project
```

### 3. Menjalankan Aplikasi
3.1. Jalankan aplikasi dengan perintah berikut:
```bash
python app.py
```

3.2. Buka alamat yang diberikan di browser untuk mengakses aplikasi.

## Deploy ke Virtual Machine

### 4. Menyiapkan Virtual Machine
4.1. SSH ke virtual machine:
```bash
ssh isrdds@192.168.14.61
```
Password: `123456`

### 5. Menginstal Dependensi di Virtual Machine
5.1. Install dependensi yang dibutuhkan di virtual machine:
```bash
pip install openai
pip install python-pptx
pip install flask
pip install flask-sqlalchemy
pip install flask-cors
pip install pytz
```

### 6. Menyalin Kode ke Virtual Machine
6.1. Clone repositori ke virtual machine:
```bash
git clone https://github.com/infrasvc-magang/test-Internship-July2024.git
```

6.2. Pindah ke direktori proyek:
```bash
cd test-Internship-July2024/backend/project
```

### 7. Menjalankan Aplikasi di Virtual Machine
7.1. Jalankan aplikasi dengan perintah berikut:
```bash
python app.py
```

7.2. Akses aplikasi di browser melalui alamat:
```
http://192.168.14.61/
```

## Konfigurasi Database
Aplikasi ini menggunakan SQLite sebagai database. Database akan secara otomatis dibuat pada pertama kali menjalankan aplikasi.

## Struktur Direktori
- `app.py`: File utama yang berisi kode aplikasi.
- `templates/`: Direktori yang berisi template HTML untuk aplikasi.
- `PPTX/`: Direktori tempat menyimpan file presentasi yang dihasilkan.

## Konfigurasi OpenAI
Gantilah `YOUR_API_KEY` di `app.py` dengan API key Anda dari OpenAI:
```python
openai.api_key = "YOUR_API_KEY"
```

Jika Anda memiliki pertanyaan atau memerlukan bantuan lebih lanjut, jangan ragu untuk menghubungi kami.

---

Dokumentasi ini bertujuan untuk memberikan panduan lengkap tentang cara menginstal, menjalankan, dan mendeply aplikasi ke virtual machine. Jika ada hal yang perlu diperbaiki atau ditambahkan, mohon berikan informasi tambahan.
```

Anda dapat menyalin dan menyimpan isi di atas ke dalam file `README.md` di proyek Anda. Jika ada perubahan atau informasi tambahan yang diperlukan, silakan beri tahu saya.
