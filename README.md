# Tochkakamen.github.io
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>tochkakamen</title>
  <style>
    body {
      margin: 0;
      background: black;
      color: white;
      font-family: monospace;
      font-size: 1.5em;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      text-align: center;
    }
    img {
      width: 180px;
      height: 180px;
      border-radius: 50%;
      margin-bottom: 20px;
      border: 2px solid white;
      object-fit: cover;
    }
    .cursor {
      display: inline-block;
      width: 10px;
      background: white;
      margin-left: 5px;
      animation: blink 1s infinite;
    }
    @keyframes blink {
      0%, 50% { background: white; }
      51%, 100% { background: transparent; }
    }
  </style>
</head>
<body>
  <img src="avatar.jpg" alt="avatar">
  <div>
    A little more sabr your Happiness will come soon<span class="cursor"></span>
  </div>
</body>
</html>
