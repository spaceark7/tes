# Tutorial Membuat Repository dan Mengunggah Code ke GitHub

ikuti langkah - langkah berikut

- Buka GitHub di browser
- Login ke akun GitHub
- Klik tanda (+) di pojok kanan atas
![Logo](/assets/a.png)

- Klik New Repository

- Isi nama repository, deskripsi, dan pilih public atau private
![Logo](/assets/b.png)
- Klik Create Repository
- Selesai

## Mengunggah Code ke GitHub
- Buka Project yang akan diunggah ke GitHub di Visual Studio Code atau IDE lainnya.
- Buka terminal
- Ketik perintah berikut
```bash
git init
git add .
git commit -m "First Commit"
git branch -M main
git remote add origin {nama_repository_github}
git push -u origin main
```
Contoh :
![Logo](/assets/c.png)

- Selesai

## Melakukan Commit dan Push Code ke GitHub
- Setelah melakukan perubahan pada code, buka terminal
- Ketik perintah berikut
```bash
git add .
git commit -m "pesan_commit"
git push -u origin main
```

- Selesai

## Mengambil Code Terbaru dari GitHub
- Buka terminal
- Ketik perintah berikut
```bash
git pull origin main
```
- Selesai

## Melakukan Clone Repository
- Buka repository di GitHub
- Klik Code
![Logo](/assets/e.png)
- Copy link repository
- Buka Visual Studio Code
- Buka terminal
- Ketik perintah berikut
```bash
git clone {link_repository}
```
Contoh :
![Logo](/assets/f.png)

- Selesai



