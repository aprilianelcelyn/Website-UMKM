<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Kontak</title>
</head>
<body>
    <header>
        <h1>Kontak Kami</h1>
        <nav>
            <ul>
                <li><a href="index.html">Beranda</a></li>
                <li><a href="about.html">Tentang Kami</a></li>
                <li><a href="contact.html">Kontak</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h2>Hubungi Kami</h2>
        <form id="contactForm">
            <label for="name">Nama:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Pesan:</label>
            <textarea id="message" name="message" required></textarea>
            <button type="submit">Kirim</button>
        </form>
    </main>
    <footer>
        <p>&copy; 2023 Website UMKM. Semua hak dilindungi.</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>
