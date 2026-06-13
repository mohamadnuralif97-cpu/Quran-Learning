# 📚 AQSA Study Community - Platform Pembelajaran Al-Qur'an

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34C26?style=flat&logo=html5&logoColor=white)](https://html.spec.whatwg.org/)
[![Responsive](https://img.shields.io/badge/Responsive-Mobile%20First-blue)](https://en.wikipedia.org/wiki/Responsive_web_design)

**AQSA Study Community** adalah platform pembelajaran Al-Qur'an yang interaktif dan modern, menggunakan metode **Iqro'** yang telah terbukti efektif. Platform ini dirancang untuk memudahkan santri belajar membaca Al-Qur'an dengan tartil, baik secara mandiri maupun dalam pembelajaran terstruktur.

## ✨ Fitur Utama

### 📖 Materi Pembelajaran Komprehensif
- **Iqro' Jilid 5**: 30 halaman latihan mencakup waqof, tasydid, idghom, alif-lam, dan lafadz Allah
- **Iqro' Jilid 6**: 32 halaman latihan untuk pendalaman tajwid (idghom, iqlab, ikhfa', waqof, qolqolah, EBTA)
- Konten interaktif dengan contoh ayat Al-Qur'an
- Kuis evaluasi di setiap jilid untuk mengukur pemahaman

### 🎨 Desain Modern & Responsif
- Interface yang user-friendly dan intuitif
- **Dark Mode** untuk kenyamanan membaca malam hari
- Fully responsive di desktop, tablet, dan mobile
- Navigasi sidebar yang mudah digunakan
- Animasi halus dan transisi yang elegan

### 📱 Aksesibilitas Penuh
- Desain mobile-first untuk akses optimal di semua perangkat
- Font Arabic KFGQPC Uthmanic yang jelas dan mudah dibaca
- Kontras warna yang baik untuk aksesibilitas visual
- Touch-friendly interface untuk pengguna smartphone

### 📊 Tracking & Progress
- **Progress Bar**: Monitor perkembangan belajar secara real-time
- **Bookmark System**: Simpan halaman favorit atau yang sedang dipelajari
- **Personal Notes**: Catat poin penting dan catatan pribadi
- **Search Functionality**: Cari materi dengan cepat dan mudah

### 💾 Penyimpanan Lokal
- Semua data tersimpan di perangkat (localStorage)
- Tidak ada server eksternal yang dibutuhkan
- Privacy terjamin - data Anda tetap aman di perangkat

### 🌙 Dark Mode & Tema
- Toggle dark/light mode dengan satu klik
- Pilihan tema tersimpan di browser
- Optimal untuk belajar di waktu siang atau malam

## 🚀 Cara Memulai

### Akses Online
Kunjungi platform langsung di:
```
https://mohamadnuralif97-cpu.github.io/Quran-Learning/
```

### Penggunaan Lokal
1. Clone repository ini:
```bash
git clone https://github.com/mohamadnuralif97-cpu/Quran-Learning.git
cd Quran-Learning
```

2. Buka file HTML di browser:
- **Halaman Utama**: `index.html`
- **Iqro' Jilid 5**: `jilid5.html`
- **Iqro' Jilid 6**: `jilid6.html`

Atau gunakan live server:
```bash
python -m http.server 8000
# atau
npx live-server
```

Kemudian akses di `http://localhost:8000`

## 📚 Struktur Materi

### Iqro' Jilid 5 (30 Halaman)
| Halaman | Materi | Deskripsi |
|---------|--------|-----------|
| 1-2 | Alif dianggap tidak ada | Latihan huruf alif |
| 3-7 | Waqof | Cara berhenti bacaan |
| 8-10 | Tanwin pada waqof | Tanwin saat berhenti |
| 12-22 | Tasydid | Huruf bertasydid |
| 23 | Surat Al-Mu'minun | Hafalan |
| 24-25 | Lafadz Allah | Bacaan tebal/tipis |
| 26-28 | Idghom | Penyatuan huruf |
| 29-30 | Latihan Campuran | Gabungan kaidah |

### Iqro' Jilid 6 (32 Halaman)
| Halaman | Materi | Deskripsi |
|---------|--------|-----------|
| 1-6 | Idghom Bighunnah | Penyatuan dengan dengung |
| 7-9 | Iqlab | Perubahan nun ke mim |
| 11-18 | Ikhfa' (15 huruf) | Pembacaan samar |
| 19-24 | Waqof & Variasi | Tanda-tanda henti |
| 25 | Latihan Campuran | Kombinasi kaidah |
| 26-28 | Huruf Awal Surat | Pengenalan fawātih |
| 29-31 | EBTA & Evaluasi | Ujian akhir |
| 32 | Penutup | Pesan dan nasihat |

## 🎯 Fitur Detail

### 📖 Pembelajaran Interaktif
```html
- Ayat Al-Qur'an dengan harakat lengkap
- Contoh bacaan yang benar
- Penjelasan kaidah tajwid praktis
- Grid latihan dengan koleksi kata
```

### 📊 Sistem Evaluasi
```
- Kuis multiple choice di akhir jilid
- Feedback instan (benar/salah)
- Perhitungan skor otomatis
- Opsi untuk mengulang kuis
```

### 🔍 Pencarian Cepat
```
- Cari materi berdasarkan nama kaidah
- Hasil search real-time
- Navigasi langsung ke halaman terkait
```

### 📝 Catatan Pribadi
```
- Tulis catatan tanpa batas
- Penyimpanan otomatis
- Hapus catatan kapan saja
```

## 🎨 Teknologi yang Digunakan

| Teknologi | Penggunaan |
|-----------|-----------|
| **HTML5** | Struktur halaman |
| **CSS3** | Styling & animasi |
| **Vanilla JavaScript** | Interaktivitas |
| **Font KFGQPC Uthmanic** | Penulisan Al-Qur'an |
| **localStorage API** | Penyimpanan data lokal |
| **CSS Grid & Flexbox** | Layout responsif |

## 📱 Kompatibilitas Browser

| Browser | Desktop | Mobile |
|---------|---------|--------|
| Chrome | ✅ | ✅ |
| Firefox | ✅ | ✅ |
| Safari | ✅ | ✅ |
| Edge | ✅ | ✅ |
| Opera | ✅ | ✅ |

## 🎓 Panduan Penggunaan

### Memulai Pembelajaran
1. Klik **"Mulai Belajar"** di halaman beranda
2. Pilih Jilid yang ingin dipelajari (5 atau 6)
3. Baca setiap halaman dengan cermat
4. Ikuti kaidah tajwid yang dijelaskan

### Menggunakan Sidebar
```
📊 Progress Bar  → Lihat persentase progres
🔍 Search       → Cari materi spesifik
📑 Daftar Isi   → Navigasi ke halaman
📝 Catatan      → Tulis catatan pribadi
```

### Navigasi Halaman
- **Scroll**: Gulir ke atas/bawah
- **Sidebar Links**: Klik untuk navigasi langsung
- **Search**: Tekan Enter untuk lompat ke hasil
- **Back Button**: Kembali ke halaman utama

### Menyimpan Progress
1. Buka halaman yang sedang dipelajari
2. Klik tombol **"Bookmark"** di sidebar
3. Bookmark tersimpan dan dapat diakses lagi

## 🌙 Dark Mode

Untuk mengaktifkan dark mode:
1. Klik tombol **"🌙 Dark"** atau **"◐"** di navbar
2. Mode akan tersimpan otomatis
3. Preferensi akan berlaku di kunjungan berikutnya

## 💡 Tips Belajar Efektif

### ✅ Untuk Santri
- **Pelan Asal Benar**: Jangan terburu-buru, utamakan ketepatan bacaan
- **Ulangi Setiap Halaman**: Latih setiap baris minimal 3 kali
- **Dengarkan Bacaan**: Jika bisa, dengarkan murottal sebagai referensi
- **Catat Kesulitan**: Gunakan fitur catatan untuk mencatat bagian sulit
- **Evaluasi Diri**: Kerjakan kuis untuk mengukur pemahaman

### ✅ Untuk Guru/Pendamping
- **Monitor Progress**: Cek progress santri secara berkala
- **Berikan Motivasi**: Apresiasi setiap pencapaian
- **Personalisasi**: Sesuaikan kecepatan dengan kemampuan santri
- **Feedback Konstruktif**: Berikan masukan untuk improvement

## 📖 Referensi

- **Metode Iqro'** oleh KH. As'ad Humam
- **Team Tadarus "AMM"** Yogyakarta
- **Balai Litbang LPTQ Nasional**

Edisi yang digunakan: **Revisi Tahun 2000**

## 🤝 Kontribusi

Kami menerima kontribusi untuk meningkatkan platform:

1. **Report Bug**: [Buat Issue Baru](https://github.com/mohamadnuralif97-cpu/Quran-Learning/issues)
2. **Saran Fitur**: Diskusikan ide Anda
3. **Pull Request**: Buat PR dengan deskripsi jelas

## 📄 Lisensi

Project ini dilisensikan di bawah **MIT License** - lihat file LICENSE untuk detail.

## 👥 Pembuat

**AQSA Study Community**
- Dikembangkan dengan ❤️ untuk umat Muslim
- Platform gratis dan terbuka untuk semua

## 🔗 Tautan Penting

- **Repository**: [GitHub](https://github.com/mohamadnuralif97-cpu/Quran-Learning)
- **Issues**: [Report Problem](https://github.com/mohamadnuralif97-cpu/Quran-Learning/issues)

---

<div align="center">

### 🌙 Semoga Bermanfaat untuk Pembelajaran Al-Qur'an

**"خَيْرُكُمْ مَنْ تَعَلَّمَ الْقُرْآنَ وَعَلَّمَهُ"**

*Sebaik-baik kalian adalah yang belajar Al-Qur'an dan mengajarkannya.*

</div>
