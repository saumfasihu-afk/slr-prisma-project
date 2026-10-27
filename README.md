# Systematic Literature Review (PRISMA 2020)

**Judul kerja:** [isi judul]
**Penulis:** [nama]
**Status:** Tahap 1 - Protokol

## Struktur repo

| Folder | Isi |
|---|---|
| `01-protocol/` | Pertanyaan penelitian, PICO/PICOS, kriteria inklusi-eksklusi, strategi pencarian |
| `02-search/` | String pencarian per database, tanggal pencarian, hasil ekspor (.ris/.csv/.bib) |
| `03-screening/` | Log seleksi judul/abstrak dan teks lengkap, alasan eksklusi, data diagram alir PRISMA |
| `04-extraction/` | Tabel ekstraksi data dan penilaian risk of bias |
| `05-synthesis/` | Sintesis naratif/tematik |
| `06-manuscript/` | Draf manuskrip per bagian |
| `references/` | `references.bib` (sumber tunggal referensi) |
| `figures/` | Diagram alir PRISMA dan gambar lain |

## Alur kerja

1. Isi `01-protocol/protocol.md` (skill: slr-prisma).
2. Cari literatur (Consensus + database lain) dan catat di `02-search/search-log.md`.
3. Seleksi studi dan catat jumlah tiap tahap di `03-screening/screening-log.md`.
4. Ekstraksi data dan nilai risk of bias di `04-extraction/`.
5. Sintesis di `05-synthesis/`.
6. Tulis manuskrip di `06-manuscript/` (skill: academic-writing).
7. Rapikan referensi di `references/references.bib` (skill: academic-citation-manager).

## Aturan

- Setiap referensi harus diverifikasi ke DOI/sumber asli sebelum dimasukkan ke `references.bib`.
- Catat setiap pencarian (database, tanggal, string, jumlah hasil) agar PRISMA dapat direproduksi.
- Jangan commit PDF berhak cipta; simpan hanya metadata dan catatan.
