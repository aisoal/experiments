# AIsoal Experiments Data

> **Peran:** Dataset & Evaluation Artifacts

Repositori ini berfungsi sebagai penyimpanan (storage) terpusat untuk seluruh data eksperimen proyek AIsoal.

## 📂 Struktur Folder

- `[model-name]/`: Berisi file JSON hasil ekstraksi untuk masing-masing model LLM.
- `*.pdf`: File materi sumber yang digunakan sebagai basis data ground-truth.

## 📈 Hasil Evaluasi (Artifacts)

Seluruh hasil perhitungan metrik (CSV, Grafik, dan Tabel Summary) tidak disimpan di folder kode, melainkan diunggah secara otomatis ke bagian **[Releases](../../releases)** pada repositori ini.

**Format Hasil:**
Setiap rilis berisi:

1. `universal/`: Grafik perbandingan antar model.
2. `by_type/`: Analisis mendalam per tipe soal (Pilihan Ganda, Esai, dll).
3. `metadata.json`: Informasi tentang data profil eksekusi eksperimen kaggle.

---

_Data ini diolah menggunakan mesin evaluasi pada repositori `evaluate` melalui lingkungan Kaggle GPU._
