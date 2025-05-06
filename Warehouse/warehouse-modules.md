
![oviz erp v3](https://github.com/user-attachments/assets/6a61505a-e375-4b43-a578-8e984ec7d737)

**Warehouse**
Modul untuk bagian gudang dalam mengelola mutasi barang di internal dan eksternal perusahaan.
1. Fitur multi gudang, zona dan rak
2. Pengelolaan data barang, satuan dan standard packing
3. Goods Receipt, Supplier Return, Supplier Replacement
   - Mencatat penerimaan barang dari supplier
   - Mencatat retur barang ke supplier dan penggantian barang oleh supplier
c) Mengatur jadwal penerimaan barang
4. Delivery Order, Customer Return, Customer Replacement
   - Mencatat pengiriman barang ke customer
   - Mencatat retur barang dari customer serta penggantian barang ke customer
   - Mengatur jadwal pengiriman barang per pesanan
5. Fitur Subcontractor
   - Menerima barang dari customer (subcont.)
   - Mengirim barang ke supplier (subcont.)
6. Other Stock Move
   - Melakukan penyesuain stock (Stock Adjustment)
   - Memindahkan barang dari gudang utama ke gudang produksi (Material Transfer)
   - Putaway, memindahkan barang yang diterima dari supplier ke rak tujuan
   - Delivery Picking, pengambilan barang dari rak berdasarkan pesanan dari pelanggan
7. Laporan
   - Stock Move History, mencatat semua aktivitas mutasi stok di gudang dan produksi per barang
   - Stock Transfer History, mencatat mutasi barang antar gudang dan atau proses produksi per barang
   - Valuation, ringkasan atas mutasi kuantitas stok per barang
   - Stock Card, ringkasan kartu stok atas item barang Storable
   - Stock Card Detail, mutasi stok barang berupa kartu stok
   - Stock Valuation (Qty), ringkasan atas mutasi stok per barang (Qty dan Nilai Barang)
   - Stock Ageing, umur stok barang ter-update, dihitung dari tanggal masuk barang atau tanggal hasil produksi barang
   - Actual Stock Moves vs Planning
