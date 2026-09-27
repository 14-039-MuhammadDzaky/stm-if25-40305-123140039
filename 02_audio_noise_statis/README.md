# Tugas 2: Analisis Sinyal Audio & Noise Statis

Pada folder ini adalah hasil pengerjaan tugas mengenai Analisis Sinyal Audio & Noise Statis.

---

## 👤 Informasi Praktikan

- **Nama** : Muhammad Dzaky
- **NIM** : 123140039
- **Mata Kuliah**: Sistem Teknologi Multimedia (IF25-40305)

---

## 💻 Catatan Perangkat
### 1. Perangkat Keras (Hardware)
- **Perangkat Perekam (Microphone)**: microphone.
- **Komputer / Laptop**: Acer Aspire 5.
---

## 🔊 Sumber Noise Statis & Karakteristik Sinyal Audio

- **Sumber Rekaman**: Rekaman suara pembacaan artikel berita olahraga dengan noise statis berupa suara elektronik pencukur rambut .
- **Rekaman Suara (`audio_original.wav`)**:
  - **Durasi Audio**: ~11Detik

---

## 📁 Deskripsi Berkas dalam Folder

| Nama Berkas | Jenis / Format | Deskripsi & Fungsi |
| :--- | :--- | :--- |
| [`tugas_audio_noise_statis.ipynb`](./tugas_audio_noise_statis.ipynb) | Jupyter Notebook | Notebook utama berisi kode pemrosesan sinyal, pemfilteran, visualisasi domain waktu & frekuensi, serta hasil eksekusi lengkap. |
| [`tugas_audio_noise_statis.pdf`](./tugas_audio_noise_statis.pdf) | Dokumen PDF | Berkas ekspor PDF dari Jupyter Notebook sebagai cadangan visual dan laporan siap cetak. |
| [`audio_original.wav`](./audio_original.wav) | Audio WAV | Rekaman asli berisi pembacaan berita olahraga dengan noise statis. |
| [`audio_downsampled_naive.wav`](./audio_downsampled_naive.wav) | Audio WAV | Hasil *downsampling* langsung tanpa filter *anti-aliasing*,. |
| [`audio_downsampled_clean.wav`](./audio_downsampled_clean.wav) | Audio WAV  | Hasil *resampling* bersih yang menerapkan *Low-Pass Filter* . |
| [`README.md`](./README.md) | Dokumentasi Markdown | Catatan ringkas perangkat dan sumber noise. |

---
