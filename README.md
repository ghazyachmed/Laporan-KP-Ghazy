# Laporan Kerja Praktik

Laporan Kerja Praktik II4090 milik Ghazy Achmed Movlech Urbayani, NIM 18223093.

## Cara melihat laporan

Berkas utama adalah Laporan_KP.tex. LaTeX tidak dirender langsung oleh GitHub seperti dokumen Word.

Cara paling mudah untuk melihat bentuk dokumen:

1. Laporan_KP.pdf tidak disimpan di repository karena memuat tanda tangan. Compile sendiri untuk mendapatkan PDF.
2. Untuk compile sendiri, gunakan XeLaTeX dan Biber dengan urutan xelatex, biber, xelatex, xelatex, xelatex. Putaran terakhir diperlukan agar nomor halaman pada Daftar Isi sesuai.
3. Di Visual Studio Code, gunakan extension LaTeX Workshop dan pilih recipe XeLaTeX -> Biber -> XeLaTeX x3.
4. Alternatif lain adalah mengunggah source repository ke Overleaf dan memilih compiler XeLaTeX.

## Kerahasiaan

Repository laporan hanya memuat versi yang telah disanitasi. Data mentah, identifier nasabah, query produksi lengkap, nama tabel internal, kredensial, dan output bisnis rinci tidak boleh dimasukkan ke repository ini.


## Tanda tangan pribadi

Source laporan mendukung file tanda tangan lokal berikut:

- `images/ttd-ghazy.png` untuk Lembar Pernyataan.
- `images/ttd-pembimbing-perusahaan.png` untuk Lembar Pengesahan Perusahaan. Wajib ada sebelum draft dikumpulkan.
- `images/ttd-dosen.png` untuk Lembar Pengesahan Dosen. Diisi setelah laporan disetujui dosen KP.

File tanda tangan sengaja masuk `.gitignore` dan tidak disimpan di repository karena repository laporan bersifat public. Simpan file tanda tangan hanya di komputer lokal dengan nama tersebut sebelum compile PDF. Jika file belum ada, ruang tanda tangan tetap kosong dengan ukuran yang sama.
