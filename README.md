# Sistem Antrean Pasien

## Deskripsi

Sistem Antrean Pasien adalah aplikasi berbasis web yang dibuat menggunakan Python dan Streamlit untuk membantu pengelolaan antrean pasien di klinik.

Aplikasi ini menerapkan struktur data Queue (deque) dengan konsep FIFO (First In First Out) serta mendukung prioritas pasien darurat.

## Fitur

- Dashboard antrean
- Tambah pasien
- Panggil pasien
- Cari pasien
- Riwayat pasien
- Reset data
- Prioritas pasien darurat

## Struktur Data

Aplikasi menggunakan Queue (deque) dari library collections.

Operasi yang digunakan:

- append() untuk menambah antrean
- popleft() untuk memanggil pasien

## Teknologi

- Python
- Streamlit
- Collections Deque

## Cara Menjalankan

Install library:

```bash
pip install streamlit
```

Jalankan aplikasi:

```bash
streamlit run app.py
```

## Flow Sistem

1. Pasien melakukan pendaftaran.
2. Sistem memberikan nomor antrean.
3. Data pasien masuk ke antrean normal atau darurat.
4. Pasien darurat diprioritaskan.
5. Pasien dipanggil sesuai urutan antrean.
6. Data pasien yang telah dilayani masuk ke riwayat.

## Pengembang

Proyek UAS Struktur Data

Sistem Antrean Klinik

Tahun 2026
