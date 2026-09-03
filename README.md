# Portofolio Digital LK 2 — PPG Prajabatan BK

Portofolio Lembar Kerja 2 milik **Fahira Firzha Wianda** (NIM 26960002, IKIP Siliwangi,
PPL di SMA Negeri 1 Cisarua): refleksi 4C, analisis artefak, dan kaitan praktis dari enam
mata kuliah PPG Prajabatan Bimbingan dan Konseling.

Satu halaman statis. Tanpa build step, tanpa framework, tanpa dependensi — buka
`index.html` langsung dari berkas dan halaman tampil utuh.

```
index.html   seluruh isi situs
style.css    token warna, tata letak, animasi
script.js    satu IntersectionObserver: memunculkan isi, memekarkan kelopak, menandai nav
assets/      foto profil
```

## Enam kelopak, enam mata kuliah

Setiap mata kuliah punya satu rona sendiri, dan rona itu dipakai konsisten pada seluruh
bagiannya. Di navigasi ada satu bunga sakura berkelopak enam: **tiap kelopak mewakili satu
mata kuliah** dan mekar ketika bagiannya terbaca. Selesai membaca, bunganya utuh.

| Mata kuliah | Rona |
|---|---|
| Filosofi Pendidikan dan Pendidikan Nilai | blossom |
| Asesmen dan Layanan BK | sky |
| PPL Terbimbing | lavender |
| Pola Pikir Bertumbuh | mint |
| Design Thinking | peach |
| Praktikum Konseling Individu | berry |

Warna teks tiap rona (`--ink`) sudah dihitung agar memenuhi WCAG AA (≥4.5:1) di atas
kartu putih maupun di atas rona mudanya sendiri. **Bila salah satu nilai warna diubah,
hitung ulang rasio kontrasnya** — pastel hanya untuk latar dan hiasan, tidak pernah untuk
teks.

## Menerbitkan ke GitHub Pages

Repo ini melayani `index.html` dari akar repo.

```bash
git add -A
git commit -m "..."
git push
```

Settings → Pages → Source: `main`, folder `/ (root)`. Pages menyebar ulang sekitar satu
menit; periksa lewat jendela incognito karena Pages menyimpan cache cukup agresif.

## Catatan privasi

Repo ini sengaja hanya berisi berkas yang memang layak publik. Materi kuliah
(`Materi\`) dan gambar artefak (`Bukti Artefak\`) **tidak pernah masuk ke sini** — di
dalamnya ada foto peserta didik yang dapat dikenali dan daftar nama lengkap kelas XI-J
SMAN 1 Cisarua. Bukti artefak dibagikan lewat tautan folder Google Drive yang aksesnya
dibatasi, bukan diunggah ke web.
