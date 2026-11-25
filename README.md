# Kontrol Anggaran Bidang UPT

Aplikasi PWA untuk kontrol anggaran, breakdown bulanan, rencana SPJ, realisasi, dan rekap tahunan.

## Berkas
- `index.html`: aplikasi utama (v42.7.0)
- `manifest.webmanifest`: identitas PWA
- `sw.js`: cache aplikasi dan pembaruan versi
- `icons/`: ikon aplikasi dan ikon layar utama iOS

## GitHub Pages
Publikasikan dari branch `main`, folder `/(root)`.

## Penggunaan dan data
Data tersimpan secara lokal pada browser/perangkat. Pertukaran data antarpengguna dilakukan dengan Ekspor Database JSON dan Impor Database JSON. Impor menggantikan data untuk tahun anggaran yang sama. Buat cadangan sebelum impor.

Jangan unggah Database JSON berisi data anggaran ke repositori publik.
