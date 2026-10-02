# Tugas Blockchain

Implementasi dasar teknologi Blockchain menggunakan Python (Level 1 — Level 3).

## Berkas Proyek

1. **`level01_hash.py`**
   - Fungsi Hash SHA-256 (`sha256_hex`).
   - Serialisasi kanonik Dictionary ke JSON (`hash_dict`).
   - Perhitungan perbedaan bit (`bit_berbeda`) dan demonstrasi Avalanche Effect (`persen_bit_berbeda`).

2. **`level02_blok.py`**
   - Struktur blok: `index`, `timestamp`, `proof`, `previous_hash`.
   - Proof of Work (PoW) sederhana dan penambangan blok (`mine_block`).
   - Validasi rantai blok (`chain_valid`).

3. **`level03_tampering.py`**
   - Eksperimen manipulasi data blok (`ubah_blok`).
   - Deteksi kerusakan tautan rantai (`cari_tautan_putus`).
   - Eksperimen penyambungan kembali tautan (*re-linking*) tanpa mengulang PoW (`sambung_ulang`).

## Cara Menjalankan

```bash
python level01_hash.py
python level02_blok.py
python level03_tampering.py
```
