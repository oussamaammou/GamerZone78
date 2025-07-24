<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>GAMERZONE78 - متجر الألعاب</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: #0e1e3d; / خلفية زرقاء داكنة/
      color: white;
    }

  header {
      text-align: center;
      padding: 30px;
      background: #1a2f5b;
      box-shadow: 0 0 10px rgba(0,0,0,0.5);
    }

   header h1 {
      font-size: 48px;
      margin: 0;
      color: #00bfff;
    }

  .games-container {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 30px;
      padding: 40px;
      max-width: 1200px;
      margin: auto;
    }

  .game-card {
      background: #1c2a48;
      border-radius: 10px;
      overflow: hidden;
      box-shadow: 0 4px 8px rgba(0,0,0,0.3);
      transition: transform 0.3s;
    }

  .game-card:hover {
      transform: scale(1.05);
    }

  .game-card img {
      width: 100%;
      height: 300px;
      object-fit: cover;
    }
    

    د.game-card h3 {
  text-align: center;
      margin: 15px;
      font-size: 20px;
      color: #ffffff;
    }

   footer {
      text-align: center;
      padding: 20px;
      background: #0c1a33;
      color: #bbb;
    }
  </style>
</head>
<body>

  <header>
    <h1>GAMERZONE78</h1>
    <p>أفضل متجر لتحميل الألعاب</p>
  </header>

  <section class="games-container">
    <div class="game-card">
      <img src="0cd047e1af130d0166878f5223799338.jpg" alt="Call of Duty Mobile">
      <h3>Call of Duty Mobile</h3>
    </div>
    <div class="game-card">
      <img src="grand-theft-auto-v-cover.jpg" alt="GTA V">
      <h3>GTA V</h3>
    </div>
    <div class="game-card">
      <img src="2ccb0dd1fc17b4e476915c5760b5333a.jpg" alt="Clash of Clans">
      <h3>Clash of Clans</h3>
    </div>
    <div class="game-card">
      <img src="104897e70cb35b21dcf0e5d305f6e119.jpg" alt="Free Fire">
      <h3>Free Fire</h3>
    </div>
    <div class="game-card">
      <img src="0f6cceff996d9c6414e098a97c918040.jpg" alt="Subway Surfers">
      <h3>Subway Surfers</h3>
    </div>
    <div class="game-card">
      <img src="jxx4wkaq.jpg" alt="Poppy Playtime">
      <h3>Poppy Playtime</h3>
    </div>
    <div class="game-card">
      <img src="48bce07fe7b079817ee07323711e33e3.jpg" alt="EA Games">
      <h3>EA Games</h3>
    </div>
    <div class="game-card">
      <img src="dc8b8a3e4c9b0e843e2d666fa41570bd.jpg" alt="Mobile Legends">
      <h3>Mobile Legends</h3>
    </div>
    <div class="game-card">
      <img src="5m1zsva.png" alt="Spider-Man">
      <h3>Spider-Man</h3>
    </div>
    <div class="game-card">
      <img src="bc3dd6723cd0117266411a95b50ec1e0.jpg" alt="PUBG Mobile">
      <h3>PUBG Mobile</h3>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 GAMERZONE78 - جميع الحقوق محفوظة</p>
  </footer>

</body>
</html>
