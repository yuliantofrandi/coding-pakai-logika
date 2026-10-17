# Coding Pakai Logika

Skill Claude berbahasa Indonesia untuk tim produk & development.

## Skill di dalamnya

### `ba-uiux`
Mode kerja **Business Analyst + UI/UX Designer** berprinsip **MVP dulu**. Panggil di awal sesi UI/UX sebagai pengganti "resume this project".

- **Siapkan repo:** pindah ke branch utama → pull → buat branch `uiux/<fitur>` saat mulai UI/UX baru. Kalau ada perubahan yang belum di-commit, Claude bertanya dulu.
- **Lanjutkan konteks:** membaca `docs/ux-rules.md` lalu meringkas flow, keputusan terbuka, dan backlog. Kalau belum ada, file dibuat dari `template-rules.md`.
- **Aturan kerja:** pisahkan must-have vs nice-to-have, tanpa menyentuh backend/API/database, tandai titik integrasi (`TODO-INTEGRASI`) untuk programmer.
- **Dokumentasi:** semua rules, acceptance criteria, dan field/record default dicatat per flow di `.md` dan diperbarui setiap ada keputusan.
- **Tombol Rules:** setiap prototype punya tombol melayang di kanan atas untuk membaca isi `.md` (`rules-button.html`).

## Pakai

```
/ba-uiux
/ba-uiux halaman checkout
```
