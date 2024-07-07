<!DOCTYPE html>
<html lang="tr">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Sabaku Fansub</title>
    <style>
      body {
        font-family: Arial, sans-serif;
        background-color: #d3d3d3; /* Gri arka plan */
        margin: 0;
        padding: 0;
      }
      header {
        background-color: #696969; /* Koyu gri */
        color: white;
        padding: 1rem 0;
        text-align: center;
        display: flex;
        align-items: center;
        justify-content: center;
      }
      .logo {
        height: 100px; /* Boyut iki katına çıkarıldı */
      }
      nav {
        display: flex;
        justify-content: center;
        background-color: #696969; /* Koyu gri */
        box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
      }
      nav a {
        color: white;
        padding: 1rem 2rem;
        text-decoration: none;
        font-size: 18px;
        transition: background-color 0.3s, color 0.3s;
      }
      nav a:hover {
        background-color: #a9a9a9; /* Açık gri tonunda hover efekti */
        color: #d3d3d3; /* Gri */
        border-radius: 5px;
      }
      main {
        padding: 2rem;
        text-align: center;
      }
      .content-section {
        margin: 2rem 0;
      }
      footer {
        background-color: #696969; /* Koyu gri */
        color: white;
        text-align: center;
        padding: 1rem 0;
        position: fixed;
        width: 100%;
        bottom: 0;
      }
    </style>
  </head>
  <body>
    <header>
      <img src="logo - Kopya-.png" alt="Logo" class="logo" />
    </header>
    <nav>
      <a href="#">Ana Sayfa</a>
      <a href="anime/anime_sitesi.html">&nbsp;Anime İzle&nbsp;</a>
      <a href="manga/manga_sitesi.html">&nbsp;Manga Oku&nbsp;</a>
      <a href="#">İletişim</a>
    </nav>
    <main>
      <section class="content-section">
        <h2>Popüler Animeler</h2>
        <p>Burada popüler animeler listelenecek.</p>
      </section>
      <section class="content-section">
        <h2>Yeni Mangalar</h2>
        <p>Burada yeni eklenen mangalar listelenecek.</p>
      </section>
    </main>
    <footer>
      <p>&copy; 2024 Sabaku Fansub. Tüm hakları saklıdır.</p>
    </footer>
  </body>
</html>
