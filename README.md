<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <title>Meu Site</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      font-family: Arial, sans-serif;
    }

    body {
      background: linear-gradient(135deg, #0f0f0f, #1a1a2e);
      color: white;
      text-align: center;
    }

    header {
      padding: 40px;
      font-size: 28px;
      font-weight: bold;
    }

    .box {
      background: rgba(255,255,255,0.05);
      margin: 30px auto;
      padding: 30px;
      width: 80%;
      max-width: 500px;
      border-radius: 15px;
      backdrop-filter: blur(10px);
      box-shadow: 0 0 20px rgba(0,0,0,0.5);
    }

    button {
      margin-top: 20px;
      padding: 12px 25px;
      border: none;
      border-radius: 10px;
      background: #5865F2;
      color: white;
      font-size: 16px;
      cursor: pointer;
      transition: 0.3s;
    }

    button:hover {
      background: #404eed;
      transform: scale(1.05);
    }

    footer {
      margin-top: 40px;
      opacity: 0.6;
      font-size: 14px;
    }
  </style>
</head>

<body>

  <header>
    🚀 Meu Site Insano
  </header>

  <div class="box">
    <h2>Bem-vindo</h2>
    <p>Esse site foi feito só no CTRL+C CTRL+V 😎</p>

    <button onclick="clicou()">Clica aqui</button>
  </div>

  <footer>
    feito por você 🔥
  </footer>

  <script>
    function clicou() {
      alert("tu clicou kkkkk 👀");
    }
  </script>

</body>
</html>
