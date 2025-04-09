<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <title>Undangan Pernikahan Hermawan & Sinta</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Great+Vibes&family=Open+Sans&display=swap');

    html, body {
      margin: 0;
      padding: 0;
      height: 100%;
      font-family: 'Open Sans', sans-serif;
      overflow: hidden;
    }

    body {
      background: url('https://images.unsplash.com/photo-1523726491678-bf852e717f6a?auto=format&fit=crop&w=1500&q=80') no-repeat center center fixed;
      background-size: cover;
      display: flex;
      justify-content: center;
      align-items: center;
    }

    .container {
      background: rgba(255, 255, 255, 0.9);
      padding: 30px;
      max-width: 600px;
      border-radius: 20px;
      box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
      animation: fadeIn 2s ease-in-out;
      text-align: center;
    }

    h1 {
      font-family: 'Great Vibes', cursive;
      color: #d63384;
      font-size: 48px;
      margin-bottom: 10px;
    }

    .date, .location, .rsvp {
      font-size: 18px;
      margin: 15px 0;
    }

    .map-placeholder {
      font-style: italic;
      color: #555;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(30px); }
      to { opacity: 1; transform: translateY(0); }
    }

    audio {
      display: none;
    }
  </style>
</head>
<body>

  <div class="container">
    <h1>Hermawan & Sinta</h1>
    <p>Dengan penuh cinta, kami mengundang Anda hadir dalam momen istimewa kami</p>

    <div class="date">
      <strong>Tanggal:</strong><br>
      Rabu, 16 April 2025<br>
      Pukul 10.00 WIB - selesai
    </div>

    <div class="location">
      <strong>Tempat:</strong><br>
      Perum Oma Indah Blok F5 No. 5
    </div>

    <div class="map-placeholder">
      Lokasi Google Maps akan ditambahkan
    </div>

    <div class="rsvp">
      <strong>RSVP:</strong><br>
      0851-7545-9791 (WA)
    </div>
  </div>

  <audio autoplay loop>
    <source src="https://www.bensound.com/bensound-music/bensound-love.mp3" type="audio/mpeg">
    Your browser does not support the audio element.
  </audio>

</body>
</html>
