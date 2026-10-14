# AI Screen Assistant (prototype)

Proyek Android awal untuk aplikasi asisten dengan tombol overlay. GitHub Actions akan membangun APK debug ketika workflow dijalankan atau ada push ke `main`.

## Build APK
1. Buat repository GitHub baru, unggah seluruh isi folder proyek ini.
2. Buka tab **Actions** dan jalankan **Build Android APK** (atau tunggu build setelah push).
3. Buka hasil workflow yang berhasil, lalu unduh artifact `AI-Screen-Assistant-APK`.
4. Ekstrak ZIP artifact untuk mendapatkan `app-debug.apk`.

## Status fitur
- Menu aplikasi dan pengaturan endpoint/model/API key: ada.
- Tombol melayang: prototipe.
- OCR dan koneksi AI: belum terhubung dalam prototipe ini.
- Pengambilan layar dan izin MediaProjection: belum selesai; harus diselesaikan dan diuji sebelum dipakai untuk scan soal nyata.

## Keamanan
Jangan gunakan API key penting dalam APK yang dibagikan. API key yang disimpan di perangkat dapat diekstrak. Untuk distribusi, gunakan backend milik sendiri.
