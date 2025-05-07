<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Sekolah Rafa</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      background: #f4f4f4;
      color: #333;
    }

    header {
      background-color: #0044cc;
      padding: 20px;
      color: white;
      text-align: center;
    }

    nav {
      background: #0033aa;
      display: flex;
      justify-content: center;
      padding: 10px;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }

    section {
      padding: 40px 20px;
      text-align: center;
    }

    .profil, .galeri, .kontak {
      background: white;
      margin: 20px auto;
      padding: 20px;
      border-radius: 10px;
      max-width: 800px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
    }

    .galeri img {
      width: 200px;
      margin: 10px;
      border-radius: 10px;
    }

    footer {
      background-color: #222;
      color: white;
      text-align: center;
      padding: 15px;
    }
  </style>
</head>
<body>

  <header>
    <h1>SEKOLAH RAFA</h1>
    <p>Belajar. Berani. Berkarya.</p>
  </header>

  <nav>
    <a href="#beranda">Beranda</a>
    <a href="#profil">Profil</a>
    <a href="#galeri">Galeri</a>
    <a href="#kontak">Kontak</a>
  </nav>

  <section id="beranda">
    <h2>Selamat Datang di Website Sekolah Rafa</h2>
    <p>Kami adalah sekolah yang mengajarkan ilmu, adab, dan teknologi masa depan.</p>
  </section>

  <section id="profil" class="profil">
    <h2>Profil Sekolah</h2>
    <p>Sekolah Rafa didirikan pada tahun 2025 dengan tujuan mencetak generasi tangguh, pintar, dan berakhlak mulia.</p>
  </section>

  <section id="galeri" class="galeri">
    <h2>Galeri Kegiatan</h2>
    <img src="https://via.placeholder.com/200x150?text=Kegiatan+1" alt="Kegiatan 1">
    <img src="https://via.placeholder.com/200x150?text=Kegiatan+2" alt="Kegiatan 2">
    <img src="https://via.placeholder.com/200x150?text=Kegiatan+3" alt="Kegiatan 3">
  </section>

  <section id="kontak" class="kontak">
    <h2>Kontak Kami</h2>
    <p>Email: sekolahrafa@email.com</p>
    <p>WhatsApp: 0812-3456-7890</p>
    <p>Alamat: Jl. Pendidikan No. 7, Sukorejo</p>
  </section>

  <footer>
    <p>&copy; 2025 Sekolah Rafa. All Rights Reserved.</p>
  </footer>

</body>
</html>

