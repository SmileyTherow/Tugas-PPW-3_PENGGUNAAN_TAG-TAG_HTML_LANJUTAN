# ArtVault Shop - Penggunaan Tag-Tag HTML Lanjutan

Sebuah aplikasi web toko online sederhana yang dibuat untuk mempelajari penggunaan tag-tag HTML lanjutan beserta CSS dan JavaScript. Aplikasi ini mensimulasikan toko online untuk penjualan gambar/artwork dengan fitur keranjang belanja yang lengkap.

## 🚀 Demo

Aplikasi ini adalah toko online "ArtVault Shop" yang menjual berbagai gambar/artwork dengan fitur:
- Katalog produk yang dinamis
- Sistem keranjang belanja
- Pencarian produk
- Proses checkout

## 📁 Struktur File

```
├── Penggunaan tag-tag HTML Lanjutan.html    # Halaman utama toko (index)
├── keranjang.html                           # Halaman keranjang belanja
├── checkout.html                            # Halaman checkout alternatif
└── Image/                                   # Folder gambar produk
    ├── 1.jpg
    ├── 2.jpg
    └── ... (hingga 30.jpg)
```

## 🎯 Fitur Utama

### 1. Halaman Utama (index)
- **Header navigasi** dengan logo toko dan link ke keranjang
- **Search bar** untuk mencari produk secara real-time
- **Katalog produk** yang menampilkan 30 gambar secara dinamis
- **Sistem notifikasi** saat produk ditambahkan ke keranjang
- **Local Storage** untuk menyimpan data keranjang

### 2. Halaman Keranjang
- **Tampilan item** yang ada di keranjang
- **Kontrol kuantitas** (tambah/kurang jumlah item)
- **Hapus item** dari keranjang
- **Total harga** dengan format mata uang Indonesia
- **Validasi data** untuk mencegah error
- **Proses checkout** dengan konfirmasi

### 3. Halaman Checkout (Alternatif)
- **Review pesanan** sebelum checkout
- **Konfirmasi pembelian** dengan alert
- **Redirect** kembali ke halaman utama setelah checkout

## 🛠 Teknologi yang Digunakan

### HTML5
- Semantic tags (`<div>`, `<header>`, dll.)
- Form elements (`<input>`, `<button>`)
- Meta tags untuk responsive design
- Proper document structure

### CSS3
- **Flexbox layout** untuk responsive design
- **CSS Grid** untuk katalog produk
- **Hover effects** untuk interaktivitas
- **Fixed positioning** untuk notifikasi
- **Box shadow** untuk depth effect
- **Media queries** (implicit responsive)

### JavaScript (Vanilla)
- **Local Storage** untuk persistent data
- **DOM manipulation** untuk dynamic content
- **Event handling** (onclick, onkeyup)
- **Array methods** (findIndex, forEach, splice)
- **JSON parsing** untuk data management
- **Dynamic content generation** dengan loops

## 📚 Konsep HTML Lanjutan yang Dipelajari

