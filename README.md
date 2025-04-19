# Sandal-Kita
Sandal Kita Bagian Dari Kaki Kita
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SandalKita - Toko Sandal Terbaik</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Header -->
    <header>
        <div class="container">
            <h1>SandalKita</h1>
            <nav>
                <a href="#produk">Produk</a>
                <a href="#kontak">Kontak</a>
            </nav>
        </div>
    </header>

    <!-- Banner atau Slider -->
    <section id="banner">
        <img src="banner.jpg" alt="SandalKita Collection">
        <p>Temukan Sandal Terbaik Untuk Semua Kalangan</p>
    </section>

    <!-- Produk -->
    <section id="produk" class="produk">
        <h2>Produk Kami</h2>
        <div class="produk-list">
            <div class="produk-item">
                <img src="sandal1.jpg" alt="Sandal Pria">
                <h3>Sandal Pria</h3>
                <p>Rp 150.000</p>
                <button onclick="tambahKeKeranjang('Sandal Pria')">Tambah ke Keranjang</button>
            </div>
            <!-- Tambahkan produk lainnya -->
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 SandalKita. Semua hak cipta dilindungi.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #333;
    color: white;
    padding: 10px 0;
    text-align: center;
}

header nav a {
    color: white;
    margin: 0 10px;
    text-decoration: none;
}

section {
    padding: 20px;
}

#banner img {
    width: 100%;
    height: auto;
}

.produk-list {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
}

.produk-item {
    background-color: white;
    padding: 15px;
    margin: 10px;
    width: 250px;
    text-align: center;
    border-radius: 5px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.produk-item img {
    width: 100%;
    height: auto;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px 0;
}function tambahKeKeranjang(produk) {
    alert(produk + " telah ditambahkan ke keranjang!");
}
