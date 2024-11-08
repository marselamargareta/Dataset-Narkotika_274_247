# Dataset Putusan Narkotika di Pengadilan Negeri Yogyakarta (2022-2024)

Dataset ini berisi informasi putusan pengadilan terkait kasus narkotika di Pengadilan Negeri Yogyakarta dari tahun 2022 hingga 2024. Data ini mencakup rincian seperti nomor putusan, lembaga peradilan, barang bukti, dan amar putusan. Dataset ini dapat digunakan untuk analisis hukum, studi kasus narkotika, serta analisis statistik mengenai putusan pengadilan di wilayah Yogyakarta.

## Struktur Dataset

| No  | Nomor Putusan               | Lembaga Peradilan              | Barang Bukti                                                                                                                        | Amar Putusan                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
|-----|------------------------------|--------------------------------|-------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1   | 326/Pid.Sus/2022/PN Yyk      | Pengadilan Negeri Yogyakarta   | - 1 (satu) paket sabu ± 0,29 gr<br>- 1 buah tas hitam<br>- 1 buah HP Samsung warna gold<br>- 1 unit motor Honda Blade AB6942-SH    | 1. Terdakwa AGUNG EKA PRATAMA terbukti bersalah menyerahkan psikotropika; pidana penjara 2 tahun 4 bulan, denda Rp20.000.000 atau kurungan 4 bulan<br>2. Masa penahanan dikurangkan dari pidana<br>3. Barang bukti:<br>   - 140 butir Alprazolam 1 Mg, 50 butir Alprazolam 1 Mg, 200 butir Alprazolam 1 Mg dirampas untuk dimusnahkan<br>   - 1 HP Realme hitam dirampas untuk negara<br>4. Terdakwa membayar biaya perkara Rp2.000 |
| 2   | 335/Pid.Sus/2023/PN Yyk      | Pengadilan Negeri Yogyakarta   | - 1 bungkus kertas putih isi ganja 3,86 gr<br>- 1 buah paper<br>Dirampas untuk dimusnahkan                                        | 1. Terdakwa Ramadhan Ulya terbukti bersalah menyalahgunakan Narkotika golongan I; pidana penjara 1 tahun<br>2. Barang bukti:<br>   - 1 bungkus ganja 3,86 gr<br>   - 1 buah paper; dirampas untuk dimusnahkan<br>3. Biaya perkara Rp2.000 |
| 3   | 238/Pid.Sus/2024/PN Yyk      | Pengadilan Negeri Yogyakarta   | - 1 paket sabu ± 0,29 gr<br>- 1 buah tas hitam; dirampas untuk dimusnahkan<br>- 1 HP Samsung gold; dirampas untuk negara<br>- 1 motor Honda Blade AB6942-SH; dikembalikan kepada terdakwa | 1. Terdakwa RR. SRI MAULATI SOLICHAH terbukti bersalah memiliki narkotika golongan I; pidana penjara 4 tahun, denda Rp800.000.000 atau 2 bulan kurungan<br>2. Masa penahanan dikurangkan dari pidana<br>3. Terdakwa tetap ditahan<br>4. Barang bukti:<br>   - 1 paket sabu, 1 tas hitam; dimusnahkan<br>   - 1 HP Samsung; disita negara<br>   - 1 motor Honda Blade; dikembalikan kepada terdakwa<br>5. Biaya perkara Rp2.000 |

## Penjelasan Kolom

- **No**: Nomor urut putusan dalam dataset.
- **Nomor Putusan**: Nomor putusan resmi dari Pengadilan Negeri Yogyakarta.
- **Lembaga Peradilan**: Lembaga yang menangani kasus ini, dalam hal ini adalah Pengadilan Negeri Yogyakarta.
- **Barang Bukti**: Daftar barang bukti yang disita dalam proses persidangan, termasuk narkotika, alat komunikasi, dan kendaraan yang terkait dengan kasus.
- **Amar Putusan**: Rincian keputusan pengadilan, termasuk hukuman yang dijatuhkan, barang bukti yang disita atau dimusnahkan, serta biaya perkara yang dikenakan.

## Tujuan dan Penggunaan Dataset

Dataset ini dapat digunakan untuk:
1. **Analisis Tren Kasus Narkotika**: Meninjau pola putusan dan jenis barang bukti yang disita dalam kurun waktu 2022 hingga 2024.
2. **Penelitian Hukum**: Mengidentifikasi bagaimana pengadilan memproses kasus narkotika, termasuk tren hukuman, lama penahanan, dan denda.
3. **Pengembangan Sistem Temu Kembali Informasi (TKI)**: Dataset ini dapat diproses dan diindeks untuk proyek pengembangan sistem TKI atau aplikasi lainnya.

## Catatan Preprocessing

Beberapa tahapan preprocessing yang dilakukan dalam pengelolaan data ini meliputi:
1. **Penghapusan Karakter Spesial**: Karakter khusus dalam barang bukti atau amar putusan dihilangkan agar lebih mudah diproses.
2. **Normalisasi Teks**: Semua teks dinormalisasi ke format standar (misalnya, semua teks diubah ke huruf kecil) untuk keperluan analisis lebih lanjut.
3. **Tokenisasi dan Stemming**: Dokumen dibagi ke dalam bentuk kata dasar agar lebih mudah dipahami oleh model pencarian atau analisis teks.
4. **Penyimpanan dalam Struktur Tabel**: Setelah preprocessing, data disimpan dalam struktur tabel yang mudah dibaca dan diakses.

## Lisensi

Dataset ini dilisensikan untuk penggunaan penelitian dan edukasi. Harap menghargai privasi dan ketentuan hukum saat menggunakan data ini.

---

*Dokumentasi ini dibuat untuk memberikan informasi yang lengkap dan terstruktur bagi pengguna dataset putusan pengadilan narkotika di Pengadilan Negeri Yogyakarta tahun 2022-2024.*
