# LASGUM — iPhone/PWA

Versi ini sudah disiapkan agar LASGUM dapat dipasang sebagai aplikasi web (PWA) di iPhone/iPad.

## Cara memasang di iPhone
1. Upload folder ini ke hosting HTTPS (misalnya GitHub Pages).
2. Buka alamat LASGUM tersebut menggunakan Safari di iPhone.
3. Tekan tombol Share/Bagikan.
4. Pilih **Add to Home Screen / Tambahkan ke Layar Utama**.
5. Tekan **Add/Tambahkan**.

## Catatan penting
- File HTML asli memakai Tailwind, SheetJS, dan Supabase dari CDN, sehingga koneksi internet tetap diperlukan untuk bagian yang membutuhkan library/CDN dan database Supabase.
- Service Worker membantu menyimpan shell aplikasi setelah pertama kali dibuka, tetapi tidak membuat Supabase menjadi offline.
- Data database tetap mengikuti konfigurasi Supabase yang ada di aplikasi.
