# nurunala

Situs tulisan personal Azhar Nurunala — *segala yang fana, abadi dalam aksara.*

HTML statis murni, tanpa build step. Di-hosting di Cloudflare Pages.

## Struktur
- `index.html` — beranda / daftar tulisan (Blog)
- `buku.html`, `kelas.html`, `tentang.html` — halaman lain
- `baca.html` — halaman baca tulisan (`baca.html?i=N`)
- `data.js` — sumber semua tulisan
- `styles.css` — gaya
- `404.html`, `robots.txt`, `sitemap.xml`, `_headers` — pendukung

## Deploy (Cloudflare Pages)
- Framework preset: **None**
- Build command: *(kosong)*
- Build output directory: **/**

Tiap push ke branch utama akan otomatis deploy ulang.
