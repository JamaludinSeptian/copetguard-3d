# CopetGuard — Landing Page (3D)

Halaman konsep demo untuk CopetGuard: pendamping disiplin keluar untuk
scalper DLMM Solana. Satu file statis (`index.html`), tanpa build step.

## Isi

- Hero dengan adegan 3D real-time (three.js 0.169.0 via CDN): 64 instanced
  bin likuiditas, pita harga + bead, orb emas + 2 cincin penjaga, grid/fog/debu,
  bloom. Kalau WebGL gagal atau CDN diblokir, fallback Canvas 2D menggambar
  adegan yang sama tanpa dependensi eksternal.
- Panel mockup posisi (angka contoh), 5 aturan exit Playbook, 3 langkah cara
  kerja, tagline reveal, 3 testimoni berlabel contoh, FAQ 8 pertanyaan,
  form waitlist front-end only (tidak menyimpan apa-apa).
- Footer menyatakan halaman ini konsep demo; edukasi, bukan saran finansial.

## Menjalankan lokal

Buka `index.html` di browser, atau layani folder ini dengan server statis
apa pun. Tidak perlu build.

## Deploy

Repo ini terhubung ke Vercel (Hobby). Setiap push ke branch utama
men-deploy ulang otomatis sebagai situs statis.
