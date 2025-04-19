<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>JASTALOSER</title>
  <style>
    body {
      margin: 0;
      font-family: 'Georgia', serif;
      background: linear-gradient(135deg, #0b0b0c, #1c1c1e);
      color: #e8c790;
      text-align: center;
      padding: 0 20px;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 40px;
      margin-top: 30px;
      font-size: 14px;
    }
    h1 {
      font-size: 50px;
      margin: 40px 0 10px;
    }
    .tagline {
      font-size: 14px;
      letter-spacing: 2px;
      margin-bottom: 40px;
    }
    .listen-btn {
      display: inline-block;
      padding: 10px 30px;
      border: 1px solid #e8c790;
      margin-bottom: 60px;
      font-size: 14px;
      cursor: pointer;
      text-decoration: none;
      color: #e8c790;
    }
    .section {
      margin-bottom: 60px;
    }
    .album-box, .merch {
      display: flex;
      justify-content: center;
      gap: 30px;
      flex-wrap: wrap;
    }
    .album-box div, .merch-item {
      border: 1px solid #e8c790;
      padding: 20px;
      font-size: 18px;
      width: 120px;
      height: 120px;
      display: flex;
      align-items: center;
      justify-content: center;
    }
    .merch img {
      height: 150px;
      object-fit: contain;
    }
  </style>
</head>
<body>
  <nav>
    <span>MUSIC</span>
    <span>MERCH</span>
    <span>ABOUT</span>
    <span>CONTACT</span>
  </nav>  <h1>JASTALOSER</h1>
  <div class="tagline">PAIN. TRUTH. FAITH. HOPE</div>
  <a class="listen-btn" href="#">LISTEN NOW</a>  <div class="section">
    <div>LATEST ALBUM</div>
    <div class="album-box">
      <div>BROKEN</div>
    </div>
  </div>  <div class="section">
    <div>MERCH</div>
    <div class="merch">
      <div class="merch-item"><img src="cap.png" alt="Cap" /></div>
      <div class="merch-item"><img src="black-hoodie.png" alt="Black Hoodie" /></div>
      <div class="merch-item"><img src="brown-hoodie.png" alt="Brown Hoodie" /></div>
    </div>
  </div>
</body>
</html>