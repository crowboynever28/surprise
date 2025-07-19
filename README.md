# surprise
<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Сюрприз</title>
  <style>
    body {
      font-family: sans-serif;
      background: #fff;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
      text-align: center;
      color: #333;
    }
    .box {
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
    }
    .coords {
      font-size: 24px;
      font-weight: bold;
      color: #007aff;
      margin: 10px 0;
    }
    .btn {
      display: inline-block;
      margin-top: 15px;
      padding: 10px 20px;
      background: #007aff;
      color: #fff;
      text-decoration: none;
      border-radius: 8px;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <div class="box">
    <p>Знаешь, что это?</p>
    <div class="coords">47.123456, 31.123456</div>
    <a class="btn" href="https://maps.google.com/?q=47.123456,31.123456" target="_blank">Смотри на карте</a>
  </div>
</body>
</html>