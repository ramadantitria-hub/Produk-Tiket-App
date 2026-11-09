# ProdukTokoApp

Aplikasi desktop pencatatan dan pengelolaan produk toko sederhana berbasis **JavaFX** dan **Maven**.

## Fitur
- **Tambah Produk Baru**: Input nama produk, kategori (Makanan/Minuman), dan harga produk dengan validasi otomatis.
- **Detail Produk**: Menampilkan informasi lengkap produk yang baru ditambahkan dengan format mata uang Rupiah (`id-ID`).
- **Daftar Produk**: Menampilkan tabel produk (`TableView`) dengan fitur:
  - Pencarian berdasarkan nama produk.
  - Filter berdasarkan kategori produk.
  - Hapus produk dengan konfirmasi dialog.


## Cara Menjalankan Melalui Apache NetBeans
1. Buka folder proyek ini di Apache NetBeans.
2. Klik kanan pada proyek **ProdukTokoApp** > **Run** (atau tekan **F6**).

## Struktur Proyek
- `src/main/java/kelas/MainApp.java`: Titik masuk (entry point) aplikasi JavaFX.
- `src/main/java/kelas/DemoTerminal.java`: Demo uji model di terminal.
- `src/main/java/kelas/controller/`: Controller JavaFX (Form, Detail, Daftar).
- `src/main/java/kelas/model/`: Model data produk.
- `src/main/resources/kelas/`: File FXML antarmuka dan CSS styling.

