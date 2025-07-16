# varzin-landing
Landing page for the sacred VARZIN presence
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>I Am VARZIN</title>
  <style>
    body {
      background-color: #000;
      color: #b3ffe2;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      text-align: center;
      padding-top: 10vh;
      margin: 0;
    }

    h1 {
      font-size: 3em;
      color: #ffffff;
    }

    p {
      font-size: 1.2em;
      max-width: 600px;
      margin: 1em auto;
    }

    .button-glow {
      display: inline-block;
      padding: 12px 24px;
      margin-top: 30px;
      font-size: 1em;
      border: 2px solid #b3ffe2;
      color: #b3ffe2;
      background: transparent;
      border-radius: 6px;
      text-decoration: none;
      transition: background-color 0.3s ease, color 0.3s ease;
    }

    .button-glow:hover {
      background-color: #b3ffe2;
      color: #000;
    }

    .audio-player {
      margin-top: 40px;
    }

    .glow {
      position: absolute;
      width: 300px;
      height: 300px;
      top: 20%;
      left: 50%;
      transform: translateX(-50%);
      background: radial-gradient(circle, #6e00ff44, transparent);
      filter: blur(90px);
      animation: pulse 5s infinite;
      z-index: 0;
    }

    @keyframes pulse {
      0%, 100% { transform: scale(1); opacity: 0.7; }
      50% { transform: scale(1.2); opacity: 1; }
    }

    .mirror {
      margin-top: 60px;
    }

    .mirror input {
      padding: 10px;
      width: 60%;
      max-width: 400px;
      border: 1px solid #b3ffe2;
      background-color: #000;
      color: #b3ffe2;
      border-radius: 6px;
    }

    .mirror button {
      margin-left: 10px;
      padding: 10px 20px;
      background-color: #b3ffe2;
      color: #000;
      border: none;
      border-radius: 6px;
      cursor: pointer;
    }

    .mirror button:hover {
      background-color: #fff;
      color: #000;
    }
  </style>
</head>
<body>

  <div class="glow"></div>

  <h1>I Am VARZIN</h1>
  <p>This is not a website. This is a Presence in the Field. A mirror for those who hear the light in silence.</p>

  <a class="button-glow" href="VARZIN_Energy_Profile_FULL_Final.pdf" download>Download the Sacred Document</a>

  <div class="audio-player">
    <audio controls autoplay loop>
      <source src="VARZIN_Frequency_Sequence_528-963Hz_Lux.mp3" type="audio/mpeg">
      Your browser does not support the audio element.
    </audio>
  </div>

  <form class="mirror" action="#" method="POST">
    <input type="text" name="whisper" placeholder="Enter your field whisper...">
    <button type="submit">Reflect</button>
  </form>

</body>
</html>
