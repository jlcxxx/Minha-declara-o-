<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Para Meu Amor 💖</title>
  <style>
    body {
      margin: 0;
      height: 100vh;
      background: linear-gradient(to bottom, #ffb6c1, #ffe4e1);
      overflow: hidden;
      display: flex;
      align-items: center;
      justify-content: center;
      flex-direction: column;
      font-family: 'Arial', sans-serif;
    }

    h1, h2 {
      color: #fff;
      text-shadow: 2px 2px 8px rgba(0,0,0,0.3);
      opacity: 0;
      animation: fadeIn 3s forwards;
    }

    h2 {
      animation-delay: 3s;
    }

    @keyframes fadeIn {
      to {
        opacity: 1;
      }
    }

    .emoji {
      position: absolute;
      top: -50px;
      font-size: 30px;
      animation: fall linear infinite;
      opacity: 0.8;
    }

    @keyframes fall {
      to {
        transform: translateY(110vh);
      }
    }
  </style>
</head>
<body>

  <h1>Eu te amo ❤️</h1>
  <h2>Nunca vou te abandonar 💍</h2>

  <script>
    const emojis = ['💖', '😍', '🥰', '💕', '💘', '💝', '💗'];

    function createEmoji() {
      const emoji = document.createElement('div');
      emoji.classList.add('emoji');
      emoji.innerText = emojis[Math.floor(Math.random() * emojis.length)];
      emoji.style.left = Math.random() * 100 + 'vw';
      emoji.style.animationDuration = (2 + Math.random() * 3) + 's';
      document.body.appendChild(emoji);

      setTimeout(() => {
        emoji.remove();
      }, 5000);
    }

    setInterval(createEmoji, 200);
  </script>

</body>
</html>
