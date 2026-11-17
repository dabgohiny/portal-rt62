# RT 62 Portal Warga — Prototype PWA

Prototype tampilan awal untuk Android dan iPhone.

Fitur contoh: beranda, data warga, iuran, INTERNET 62, surat, kas, kegiatan, sosial, pengaduan, pilihan peran demo.

## Menjalankan
Buka index.html pada browser. Untuk memasang PWA dengan service worker, hosting harus menggunakan HTTPS.

## Status dan batasan
Ini belum aplikasi produksi. Tidak ada login sungguhan, database, sinkronisasi antarperangkat, notifikasi, pembayaran, atau pengiriman formulir. Jangan masukkan data pribadi warga. Data pelanggan INTERNET 62 masih perlu diverifikasi.

## Sebelum dipakai warga
Bangun backend API dan database, autentikasi, hak akses warga/pengurus/bendahara/ketua RT, backup, audit log, persetujuan dan kebijakan privasi. Setelah itu tambahkan integrasi MikroTik/RADIUS untuk otomatisasi status internet jika perangkat dan konfigurasi mendukung.
