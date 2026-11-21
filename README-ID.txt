SVG2AM STUDIO — PROYEK ANDROID

Isi:
- Aplikasi Android WebView
- Pilih SVG dari penyimpanan
- Preview SVG
- Deteksi objek/layer dasar
- Ekspor ulang SVG dan XML terstruktur

PENTING:
File XML hasil ekspor adalah XML konversi SVG buatan aplikasi, BUKAN format proyek Alight Motion resmi yang telah diverifikasi. Impor langsung ke Alight Motion tidak dijamin. Dukungan filter, mask, gradient, font, dan fitur SVG kompleks bisa berbeda.

CARA MEMBUAT APK DENGAN HP ANDROID:
1. Buat akun GitHub dan login.
2. Buat repository baru bernama SVG2AM-Studio.
3. Upload semua isi folder proyek ZIP ini ke repository (termasuk folder .github).
4. Buka tab Actions pada repository.
5. Pilih workflow "Build Android APK", lalu tekan Run workflow.
6. Setelah selesai, buka hasil run dan unduh Artifacts bernama SVG2AM-Studio-debug-apk.
7. Ekstrak ZIP artifact untuk mendapatkan app-debug.apk.

APK ini masih versi debug untuk uji coba. Untuk rilis publik diperlukan signing release.

Untuk mengembangkan lokal, gunakan Android Studio + JDK 17 + Android SDK 35, lalu jalankan:
gradle assembleDebug
