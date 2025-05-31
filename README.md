
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Happy Birthday Rhushitha!</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background: #1b1b2f;
      color: #fff;
      font-family: 'Georgia', serif;
      overflow: hidden;
    }

    .container {
      text-align: center;
      padding-top: 120px;
      z-index: 2;
      position: relative;
      animation: fadeIn 2s ease-in;
    }

    h1 {
      font-size: 3em;
      color: #f7d9d9;
    }

    p {
      font-size: 1.3em;
      max-width: 600px;
      margin: 10px auto;
      line-height: 1.6;
    }

    .moon {
      position: absolute;
      top: 30px;
      right: 40px;
      width: 100px;
      height: 100px;
      background: radial-gradient(circle, #fff 40%, #ccc 70%, #aaa 100%);
      border-radius: 50%;
      box-shadow: 0 0 40px rgba(255, 255, 255, 0.3);
    }

    .signature {
      position: absolute;
      bottom: 50px;
      width: 100%;
      text-align: center;
      font-size: 1.2em;
      color: #cccccc;
      font-style: italic;
    }

    .petal {
      position: absolute;
      width: 12px;
      height: 12px;
      background: #f7d9d9;
      border-radius: 50%;
      opacity: 0.7;
      animation: fall 10s linear infinite;
    }

    @keyframes fall {
      0% {
        transform: translateY(-10vh) rotate(0deg);
        opacity: 0;
      }
      50% {
        opacity: 0.9;
      }
      100% {
        transform: translateY(110vh) rotate(360deg);
        opacity: 0;
      }
    }

    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }
  </style>
</head>
<body>

  <div class="moon" title="Shining bright like the moon 🌙"></div>

  <div class="container">
    <h1>Happy Birthday Rhushitha 🌙</h1>
    <p>Wishing you a day filled with smiles and surprises,</p>
    <p>just like the bright smile you’ll bring as an amazing dentist! 🦷🪥</p>
    <p>Keep shining like the moon and spreading joy wherever you go. 🌙✨</p>
  </div>
  <div class="signature">
    — Your friend, Sid 👋
  </div>

  <script>
    // Create soft floating petals
    for (let i = 0; i < 40; i++) {
      const petal = document.createElement('div');
      petal.className = 'petal';
      petal.style.left = Math.random() * 100 + 'vw';
      petal.style.animationDuration = (5 + Math.random() * 10) + 's';
      petal.style.animationDelay = (Math.random() * 5) + 's';
      document.body.appendChild(petal);
    }
  </script>

</body>
</html>
