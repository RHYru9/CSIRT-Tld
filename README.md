# CSIRT Domain List: TLD `.go.id` dan `.ac.id`

Repositori ini menyediakan daftar domain yang berada di bawah lingkup TLD (Top-Level Domain) `.go.id`, `co.id` dan `.ac.id`, yang masing-masing digunakan oleh instansi pemerintahan dan institusi pendidikan tinggi di Indonesia. Daftar ini ditujukan untuk mendukung kegiatan riset keamanan, termasuk *threat hunting*, analisis permukaan serangan (*attack surface mapping*), dan pelaporan kerentanan secara bertanggung jawab.

---

## Tujuan

Menyediakan referensi yang akurat dan terkurasi terkait domain:

* `.go.id` — domain milik lembaga pemerintah Indonesia
* `.ac.id` — domain milik institusi pendidikan tinggi di Indonesia
* `.co.id` — domain milik perusahaan berbadan hukum di Indonesia

Repositori ini bersifat terbuka dan dapat digunakan untuk mendukung kegiatan riset keamanan siber dan pelaporan insiden kepada CSIRT (Computer Security Incident Response Team) yang relevan.

---

## Struktur Data

Data disusun dalam beberapa format:

* `go.id.txt` — daftar `.go.id` Tld
* `ac.id.txt` — daftar `.ac.id` Tld
* `co.id.txt` — daftar `.co.id` Tld
* `csirt_go.id.csv` — daftar informasi CSIRT terkait domain `.go.id`
* `csirt_ac.id.csv` — daftar informasi CSIRT terkait domain `.ac.id`
* `csirt_co.id.csv` — daftar informasi CSIRT terkait domain `.co.id`

---

## Sumber Data

Domain dikumpulkan dari berbagai sumber, antara lain:

* WHOIS publik
* Tools seperti Subfinder, C99, SecurityTrails, dan crt.sh
* Web scraping direktori domain terkait
* Proses normalisasi (pembersihan duplikat, trimming ke root domain, pengelompokan berdasarkan TLD) menggunakan [rhyru9.github.io/uri](https://rhyru9.github.io/uri)

---

## Etika dan Tanggung Jawab

* Gunakan data ini hanya untuk kegiatan riset keamanan yang sah
* Patuhi prinsip *Responsible Disclosure* dalam pelaporan kerentanan
* Tidak diperkenankan menggunakan data ini untuk aktivitas yang bersifat merusak atau ilegal
* Laporkan temuan kerentanan kepada CSIRT atau pengelola domain terkait secara tepat dan profesional

---

## Kontribusi

Kontribusi dalam bentuk domain baru, metadata tambahan, atau perbaikan data sangat disarankan. Mohon pastikan bahwa setiap data yang dikirimkan:

* Sudah melalui validasi (terutama resolusi DNS)
* Bebas dari duplikat
* Mengikuti format standar berikut:

  * `.txt` — list domain
  * `.csv` — berisi kolom `no`, `base_domain`, `csirt_url`, `telepon`, `email`, `apresiasi`, dan `RFC_2350`

---

## Lisensi

Repositori ini menggunakan [MIT License](LICENSE). Namun, penggunaan data tetap tunduk pada ketentuan dan kebijakan masing-masing domain atau instansi pemiliknya.

---

## Kontak

Jika Anda menemukan kesalahan data, memiliki pertanyaan, atau ingin berkontribusi, silakan buka *Issue* di repositori ini atau hubungi maintainer melalui kontak yang tersedia pada profil.

---