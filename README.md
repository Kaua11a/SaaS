<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<title>K-Flow AI | Dashboard</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #000;
  color: #fff;
  display: flex;
}
.sidebar {
  width: 240px;
  background: #111;
  padding: 20px;
  height: 100vh;
}
.sidebar h2 {
  color: gold;
  text-align: center;
}
.sidebar a {
  display: block;
  color: #fff;
  text-decoration: none;
  margin: 15px 0;
}
.sidebar a:hover {
  color: gold;
}
.main {
  flex: 1;
  padding: 30px;
}
.card {
  background: #111;
  padding: 20px;
  border-radius: 8px;
  margin-bottom: 20px;
}
.btn {
  background: gold;
  color: #000;
  padding: 10px 20px;
  border: none;
  cursor: pointer;
  font-weight: bold;
}
input, select, textarea {
  width: 100%;
  padding: 10px;
  margin-top: 10px;
  background: #000;
  color: #fff;
  border: 1px solid #333;
}
</style>
</head>

<body>

<div class="sidebar">
  <h2>K-Flow AI</h2>
  <a href="#">📊 Visão Geral</a>
  <a href="#">✍️ Conteúdo</a>
  <a href="#">📢 Anúncios</a>
  <a href="#">💬 Atendimento IA</a>
  <a href="#">🧠 Estratégia</a>
  <a href="#">📁 Histórico</a>
  <a href="#">⚙️ Configurações</a>
</div>

<div class="main">
  <h1>Gerador de Conteúdo com IA</h1>

  <div class="card">
    <label>Nicho</label>
    <input type="text" placeholder="Ex: Infoprodutor">

    <label>Plataforma</label>
    <select>
      <option>Instagram</option>
      <option>TikTok</option>
      <option>Reels</option>
    </select>

    <label>Objetivo</label>
    <select>
      <option>Engajamento</option>
      <option>Venda</option>
      <option>Autoridade</option>
    </select>

    <button class="btn">Gerar Conteúdo</button>
  </div>

  <div class="card">
    <h3>Resultado da IA</h3>
    <textarea rows="6">Seu conteúdo aparecerá aqui...</textarea>
  </div>
</div>

</body>
</html>
