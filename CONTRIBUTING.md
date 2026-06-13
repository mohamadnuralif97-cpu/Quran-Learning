# 🤝 Kontribusi untuk AQSA Study Community

Terima kasih telah tertarik untuk berkontribusi pada AQSA Study Community! Panduan ini akan membantu Anda memahami proses kontribusi kami.

## 📋 Kode Etik Kami

Kami berkomitmen pada komunitas yang inklusif dan menghormati semua kontributor. Silakan baca [Code of Conduct](CODE_OF_CONDUCT.md) kami sebelum berkontribusi.

### Prinsip Utama
- ✅ Hormati semua orang dalam komunitas
- ✅ Bersikap konstruktif dan positif
- ✅ Fokus pada tujuan bersama (pembelajaran Al-Qur'an)
- ✅ Sangat welcome untuk semua level keahlian

## 🚀 Cara Berkontribusi

### 1. Report Bug / Laporkan Masalah

Jika Anda menemukan bug atau masalah, silakan [buat issue baru](https://github.com/mohamadnuralif97-cpu/Quran-Learning/issues).

**Informasi yang kami butuhkan:**
```
- Deskripsi masalah yang jelas
- Steps to reproduce (langkah-langkah untuk mereproduksi)
- Expected behavior (perilaku yang diharapkan)
- Actual behavior (perilaku sebenarnya)
- Browser dan device yang digunakan
- Screenshot (jika relevan)
```

**Contoh:**
```
Title: Search tidak berfungsi di mobile
Description: Ketika saya mencari materi di iPhone, search box tidak merespons input.
Steps: 1. Buka jilid5.html di iPhone, 2. Klik search box, 3. Ketik text
Expected: Text muncul dan search bekerja
Actual: Text tidak muncul, search tidak berfungsi
Device: iPhone 12, Safari
```

### 2. Saran Fitur Baru

Punya ide bagus? Kami ingin mendengarnya!

**Sebelum membuat issue:**
- Cek apakah fitur sudah ada atau sudah diusulkan
- Jelaskan use case Anda
- Deskripsikan bagaimana fitur ini akan membantu pengguna

**Template Saran Fitur:**
```
Title: [FEATURE] Deskripsi singkat fitur

## Deskripsi
Penjelasan detail tentang fitur yang diinginkan

## Use Case
Bagaimana fitur ini akan digunakan?

## Contoh
Berikan contoh konkret dari kasus penggunaan

## Alternatif
Apakah ada cara lain untuk mencapai tujuan ini?
```

### 3. Pull Request (Kontribusi Kode)

#### Setup Development Environment

```bash
# Clone repository
git clone https://github.com/mohamadnuralif97-cpu/Quran-Learning.git
cd Quran-Learning

# Buat branch baru
git checkout -b feature/nama-fitur-anda
# atau
git checkout -b fix/nama-bug-yang-anda-perbaiki

# Setup live server (pilih salah satu)
python -m http.server 8000
# atau
npx live-server
```

#### Membuat PR

1. **Fork repository** ke akun GitHub Anda
2. **Clone fork** ke komputer lokal
3. **Buat branch** dengan nama deskriptif:
   - `feature/` untuk fitur baru
   - `fix/` untuk perbaikan bug
   - `docs/` untuk dokumentasi
   - `style/` untuk styling/CSS

4. **Commit dengan pesan yang jelas:**
```bash
git commit -m "Add: feature description" 
# atau
git commit -m "Fix: bug description"
# atau
git commit -m "Docs: documentation update"
```

5. **Push ke GitHub:**
```bash
git push origin feature/nama-fitur-anda
```

6. **Buat Pull Request** dengan:
   - Judul yang deskriptif
   - Deskripsi detail tentang perubahan
   - Link ke issue yang terkait (jika ada)
   - Screenshot dari UI changes (jika relevan)

#### PR Template
```
## Deskripsi
Jelaskan perubahan yang Anda buat secara singkat.

## Tipe Perubahan
- [ ] Bug fix (perbaikan bug yang tidak mengganggu fitur ada)
- [ ] Feature (fitur baru atau enhancement)
- [ ] Breaking change (perubahan yang mengganggu fitur existing)
- [ ] Documentation update

## Testing
Bagaimana Anda menguji perubahan ini?

## Checklist
- [ ] Kode saya mengikuti gaya kode project
- [ ] Saya telah melakukan self-review
- [ ] Saya telah mengomentari kode yang kompleks
- [ ] Saya telah memperbarui dokumentasi (jika diperlukan)
- [ ] Perubahan saya tidak membuat warning baru
- [ ] Saya telah menguji di desktop dan mobile
```

## 📝 Gaya Kode

### HTML
```html
<!-- Gunakan semantic HTML -->
<section class="content">
  <h2>Judul Section</h2>
  <p>Paragraf dengan ...</p>
</section>

<!-- Attributes dalam order: class, id, data-* -->
<button class="btn btn-primary" id="submitBtn" data-action="submit">
  Submit
</button>
```

### CSS
```css
/* Gunakan CSS custom properties untuk tema */
:root {
  --primary: #1a5f4a;
  --text: #1a2b2f;
}

/* BEM naming convention */
.button {
  padding: 0.5rem 1rem;
}

.button--primary {
  background: var(--primary);
  color: white;
}

.button__text {
  font-weight: 600;
}
```

### JavaScript
```javascript
// Gunakan camelCase untuk variabel dan fungsi
const searchBox = document.getElementById('searchBox');
const results = [];

// Gunakan const/let, hindari var
const updateProgress = () => {
  // ...
};

// Gunakan template literals
console.log(`Progress: ${percentage}%`);

// Tambahkan komentar untuk logika kompleks
// Update progress bar every 200ms
const debounceTimer = setTimeout(() => {
  updateProgress();
}, 200);
```

## 🧪 Testing

### Manual Testing Checklist
- [ ] Tested di Chrome desktop
- [ ] Tested di Firefox desktop
- [ ] Tested di Safari desktop
- [ ] Tested di Chrome mobile
- [ ] Tested di Firefox mobile
- [ ] Tested di Safari mobile (iOS)
- [ ] Dark mode berfungsi
- [ ] Responsive design OK
- [ ] No console errors
- [ ] All links work

### Testing Khusus untuk Fitur
```
✅ Jika menambah halaman baru:
  - Sidebar link berfungsi
  - Back button berfungsi
  - Progress tracking bekerja
  - Search berfungsi
  - Dark mode berfungsi

✅ Jika mengubah styling:
  - Responsif di mobile
  - Dark mode konsisten
  - Aksesibilitas terjaga
  - Font Arabic tampil benar

✅ Jika menambah fitur interaktif:
  - localStorage bekerja
  - Data persisten
  - Error handling OK
  - Mobile-friendly
```

## 📚 Jenis Kontribusi

### Kode
- Fitur baru yang berguna
- Bug fixes
- Performance improvements
- Code refactoring
- Accessibility improvements

### Dokumentasi
- Memperbaiki typo
- Menambah contoh
- Menerjemahkan ke bahasa lain
- Membuat tutorial
- Menyempurnakan README

### Testing
- Melaporkan bug
- Menguji fitur baru
- Cross-browser testing
- Performance testing

### Community
- Menjawab pertanyaan di Issues
- Share pengalaman di Discussions
- Membantu pengguna lain
- Memberikan feedback

## 🎯 Prioritas Kontribusi

### 🔴 High Priority
- Bug fixes (terutama yang mengganggu UX)
- Accessibility improvements
- Performance optimization
- Security fixes

### 🟡 Medium Priority
- Fitur enhancement yang diminta banyak
- Documentation improvements
- Code refactoring
- UI/UX improvements

### 🟢 Nice to Have
- Minor UI tweaks
- New experimental features
- Additional translations
- Community contributions

## 💬 Komunikasi

- **Issues**: Untuk bug reports dan feature requests
- **Discussions**: Untuk tanya jawab dan diskusi umum
- **Pull Requests**: Untuk diskusi implementasi
- **Email**: Untuk topik sensitif atau direct contact

## 📖 Dokumentasi Terkait

- [Panduan Gaya](STYLE_GUIDE.md)
- [Roadmap](ROADMAP.md)
- [FAQ](FAQ.md)
- [Code of Conduct](CODE_OF_CONDUCT.md)

## 🏆 Pengakuan Kontributor

Kami akan mengakui semua kontributor di:
- [CONTRIBUTORS.md](CONTRIBUTORS.md)
- GitHub repository page
- Halaman About (segera hadir)

## ❓ Pertanyaan?

- Buka discussion di GitHub
- Buat issue dengan tag `question`
- Email kami di info@aqsastudy.com

---

<div align="center">

### Terima kasih telah membantu membuat AQSA Study Community lebih baik! ❤️

**Setiap kontribusi, besar atau kecil, sangat kami apresiasi.**

</div>
