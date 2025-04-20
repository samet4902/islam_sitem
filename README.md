# islam_sitem<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>İslam Hakkında Bilgi</title>
  <link href="https://fonts.googleapis.com/css2?family=Reem+Kufi+Ink&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Reem Kufi Ink', sans-serif;
      background: linear-gradient(to right, #f3f4f6, #d1fae5);
      color: #1f2937;
    }

    header {
      background-color: #10b981;
      color: white;
      padding: 2rem;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }

    nav {
      background-color: #059669;
      display: flex;
      justify-content: center;
      padding: 0.8rem;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 1.5rem;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }

    .container {
      max-width: 1000px;
      margin: 2rem auto;
      padding: 1rem;
      background-color: #ffffffdd;
      border-radius: 12px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }

    .section {
      margin-bottom: 2.5rem;
    }

    .section h2 {
      color: #0f766e;
      font-size: 1.8rem;
      margin-bottom: 1rem;
      border-bottom: 2px solid #a7f3d0;
      display: inline-block;
      padding-bottom: 0.3rem;
    }

    .section img {
      max-width: 100%;
      border-radius: 10px;
      margin-top: 1rem;
    }

    footer {
      text-align: center;
      padding: 1.5rem;
      background-color: #10b981;
      color: white;
    }

    button {
      background-color: #047857;
      color: white;
      padding: 0.6rem 1.2rem;
      border: none;
      border-radius: 8px;
      font-size: 1rem;
      cursor: pointer;
    }

    button:hover {
      background-color: #065f46;
    }
  </style>
</head>
<body>
  <header>
    <h1>İslam Dini Hakkında</h1>
  </header>

  <nav>
    <a href="#ayetler">Ayetler</a>
    <a href="#peygamber">Peygamber Efendimiz</a>
    <a href="#ibadet">İbadetler</a>
  </nav>

  <div class="container">
    <section class="section" id="ayetler">
      <h2>Kur'an-ı Kerim'den Ayetler</h2>
      <p>“Hiç bilenlerle bilmeyenler bir olur mu?” (Zümer, 39/9)</p>
      <p>“Gerçekten namaz, hayâsızlıktan ve kötülükten alıkoyar.” (Ankebut, 29/45)</p>
      <img src="https://i.imgur.com/YkczDgt.jpg" alt="Kur'an-ı Kerim" />
    </section>

    <section class="section" id="peygamber">
      <h2>Hz. Muhammed (S.A.V)</h2>
      <p>Peygamberimiz, ahlakı en güzel olan, doğruluğu ile tanınan ve ümmetine örnek bir insandı. O'nun hayatı, bizler için bir rehberdir.</p>
      <img src="https://i.imgur.com/fIWT5sM.jpg" alt="Peygamber Efendimiz" />
    </section>

    <section class="section" id="ibadet">
      <h2>İslam’da İbadet</h2>
      <p>İslam’ın 5 temel şartı vardır: Kelime-i Şehadet, Namaz, Oruç, Zekât ve Hac. Bunlar, bir Müslümanın yaşamındaki en önemli ibadetlerdir.</p>
      <button onclick="alert('Allah kabul etsin!')">Daha fazla oku</button>
    </section>
  </div>

  <footer>
    &copy; 2025 İslam Bilgi Sitesi | Hazırlayan: Samet
  </footer>
</body>
</html>
