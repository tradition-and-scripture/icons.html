# icons.html
<!DOCTYPE html>
<html lang="bg">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Галерия с Икони</title>
  <link href="https://fonts.googleapis.com/css2?family=Old+Standard+TT&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Old Standard TT', serif;
      margin: 0;
      padding: 0;
      background-color: #fff;
      color: #333;
    }
    nav {
      background-color: #222;
      color: #fff;
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 1rem;
      padding: 1rem;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    h1 {
      text-align: center;
      padding-top: 1rem;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 1rem;
      padding: 2rem;
    }
    .gallery img {
      width: 100%;
      border: 2px solid #ccc;
      border-radius: 10px;
      transition: transform 0.3s;
    }
    .gallery img:hover {
      transform: scale(1.05);
      cursor: pointer;
    }
    @media (max-width: 600px) {
      nav {
        flex-direction: column;
        align-items: center;
      }
    }
  </style>
</head>
<body>
  <nav>
    <a href="index.html">Начало</a>
    <a href="literature.html">Литература</a>
    <a href="articles.html">Статии</a>
    <a href="author.html">За Автора</a>
    <a href="icons.html">Икони</a>
  </nav>

  <h1>Византийска Галерия с Икони</h1>
<a href="search.html">Търсачка</a>

  <div class="gallery">
    <img src="images/jesus-icon.jpg" alt="Икона на Христос">
    <img src="images/theotokos-icon.jpg" alt="Икона на Богородица">
    <img src="images/st-nicholas.jpg" alt="Свети Николай">
    <img src="images/annunciation.jpg" alt="Благовещение">
  </div>
</body>
</html>
