# SENDIKO AI AGENT v1.0 — Prototipe Android

## Perangkat sasaran
Samsung Galaxy A32, Android 11 (minSdk 26).

## Status jujur prototipe
Ini adalah kerangka proyek Android, **belum APK siap instal** dan belum menjadi agent AI yang bisa mengendalikan aplikasi secara otomatis.

Yang sudah disiapkan:
- Kerangka aplikasi Android native.
- Tombol memilih video pembelajaran dari penyimpanan.
- Jalan pintas ke pengaturan Accessibility Android.
- Kerangka layanan Accessibility (pasif; belum melakukan klik/ketik).
- Dasar mode persetujuan tindakan penting.

Belum tersedia:
- Analisis video dengan model AI.
- Pencatatan sentuhan/gesture saat rekaman.
- Mesin perencana tugas dan eksekusi otomatis.
- Perekaman layar di dalam aplikasi.
- Backend/cloud worker.
- Build APK yang telah diuji di perangkat.

## Cara membuka proyek
Proyek ini perlu dibuka dan dibangun dengan Android Studio pada komputer, atau layanan build Android yang kompatibel. ZIP ini bukan file APK.

## Tahap pengembangan berikutnya
1. Tambahkan analisis video dan ekstraksi langkah.
2. Tambahkan penyimpanan keterampilan.
3. Implementasikan eksekusi Accessibility berdasarkan rencana yang disetujui.
4. Tambahkan konfirmasi sebelum tindakan sensitif dan tombol STOP.
5. Tambahkan backend AI/cloud dan autentikasi.
6. Uji pada perangkat Android 11.

## Privasi dan keamanan
Accessibility dapat melihat dan berinteraksi dengan antarmuka aplikasi. Jangan aktifkan layanan untuk penggunaan nyata sebelum kebijakan privasi, batas akses, indikator aktif, dan konfirmasi tindakan selesai diterapkan. Jangan merekam atau mengirim kata sandi, OTP, data pembayaran, atau informasi pribadi.
