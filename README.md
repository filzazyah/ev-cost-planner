# EV Cost Planner

Kalkulator biaya ideal pemeliharaan dan pemakaian mobil listrik di Indonesia.

## Fitur
- Estimasi biaya charging di rumah dan stasiun pengisian publik.
- Perhitungan servis, ban, komponen kecil, pajak, asuransi, parkir/tol, dan dana cadangan.
- Cadangan baterai opsional dan buffer anggaran.
- Ringkasan bulanan, tahunan, serta biaya per kilometer.
- Unduh rincian CSV dan cetak/simpan sebagai PDF.
- Tampilan responsif untuk ponsel dan desktop; perhitungan dilakukan di browser.

## Jalankan
Buka `index.html` langsung di browser, atau jalankan server lokal:

```bash
python3 -m http.server 8000
```

Kemudian buka http://localhost:8000.

## Aktifkan GitHub Pages
1. Buka **Settings → Pages** pada repository.
2. Pada **Build and deployment**, pilih **Deploy from a branch**.
3. Pilih branch **main** dan folder **/(root)**, lalu tekan **Save**.
4. Tunggu proses publikasi selesai.

Website: https://filzazyah.github.io/ev-cost-planner/

## Catatan
Nilai awal hanya contoh dan perlu disesuaikan dengan kendaraan, tarif listrik, wilayah, serta biaya aktual. Cadangan baterai adalah pilihan perencanaan, bukan prediksi penggantian baterai. Perhitungan tidak mencakup harga pembelian, cicilan, depresiasi, atau biaya modal.
