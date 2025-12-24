# Christmas-card-
<!DOCTYPE html>
<html lang="en">
<head>
Â  Â  <meta charset="UTF-8">
Â  Â  <meta name="viewport" content="width=device-width, initial-scale=1.0">
Â  Â  <title>Merry Christmas!</title>
Â  Â  <style>
Â  Â  Â  Â  @import url('https://fonts.googleapis.com/css2?family=Mountains+of+Christmas:wght@700&family=Playfair+Display:ital,wght@0,400;1,700&display=swap');


Â  Â  Â  Â  body {
Â  Â  Â  Â  Â  Â  margin: 0;
Â  Â  Â  Â  Â  Â  padding: 0;
Â  Â  Â  Â  Â  Â  background: radial-gradient(circle, #200122, #6f0000); /* Deep festive red/purple */
Â  Â  Â  Â  Â  Â  height: 100vh;
Â  Â  Â  Â  Â  Â  display: flex;
Â  Â  Â  Â  Â  Â  justify-content: center;
Â  Â  Â  Â  Â  Â  align-items: center;
Â  Â  Â  Â  Â  Â  color: white;
Â  Â  Â  Â  Â  Â  font-family: 'Playfair Display', serif;
Â  Â  Â  Â  Â  Â  overflow: hidden;
Â  Â  Â  Â  }


Â  Â  Â  Â  /* Snowflake Background */
Â  Â  Â  Â  .snow {
Â  Â  Â  Â  Â  Â  position: absolute;
Â  Â  Â  Â  Â  Â  top: 0; left: 0;
Â  Â  Â  Â  Â  Â  width: 100%; height: 100%;
Â  Â  Â  Â  Â  Â  pointer-events: none;
Â  Â  Â  Â  Â  Â  z-index: 1;
Â  Â  Â  Â  }


Â  Â  Â  Â  .container {
Â  Â  Â  Â  Â  Â  text-align: center;
Â  Â  Â  Â  Â  Â  z-index: 2;
Â  Â  Â  Â  Â  Â  padding: 20px;
Â  Â  Â  Â  Â  Â  animation: fadeIn 2s ease-in;
Â  Â  Â  Â  }


Â  Â  Â  Â  h1 {
Â  Â  Â  Â  Â  Â  font-family: 'Mountains of Christmas', cursive;
Â  Â  Â  Â  Â  Â  font-size: 4rem;
Â  Â  Â  Â  Â  Â  margin-bottom: 10px;
Â  Â  Â  Â  Â  Â  color: #FFD700; /* Gold */
Â  Â  Â  Â  Â  Â  text-shadow: 0 0 20px rgba(255, 215, 0, 0.6);
Â  Â  Â  Â  }


Â  Â  Â  Â  .name {
Â  Â  Â  Â  Â  Â  font-size: 2.5rem;
Â  Â  Â  Â  Â  Â  font-style: italic;
Â  Â  Â  Â  Â  Â  display: block;
Â  Â  Â  Â  Â  Â  margin-top: 10px;
Â  Â  Â  Â  Â  Â  color: #ffffff;
Â  Â  Â  Â  }


Â  Â  Â  Â  .message {
Â  Â  Â  Â  Â  Â  font-size: 1.2rem;
Â  Â  Â  Â  Â  Â  margin-top: 20px;
Â  Â  Â  Â  Â  Â  letter-spacing: 2px;
Â  Â  Â  Â  Â  Â  opacity: 0.8;
Â  Â  Â  Â  }


Â  Â  Â  Â  @keyframes fadeIn {
Â  Â  Â  Â  Â  Â  from { opacity: 0; transform: translateY(20px); }
Â  Â  Â  Â  Â  Â  to { opacity: 1; transform: translateY(0); }
Â  Â  Â  Â  }


Â  Â  Â  Â  /* Simple CSS Snowflakes */
Â  Â  Â  Â  .snowflake {
Â  Â  Â  Â  Â  Â  position: fixed;
Â  Â  Â  Â  Â  Â  top: -10%;
Â  Â  Â  Â  Â  Â  color: white;
Â  Â  Â  Â  Â  Â  font-size: 1em;
Â  Â  Â  Â  Â  Â  user-select: none;
Â  Â  Â  Â  Â  Â  z-index: 1;
Â  Â  Â  Â  Â  Â  animation: fall linear infinite;
Â  Â  Â  Â  }


Â  Â  Â  Â  @keyframes fall {
Â  Â  Â  Â  Â  Â  to { transform: translateY(110vh); }
Â  Â  Â  Â  }
Â  Â  </style>
</head>
<body>


Â  Â  <div class="container">
Â  Â  Â  Â  <h1>Merry Christmas,</h1>
Â  Â  Â  Â  <span class="name">cutie bachi!</span>
Â  Â  Â  Â  <p class="message">Wishing you a season full of magic and joy.</p>
Â  Â  </div>


Â  Â  <script>
Â  Â  Â  Â  function createSnowflake() {
Â  Â  Â  Â  Â  Â  const snowflake = document.createElement('div');
Â  Â  Â  Â  Â  Â  snowflake.innerHTML = 'â„';
Â  Â  Â  Â  Â  Â  snowflake.classList.add('snowflake');
Â  Â  Â  Â  Â  Â  snowflake.style.left = Math.random() * 100 + 'vw';
Â  Â  Â  Â  Â  Â  snowflake.style.animationDuration = Math.random() * 3 + 2 + 's';
Â  Â  Â  Â  Â  Â  snowflake.style.opacity = Math.random();
Â  Â  Â  Â  Â  Â  document.body.appendChild(snowflake);


Â  Â  Â  Â  Â  Â  setTimeout(() => {
Â  Â  Â  Â  Â  Â  Â  Â  snowflake.remove();
Â  Â  Â  Â  Â  Â  }, 5000);
Â  Â  Â  Â  }
Â  Â  Â  Â  setInterval(createSnowflake, 100);
Â  Â  </script>
</body>
</html>
