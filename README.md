<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>The Lord Imam</title>
  <style>
    body {
      background-color: #000;
      color: #fff;
      font-family: 'Arial', sans-serif;
      text-align: center;
      padding: 60px 20px;
      overflow-x: hidden;
    }

    h1 {
      color: #FFD700;
      font-size: 42px;
      margin-bottom: 30px;
      opacity: 0;
      transform: translateY(-20px);
      animation: fadeInDown 2s ease forwards;
    }

    @keyframes fadeInDown {
      0% { opacity: 0; transform: translateY(-30px); }
      100% { opacity: 1; transform: translateY(0); }
    }

    p {
      max-width: 600px;
      margin: 20px auto;
      line-height: 1.6;
      opacity: 0;
      animation: fadeIn 3s ease forwards;
      animation-delay: 1.2s;
    }

    @keyframes fadeIn {
      to { opacity: 1; }
    }

    a {
      display: inline-block;
      margin-top: 30px;
      padding: 12px 28px;
      color: #FFD700;
      border: 2px solid #FFD700;
      border-radius: 25px;
      text-decoration: none;
      font-weight: bold;
      position: relative;
      overflow: hidden;
      transition: color 0.3s, border-color 0.3s;
      animation: fadeIn 3s ease forwards;
      animation-delay: 2s;
    }

    a::before {
      content: "";
      position: absolute;
      top: 0;
      left: -100%;
      width: 100%;
      height: 100%;
      background: linear-gradient(120deg, transparent, rgba(255, 215, 0, 0.5), transparent);
      transition: all 0.5s;
    }

    a:hover::before {
      left: 100%;
    }

    a:hover {
      color: #fff;
      border-color: #fff;
    }

    footer {
      margin-top: 60px;
      font-size: 14px;
      color: #888;
      animation: fadeIn 3s ease forwards;
      animation-delay: 3s;
    }
  </style>
</head>
<body>
  <h1>The Lord Imam</h1>
  <p>“Bu dünyada herkesin bir imzası vardır; fakat çoğu insan o imzayı atamadan gider. Ben ise o imzayı atmak için çabalıyorum — ya da en azından böyle bir imzadan haberdarım.”</p>
  <p>Ben Murat — kelimelerin, düşüncelerin ve sınırların ötesinde bir iz bırakmaya çalışan biri.</p>
  <a href="https://instagram.com" target="_blank">Instagram</a>
  <footer>© 2025 The Lord Imam. All rights reserved.</footer>
</body>
</html>
