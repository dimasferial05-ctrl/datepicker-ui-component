# Datepicker UI Component

Proyek ini adalah implementasi antarmuka pengguna (UI) pencari tanggal (*datepicker*) statis yang dibangun sebagai solusi tantangan dari [roadmap.sh]([https://roadmap.sh/](https://roadmap.sh/projects/datepicker-ui)). Fokus utama proyek ini adalah melatih teknik pemosisian elemen dan tata letak tabel kalender menggunakan CSS modern.

Meskipun saat ini bersifat statis (tanpa JavaScript), komponen ini menyediakan fondasi struktur yang kuat untuk dikembangkan menjadi *datepicker* interaktif di masa depan.

## ✨ Fitur Utama

- **CSS Grid Power:** Menggunakan tata letak Grid untuk menyusun hari dan tanggalan secara presisi dalam 7 kolom (Su-Sa).
- **Absolute Positioning:** Implementasi *popup* kalender menggunakan `position: absolute` sehingga muncul tepat di bawah *input field* dengan *depth* (z-index) yang benar.
- **Clean & Modern UI:** Desain minimalis menggunakan Google Fonts (Inter) dengan fokus pada keterbacaan tinggi.
- **Hover & Selection States:** Menyediakan efek visual saat tanggal disorot (*hover*) dan indikator untuk tanggal yang sedang dipilih (*selected*).
- **Ikon Vektor:** Menggunakan SVG untuk ikon kalender agar tetap tajam di semua resolusi layar.

## 📂 Struktur Proyek

- `index.html` - Struktur semantik untuk input grup dan kontainer kalender.
- `style.css` - Logika desain, sistem Grid, dan teknik pemosisian *absolute*.

## 🛠️ Teknologi yang Digunakan

- **HTML5** (Semantik)
- **CSS3** (CSS Grid, Absolute Positioning, Flexbox)
- **Google Fonts** (Inter)

## 💻 Cara Menjalankan Secara Lokal

1.  *Clone* repositori ini:
    ```bash
    git clone [https://github.com/dimasferial05-ctrl/datepicker-ui-component.git](https://github.com/dimasferial05-ctrl/datepicker-ui-component.git)
    ```
2.  Buka folder proyek di dalam direktori kerja Anda (misalnya di Laragon).
3.  Buka file `index.html` melalui browser pilihan Anda.

## 👨‍💻 Penulis

**Dimas Ferial Hidayat**
- GitHub: [@dimasferial05-ctrl](https://github.com/dimasferial05-ctrl)
