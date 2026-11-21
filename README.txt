BUMISARI 3D MAP — PWA STARTER (Android)
=======================================

File:
- index.html             aplikasi peta 3D
- manifest.webmanifest   identitas PWA
- sw.js                  cache shell untuk pembukaan ulang
- icon.svg, icon-192.png, icon-512.png  ikon aplikasi

CARA TERMUDAH DARI HP ANDROID
1. Unduh ZIP ini dan ekstrak menggunakan aplikasi File / pengelola ZIP.
2. Buka https://github.com lalu masuk atau buat akun.
3. Buat repository baru bernama bumisari-3d-map, pilih Public, lalu Create repository.
4. Pada repository, pilih Add file > Upload files.
5. Unggah SEMUA file di dalam folder hasil ekstrak (index.html, manifest.webmanifest, sw.js, icon.svg) ke bagian utama/root repository. Jangan unggah folder ZIP-nya.
6. Tekan Commit changes.
7. Buka Settings > Pages.
8. Pada Build and deployment pilih Deploy from a branch; Branch: main; Folder: /(root); Save.
9. Tunggu proses selesai. Alamat aplikasi biasanya:
   https://USERNAME.github.io/bumisari-3d-map/
10. Buka alamat itu di Chrome Android. Pilih menu ⋮ > Tambahkan ke layar utama / Install app.

CITRA 3D GOOGLE
- Buat project di Google Cloud Console.
- Aktifkan billing dan Map Tiles API.
- Buat API key dan batasi key pada Map Tiles API.
- Setelah alamat GitHub Pages diketahui, tambahkan pembatasan website (HTTP referrer) untuk:
  https://USERNAME.github.io/*
- Masukkan API key di dalam aplikasi untuk mengaktifkan Google Photorealistic 3D Tiles.
- Jangan bagikan API key. Jangan simpan key dalam repository.
- Pemakaian Google Maps Platform dapat menimbulkan biaya sesuai ketentuan dan kuota akun. Periksa harga dan batas penggunaan sebelum dipakai.

CATATAN
- Peta dasar OpenStreetMap dapat tampil tanpa Google API key.
- Citra Google 3D memerlukan internet dan cakupan 3D di lokasi. Ketersediaan model fotorealistik Desa Bumisari belum dipastikan.
- Mode berjalan dalam paket ini adalah prototipe navigasi kamera dengan tombol arah; belum ada collision, gravitasi, atau model avatar.
- Versi ini belum memuat batas desa resmi atau bangunan hasil rekonstruksi.
- Untuk aplikasi publik, perhatikan privasi data lokasi dan foto warga.