### 1. Meta Tags & Document Structure
```html
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

### 2. CSS Integration
- **Internal CSS** dengan tag `<style>`
- **Responsive design** dengan flexbox
- **CSS selectors** (class, ID, pseudo-classes)

### 3. JavaScript Integration
- **Event handlers** dalam HTML
- **Dynamic content generation**
- **Browser APIs** (localStorage)

### 4. Form Elements & User Input
- **Search functionality** dengan `onkeyup`
- **Button interactions** dengan `onclick`
- **Input validation** dan error handling

### 5. Image Handling
- **Dynamic image loading** dengan JavaScript
- **Alt text** untuk accessibility
- **Title attributes** untuk tooltips

## 🎨 Styling Features

### Design System
- **Color Palette**: Biru (#1e3a8a) sebagai primary color
- **Typography**: Arial sans-serif untuk readability
- **Spacing**: Consistent padding dan margin
- **Layout**: Mobile-first responsive approach

### Interactive Elements
- **Hover effects** pada buttons dan links
- **Smooth transitions** untuk user experience
- **Visual feedback** dengan notifications
- **Loading states** dan error handling

## ⚙️ Fungsionalitas JavaScript

### Data Management
```javascript
// Contoh struktur data keranjang
let cart = [
  {
    nama: "Gambar 1",
    harga: 100000,
    gambar: "Image/1.jpg",
    jumlah: 2
  }
];
```

### Key Functions
1. `tambahKeKeranjang()` - Menambah produk ke keranjang
2. `cariGambar()` - Pencarian real-time
3. `tampilkanKeranjang()` - Render keranjang belanja
4. `ubahJumlah()` - Update kuantitas item
5. `checkout()` - Proses pembelian

## 🚀 Cara Menjalankan

1. **Setup Files**
   ```bash
   # Pastikan struktur folder benar
   ├── Penggunaan tag-tag HTML Lanjutan.html
   ├── keranjang.html
   ├── checkout.html
   └── Image/
       ├── 1.jpg
       ├── 2.jpg
       └── ... (hingga 30.jpg)
   ```

2. **Buka Aplikasi**
   - Double click file `Penggunaan tag-tag HTML Lanjutan.html`
   - Atau buka melalui web browser

3. **Navigasi**
   - Browse produk di halaman utama
   - Gunakan search bar untuk mencari gambar
   - Klik "Tambah ke Keranjang" untuk menambah item
   - Klik "Keranjang" untuk melihat keranjang belanja
   - Lakukan checkout untuk menyelesaikan pembelian

## 📱 Responsive Design

Aplikasi ini menggunakan:
- **Flexbox** untuk layout yang fleksibel
- **Viewport meta tag** untuk mobile optimization
- **Percentage-based** widths untuk adaptability
- **CSS media queries** (implicit dalam flexbox)

## 🔧 Fitur Teknis

### Local Storage Integration
- Data keranjang tersimpan di browser
- Persistent shopping cart
- Data tidak hilang saat refresh halaman

### Error Handling
- Validasi input untuk mencegah crash
- Default values untuk data yang hilang
- User-friendly error messages

### Search Functionality
- Real-time search saat mengetik
- Case-insensitive search
- Filter berdasarkan nama produk

## 🎓 Pembelajaran

### Untuk Pemula
- Struktur HTML yang proper dan semantic
- Integrasi CSS untuk styling yang menarik
- Dasar-dasar JavaScript untuk interaktivitas

### Untuk Intermediate
- DOM manipulation yang efisien
- Local Storage untuk data persistence
- Event handling yang proper
- Responsive design principles

### Advanced Concepts
- Data validation dan error handling
- Dynamic content generation
- State management dengan JavaScript
- User experience optimization

## 💡 Pengembangan Lebih Lanjut

Aplikasi ini bisa dikembangkan dengan:
- **Backend integration** untuk real database
- **Payment gateway** untuk pembayaran nyata
- **User authentication** sistem
- **Product categories** dan filtering
- **Reviews dan ratings** sistem
- **Inventory management**

## 🐛 Known Issues

1. Gambar harus tersedia di folder `Image/` (1.jpg - 30.jpg)
2. Data keranjang hilang jika localStorage dibersihkan
3. Tidak ada validasi stok produk
4. Checkout hanya simulasi (tidak ada payment gateway)

## 📞 Dukungan

File ini dibuat untuk tujuan pembelajaran HTML lanjutan. Untuk pertanyaan atau saran pengembangan, silakan:
- Buat issue di repository
- Kontribusi melalui pull request
- Diskusikan pengembangan lebih lanjut

---

**🎨 ArtVault Shop - Tempat terbaik untuk koleksi artwork digital Anda!**

*Dibuat untuk pembelajaran tag-tag HTML lanjutan dengan integrasi CSS dan JavaScript*