<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Exclusive Content</title>

<style>
body {
  margin: 0;
  height: 100vh;
  font-family: Arial, sans-serif;
  background: linear-gradient(to right, #1e3c72, #2a5298);
  display: flex;
  justify-content: center;
  align-items: center;
  color: white;
  text-align: center;
}

.container {
  width: 100%;
  padding: 20px;
}

h1 {
  font-size: 28px;
  margin-bottom: 15px;
}

p {
  font-size: 18px;
  margin-bottom: 20px;
}

.btn {
  display: block;
  width: 85%;
  max-width: 320px;
  margin: 12px auto;
  padding: 15px;
  font-size: 18px;
  border-radius: 12px;
  text-decoration: none;
  color: white;
  transition: 0.3s;
}

.telegram {
  background: #0088cc;
}

.watch {
  background: #ff3d3d;
}

.btn:hover {
  transform: scale(1.05);
  opacity: 0.9;
}

/* Fake video box */
.video-box {
  width: 90%;
  max-width: 350px;
  height: 200px;
  background: black;
  margin: 20px auto;
  border-radius: 10px;
  position: relative;
  cursor: pointer;
}

.play-btn {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  font-size: 40px;
}
</style>

</head>

<body>

<div class="container">

  <h1>🔥 Exclusive Content 🔥</h1>

  <p>👉 আমাদের টেলিগ্রাম গ্রুপে জয়েন করতে নিচে ক্লিক করুন</p>
  <a href="https://t.me/+aTBIosXEwRtmZWM1" class="btn telegram">📲 Join Telegram</a>

  <p>🎬 ভিডিও দেখতে নিচে ক্লিক করুন</p>

  <!-- Fake Video -->
  <div class="video-box" onclick="goLink()">
    <div class="play-btn">▶️</div>
  </div>

  <a href="https://youtu.be/BN47qHJYk64?si=7WUG5aDlsnWoCX_X" class="btn watch">▶️ Watch Now</a>

</div>



</body>
</html>
