html
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <title>GEMS 78</title>
  <style>
    body {
      background-color: #007bff;
      margin: 0;
      font-family: 'Arial', sans-serif;
    }
    header {
      text-align: center;
      padding: 30px 10px;
    }
    h1 {
      font-size: 48px;
      font-weight: bold;
      font-style: italic;
      color: red;
      text-shadow: 2px 2px 0 black;
    }
    .controller {
      width: 100px;
      display: block;
      margin: 0 auto 10px;
    }
    .games {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
      padding: 20px;
    }
    .game {
      background-color: white;
      border-radius: 10px;
      text-align: center;
      box-shadow: 0 0 10px rgba(0,0,0,0.3);
      overflow: hidden;
    }
    .game img {
      width: 100%;
      height: 150px;
      object-fit: cover;
    }
    .game-title {
      font-weight: bold;
      font-size: 18px;
      margin: 10px 0;
      color: #333;
    }
    .btn {
      background-color: crimson;
      color: white;
      padding: 10px 15px;
      text-decoration: none;
      border-radius: 5px;
      font-weight: bold;
      display: inline-block;
margin-bottom: 10px;
    }
    .btn:hover {
      background-color: darkred;
    }
  </style>
</head>
<body>
  <header>
    <img class="controller" src="https://i.imgur.com/59O2gfz.png" alt="controller">
    <h1>GEMS 78</h1>
  </header>
  <div class="games">
    <div class="game">
      <img src="https://i.imgur.com/yKpUGV3.png" alt="PUBG">
      <div class="game-title">PUBG Mobile</div>
      <a class="btn" href="#">تحميل</a>
    </div>
    <div class="game">
      <img src="https://i.imgur.com/hHgyHfH.png" alt="Free Fire">
      <div class="game-title">Free Fire</div>
      <a class="btn" href="#">تحميل</a>
    </div>
    <div class="game">
      <img src="https://i.imgur.com/41fOvvo.png" alt="COD">
      <div class="game-title">Call of Duty Mobile</div>
      <a class="btn" href="#">تحميل</a>
    </div>
    <div class="game">
      <img src="https://i.imgur.com/BXUFeh2.png" alt="Clash of Clans">
      <div class="game-title">Clash of Clans</div>
      <a class="btn" href="#">تحميل</a>
    </div>
    <div class="game">
      <img src="https://i.imgur.com/8zgyuHK.png" alt="Clash Royale">
      <div class="game-title">Clash Royale</div>
      <a class="btn" href="#">تحميل</a>
    </div>
    <div class="game">
      <img src="https://i.imgur.com/SVgsS8H.png" alt="FIFA">
<div class="game-title">FIFA Mobile</div>
      <a class="btn" href="#">تحميل</a>
    </div>
    <div class="game">
      <img src="https://i.imgur.com/yzkfsyo.png" alt="Mobile Legends">
      <div class="game-title">Mobile Legends</div>
      <a class="btn" href="#">تحميل</a>
    </div>
    <div class="game">
      <img src="https://i.imgur.com/p0t1bMR.png" alt="Among Us">
      <div class="game-title">Among Us</div>
      <a class="btn" href="#">تحميل</a>
    </div>
    <div class="game">
      <img src="https://i.imgur.com/fAzCwvu.png" alt="Subway">
      <div class="game-title">Subway Surfers</div>
      <a class="btn" href="#">تحميل</a>
    </div>
    <div class="game">
      <img src="https://i.imgur.com/OEKhvGB.png" alt="Candy Crush">
      <div class="game-title">Candy Crush</div>
      <a class="btn" href="#">تحميل</a>
    </div>
  </div>
</body>
</html>
