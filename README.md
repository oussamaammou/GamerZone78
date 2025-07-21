html
<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8" />
  <title>GEMS 78</title>
  <style>
    body {
      margin: 0;
      font-family: 'Arial', sans-serif;
      background-color: #007bff;
      color: white;
    }

   header {
      text-align: center;
      padding: 20px;
      background-color: #0056b3;
    }

  header h1 {
      font-size: 36px;
      font-weight: bold;
      font-style: italic;
      color: red;
    }
    
  header h1 span {
      color: black;
    }

  .games {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding: 20px;
      gap: 20px;
    }

   .game {
      background-color: #ffffff15;
      padding: 10px;
      border-radius: 10px;
      width: 180px;
      text-align: center;
      transition: 0.3s;
    }

   .game img {
     width: 100%;
      height: 100px;
      object-fit: contain;
      border-radius: 8px;
    }

   .game h2 {
      font-size: 18px;
      margin: 10px 0;
      font-weight: bold;
    }

  .game a {
      background-color: #ff4757;
      color: white;
      padding: 8px 14px;
      border-radius: 6px;
      text-decoration: none;
display: inline-block;
      font-weight: bold;
    }

   .game:hover {
      transform: scale(1.05);
    }

   footer {
      text-align: center;
      padding: 15px;
      background-color: #004494;
    }
  </style>
</head>
<body>
  <header>
    <h1><span>GEMS</span> 78</h1>
    <p>أفضل الألعاب للجوال - حمل الآن</p>
  </header>

  <div class="games">
    <div class="game">
      <img src="https://upload.wikimedia.org/wikipedia/en/2/2e/PUBG_Mobile_logo.png" alt="PUBG Mobile" />
      <h2>PUBG Mobile</h2>
      <a href="#">تحميل</a>
    </div>
    <div class="game">
      <img src="https://upload.wikimedia.org/wikipedia/en/6/65/Free_Fire_logo.png" alt="Free Fire" />
      <h2>Free Fire</h2>
      <a href="#">تحميل</a>
    </div>
    <div class="game">
      <img src="https://upload.wikimedia.org/wikipedia/en/7/77/Call_of_Duty_Mobile_logo.png" alt="COD Mobile" />
      <h2>Call of Duty Mobile</h2>
      <a href="#">تحميل</a>
    </div>
    <div class="game">
      <img src="https://upload.wikimedia.org/wikipedia/en/5/5e/Clash_of_Clans_logo.png" alt="Clash of Clans" />
      <h2>Clash of Clans</h2>
      <a href="#">تحميل</a>
    </div>
    <div class="game">
      <img src="https://upload.wikimedia.org/wikipedia/en/f/fd/Clash_Royale_Logo.png" alt="Clash Royale" />
<h2>Clash Royale</h2>
      <a href="#">تحميل</a>
    </div>
    <div class="game">
      <img src="https://upload.wikimedia.org/wikipedia/en/f/f4/FIFA_Mobile_logo.png" alt="FIFA Mobile" />
      <h2>FIFA Mobile</h2>
      <a href="#">تحميل</a>
    </div>
    <div class="game">
      <img src="https://upload.wikimedia.org/wikipedia/en/8/8e/Mobile_Legends_Bang_Bang_logo.png" alt="Mobile Legends" />
      <h2>Mobile Legends</h2>
      <a href="#">تحميل</a>
    </div>
    <div class="game">
      <img src="https://upload.wikimedia.org/wikipedia/en/3/33/Among_Us_cover_art.png" alt="Among Us" />
      <h2>Among Us</h2>
      <a href="#">تحميل</a>
    </div>
    <div class="game">
      <img src="https://upload.wikimedia.org/wikipedia/en/5/5e/Subway_Surfers_app_logo.png" alt="Subway Surfers" />
      <h2>Subway Surfers</h2>
      <a href="#">تحميل</a>
    </div>
    <div class="game">
      <img src="https://upload.wikimedia.org/wikipedia/en/2/2f/Candy_Crush_Saga_logo.png" alt="Candy Crush" />
      <h2>Candy Crush</h2>
      <a href="#">تحميل</a>
    </div>
  </div>

  <footer>
    <p>&copy; 2025 GEMS 78 - جميع الحقوق محفوظة</p>
  </footer>
</body>
</html>
