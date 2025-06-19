<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>skinmap</title>
  <style>
    body {
      background-color: #111;
      color: white;
      font-family: sans-serif;
      text-align: center;
    }
    h1 {
      margin-top: 50px;
      font-size: 2em;
    }
    .country-list {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 30px;
      margin-top: 50px;
    }
    .country {
      transition: transform 0.2s ease;
    }
    .country:hover {
      transform: scale(1.05);
    }
    img {
      width: 180px;
      border-radius: 8px;
    }
  </style>
</head>
<body>

  <h1>Choose a Country</h1>

  <div class="country-list">
    <a href="artists/japan.html" class="country">
      <img src="images/japan.png" alt="Japan">
    </a>
    <a href="artists/usa.html" class="country">
      <img src="images/usa.png" alt="USA">
    </a>
    <a href="artists/germany.html" class="country">
      <img src="images/germany.png" alt="Germany">
    </a>
  </div>

</body>
</html>
