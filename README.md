# surprise
 <!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Сюрприз</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(135deg, #ffe0ec, #ffd6e0);
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
      text-align: center;
      color: #5c2a44;
    }
    .box {
      background: #fff0f6;
      padding: 30px 25px;
      border-radius: 16px;
      box-shadow: 0 8px 20px rgba(0, 0, 0, 0.1);
      max-width: 300px;
    }
    .box p {
      font-size: 20px;
      margin-bottom: 15px;
    }
    .coords {
      font-size: 20px;
      font-weight: bold;
      color: #d63384;
      margin-bottom: 15px;
    }
    .btn {
      display: inline-block;
      margin-top: 10px;
      padding: 10px 20px;
      background: #ff66a3;
      color: white;
      text-decoration: none;
      border-radius: 8px;
      font-weight: bold;
      transition: background 0.3s ease;
    }
    .btn:hover {
      background: #e05592;
    }
  </style>
</head>
<body>
  <div class="box">
    <p>Знаешь, что это?</p>
    <div class="coords">46.3959043, 30.729810</div>
    <a class="btn" href="https://maps.google.com/?q=46.3959043,30.729810" target="_blank">Смотри на карте</a>
  </div>
</body>
</html>