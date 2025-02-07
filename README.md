<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>¿Quieres ser mi San Valentín, Karla?</title>
  <style>
    body {
      background: linear-gradient(45deg, #ff9a9e, #fbc2eb, #fffcab);
      font-family: 'Comic Sans MS', cursive, sans-serif;
      text-align: center;
      padding: 20px;
      color: #ff69b4;
    }
    h1 {
      font-size: 3rem;
      color: #ff4081;
    }
    .heart {
      font-size: 5rem;
      color: red;
      animation: beat 1s infinite alternate;
    }
    @keyframes beat {
      0% { transform: scale(1); }
      100% { transform: scale(1.2); }
    }
    .gif-container img {
      width: 250px;
      border-radius: 20px;
      margin: 10px;
    }
    .button {
      background-color: #ff69b4;
      color: white;
      border: none;
      padding: 15px 30px;
      font-size: 1.5rem;
      cursor: pointer;
      border-radius: 10px;
      transition: background-color 0.3s;
    }
    .button:hover {
      background-color: #ffa4d8;
    }
  </style>
</head>
<body>

  <h1>¿Quieres ser mi San Valentín, mi reina? ✨♥️</h1>
  <p class="heart">❤️❤️❤️</p>

  <p>Eres el corazón que hace latir mis días preciosa😘🥰</p>

  <div class="gif-container">
    <img src="https://media.giphy.com/media/26AHONQ79FdWZhAI0/giphy.gif" alt="GIF de amor divertido">
    <img src="https://media.giphy.com/media/l0MYt5jPR6QX5pnqM/giphy.gif" alt="Gatito enamorado">
    <img src="https://media.giphy.com/media/xUPGcEliCc7bETyfO8/giphy.gif" alt="Baile feliz">
  </div>

  <button class="button" onclick="mostrarRespuesta()">¡Claro que sí! 💕</button>

  <p id="respuesta" style="display: none; margin-top: 20px; font-size: 1.5rem;">¡Sabía que dirías que sí, mi Karla! ✨♥️</p>

  <script>
    function mostrarRespuesta() {
      document.getElementById('respuesta').style.display = 'block';
    }
  </script>
</body>
</html>
