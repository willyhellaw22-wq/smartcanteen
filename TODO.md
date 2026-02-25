# TODO - Fitur Penjual: Pesanan Masuk & Stok

## Plan:

### 1. Tambahkan sistem manajemen stok
- [x] Tambahkan default stock untuk setiap item menu
- [x] Simpan data stok di localStorage

### 2. Ubah tampilan seller menjadi "Daftar Pesanan Masuk"
- [x] Saat login sebagai seller, tampilkan section pesanan masuk
- [x] Tampilkan detail pesanan: nama siswa, kelas, item, jumlah, total

### 3. Tambahkan fitur pengelolaan stok untuk seller
- [x] Tampilkan input stock di setiap item menu saat login sebagai seller
- [x] Function untuk update stock

### 4. Validasi stok saat pemesanan
- [x] Cek ketersediaan stock sebelum add to cart
- [x] Tampilkan notifikasi jika stock habis atau tidak mencukupi
- [x] Update tampilan button jika stock = 0

### 5. Simpan pesanan untuk dilihat oleh seller
- [x] Simpan pesanan ke array orders
- [x] Tampilkan pesanan di section "Pesanan Masuk" seller
