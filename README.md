# Aplikasi Wali Kelas SMP (Prototipe)

UPT SMP Negeri 40 Kota Makassar. Situs statis (HTML + CSS), tanpa build.

## Halaman
index (Beranda), absensi, daftar (daftar siswa), lengkap (data lengkap siswa), siswa (detail), kelas (pilih kelas), jadwal, pengaturan.

## Deploy ke GitHub
```
git init
git add .
git commit -m "Prototipe aplikasi wali kelas"
git branch -M main
git remote add origin https://github.com/USERNAME/wali-kelas.git
git push -u origin main
```

## Deploy ke Vercel
1. Buka vercel.com, klik Add New > Project, lalu import repo GitHub tadi.
2. Framework Preset: Other. Biarkan Build Command dan Output Directory kosong.
3. Klik Deploy.

Atau lewat terminal: `npm i -g vercel` lalu `vercel --prod` di folder ini.

## Catatan
- Semua data siswa hanya contoh.
- Repo public membuat foto di assets/foto-wali.jpg bisa dilihat siapa saja. Pakai repo private atau ganti fotonya bila perlu.
