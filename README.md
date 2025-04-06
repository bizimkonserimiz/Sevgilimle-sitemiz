<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Bizim Sitemiz</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #ffe6f0; /* Açık pembe arka plan */
      margin: 0;
      padding: 0;
      color: #333;
    }
    header {
      background: #ff69b4; /* Canlı pembe */
      color: white;
      padding: 1em;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2em;
    }
    header p {
      margin: 0.5em 0 0;
      font-size: 1.2em;
    }
    .love-note {
      text-align: center;
      font-size: 1.8em;
      margin: 1em;
      color: #ff1493; /* Derin pembe */
    }
    .gallery {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding: 1em;
    }
    .gallery img {
      margin: 0.5em;
      max-width: 300px;
      height: auto;
      border-radius: 8px;
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.2);
    }
    .music {
      text-align: center;
      padding: 1em;
    }
    audio {
      margin: 1em;
    }
  </style>
</head>
<body>
  <header>
    <h1>Bizim Sitemiz</h1>
    <p>Fotoğraflarımız, Müziklerimiz ve Sevgi Dolu Anlar</p>
  </header>

  <div class="love-note">
    <p>Seni Çok Seviyorum!</p>
  </div>
  
  <section class="gallery">
    <!-- Fotoğraf galerisi -->
    <img src="foto1.jpg" alt="Fotoğraf 1">
    <img src="foto2.jpg" alt="Fotoğraf 2">
    <img src="foto3.jpg" alt="Fotoğraf 3">
    <img src="foto4.jpg" alt="Fotoğraf 4">
  </section>
  
  <section class="music">
    <h2>Bizim Müziklerimiz</h2>
    <!-- Kendi sesinle kaydettiğin şarkı -->
    <audio controls>
      <source src="sarki.mp3" type="audio/mpeg">
      Tarayıcınız audio elementini desteklemiyor.
    </audio>
    <br>
    <!-- Kağan Boşnak - Benimle Kayboldun parçası -->
    <audio controls>
      <source src="kaaganBosnak.mp3" type="audio/mpeg">
      Tarayıcınız audio elementini desteklemiyor.
    </audio>
  </section>
</body>
</html>
