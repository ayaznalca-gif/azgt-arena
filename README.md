# azgt-arena
<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Futbol Kulübü</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Header / Menü -->
    <header>
        <div class="logo">
            <h2>⚽ FC ŞAMPİYON</h2>
        </div>
        <nav>
            <ul>
                <li><a href="#anasayfa">Ana Sayfa</a></li>
                <li><a href="#kadro">Kadro</a></li>
                <li><a href="#fikstur">Fikstür</a></li>
                <li><a href="#iletisim">İletişim</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero / Karşılama Alanı -->
    <section id="anasayfa" class="hero">
        <h1>ZAFERE GİDEN YOL!</h1>
        <p>Takımımızın en güncel haberleri, maç sonuçları ve kadro detayları burada.</p>
        <a href="#fikstur" class="btn">Sonraki Maçı Gör</a>
    </section>

    <!-- Kadro Alanı -->
    <section id="kadro" class="container">
        <h2>Öne Çıkan Oyuncular</h2>
        <div class="cards">
            <div class="card">
                <span class="number">1</span>
                <h3>Ahmet Yılmaz</h3>
                <p>Mevki: Kaleci</p>
            </div>
            <div class="card">
                <span class="number">4</span>
                <h3>Mehmet Demir</h3>
                <p>Mevki: Stoper</p>
            </div>
            <div class="card">
                <span class="number">10</span>
                <h3>Ali Kaya</h3>
                <p>Mevki: On Numara</p>
            </div>
            <div class="card">
                <span class="number">9</span>
                <h3>Burak Çelik</h3>
                <p>Mevki: Santrafor</p>
            </div>
        </div>
    </section>

    <!-- Maç Fikstürü -->
    <section id="fikstur" class="container bg-light">
        <h2>Gelecek Maçlar</h2>
        <div class="match-list">
            <div class="match-card">
                <span class="team">FC Şampiyon</span>
                <span class="vs">VS</span>
                <span class="team">Anadolu Gücü</span>
                <span class="date">18 Eylül - 20:00</span>
            </div>
            <div class="match-card">
                <span class="team">Yıldızlar SK</span>
                <span class="vs">VS</span>
                <span class="team">FC Şampiyon</span>
                <span class="date">25 Eylül - 21:30</span>
            </div>
        </div>
    </section>

    <!-- İletişim / Tesis Rezervasyonu -->
    <section id="iletisim" class="container">
        <h2>Bize Ulaşın / Oyuncu Başvurusu</h2>
        <form class="contact-form">
            <input type="text" placeholder="Adınız Soyadınız" required>
            <input type="email" placeholder="E-posta Adresiniz" required>
            <select required>
                <option value="">Mevki Seçiniz...</option>
                <option value="kaleci">Kaleci</option>
                <option value="defans">Defans</option>
                <option value="ortasaha">Orta Saha</option>
                <option value="forvet">Forvet</option>
            </select>
            <textarea placeholder="Mesajınız veya futbol geçmişiniz..." rows="4" required></textarea>
            <button type="submit" class="btn">Gönder</button>
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2026 FC Şampiyon. Tüm hakları saklıdır.</p>
    </footer>

</body>
</html>
