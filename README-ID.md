# SIPAS Web
Sistem Informasi Pramuka Ambalan Soeharto
Gudep 05.057–05.058 · Pangkalan SMA Negeri 2 Long Ikis

## Cara mencoba
Buka `index.html` melalui browser. Untuk publikasi sederhana, unggah `index.html` ke root repositori GitHub dan aktifkan Settings → Pages → Deploy from a branch → `main` → `/(root)`.

## Fitur
- Dashboard ringkas
- Data anggota, surat masuk/keluar, kegiatan, notulen, inventaris, arsip
- Tambah, edit, dan hapus data
- Ekspor/impor cadangan JSON
- Pengaturan identitas dan tahun bakti

## Catatan penting
Versi ini menyimpan data di `localStorage` browser/perangkat yang sedang digunakan. Belum ada sinkronisasi online antarperangkat. Untuk penggunaan bersama, integrasikan Firebase atau layanan backend dengan autentikasi dan aturan akses yang aman. Jangan memasukkan data pribadi sensitif sebelum sinkronisasi dan keamanan dikonfigurasi.
