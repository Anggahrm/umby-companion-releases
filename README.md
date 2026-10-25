# UMBY Companion — Releases

APK **UMBY Companion** untuk distribusi. Repositori ini hanya berisi distribusi
APK dan manifest pembaruan; source code tersimpan di repositori privat.
Aplikasi ini proyek pribadi dan tidak berafiliasi dengan universitas.

## Unduh

- Rilis terbaru: https://github.com/Anggahrm/umby-companion-releases/releases/latest
- Manifest pembaruan: https://raw.githubusercontent.com/Anggahrm/umby-companion-releases/refs/heads/main/version.json

## Versi 1.0.4

- Package: `dev.zumy.umbycompanion`
- Minimal Android 8.0 (API 26)
- Ukuran: 24.343.813 byte (23,2 MiB)
- SHA-256:
  `C11F4C05590F6BF2C733E9DC52A90004D5E0B2D3B5426748509CB2EE27252930`

### Perubahan

- Checkbox login sekarang bernama **Simpan kredensial**.
- Kalau dicentang, NIM dan kata sandi disimpan terenkripsi, lalu aplikasi mencoba login otomatis saat dibuka kembali.
- Login otomatis tetap berhenti di verifikasi Two Step/TOTP bila SSO kampus memintanya.
- Kredensial tersimpan dihapus saat checkbox dilepas, logout, kembali ke halaman login, atau saat login otomatis ditolak.
- Istilah **NIS** diganti menjadi **NIM** di seluruh aplikasi.

## Cara pasang

1. Unduh APK dari halaman rilis.
2. Izinkan pemasangan dari sumber tidak dikenal untuk browser/File Manager.
3. Pasang APK. Jika sebelumnya memasang build debug, uninstall dulu karena
   signature-nya berbeda.
4. Untuk update berikutnya, buka aplikasi lalu gunakan tombol pembaruan yang
   muncul; aplikasi akan mengunduh dan membuka pemasang APK.

APK ditandatangani dengan kunci rilis tetap. Jangan memasang APK dari sumber
yang tidak dikenal selain halaman rilis ini.
