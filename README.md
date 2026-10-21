# UMBY Companion — Releases

APK **UMBY Companion** untuk distribusi. Repositori ini hanya berisi distribusi
APK dan manifest pembaruan; source code tersimpan di repositori privat.
Aplikasi ini proyek pribadi dan tidak berafiliasi dengan universitas.

## Unduh

- Rilis terbaru: https://github.com/Anggahrm/umby-companion-releases/releases/latest
- Manifest pembaruan: https://raw.githubusercontent.com/Anggahrm/umby-companion-releases/refs/heads/main/version.json

## Versi 1.0.2

- Package: `dev.zumy.umbycompanion`
- Minimal Android 8.0 (API 26)
- Ukuran: 24.343.813 byte (23,2 MiB)
- SHA-256:
  `B7C973BD545EE99D473521E6BE0379E80CCFA25BB08DBF9338C8218F257E3FA3`

### Perubahan

- Kolom kode presensi menerima huruf dan angka, bukan hanya nomor.
- Keyboard alfanumerik otomatis kapital; kode dinormalisasi ke huruf besar.
- Validasi kode menjadi 6 karakter (contoh: `UJSEUS`).
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
