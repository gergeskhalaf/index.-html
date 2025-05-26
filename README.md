<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>I love you</title>
  <style>
    body {
      margin: 0;
      height: 100vh;
      background: linear-gradient(to right, #ff9a9e, #fad0c4);
      display: flex;
      align-items: center;
      justify-content: center;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }

    .heart-message {
      text-align: center;
      font-size: 3em;
      color: white;
      text-shadow: 2px 2px 6px rgba(0, 0, 0, 0.3);
      animation: fadeIn 2s ease-in-out;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: scale(0.9); }
      to { opacity: 1; transform: scale(1); }
    }
  </style>
</head>
<body>
  <div class="heart-message">I love you</div>
</body>
</html>
