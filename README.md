# UMBY Companion — Releases

APK **UMBY Companion** untuk distribusi. Repositori ini hanya berisi distribusi
APK dan manifest pembaruan; source code tersimpan di repositori privat.
Aplikasi ini proyek pribadi dan tidak berafiliasi dengan universitas.

## Unduh

- Rilis terbaru: https://github.com/Anggahrm/umby-companion-releases/releases/latest
- Manifest pembaruan: https://raw.githubusercontent.com/Anggahrm/umby-companion-releases/refs/heads/main/version.json

## Versi 1.0.5

- Package: `dev.zumy.umbycompanion`
- Minimal Android 8.0 (API 26)
- Ukuran: 24.343.813 byte (23,2 MiB)
- SHA-256:
  `700479E6DCC889FB3FF28308E3ED7066F7479895859A2AB7763613D8C7EB87AF`

### Perubahan

- Memperbaiki crash saat memindai QR absensi. Penyebabnya tugas lanjutan ML Kit ditolak setelah penutupan layar pemindai.
- Pemindai memakai kamera depan bila kamera belakang tidak tersedia.
- Kalau kamera gagal dibuka, muncul pesan dan tombol **Coba lagi**.

## Cara pasang

1. Unduh APK dari halaman rilis.
2. Izinkan pemasangan dari sumber tidak dikenal untuk browser/File Manager.
3. Pasang APK. Jika sebelumnya memasang build debug, uninstall dulu karena
   signature-nya berbeda.
4. Untuk update berikutnya, buka aplikasi lalu gunakan tombol pembaruan yang
   muncul; aplikasi akan mengunduh dan membuka pemasang APK.

APK ditandatangani dengan kunci rilis tetap. Jangan memasang APK dari sumber
yang tidak dikenal selain halaman rilis ini.
