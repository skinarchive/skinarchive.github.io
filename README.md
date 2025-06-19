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
      display: flex;
      flex-direction: column;
      align-items: center;
      text-decoration: none;
      color: white;
    }

    .country:hover {
      transform: scale(1.05);
    }

    .country img {
      width: 150px;
      height: 100px;
      object-fit: contain;
      background-color: transparent;
      border-radius: 8px;
    }

    .country-name {
      margin-top: 10px;
      font-size: 1em;
      font-weight: bold;
    }
  </style>
</head>
<body>

  <h1>Choose a Country</h1>

  <div class="country-list">
    <a href="artists/japan.html" class="country">
      <img src="images/japan.png" alt="Japan">
      <span class="country-name">Japan</span>
    </a>
    <a href="artists/usa.html" class="country">
      <img src="images/usa.png" alt="USA">
      <span class="country-name">USA</span>
    </a>
    <a href="artists/germany.html" class="country">
      <img src="images/germany.png" alt="Germany">
      <span class="country-name">Germany</span>
    </a>
  </div>

</body>
</html>
