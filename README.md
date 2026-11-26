# 🧮 Math Fun Quiz — Cambridge Grade 1 (Chapter 5–8)

Aplikasi kuis **Mathematics** untuk anak kelas 1 SD (Cambridge Primary), mencakup **Chapter 5, 6, 7, dan 8**.

Dibuat dengan HTML, CSS, dan JavaScript murni dalam **satu file**. Tanpa database, tanpa CDN, tanpa internet. Tampilan diutamakan untuk **mobile**.

---

## ✨ Fitur

### Mode 1 — 📝 Multiple Choice
- 24 soal pilihan ganda (4 soal per topik)
- Soal Bahasa Inggris sederhana + terjemahan Bahasa Indonesia
- Pilihan jawaban **diacak** tiap kali main
- Tombol **🔊 Dengar soal** (speech synthesis `en-US`)
- Feedback langsung: benar/salah + kunci jawaban + penjelasan
- Skor otomatis + rincian per topik

### Mode 2 — 🕐 Clock Practice
- 6 tugas menggambar jarum jam sesuai waktu yang diminta
- **Jarum bisa digeser langsung** di jam analog (pointer/drag)
- Alternatif tombol besar: pilih jam 1–12 dan pilih menit **tepat (12)** atau **setengah (6)**
- Tampilan digital otomatis (`03:00`, `half past 2`, dll.) — melatih **menulis waktu**
- Siswa juga memilih **tulisan waktu** yang benar (`3 o'clock`, `half past 3`, ...)
- Skor 1 poin per tugas (jarum + tulisan harus benar) + rincian per jam

### Umum
- Progress bar, skor sementara, efek suara, konfeti, bintang 1–3
- Tombol **Ulangi** dan **Beranda**

---

## 📖 Cakupan materi

| Chapter | Topik | Jumlah soal |
|---------|-------|-------------|
| 5 | 🍎 Add quantities by combining two sets | 4 |
| 5 | 🔗 Begin to remember number bonds | 4 |
| 5 | ➖ Subtract by taking away a part from the whole | 4 |
| 6 | 🥇 Words for position and ordinal numbers | 4 |
| 7 | ⭕ Record, sort and show data using Venn diagrams | 4 |
| 8 | 📅 Names of days, write times, draw clock hands | 4 + 6 clock tasks |

**Kosa kata penting:** first, second, third, on, under, in, behind, between; overlapping circles, in both groups, sort; Monday–Sunday; o'clock, half past, minute hand, hour hand.

---

## 🔑 Kunci jawaban Multiple Choice

> Urutan mengikuti soal di file. **Pilihan diacak di aplikasi**, jadi lihat **teks jawaban**, bukan huruf A/B/C/D.

| No | Topik | Soal (singkat) | Jawaban |
|----|-------|----------------|---------|
| 1 | Add | 2 apples + 3 | **5** |
| 2 | Add | 4 + 3 | **7** |
| 3 | Add | 6 birds + 3 | **9** |
| 4 | Add | 5 balls + 3 balls | **8** |
| 5 | Bonds | 3 + ? = 10 | **7** |
| 6 | Bonds | 6 + 4 | **10** |
| 7 | Bonds | Bond making 10 | **6 + 4** |
| 8 | Bonds | 10 = 7 + ? | **3** |
| 9 | Subtract | 8 sweets − 2 | **6** |
| 10 | Subtract | 9 − 4 | **5** |
| 11 | Subtract | 7 ducks − 2 | **5** |
| 12 | Subtract | 10 − 6 | **4** |
| 13 | Position | Ordinal for 1 | **first** |
| 14 | Position | Who is second? | **Tortoise** |
| 15 | Position | Cat on top of box | **on** |
| 16 | Position | "di antara" | **between** |
| 17 | Venn | Venn uses | **overlapping circles** |
| 18 | Venn | Middle part | **in both groups** |
| 19 | Venn | Wings AND swim | **Duck** |
| 20 | Venn | Why sort data? | **to put things into groups** |
| 21 | Time | Day after Monday | **Tuesday** |
| 22 | Time | Days in a week | **7** |
| 23 | Time | 4 o'clock, minute hand | **12** |
| 24 | Time | Half past 3, minute hand | **6** |

