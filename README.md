# Terryus Wijaya — Self Landing Page Portfolio

Landing page portofolio pribadi berbasis **HTML + CSS murni** (tanpa JavaScript).

## Bahasa
Website tersedia dalam **Bahasa Indonesia** dan **English**. Tombol **ID / EN** di navigasi memakai CSS murni (radio button + selector `:has()`), tanpa JavaScript.

## Halaman / Section
1. **Homepage** — hero, status, CTA, ilustrasi rute beranimasi, ticker keahlian
2. **About** — profil, statistik, skill
3. **Project** — kartu project pilihan
4. **Hobby** — kartu hobi
5. **Kontak** — form kontak (Form CSS)

## CSS Animation yang dipakai
- `@keyframes fadeUp` — teks hero muncul bertahap (stagger dengan `animation-delay`)
- `@keyframes drawRoute` — garis rute tergambar (`stroke-dashoffset`)
- `@keyframes drive` — titik "truk" bergerak di jalur (`offset-path`)
- `@keyframes pulse` — indikator status berdenyut
- `@keyframes marquee` — ticker berjalan (pause saat hover)
- `@keyframes float` — chip melayang
- `@keyframes blink` — kursor ketik
- `@keyframes spin` — bingkai foto berputar
- `@keyframes reveal` + `animation-timeline: view()` — reveal saat scroll (progressive enhancement)
- Transisi hover pada nav, tombol, kartu project, dan kartu hobi
- Menghormati `prefers-reduced-motion`

## Form CSS
- Floating label dengan `:placeholder-shown` dan `:focus`
- Validasi visual `:user-valid` / `:user-invalid` + pesan hint
- Custom select arrow, custom checkbox (`appearance: none` + `:checked`)
- Tombol submit redup saat form belum valid (`form:invalid`)

## Struktur
```
terry-portfolio/
├── index.html
├── css/style.css
├── img/ (foto hero & about)
└── README.md
```

## Menjalankan
Buka `index.html` di browser. Untuk GitHub Pages: Settings → Pages → Deploy from branch `main` / root.

Semua konten sudah terisi.
