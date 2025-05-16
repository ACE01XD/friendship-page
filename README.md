<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Best Friends Forever 💖</title>
  <link rel="stylesheet" href="style.css"/>
</head>
<body>
  <div class="container">
    <img src="https://i.imgur.com/BOZ3Q1V.png" alt="Cute friends" class="cute-img" />
    <h1>Will you be my Best Friend Forever? 🥺💞</h1>
    <p>You always make my day better. Let's be BFFs forever! 😄</p>
    <div class="buttons">
      <button onclick="reply('yes')">Yes! 💖</button>
      <button onclick="reply('always')">Always! 🌟</button>
    </div>
    <p id="response"></p>
  </div>

  <script>
    function reply(answer) {
      document.getElementById('response').innerText = `Yay! You said "${answer}" 😊💫`;
    }
  </script>
</body>
</html>
