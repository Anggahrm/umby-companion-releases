# UMBY Companion — Releases

APK **UMBY Companion** untuk distribusi. Repositori ini hanya berisi distribusi
APK dan manifest pembaruan; source code tersimpan di repositori privat.
Aplikasi ini proyek pribadi dan tidak berafiliasi dengan universitas.

## Unduh

- Rilis terbaru: https://github.com/Anggahrm/umby-companion-releases/releases/latest
- Manifest pembaruan: https://raw.githubusercontent.com/Anggahrm/umby-companion-releases/refs/heads/main/version.json

## Versi 1.0.3

- Package: `dev.zumy.umbycompanion`
- Minimal Android 8.0 (API 26)
- Ukuran: 24.343.813 byte (23,2 MiB)
- SHA-256:
  `9835E29FAD352DB66170279A5DAC55DF2567CECE05BB6B7B8F135281938CBBD7`

### Perubahan

- Perbaikan absensi: token CSRF SIA diambil dari cookie dan script dashboard.
- Token di-refresh otomatis sekali saat SIA membalas HTTP 419.
- Respons `success:false` dari SIA ditampilkan sebagai gagal, bukan "Absensi tercatat".
- Kolom kode presensi menerima huruf dan angka, keyboard alfanumerik, validasi 6 karakter (contoh: `UJSEUS`).
- Player YouTube langsung di dalam aplikasi.
- Halaman detail native untuk tautan e-learning (`mod_url`).
- Pembaruan APK bisa diunduh dan dipasang dari dalam aplikasi.

## Cara pasang

1. Unduh APK dari halaman rilis.
2. Izinkan pemasangan dari sumber tidak dikenal untuk browser/File Manager.
3. Pasang APK. Jika sebelumnya memasang build debug, uninstall dulu karena
   signature-nya berbeda.
4. Untuk update berikutnya, buka aplikasi lalu gunakan tombol pembaruan yang
   muncul; aplikasi akan mengunduh dan membuka pemasang APK.

APK ditandatangani dengan kunci rilis tetap. Jangan memasang APK dari sumber
yang tidak dikenal selain halaman rilis ini.
