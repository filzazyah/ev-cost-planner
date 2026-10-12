# EV Cost Planner

Kalkulator biaya pemakaian dan pemeliharaan mobil listrik di Indonesia. Website statis; semua perhitungan berlangsung di browser.

## Fitur
- Preset BYD ATTO 1 Dynamic dan Premium berdasarkan brosur resmi BYD Indonesia.
- Campuran charging rumah/SPKLU yang bisa diatur, termasuk tarif dan rugi pengisian.
- Estimasi servis, ban, komponen kecil, pajak, asuransi, parkir/tol, dan dana cadangan.
- Ringkasan anggaran bulanan, tahunan, serta biaya per kilometer.
- Ekspor CSV dan cetak/simpan sebagai PDF.
- Tampilan responsif untuk ponsel dan desktop.

## Data kendaraan dan biaya
- BYD ATTO 1 Dynamic: baterai 30,08 kWh, jarak WLTP 230 km, AC maksimum 6,6 kW, DC maksimum 30 kW.
- BYD ATTO 1 Premium: baterai 38,88 kWh, jarak WLTP 300 km, AC maksimum 6,6 kW, DC maksimum 40 kW.
- Kedua varian: ukuran ban 185/55 R16.
- Interval servis umum BYD: setiap 1 tahun atau 20.000 km; servis pertama 3 bulan/5.000 km hanya berlaku pada model tertentu. Ikuti buku manual kendaraan Anda.
- Angka Rp1.000.000 per tahun sebagai biaya servis adalah estimasi awal yang diberitakan media berdasarkan data internal BYD, bukan daftar tarif resmi yang dijamin. Konfirmasikan biaya dan jadwal dengan dealer resmi.
- Konsumsi kWh/100 km dalam preset adalah nilai awal perkiraan berdasarkan kapasitas baterai dan jarak WLTP, bukan konsumsi aktual yang dijamin. Ubah berdasarkan pemakaian Anda.
- Pajak, asuransi, ban, perbaikan, dan cadangan baterai perlu disesuaikan dengan kondisi pemilik. Cadangan baterai bukan prediksi penggantian baterai.

## Sumber
- Brosur resmi BYD ATTO 1: https://www.byd.com/content/dam/byd-site/id/product/atto1/ATTO1-BROCHURE-1-FINAL.pdf
- Servis dan pemeliharaan BYD Indonesia: https://www.byd.com/id/aftersales/service-pemeliharaan
- Garansi BYD Indonesia: https://www.byd.com/id/aftersales/warranty
- Laporan media mengenai estimasi servis: https://oto.detik.com/mobil-listrik/d-8143330/murah-meriah-biaya-perawatan-byd-atto-1-setahun-cuma-habis-segini/

## Jalankan lokal
Buka `index.html` langsung di browser atau jalankan:

```bash
python3 -m http.server 8000
```

Lalu buka http://localhost:8000.

## GitHub Pages
Di **Settings → Pages**, pilih **Deploy from a branch**, branch `main`, folder `/(root)`, lalu simpan.

Website: https://filzazyah.github.io/ev-cost-planner/

## Batasan
Estimasi bukan penawaran resmi dari BYD/dealer dan tidak mencakup harga pembelian, cicilan, depresiasi, atau biaya modal. Periksa kembali angka serta syarat garansi langsung pada dokumen BYD yang berlaku untuk VIN/kendaraan Anda.
