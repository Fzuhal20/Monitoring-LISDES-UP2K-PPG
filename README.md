# Dashboard Monitoring Pekerjaan ABT TA 2026
**PLN UP2K Papua Pegunungan**

Dashboard satu halaman (`index.html`) untuk memantau progres fisik 32 lokasi, kebutuhan MDU, laporan harian, ekspor WhatsApp (teks & PNG), peta/tagging KMZ, dan dokumentasi.

## Isi repo
- `index.html` — aplikasi lengkap dalam satu file (aset, logo, dan latar sudah tertanam).
- `README.md` — panduan ini.

## Sumber data (baca-saja, CSV publik Google Sheets)
| Menu | Sheet |
| --- | --- |
| Ringkasan, Progres Fisik, Laporan Harian, Peta, Format Gambar | `gid=813647239` (Progress Pekerjaan ABT 2026) |
| Format Chat WhatsApp (rincian item) | `gid=536863649` |
| Monitoring MDU | sheet Keb MDU (`pub?output=csv`) |

Data dimuat ulang setiap halaman dibuka atau tombol **Muat Ulang Data** ditekan. Jika koneksi gagal, dashboard memakai cuplikan data terakhir yang tertanam.

## Publikasi lewat GitHub Pages
1. Buat repository baru di GitHub (mis. `dashboard-abt-2026`).
2. Unggah `index.html` dan `README.md` ke branch `main` (Add file → Upload files).
3. Buka **Settings → Pages**, pilih *Deploy from a branch*, branch `main`, folder `/ (root)`, lalu **Save**.
4. Setelah 1–2 menit dashboard dapat diakses di `https://<username>.github.io/dashboard-abt-2026/`.

## Catatan
- Spreadsheet harus tetap **dipublikasikan ke web** agar data terbaca.
- Hasil tagging KMZ dan foto unggahan hanya tersimpan di browser pengguna (tidak menulis ke spreadsheet).
- Link KMZ dari Google Drive umumnya tidak dapat diunduh langsung oleh browser — unduh lalu unggah manual di menu Peta & Tagging.
