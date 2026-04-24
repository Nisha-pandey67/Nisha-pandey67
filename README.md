<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Nisha Kumari | Software Developer</title>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Arial;
}

body {
  background: radial-gradient(circle at top, #0f2027, #000);
  color: white;
  overflow-x: hidden;
}

/* floating glow animation background */
.glow {
  position: absolute;
  width: 400px;
  height: 400px;
  background: #00c2ff;
  filter: blur(120px);
  opacity: 0.2;
  animation: move 10s infinite alternate;
}

@keyframes move {
  from { transform: translate(0,0); }
  to { transform: translate(200px,150px); }
}

header {
  text-align: center;
  padding: 100px 20px 50px;
}

h1 {
  font-size: 55px;
  animation: fadeIn 2s ease-in-out;
}

@keyframes fadeIn {
  from {opacity:0; transform: translateY(-20px);}
  to {opacity:1; transform: translateY(0);}
}

.subtitle {
  font-size: 18px;
  opacity: 0.8;
  margin-top: 10px;
  animation: fadeIn 2.5s ease-in-out;
}

/* typing effect */
.typing {
  display: inline-block;
  border-right: 2px solid white;
  white-space: nowrap;
  overflow: hidden;
  animation: typing 4s steps(40) infinite alternate;
}

@keyframes typing {
  from { width: 0; }
  to { width: 100%; }
}

.container {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
  width: 80%;
  margin: auto;
  padding-bottom: 50px;
}

.card {
  background: rgba(255,255,255,0.06);
  border: 1px solid rgba(255,255,255,0.1);
  padding: 25px;
  border-radius: 15px;
  backdrop-filter: blur(10px);
  transition: 0.4s;
  transform: translateY(20px);
  animation: slideUp 1s forwards;
}

.card:hover {
  transform: scale(1.05);
  border: 1px solid #00c2ff;
}

@keyframes slideUp {
  to { transform: translateY(0); }
}

footer {
  text-align: center;
  padding: 30px;
  opacity: 0.7;
  font-size: 14px;
}
</style>
</head>

<body>

<div class="glow"></div>

<header>
  <h1>Nisha Kumari</h1>
  <p class="subtitle typing">Software Developer | CSE Final Year Student | Job Ready</p>
</header>

<div class="container">

  <div class="card">
    <h2>👩‍💻 About Me</h2>
    <p>CSE final year student focused on building real-world software solutions using IoT and Machine Learning.</p>
  </div>

  <div class="card">
    <h2>🚀 Projects</h2>
    <p>
      🔥 Fire Detection System (IoT + GSM)<br><br>
      🧠 Fake Review Detector (NLP + ML Extension)
    </p>
  </div>

  <div class="card">
    <h2>🛠 Skills</h2>
    <p>
      HTML, CSS, JavaScript<br>
      Python<br>
      IoT (Arduino + Sensors)
    </p>
  </div>

  <div class="card">
    <h2>📫 Contact</h2>
    <p>
      Email: pandeynisha797@gmail.com<br>
      GitHub: Nisha-pandey67<br>
      LinkedIn: your-link
    </p>
  </div>

</div>

<footer>
  © 2026 Nisha Kumari | Job-Ready Developer Portfolio
</footer>

</body>
</html>
