# idkmee-linktree
!DOCTYPE html>
<html lang="pl">
<head>
  <meta charset="UTF-8">
  <title>IDKMEE333 – Linktree</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="overlay"></div>
  <div class="container">
    <h1>@idkmee333</h1>
    <p>🎧🎧🎧</p>

    <!-- Instagram Link z logo -->
    <a class="link" href="https://www.instagram.com/idkmee333?igsh=MTE0d2tpem5zYjAz&utm_source=qr" target="_blank">
      <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/95/Instagram_logo_2022.svg/1200px-Instagram_logo_2022.svg.png" alt="Instagram" class="icon"> idkmee333
    </a>

    <!-- SoundCloud Link z logo -->
    <a class="link" href="https://on.soundcloud.com/hPCHtxgkWKjmkZq0ty" target="_blank">
      <img src="https://img.favpng.com/7/25/13/computer-icons-soundcloud-logo-png-favpng-GTaCRmJZ8ZgEDvNXAZhqdKVst.jpg" class="icon"> idkmee
    </a>
  </div>
</body>
</html>
body {
  margin: 0;
  padding: 0;
  font-family: 'Arial', sans-serif;
  background: url('https://i.pinimg.com/736x/2b/57/74/2b57740271bbf07cb63a104b610b5ddc.jpg') no-repeat center center fixed;
  background-size: cover;
  height: 100vh;
  position: relative;
  color: white;
  text-shadow: 1px 1px 4px #000;
  display: flex;
  justify-content: center;
  align-items: center;
}

.overlay {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: rgba(0, 0, 0, 0.5);
  z-index: 0;
}

.container {
  position: relative;
  z-index: 1;
  text-align: center;
  padding: 30px;
  border-radius: 15px;
  background-color: rgba(0, 0, 0, 0.4);
}

h1 {
  font-size: 36px;
  margin-bottom: 10px;
}

p {
  font-size: 18px;
  margin-bottom: 20px;
}

.link {
  display: inline-flex;
  align-items: center;
  text-decoration: none;
  color: white;
  background: rgba(255, 255, 255, 0.1);
  padding: 12px 25px;
  margin: 12px;
  border-radius: 30px;
  border: 1px solid white;
  font-size: 18px;
  transition: all 0.3s ease;
  animation: pulse 2s infinite;
}

.link:hover {
  background: rgba(255, 255, 255, 0.3);
  transform: scale(1.05);
}

.icon {
  width: 24px;
  height: 24px;
  margin-right: 8px;
}

@keyframes pulse {
  0%, 100% {
    transform: scale(1);
    box-shadow: 0 0 10px rgba(255,255,255,0.5);
  }
  50% {
    transform: scale(1.02);
    box-shadow: 0 0 20px rgba(255,255,255,0.8);
  }
}