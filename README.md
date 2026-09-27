# 📊 Kalkulator Pembagian Deviden & Bagi Hasil Usaha (Devident Duta)

Aplikasi web interaktif dan dinamis untuk menghitung dan mensimulasikan pembagian keuntungan bersih usaha, simpanan pemeliharaan mesin, deviden saham pokok, *sweat equity*, serta kepatuhan **Pajak Penghasilan Dividen (PPh Final)** sesuai peraturan perpajakan di Indonesia.

---

## 🌟 Skema Alokasi Laba Bersih

Total Laba Bersih Usaha (100%) dialokasikan secara bertahap:
1. **⚙️ Simpanan Pemeliharaan Mesin-Mesin (20%):** 
   - Disimpan terlebih dahulu sebagai dana cadangan dan operasional perawatan mesin (Bebas dari PPh Dividen).
2. **📈 Sisa Laba Bersih Siap Dibagikan (80%):**
   - **Bagian Pendiri / Owner (51% dari sisa laba = 40,8% dari total laba):** Alokasi dividen untuk pemilik/pendiri usaha.
   - **Bagian Anak-Anak / Tim (49% dari sisa laba = 39,2% dari total laba):** Dialokasikan khusus ke seluruh jajaran manajemen dan anggota tim (100% pool tim).

---

## 🏛️ Ketentuan Pajak Sesuai Aturan Resmi DJP

Berdasarkan **UU No. 7 Tahun 2021 (Harmonisasi Peraturan Perpajakan)** dan **PMK No. 18/PMK.03/2021**:

1. **🔴 Skema Bayar PPh Final (10,0%):**
   - Berlaku untuk Wajib Pajak Orang Pribadi Dalam Negeri jika dividen ditarik tunai/tidak diinvestasikan kembali di wilayah NKRI.
   - Bersifat Final (Pasal 4 Ayat 2 UU PPh).
   - Perusahaan memotong dan menyetorkan pajak ke Kas Negara paling lambat tanggal 10 bulan berikutnya.
2. **🟢 Skema Bebas Pajak (0% Non-Objek Pajak):**
   - Berlaku jika dividen **diinvestasikan kembali** di wilayah NKRI minimal 3 tahun berturut-turut pada instrumen yang sah (modal kerja usaha, tabungan/deposito perbankan, obligasi, dll) dan dilaporkan dalam Laporan Realisasi Investasi SPT Tahunan.

---

## 👥 Struktur Kepemilikan Saham & Sweat Equity Tim

Porsi pool tim dibagikan ke 7 anggota dengan komposisi default:
- **Direktur:** Saham 7,0% + Sweat Equity 3,0% = 10,0%
- **Manager:** Saham 7,0% + Sweat Equity 2,0% = 9,0%
- **5 Anggota Tim (RENEEO, NOREEN, VISA NAUVAL, RAMPAN, AL QAULUST TSAABIT):** Masing-masing Saham 6,0% (Total: 30,0%)
- **Total Porsi Tim:** Tepat 49,0% (100% dari alokasi pool tim).

---

## 🚀 Fitur Utama

- **Real-Time Dynamic Calculator:** Setiap perubahan laba atau perpindahan skema pajak langsung mengkalkulasi ulang seluruh porsi dividen bruto, potongan PPh, dan dividen bersih (netto).
- **Tabel & Rekonsiliasi Otomatis:** Menampilkan perbandingan nominal Bruto, PPh Final 10%, dan Netto Diterima secara transparan.
- **Ekspor Data ke CSV Sesuai Standar Pajak:** File CSV menyertakan kolom Bruto, Pajak, Netto, dan Keterangan Dasar Regulasi.
