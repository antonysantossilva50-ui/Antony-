<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>PlayZone</title>
<style>
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #090018;
  color: white;
  text-align: center;
}
header {
  background: #16002e;
  padding: 25px;
  border-bottom: 3px solid #00ffff;
}
h1 {
  color: #00ffff;
  font-size: 38px;
}
main { padding: 20px; }
.jogo {
  background: #1d1035;
  border: 2px solid #a100ff;
  border-radius: 15px;
  padding: 20px;
  margin: 18px auto;
  max-width: 350px;
}
button {
  background: #00ffff;
  color: #090018;
  border: none;
  padding: 12px 20px;
  border-radius: 8px;
  font-weight: bold;
}
footer {
  padding: 20px;
  color: #aaa;
}
</style>
</head>
<body>
<header>
  <h1>🎮 PlayZone</h1>
  <p>Seu universo gamer começa aqui!</p>
</header>
<main>
  <h2>🔥 Jogos em destaque</h2>
  <div class="jogo">
    <h3>🏴‍☠️ Blox Fruits</h3>
    <p>Aventure-se, explore e fique mais forte!</p>
    <button onclick="window.open('https://www.roblox.com/', '_blank')">Jogar no Roblox</button>
  </div>
  <div class="jogo">
    <h3>🔫 Free Fire</h3>
    <p>Entre na batalha e mostre sua habilidade!</p>
    <button onclick="window.open('https://ff.garena.com/', '_blank')">Site do Free Fire</button>
  </div>
</main>
<footer>© 2026 PlayZone — Feito para gamers</footer>
</body>
</html>
