<!DOCTYPE html>
<html lang="uk">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Garro_ine</title>
  <style>
    body {
      margin: 0;
      font-family: 'Orbitron', sans-serif;
      background: radial-gradient(circle at center, #000000 60%, #0b0b0b 100%);
      color: #fff;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      min-height: 100vh;
      overflow: hidden;
    }

    .avatar {
      width: 180px;
      height: 180px;
      border-radius: 50%;
      border: 3px solid red;
      box-shadow: 0 0 25px red;
      margin-bottom: 25px;
    }

    h1 {
      font-size: 2.8rem;
      color: #ff1a1a;
      text-shadow: 0 0 15px red, 0 0 30px #ff0000;
      margin: 0 0 25px 0;
    }

    .links a {
      display: block;
      width: 220px;
      margin: 10px;
      padding: 12px 0;
      text-align: center;
      text-decoration: none;
      color: white;
      border: 2px solid #ff1a1a;
      border-radius: 8px;
      box-shadow: 0 0 15px #ff0000;
      transition: all 0.3s ease;
      background: rgba(20, 0, 0, 0.4);
    }

    .links a:hover {
      background: #ff1a1a;
      color: #000;
      box-shadow: 0 0 30px #ff0000, 0 0 60px #ff0000;
      transform: scale(1.05);
    }

    .neon-line {
      position: absolute;
      width: 200%;
      height: 2px;
      background: linear-gradient(90deg, transparent, red, transparent);
      animation: move 3s linear infinite;
      opacity: 0.4;
    }

    .neon-line.top { top: 15%; }
    .neon-line.bottom { bottom: 15%; animation-delay: 1.5s; }

    @keyframes move {
      from { left: -100%; }
      to { left: 100%; }
    }
  </style>
</head>
<body>
  <div class="neon-line top"></div>
  <div class="neon-line bottom"></div>

  <img src="A_digital_graphic_design_profile_banner_features_t.png" alt="Garro_ine Avatar" class="avatar">
  <h1>Garro_ine</h1>

  <div class="links">
    <a href="https://youtube.com/@garro_ine" target="_blank">🎥 YouTube</a>
    <a href="https://twitch.tv/garro_ine" target="_blank">🎮 Twitch</a>
    <a href="https://discord.gg/prCGXQ8M2P" target="_blank">💬 Discord</a>
    <a href="https://donatello.to/Garro_ine" target="_blank">💸 Donatello</a>
  </div>
</body>
</html>
