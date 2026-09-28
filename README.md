# KasirKu — Cafe POS Web

Aplikasi POS web untuk operasional cafe dengan UI modern.

## Fitur
- POS kasir dengan pencarian, kategori, keranjang, pajak, diskon dan pembayaran Tunai/QRIS/Transfer/Debit
- Kelola produk & jasa, HPP, markup, harga jual, SKU/barcode, BOM dan stok
- Voucher
- Riwayat transaksi, pencarian, void dan export CSV
- Laporan penjualan, HPP, laba kotor, margin, transaksi dan stok menipis
- Preview & cetak struk
- Upload logo toko untuk sidebar dan struk
- Backup & restore data
- Responsive desktop/mobile
- Customer QR ordering: `customer.html`
- Kitchen/Bar Display: `kitchen.html`

## Alur
Customer QR / Kasir -> Order -> Pembayaran -> Kitchen/Bar -> Stok -> Struk -> Laporan

## Catatan
Versi ini masih menggunakan localStorage browser. Agar kasir, customer QR, dan kitchen dapat tersinkron real-time antar perangkat, tahap berikutnya adalah backend/database bersama.
