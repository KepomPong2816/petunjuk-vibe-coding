# Petunjuk Vibe Coding Indonesia V1.4

**Metodologi pengembangan perangkat lunak kolaboratif antara Manusia dan AI**

Vibe Coding adalah pendekatan pengembangan perangkat lunak di mana **Manusia dan AI bekerja sebagai tim hibrida yang setara**. Setiap anggota tim memiliki tanggung jawab jelas dan berkontribusi langsung ke basis kode.

## 🚀 Mulai Cepat

1. **[Download/Clone repositori ini](./INSTALASI.md#-cara-mendapatkan-vibe-coding)**
2. **Salin folder `vibe-guide/` ke proyek Anda**
3. **Jalankan setup:**
   ```bash
   chmod +x vibe-guide/init_vibe.sh
   ./vibe-guide/init_vibe.sh
   ```
4. **Mulai coding:** Baca [Panduan Singkat](./PANDUAN_SINGKAT.md)

> **Detail lengkap:** Lihat [Panduan Instalasi](./INSTALASI.md)

## 🌟 Fitur Utama V1.4

- **Tim Hibrida**: AI sebagai pengembang resmi dengan tanggung jawab tercatat
- **Tugas Teralokasi**: Setiap tugas memiliki assignee yang jelas (manusia atau AI)
- **Otomatisasi Penuh**: Skrip untuk setup dan reset alur kerja
- **Git Commit oleh AI**: AI melakukan commit atas nama mereka sendiri
- **Panduan Terintegrasi**: Semua materi dalam satu folder `vibe-guide/`

## 📂 Struktur Proyek

Setelah inisialisasi, proyek Anda akan memiliki struktur:

```
proyek-anda/
├── vibe-guide/           # Panduan dan tools (salin dari repositori ini)
│   ├── init_vibe.sh
│   ├── template-papan.md
│   └── team-manifest.md
├── memory-bank/          # Konteks aktif proyek (dibuat otomatis)
│   ├── spesifikasi-produk.md
│   ├── papan-proyek.md
│   ├── architecture.md
│   └── progress.md
├── baby-steps-archive/   # Riwayat pekerjaan (dibuat otomatis)
└── src/                  # Kode aplikasi Anda
```

## 🔄 Alur Kerja Singkat

1. **Perencanaan**: Update `memory-bank/papan-proyek.md` dengan tugas-tugas kecil
2. **Penugasan**: Tentukan assignee untuk setiap tugas (manusia/AI)
3. **Implementasi**: Setiap assignee mengerjakan tugasnya
4. **Testing**: Validasi hasil sesuai kriteria
5. **Commit**: Assignee melakukan git commit
6. **Reset**: Jalankan `./vibe-guide/init_vibe.sh --reset` untuk siklus baru

## 📖 Dokumentasi

- **[⚡ Instalasi](./INSTALASI.md)** - Cara mendapatkan dan setup Vibe Coding
- **[📋 Panduan Singkat](./PANDUAN_SINGKAT.md)** - Konsep dasar & alur kerja
- **[📚 Panduan Lengkap V1.4](./PANDUAN_V1.4.md)** - Dokumentasi detail & contoh

## 🤝 Kontribusi

Kami menerima kontribusi untuk meningkatkan panduan ini. Silakan buat issue atau pull request.

---

**Lisensi:** MIT | **Versi:** 1.4 | **Bahasa:** Indonesia