---

## 🕐 Kunci Clock Practice

| Task | Perintah | Jarum jam | Jarum menit | Digital | Tulisan benar |
|------|----------|-----------|-------------|---------|---------------|
| 1 | Draw 3 o'clock | 3 | 12 | 03:00 | `3 o'clock` |
| 2 | Draw 7 o'clock | 7 | 12 | 07:00 | `7 o'clock` |
| 3 | Draw half past 2 | 2 | 6 | 02:30 | `half past 2` |
| 4 | Draw 10 o'clock | 10 | 12 | 10:00 | `10 o'clock` |
| 5 | Draw half past 6 | 6 | 6 | 06:30 | `half past 6` |
| 6 | Draw 12 o'clock | 12 | 12 | 12:00 | `12 o'clock` |

**Cara menggeser jarum:** tekan dan tahan bulatan kecil di ujung jarum (atau langsung tekan area jam), lalu geser ke angka yang diinginkan. Jarum jam akan menempel ke angka terdekat. Jarum menit otomatis menempel ke **12** (tepat jam) atau **6** (setengah jam).

---

## 🧮 Sistem penilaian

### Multiple Choice
- Tiap soal = **5 poin** → maksimal **24 × 5 = 120 poin**
- Nilai = `skor / 120 × 100%`

### Clock Practice
- Tiap tugas = **1 poin** (hanya jika jarum **dan** tulisan waktu benar)
- Maksimal **6 poin** → Nilai = `skor / 6 × 100%`

### Predikat (kedua mode)
| Persentase | Bintang | Keterangan |
|-----------|---------|------------|
| ≥ 90% | ⭐⭐⭐ | Luar Biasa! |
| ≥ 70% | ⭐⭐ | Hebat! |
| ≥ 50% | ⭐ | Bagus! |
| < 50% | ⭐ | Semangat! |

---

## 🚀 Cara menjalankan

### Opsi 1 — XAMPP
1. Pastikan Apache sudah *start*.
2. Letakkan folder di `C:\xampp\htdocs\math-quiz-kelas1\`.
3. Buka: `http://localhost/math-quiz-kelas1/index.html`

### Opsi 2 — Tanpa server
Klik 2x `index.html`. Tetap berfungsi lewat `file://` karena semua kode tertanam dalam satu file.

### Opsi 3 — GitHub Pages
`Settings → Pages → main / root`.

> **Catatan:** tombol 🔊 memakai `SpeechSynthesis` browser (paling stabil di Chrome/Edge desktop). Kuis tetap bisa dipakai tanpa suara. Menggeser jarum memakai Pointer Events — didukung Chrome/Edge/Safari modern, baik desktop maupun mobile.

---

## 📁 Struktur file

```
math-quiz-kelas1/
├── index.html   # aplikasi lengkap (HTML + CSS + JS)
└── README.md    # dokumentasi + kunci jawaban
```

---

## 🛠️ Cara mengubah soal

### Soal pilihan ganda
Cari `const MC_BANK = [ ... ]`:

```js
{
  t:'add',                       // id topik
  e:'🍎',                        // emoji
  q:'You have 2 apples...',      // soal (Inggris)
  id:'Kamu punya 2 apel...',     // terjemahan
  o:['4','5','6','7'],           // 4 pilihan
  a:'5',                         // kunci (teks harus persis sama dengan pilihan)
  tip:'2 + 3 = 5.'               // penjelasan
}
```

Id topik: `add`, `bonds`, `sub`, `position`, `venn`, `time`.

### Tugas jam
Cari `const CLOCK_TASKS = [ ... ]`:

```js
{h:3, m:0, id:'Gambar pukul 3 tepat.'}
```

`h` = jam (1–12), `m` = menit (`0` untuk o'clock, `30` untuk half past).  
Tulisan waktu dan pilihan pengganggu dibuat otomatis, jadi tidak perlu ditulis manual.

> Menambah/mengurangi soal otomatis mengubah nilai maksimal (`jumlah soal × 5` untuk MC, `jumlah task × 1` untuk Clock).

---

## 📄 Lisensi

Bebas digunakan dan dimodifikasi untuk keperluan belajar mengajar.
