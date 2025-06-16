# Panduan Instalasi Vibe Coding V1.4

## 📥 Cara Mendapatkan Vibe Coding

### Opsi 1: Clone dari GitHub (Direkomendasikan)
```bash
# Clone repositori
git clone https://github.com/username/petunjuk-vibe-coding.git

# Masuk ke direktori
cd petunjuk-vibe-coding
```

### Opsi 2: Download ZIP
1. Kunjungi halaman GitHub repositori ini
2. Klik tombol "Code" → "Download ZIP"
3. Extract file ZIP ke komputer Anda

## 🚀 Setup di Proyek Baru

### Langkah 1: Salin Folder Vibe-Guide
```bash
# Dari direktori proyek Anda
cp -r /path/to/petunjuk-vibe-coding/vibe-guide .

# Contoh konkret:
# cp -r ~/Downloads/petunjuk-vibe-coding/vibe-guide .
```

### Langkah 2: Inisialisasi
```bash
# Berikan izin eksekusi
chmod +x vibe-guide/init_vibe.sh

# Jalankan inisialisasi
./vibe-guide/init_vibe.sh
```

### Langkah 3: Konfigurasi Tim
```bash
# Edit file team manifest
nano vibe-guide/team-manifest.md
# atau
code vibe-guide/team-manifest.md
```

## 📁 Struktur Setelah Instalasi

Setelah menjalankan `init_vibe.sh`, proyek Anda akan memiliki:

```
proyek-anda/
├── vibe-guide/           # Tools dan template
│   ├── init_vibe.sh      # Skrip inisialisasi/reset
│   ├── template-papan.md # Template papan proyek
│   └── team-manifest.md  # Daftar anggota tim
├── memory-bank/          # Konteks aktif (dibuat otomatis)
│   ├── spesifikasi-produk.md
│   ├── papan-proyek.md
│   ├── architecture.md
│   └── progress.md
├── baby-steps-archive/   # Riwayat pekerjaan (dibuat otomatis)
└── src/                  # Kode aplikasi Anda (dibuat otomatis)
```

## ✅ Verifikasi Instalasi

Pastikan instalasi berhasil dengan mengecek:

```bash
# Cek struktur folder
ls -la

# Cek isi memory-bank
ls -la memory-bank/

# Cek template papan proyek
cat memory-bank/papan-proyek.md
```

## 🔄 Reset/Update

Untuk mereset papan proyek setelah menyelesaikan baby-step:

```bash
./vibe-guide/init_vibe.sh --reset
```

## 🆘 Troubleshooting

### Permission Denied
```bash
# Jika mendapat error permission denied
chmod +x vibe-guide/init_vibe.sh
```

### File Tidak Ditemukan
```bash
# Pastikan Anda berada di direktori yang benar
pwd

# Pastikan folder vibe-guide ada
ls -la vibe-guide/
```

### Skrip Tidak Berjalan
```bash
# Jalankan dengan bash eksplisit
bash vibe-guide/init_vibe.sh
```

---

**Selanjutnya:** Baca [PANDUAN_SINGKAT.md](./PANDUAN_SINGKAT.md) untuk memulai pengembangan dengan Vibe Coding.