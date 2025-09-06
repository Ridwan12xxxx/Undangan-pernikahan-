<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Otong & Rizky</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(to bottom, #fdf6f0, #fff);
      margin: 0;
      padding: 0;
      scroll-behavior: smooth;
    }

    header {
      display: flex;
      justify-content: center;
      align-items: center;
      padding: 4em 1em;
    }

    .cover-box {
      position: relative;
      overflow: hidden;
      border-radius: 16px;
      padding: 3em 2em;
      text-align: center;
      box-shadow: 0 4px 12px rgba(0,0,0,0.2);
      color: white;
      max-width: 700px;
      width: 100%;
    }

    .cover-box::before {
      content: "";
      position: absolute;
      inset: 0;
      background-image: url('https://mudwebsite.com/wp-content/uploads/2024/11/sampul-baru-elegant-view.jpg');
      background-size: cover;
      background-position: center;
      filter: brightness(0.5);
      z-index: 0;
    }

    .cover-box h1,
    .cover-box p {
      position: relative;
      z-index: 1;
    }

    .container {
      max-width: 800px;
      margin: 0 auto;
      padding: 2em;
    }

    .box {
      background: white;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
      padding: 2em;
      margin-bottom: 2em;
      animation: fadeIn 1.2s ease-in;
    }

    .couple {
      display: flex;
      justify-content: center;
      gap: 2em;
      flex-wrap: wrap;
      margin-top: 1em;
    }

    .person {
      width: 200px;
      text-align: center;
    }

    .person img {
      width: 100%;
      border-radius: 50%;
      box-shadow: 0 4px 8px rgba(0,0,0,0.2);
      transition: transform 0.3s ease;
    }

    .person img:hover {
      transform: scale(1.05);
    }

    #countdown-box {
      background: #fff;
      border: 2px solid #f2c4a0;
      border-radius: 12px;
      padding: 1em;
      text-align: center;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
      max-width: 400px;
      margin: 0 auto;
    }

    #countdown {
      font-size: 2em;
      font-weight: bold;
      color: #d4a373;
      animation: pulse 1.5s infinite;
    }

    @keyframes pulse {
      0% { transform: scale(1); opacity: 1; }
      50% { transform: scale(1.05); opacity: 0.8; }
      100% { transform: scale(1); opacity: 1; }
    }

    .quote {
      font-style: italic;
      color: #555;
      font-size: 1.2em;
      margin-top: 1em;
    }

    .gallery {
      display: flex;
      gap: 1em;
      flex-wrap: wrap;
      justify-content: center;
    }

    .gallery img {
      width: 180px;
      border-radius: 8px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }

    form {
      display: flex;
      flex-direction: column;
      gap: 1em;
    }

    input, textarea, button {
      padding: 0.8em;
      border-radius: 8px;
      border: 1px solid #ccc;
      font-size: 1em;
    }

    button {
      background-color: #f2c4a0;
      color: white;
      border: none;
      cursor: pointer;
    }

    button:hover {
      background-color: #e0b28f;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(40px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>

<audio autoplay loop controls style="display:none">
  <source src="https://example.com/musik-latar.mp3" type="audio/mpeg">
</audio>

<header>
  <div class="cover-box">
    <h1>Otong & Rizky</h1>
    <p>06–07 September 2025</p>
  </div>
</header>

<div class="container">

  <div class="box">
    <h2>Assalamu’alaikum Warahmatullahi Wabarakatuh</h2>
    <p>Dengan memohon rahmat dan ridho Allah SWT, kami mengundang Bapak/Ibu/Saudara/i untuk menghadiri acara pernikahan kami.</p>
  </div>

  <div class="box">
    <h2>Pasangan Mempelai</h2>
    <div class="couple">
      <div class="person">
        <img src="s.jpg" alt="Otong">
        <h3>Otong</h3>
        <p>Putra dari Bapak Sariman dan Ibu Choyati</p>
      </div>
      <div class="person">
        <img src="https://mudwebsite.com/wp-content/uploads/2025/08/Anggi-Ayu-45-scaled.jpg" alt="Ayu">
        <h3>Ayu Sri Hastuti</h3>
        <p>Putri dari Bapak Imron Rosadi dan Ibu Danisem</p>
      </div>
    </div>
  </div>

  <div class="box">
    <h2>Waktu & Lokasi Acara</h2>
    <p>📅 Hari: Sabtu & Minggu</p>
    <p>🗓️ Tanggal: 06–07 September 2025</p>
    <p>⏰ Waktu: Pukul 10.00 WIB – Selesai</p>
    <p>📍 Lokasi: Jl. Habib Keling, Ds. Pringgacala, Indramayu</p>
  </div>

  <div class="box">
    <h2>Countdown Menuju Hari Bahagia 🎉</h2>
    <div id="countdown-box">
      <div id="countdown">Loading...</div>
    </div>
  </div>

  <div class="box">
    <h2>Galeri Prewedding 📸</h2>
    <div class="gallery">
      <img src="p.png" alt="Prewed 1">
      <img src="n.png" alt="Prewed 2">
      <img src="d.jpeg" alt="Prewed 3">
    </div>
  </div>

  <div class="box">
    <h2>Konfirmasi Kehadiran (RSVP)</h2>
    <form>
      <input type="text" placeholder="Nama Anda" required>
      <input type="email" placeholder="Email (opsional)">
      <textarea placeholder="Ucapan atau doa..." rows="4"></textarea>
      <button type="submit">Kirim</button>
    </form>
  </div>

  <div class="box">
    <h2>Lokasi Acara</h2>
    <p>📍 Jl. Gubernur suryo, Kabupaten Ngawi</p>
    <div style="text-align: center; margin-top: 1em;">
      <a href="https://www.google.com/maps?q=Jl.+Habib+Keling,+Ds.+Pringgacala,+Indramayu" target="_blank"
         style="display: inline-block; background-color: #f2c4a0; color: white; padding: 1em 2em; border-radius: 8px; text-decoration: none; font-weight: bold; box-shadow: 0 2px 6px rgba(0,0,0,0.1);">
        📍 Buka Lokasi di Google Maps
      </a>
    </div>
<script>
  document.addEventListener("DOMContentLoaded", function () {
    const targetDate = new Date(2025, 8, 6, 10, 0, 0).getTime(); // 6 Sept 2025, 10:00 WIB
    const countdown = document.getElementById("countdown");

    function updateCountdown() {
      const now = new Date().getTime();
      const distance = targetDate - now;

      if (distance <= 0) {
        countdown.innerHTML = "💍 Acara telah dimulai!";
        return;
      }

      const days = Math.floor(distance / (1000 * 60 * 60 * 24));
      const hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
      const minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
      const seconds = Math.floor((distance % (1000 * 60)) / 1000);

      countdown.innerHTML = `${days} hari ${hours} jam ${minutes} menit ${seconds} detik`;
    }

    updateCountdown();
    setInterval(updateCountdown, 1000);
  });
</script>
