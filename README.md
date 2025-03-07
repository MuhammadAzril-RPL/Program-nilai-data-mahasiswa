# Program Nilai Data Mahasiswa

Program ini dibuat untuk mengelola data nilai mahasiswa, termasuk input data, melihat data, mengubah data, dan menghapus data mahasiswa. Program ini memiliki dua jenis menu login: Dosen dan Mahasiswa.

## Fitur

1. **Login Dosen**: Dosen dapat melakukan login dengan kode tertentu dan mengakses berbagai menu untuk mengelola data mahasiswa.
2. **Input Data Mahasiswa**: Dosen dapat menambahkan data mahasiswa, seperti nama, NIM, kelas, prodi, serta nilai kehadiran, tugas, UTS, dan UAS.
3. **Lihat Data Mahasiswa**: Dosen dapat melihat data mahasiswa yang sudah dimasukkan.
4. **Ubah Data Mahasiswa**: Dosen dapat mengubah data mahasiswa, baik untuk biodata (nama, NIM, kelas, prodi) atau nilai (kehadiran, tugas, UTS, UAS).
5. **Hapus Data Mahasiswa**: Dosen dapat menghapus data mahasiswa berdasarkan NIM.
6. **Login Mahasiswa**: Mahasiswa dapat melihat data mereka sendiri dengan memasukkan NIM.

## Struktur Program

### 1. **Menu Utama**
   Menu utama akan meminta pengguna untuk memilih apakah mereka adalah Dosen atau Mahasiswa.
   - **1. DOSEN**: Dosen dapat mengakses menu untuk mengelola data mahasiswa.
   - **2. MAHASISWA**: Mahasiswa dapat melihat data mereka sendiri.
   - **3. KELUAR**: Keluar dari program.

### 2. **Login Dosen**
   - Dosen harus memasukkan kode login yang benar (misalnya `admin`).
   - Jika kode salah, program akan meminta dosen untuk mencoba lagi.

### 3. **Menu Dosen**
   Dosen akan disajikan dengan beberapa pilihan menu:
   - **1. Tambah Data**: Menambahkan data mahasiswa baru.
   - **2. Lihat Data Mahasiswa**: Melihat data mahasiswa yang sudah ada.
   - **3. Ubah Data Mahasiswa**: Mengubah data mahasiswa (biodata atau nilai).
   - **4. Hapus Data Mahasiswa**: Menghapus data mahasiswa berdasarkan NIM.
   - **5. Selesai**: Kembali ke menu utama.

### 4. **Tambah Data Mahasiswa**
   Dosen dapat memasukkan data mahasiswa baru, termasuk:
   - Nama
   - NIM
   - Kelas
   - Prodi (TI/SI)
   - Nilai Kehadiran (dalam persentase)
   - Nilai Tugas
   - Nilai UTS
   - Nilai UAS

   Nilai akhir mahasiswa dihitung berdasarkan bobot dari nilai yang dimasukkan, dengan ketentuan:
   - Kehadiran: 20%
   - Tugas: 25%
   - UTS: 25%
   - UAS: 30%

### 5. **Lihat Data Mahasiswa**
   Dosen dapat melihat data mahasiswa yang sudah terdaftar, termasuk:
   - Nama
   - NIM
   - Kelas
   - Prodi
   - Nilai Kehadiran
   - Nilai Tugas
   - Nilai UTS
   - Nilai UAS
   - Nilai Akhir

### 6. **Ubah Data Mahasiswa**
   Dosen dapat mengubah data mahasiswa, baik untuk:
   - **Biodata**: Nama, NIM, Kelas, Prodi.
   - **Nilai**: Kehadiran, Tugas, UTS, UAS.

   Dosen akan diminta untuk memasukkan NIM mahasiswa yang ingin diubah datanya.

### 7. **Hapus Data Mahasiswa**
   Dosen dapat menghapus data mahasiswa berdasarkan NIM yang dimasukkan.

### 8. **Login Mahasiswa**
   Mahasiswa dapat melihat data mereka sendiri dengan memasukkan NIM yang telah terdaftar. Data yang dapat dilihat oleh mahasiswa meliputi:
   - Nama
   - NIM
   - Kelas
   - Prodi
   - Nilai Kehadiran
   - Nilai Tugas
   - Nilai UTS
   - Nilai UAS

## Cara Menjalankan Program

1. Pastikan Anda memiliki Python 3.x terinstal di komputer Anda.
2. Salin kode program ini ke dalam file dengan ekstensi `.py` (misalnya `program_nilai.py`).
3. Jalankan program dengan perintah berikut di terminal atau command prompt:
   ```bash
   python program_nilai.py
