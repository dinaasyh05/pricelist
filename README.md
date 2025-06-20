# pricelist
menjual berbagai kebutuhan produk digital dengan harga termurah
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pricelist Dandin Apps Store</title>
  <link href="https://fonts.googleapis.com/css2?family=Fredoka:wght@700&family=Poppins:wght@600;700;800&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(135deg, #fde2ff, #e0f7fa);
      padding: 3rem 1rem;
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    h1 {
      font-size: 2.5rem;
      color: #d45a85;
      margin-bottom: 2rem;
      font-family: 'Fredoka', sans-serif;
      text-shadow: 1px 1px 2px #fff;
    }

    .container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 1.5rem;
      max-width: 1000px;
    }

    .card {
      background-color: #fff8f8;
      border-radius: 20px;
      padding: 1.5rem;
      width: 280px;
      box-shadow: 0 5px 15px rgba(0,0,0,0.1);
      transition: transform 0.3s ease;
    }

    .card:hover {
      transform: translateY(-6px);
    }

    .card h3 {
      color: #b34773;
      margin-bottom: 1rem;
      font-size: 1.4rem;
      font-weight: 800;
    }

    .card p {
      font-size: 1rem;
      color: #555;
      margin: 0.3rem 0;
    }

    .note {
      margin-top: 2rem;
      font-size: 0.9rem;
      color: #777;
      text-align: center;
    }

    .footer {
      margin-top: 3rem;
      font-size: 0.8rem;
      color: #999;
      text-align: center;
      font-style: italic;
    }

    .wa-button {
      display: inline-block;
      margin-top: 2rem;
      padding: 0.8rem 1.5rem;
      background-color: #ffc0cb;
      color: #fff;
      border-radius: 30px;
      text-decoration: none;
      font-weight: bold;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      transition: background-color 0.3s ease;
    }

    .wa-button:hover {
      background-color: #ff94a2;
    }
  </style>
</head>
<body>
  <h1>Daftar Harga Digital 💻✨</h1>

  <div class="container">
    <!-- YouTube Section -->
    <div class="card">
      <h3>📺 YouTube</h3>
      <p><strong>Famplan</strong><br>1 bulan 10k<br>2 bulan 15k</p>
      <p><strong>Indplan</strong><br>1 bulan 12k<br>3 bulan 23k (acc store, nogar)<br>3 bulan 35k (acc store, fullgar)</p>
      <p><strong>Mixplan</strong><br>4 bulan 37k<br>5 bulan 45k (acc store, fullgar)</p>
    </div>

    <!-- Spotify Section -->
    <div class="card">
      <h3>🎶 Spotify</h3>
      <p><strong>Famplan Fullgar</strong><br>1 bulan 18k<br>2 bulan 35k</p>
      <p><strong>Indplan Replace No Gar</strong><br>1 bulan 15k<br>2 bulan 20k<br>3 bulan 30k</p>
      <p><strong>Indplan Replace Fullgar 🔒</strong><br>2 bulan 33k<br>3 bulan 40k<br>4 bulan 50k</p>
    </div>

    <!-- VIU Section -->
    <div class="card">
      <h3>🍟 VIU</h3>
      <p><strong>Antilimit</strong><br>1 bulan 15k<br>2 bulan 20k<br>3 bulan 25k</p>
      <p><strong>Private Biasa</strong><br>1 bulan 10k<br>2 bulan 15k<br>3 bulan 20k<br>4 bulan 25k<br>5 bulan 30k<br>6 bulan 35k</p>
      <p><strong>Private Less Limit</strong><br>1 bulan 12k<br>2 bulan 20k<br>3 bulan 25k<br>4 bulan 30k<br>5 bulan 35k<br>6 bulan 38k</p>
    </div>

    <!-- Canva Section -->
    <div class="card">
      <h3>🎨🖌 Canva</h3>
      <p>1 bulan 7k<br>3 bulan 10k<br>6 bulan 17k<br>1 tahun 27k<br>Lifetime 35k<br><em>+designer fee 3k</em></p>
      <p><strong>Harian</strong><br>1 hari 2k<br>2 hari 3k<br>3 hari 4,5k<br>7 hari 8k</p>
    </div>

    <!-- Vidio Section -->
    <div class="card">
      <h3>🎬 Vidio</h3>
      <p><strong>Sharing</strong><br>1 bulan 20k<br>1 hari 6k<br>3 hari 12k</p>
      <p><strong>Private 🔒</strong><br>1 bulan 33k</p>
    </div>

    <!-- Netflix Section -->
    <div class="card">
      <h3>🍿 Netflix</h3>
      <p><strong>Sharing 1p2u</strong><br>1 bulan 22k<br>2 bulan 35k<br>3 bulan 50k</p>
      <p><strong>Harian</strong><br>1 hari 4k<br>2 hari 5k<br>3 hari 6k<br>5 hari 8k<br>7 hari 10k<br>14 hari 15k</p>
      <p><strong>Private 1p1u 🔒</strong><br>1 bulan 35k<br>3 bulan 98k</p>
    </div>
  </div>

  <p class="note">🗒️ Notes:<br>
    - Indplan akun WAJIB FRESH YANG BARU BUAT<br>
    - 3 BULAN INDPLAN FULL 3 BULAN (hanya tersedia akun store)<br>
    - Akun dari store + fee Rp 2.000<br>
    - Spotify akun dari seller + fee Rp 3.000<br>
    - VIU Less Limit = lebih jarang limit<br>
    - Canva 1-3 Bulan Full Garansi<br>
    - 1 Tahun & Lifetime Garansi 6 Bulan<br>
    - Canva: Acc Cust Need Email Saja<br>
    - Vidio: Akun dari seller, Private made by seller, Sharing login 1 device
  </p>

  <a href="https://wa.me/6287781329599" class="wa-button">Chat via WhatsApp 💬</a>

  <div class="footer">
    Website ini dibuat dengan cinta 💖 oleh <strong>Cutie Pookie</strong><br>
    Terima kasih sudah mampir! Semoga harimu menyenangkan 🌸✨
  </div>
</body>
</html>
