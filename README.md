# xcan_edit.github

<!DOCTYPE html>
<html lang="tr">
<head>
<meta charset="UTF-8">
<title>xcanedit Shorts Feed</title>

<style>
body {
  margin: 0;
  background: black;
  overflow: hidden;
  font-family: Arial;
}

/* TOP LOGO */
.logo {
  position: fixed;
  top: 10px;
  left: 15px;
  color: #00ffcc;
  font-weight: bold;
  z-index: 10;
}

/* SCROLL AREA */
.container {
  height: 100vh;
  overflow-y: scroll;
  scroll-snap-type: y mandatory;
}

/* VIDEO CARD */
.video {
  height: 100vh;
  scroll-snap-align: start;
  position: relative;
}

iframe {
  width: 100%;
  height: 100%;
  border: none;
}

/* INFO OVERLAY */
.info {
  position: absolute;
  bottom: 40px;
  left: 20px;
  color: white;
}

.info h2 {
  margin: 0;
  font-size: 18px;
}

.info p {
  font-size: 13px;
  color: #ccc;
}

.btn {
  display: inline-block;
  margin-top: 8px;
  padding: 6px 10px;
  background: #00ffcc;
  color: black;
  text-decoration: none;
  border-radius: 6px;
  font-weight: bold;
}
</style>

</head>

<body>

<div class="logo">xcanedit 🔥</div>

<div class="container">

  <!-- VIDEO 1 -->
  <div class="video">
    <iframe src="https://www.youtube.com/embed/r81mMI-hwr8?autoplay=1&mute=1"></iframe>
    <div class="info">
      <h2>Yayın Kesit Edit</h2>
      <p>Viral an 🔥</p>
      <a class="btn" href="https://youtube.com/@xcan_edit?si=hS1xLGAkp8qD9Ejm" target="_blank">Kanala Git</a>
    </div>
  </div>

  <!-- VIDEO 2 -->
  <div class="video">
    <iframe src="https://www.youtube.com/embed/dQw4w9WgXcQ?autoplay=1&mute=1"></iframe>
    <div class="info">
      <h2>Trend Edit</h2>
      <p>Komik kesit 🔥</p>
      <a class="btn" href="https://youtube.com/@xcan_edit?si=hS1xLGAkp8qD9Ejm" target="_blank">Kanala Git</a>
    </div>
  </div>

  <!-- VIDEO 3 -->
  <div class="video">
    <iframe src="https://www.youtube.com/embed/r81mMI-hwr8?autoplay=1&mute=1"></iframe>
    <div class="info">
      <h2>Yeni Edit</h2>
      <p>Viral shorts 🔥</p>
      <a class="btn" href="https://youtube.com/@xcan_edit?si=hS1xLGAkp8qD9Ejm" target="_blank">Kanala Git</a>
    </div>
  </div>

</div>

</body>
</html>
