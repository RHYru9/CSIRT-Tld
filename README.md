# CSIRT Indonesia - Penjelasan Lengkap

## Apa itu CSIRT Domain List?

**CSIRT Domain List** adalah repositori (kumpulan data) yang berisi daftar lengkap domain-domain Indonesia yang menggunakan Top-Level Domain (TLD) khusus:
- **`.go.id`** - Domain resmi instansi pemerintah Indonesia
- **`.ac.id`** - Domain institusi pendidikan tinggi Indonesia  
- **`.co.id`** - Domain perusahaan berbadan hukum Indonesia

## Mengapa ada Repositori ini?

### 1. **Untuk Keamanan Siber**
- Membantu peneliti keamanan mengidentifikasi domain-domain Indonesia yang perlu dipantau
- Mendukung aktivitas **threat hunting** (pencarian ancaman keamanan)
- Memfasilitasi **attack surface mapping** (pemetaan permukaan serangan potensial)

### 2. **Untuk Pelaporan Kerentanan**
- Menyediakan informasi kontak CSIRT (Computer Security Incident Response Team) yang tepat
- Memudahkan **responsible disclosure** - pelaporan kerentanan keamanan secara etis dan bertanggung jawab
- Mengurangi waktu respons dalam penanganan insiden keamanan

## Struktur dan Isi Data

### Format File:
- **`.txt`** - Daftar domain sederhana (satu domain per baris)
- **`.csv`** - Data terstruktur dengan kolom:
  - `no` - Nomor urut
  - `base_domain` - Domain utama
  - `csirt_url` - URL kontak tim keamanan
  - `telepon` - Nomor telepon kontak
  - `email` - Email kontak
  - `apresiasi` - Informasi program bug bounty/penghargaan
  - `RFC_2350` - Standar internasional untuk tim respons keamanan

### Sumber Data:
Data dikumpulkan melalui berbagai metode:
- **WHOIS Database** - Database registrasi domain publik
- **Tools Otomatis**: Subfinder, C99, SecurityTrails, crt.sh
- **Web Scraping** - Pengumpulan data otomatis dari direktori domain
- **Normalisasi Data** - Pembersihan duplikat dan standardisasi format

## Etika Penggunaan

### ✅ **Penggunaan yang Diizinkan:**
- Penelitian keamanan siber yang sah
- Audit keamanan dengan izin
- Pelaporan kerentanan secara bertanggung jawab
- Analisis akademis dan riset

### ❌ **Penggunaan yang Dilarang:**
- Aktivitas peretasan atau penyerangan
- Penggunaan untuk tujuan kriminal
- Penyalahgunaan data untuk spam atau phishing
- Aktivitas yang melanggar hukum Indonesia

## Cara Berkontribusi

### Syarat Kontribusi:
1. **Validasi DNS** - Domain harus dapat di-resolve
2. **Bebas Duplikat** - Tidak ada domain yang sama
3. **Format Standar** - Mengikuti struktur file yang sudah ditetapkan
4. **Verifikasi Data** - Informasi kontak harus akurat

### Jenis Kontribusi:
- Menambahkan domain baru yang terlewat
- Memperbarui informasi kontak CSIRT
- Melaporkan domain yang sudah tidak aktif
- Memperbaiki kesalahan data

## Keterbatasan dan Disclaimer

### ⚠️ **Perhatian Penting:**
- **Tidak Ada Jaminan Akurasi 100%** - Beberapa data mungkin sudah usang
- **Perubahan Dinamis** - Domain dan organisasi dapat berubah sewaktu-waktu
- **Tanggung Jawab Pengguna** - Verifikasi ulang sebelum menggunakan data
- **Kepatuhan Hukum** - Pengguna bertanggung jawab mematuhi regulasi yang berlaku

### Kemungkinan Ketidakakuratan:
- Domain yang sudah tidak aktif atau expired
- Perubahan kepemilikan organisasi
- Informasi kontak yang sudah tidak valid
- Restrukturisasi institusi/perusahaan

## Manfaat untuk Ekosistem Keamanan Siber Indonesia

1. **Peningkatan Respons Insiden** - Kontak yang jelas mempercepat penanganan
2. **Kolaborasi Antar Institusi** - Memfasilitasi kerjasama keamanan siber
3. **Peningkatan Kesadaran** - Membantu organisasi memahami landscape digital mereka
4. **Standardisasi Pelaporan** - Mengikuti best practice internasional (RFC 2350)

## Lisensi dan Penggunaan

- **MIT License** - Lisensi terbuka yang memungkinkan penggunaan bebas
- **Batasan Institusional** - Tetap harus menghormati kebijakan masing-masing organisasi
- **Penggunaan Komersial** - Diizinkan dengan tetap mematuhi etika dan hukum

---

*Repositori ini merupakan upaya kolektif untuk meningkatkan keamanan siber di Indonesia melalui transparansi dan kolaborasi yang bertanggung jawab.*
