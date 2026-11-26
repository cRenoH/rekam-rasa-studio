# Rekam Rasa Studio — halaman portofolio

Satu berkas: `index.html`. Tanpa dependensi, tanpa build.

## Publikasi ke GitHub Pages

```bash
cd portofolio
git init
git add index.html
git commit -m "portofolio Rekam Rasa Studio"
git branch -M main
git remote add origin https://github.com/USERNAME/rekam-rasa-studio.git
git push -u origin main
```

Lalu di GitHub: **Settings → Pages → Source: Deploy from a branch → main / (root) → Save**.
Alamat aktif dalam 1–2 menit: `https://USERNAME.github.io/rekam-rasa-studio/`

## Uji lokal sebelum push

```bash
python -m http.server 8080
# buka http://localhost:8080
```

## Yang perlu diganti

- `mailto:23.11.5811@students.amikom.ac.id` → email aktif (jika berbeda)
- Kotak `Klip sebelum–sesudah (video menyusul)` → ganti dengan `<video src="assets/nama.mp4" controls playsinline poster="assets/poster.jpg"></video>`
- Harga di bagian `#layanan` → sesuaikan bila berubah

## Isi halaman

Hero · Karya (3 studi kasus) · Layanan & Harga · Proses 4 tahap · Tentang · Kontak

Semua karya diberi label **proyek latihan** — jangan dihapus. Itu bagian dari kejujuran dokumen Pertemuan 6.
