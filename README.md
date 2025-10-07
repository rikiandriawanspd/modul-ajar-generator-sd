# Modul Ajar Generator

Aplikasi web untuk membuat dan men-generate modul ajar berbasis Kurikulum Merdeka secara otomatis. Hasil bisa diunduh dalam format PDF & siap cetak.

---

## Instalasi & Menjalankan Lokal

1. Clone repo ini:
   ```bash
   git clone https://github.com/username/modul-ajar-generator.git
   cd modul-ajar-generator
   ```

2. Install dependencies:
   ```bash
   npm install
   # atau
   yarn install
   ```

3. Jalankan aplikasi lokal:
   ```bash
   npm run dev
   # atau
   yarn dev
   ```

4. Buka browser dan akses:
   ```
   http://localhost:3000
   ```

---

## Deploy ke Vercel

1. Login ke [Vercel](https://vercel.com/) dengan akun GitHub.
2. Klik "New Project" dan pilih repo ini.
3. Ikuti wizard (Next.js akan otomatis terdeteksi).
4. Klik "Deploy".
5. Setelah selesai, aplikasi online dan dapat diakses melalui URL yang diberikan Vercel.

## Deploy ke Netlify

1. Login ke [Netlify](https://netlify.com/) dengan akun GitHub.
2. Klik "Add new site" > "Import an existing project".
3. Pilih repo ini.
4. Build command: `npm run build`
5. Publish directory: `.next`
6. Klik "Deploy Site".

---

## Contoh Tampilan

![Screenshot](public/screenshot.png)

---

## Lisensi

MIT License
