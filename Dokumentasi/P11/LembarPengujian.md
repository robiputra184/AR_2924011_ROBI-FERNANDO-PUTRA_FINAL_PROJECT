# Lembar Catatan Pengujian - P11
Nama: Mhd. Abdi Al-Zikra | NIM: 2924037

| Uji | Kondisi | Masalah yang terlihat | Perbaikan yang dilakukan |
|-----|---------|----------------------|--------------------------|
| 1 | Model roket .glb diimport | Preview tidak muncul (ikon putih) | Ganti format ke .obj |
| 2 | Roket di-scan, tidak muncul | Kemungkinan scale 0.1 terlalu kecil | Ubah scale ke 1 |
| 3 | Roket tetap tidak muncul | Pivot/material belum terkonfirmasi | Tes kubus (TestCube) |
| 4 | TestCube muncul di HP | Tracking ARCore valid | Ganti model ke mobil .fbx |
| 5 | Mobil muncul, scale 0.05 | Proporsional | Kunci konfigurasi |
| 6 | Mobil "lari" saat kamera cepat | Tracking loss (normal) | Atur jarak & gerakan lambat |

## Refleksi Singkat
1. Masalah paling sulit: Model .glb tidak terbaca Unity tanpa plugin.
2. Perbaikan paling berpengaruh: Mengganti format file ke .obj/.fbx.
3. Kondisi tracking paling stabil: Marker kertas cetak, jarak 20-40 cm, gerakan lambat.
4. Hal yang perlu diperbaiki sebelum P12: Stabilitas tracking saat kamera miring.