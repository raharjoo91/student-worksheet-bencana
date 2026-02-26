# Lembar Kerja Rumah Sakit Lapangan Darurat

Sumber daya pelatihan interaktif untuk mengajar perencanaan situs rumah sakit lapangan darurat melalui latihan simulasi hands-on. Dirancang untuk kursus manajemen bencana dan pelatihan respons darurat profesional.

## Ringkasan

Proyek ini berisi **lembar kerja interaktif** untuk latihan perencanaan situs rumah sakit lapangan selama **45 menit**. Peserta belajar mendesain tata letak situs 2D yang sesuai standar untuk fasilitas medis darurat berdasarkan skenario nyata dan standar internasional.

## Fitur

- **Antarmuka Interaktif**: Lembar kerja digital dengan fungsionalitas lengkap
- **Tiga Skenario**: Tipe 1 (20-50 tempat tidur), Tipe 2 (50-100 tempat tidur), dan Tipe 3 (100-200+ tempat tidur)
- **Alat Menggambar**: Kanvas interaktif dengan pena, penghapus, teks, dan bentuk geometris
- **Stamp Zona**: 19 zona fungsional siap pakai untuk ditambahkan ke desain
- **Timer Terintegrasi**: Timer latihan 45 menit
- **Daftar Periksa**: Interaktif dengan fitur klik untuk menandai
- **Auto-save**: Menyimpan progres secara otomatis ke browser
- **Ekspor PDF**: Mengunduh lembar kerja lengkap sebagai PDF
- **Referensi Visual**: 6 contoh tata letak untuk panduan
- **Bahasa Indonesia**: Semua konten dalam Bahasa Indonesia

## Cara Menggunakan

### Langkah 1: Buka Lembar Kerja
Buka `index.html` di browser modern apa saja (Chrome, Firefox, Safari, Edge)

### Langkah 2: Isi Informasi Tim
- Masukkan nama tim
- Daftarkan anggota tim
- Pilih skenario (A, B, atau C)

### Langkah 3: Pelajari Referensi
- Tinjau zona fungsional yang diperlukan
- Lihat contoh tata letak referensi
- Baca aturan keamanan kritis

### Langkah 4: Gambar Desain
Gunakan alat menggambar untuk membuat tata letak situs:
- ✏️ **Pena** - Menggambar garis bebas
- 🧹 **Penghapus** - Menghapus garis
- 📝 **Teks** - Menambahkan label teks
- ⬜ **Kotak** - Membuat persegi panjang
- ⭕ **Lingkaran** - Membuat lingkaran
- **Stamp Zona** - Klik tombol zona untuk menambahkan label zona siap pakai

### Langkah 5: Simpan & Ekspor
- **Simpan Secara Lokal** - Menyimpan progres di browser
- **Ekspor sebagai PDF** - Mengunduh seluruh lembar kerja sebagai PDF
- **Download Gambar Desain** - Mengunduh hanya gambar tata letak
- **Kirim ke Google Drive** - Petunjuk untuk upload ke Google Drive

## Struktur Skenario

### Skenario A: Gempa Bumi Remote (Tipe 1)
- **Konteks**: Gempa 7.0 SR di wilayah pegunungan
- **Situs**: 80m × 60m lapangan datar
- **Kapasitas**: 20-50 tempat tidur
- **Fokus**: Perawatan rawat jalan, manajemen luka, kesehatan maternal

### Skenario B: Banjir Urban + Wabah Kolera (Tipe 2)
- **Konteks**: Banjir muson, 20.000 jiwa mengungsi
- **Situs**: 120m × 100m tanah sekolah yang elevated
- **Kapasitas**: 50-100 tempat tidur
- **Fokus**: Rawat inap, kontrol infeksi, bedah, MHPSS

### Skenario C: Erupsi Vulkanik (Tipe 3)
- **Konteks**: Erupsi besar, 50.000+ jiwa mengungsi
- **Situs**: 150m × 120m area evakuasi
- **Kapasitas**: 100-200+ tempat tidur
- **Fokus**: Suite bedah lengkap, ICU, perawatan respirasi, telemedisin

## Zona Fungsional (19)

| Kode | Fungsi |
|------|--------|
| 1 | Komando & Admin |
| 2 | Rawat Inap Pria |
| 3 | Rawat Inap Wanita |
| 4 | Rawat Jalan (OPD) + Kesehatan Reproduksi |
| 5 | ICU |
| 6 | IGD (UGD) |
| 7 | Akomodasi Staf |
| 8 | Ruang Operasi |
| 9 | CSSD (Sterilisasi) |
| 10 | Farmasi |
| 11 | Toilet Staf |
| 12 | X-Ray |
| 13 | Toilet Pasien/WC |
| 14 | Purifikasi Air |
| 15 | Tangki Air Utama |
| 16 | Dapur |
| 17 | Gudang Logistik |
| 18 | Genset |
| 19 | Keamanan/Bendera |
| — | Unit MHPSS (Tipe 2/3) |

## Standar Keamanan Kritis

- **WASH**: Sanitasi ≥30m dari sumber air
- **Limbah**: Limbah medis ≥500m dari populasi
- **Zonasi**: Fasilitas WASH staf dan pasien terpisah
- **Akses**: Area ambulance dan pintu keluar darurat jelas
- **Keamanan**: Genset menjauh dari area pasien

## File

| File | Deskripsi |
|------|-----------|
| `index.html` | Lembar kerja siswa interaktif (utama) |
| `REFERENCE LAYOUT/` | 6 gambar referensi tata letak |
| `README.md` | Dokumentasi proyek |
| `.gitignore` | Konfigurasi git |

## Browser yang Didukung

- Chrome/Edge (terbaru)
- Firefox (terbaru)
- Safari (terbaru)
- Browser mobile (iOS Safari, Chrome Mobile)

## Struktur Latihan (45 Menit)

| Waktu | Aktivitas |
|-------|-----------|
| 0-10 menit | Pengenalan skenario; tim memilih satu (A, B, atau C) |
| 10-35 menit | Tim membuat tata letak 2D menggunakan kanvas menggambar |
| 35-45 menit | Presentasi tim + diskusi facilitated |

## Teknologi

- HTML5 Canvas untuk menggambar
- LocalStorage untuk auto-save
- html2canvas + jsPDF untuk ekspor PDF
- CSS3 responsif untuk mobile
- JavaScript vanilla (tanpa framework)

## Cara Deploy ke GitHub Pages

1. Upload file-file ini ke repository GitHub baru
2. Go ke Settings > Pages
3. Pilih main branch sebagai source
4. Akses di: `https://usernameanda.github.io/nama-repo/`

## Kredit & Referensi

Latihan ini berdasarkan:
- WHO Classification and Minimum Standards for Foreign Medical Teams
- Panduan Desain Rumah Sakit ICRC
- Pedoman Nasional Indonesia untuk Rumah Sakit Lapangan

## Lisensi

**UNTUK KEGIATAN PELATIHAN SAJA**

Material ini ditujukan untuk tujuan pendidikan dalam pelatihan manajemen bencana dan respons darurat.

---

*Mata Kuliah: Manajemen Bencana*
*Tahun Ajaran: 2025/2026 Genap*
