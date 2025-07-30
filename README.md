<!DOCTYPE html>
<html lang="it">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>INDASTRIAL BUSSINES</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(to right, #0f2027, #203a43, #2c5364);
      color: #fff;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      text-align: center;
      animation: fadeIn 2s ease-in;
    }

    h1 {
      font-size: 4em;
      text-transform: uppercase;
      letter-spacing: 4px;
      background: linear-gradient(to right, #f9d423, #ff4e50);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      animation: glow 3s ease-in-out infinite;
    }

    @keyframes glow {
      0%, 100% {
        text-shadow: 0 0 10px rgba(255, 255, 255, 0.6);
      }
      50% {
        text-shadow: 0 0 20px rgba(255, 255, 255, 0.9);
      }
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    .subtitle {
      margin-top: 20px;
      font-size: 1.2em;
      color: #cccccc;
    }

    .social {
      margin-top: 10px;
      font-size: 1em;
      color: #aaaaaa;
      font-style: italic;
    }
  </style>
</head>
<body>
  <div>
    <h1>INDASTRIAL BUSSINES</h1>
    <p class="subtitle">Innovazione. Potenza. Futuro Industriale.</p>
    <p class="social">Seguiteci sui social col nome di <strong>indastrial_minecraft</strong></p>
  </div>
</body>
</html>
