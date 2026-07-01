<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Minha Primeira Página</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <div class="conteudo">
        <h1>Olá, Mundo!</h1>
        <p>Este é o meu primeiro projeto web do zero.</p>
        
        <button id="meuBotao">Clique Aqui</button>
        
        <p id="mensagem"></p>
    </div>

    <script src="script.js"></script>
</body>
</html>
// 1. Selecionar o botão e o texto do HTML usando o ID
const botao = document.getElementById('meuBotao');
const mensagem = document.getElementById('mensagem');

// 2. Criar a função que diz o que vai acontecer no clique
function mostrarMensagem() {
    mensagem.textContent = "Excelente! Conseguiste fazer a tua primeira interação!";
    mensagem.style.color = "green";
}

// 3. Ativar o botão para que ele "escute" o clique do rato
botao.addEventListener('click', mostrarMensagem);
body {
    font-family: Arial, sans-serif;
    background-color: #eef2f3;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
}

.conteudo {
    text-align: center;
    background: white;
    padding: 40px;
    border-radius: 10px;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
}

button {
    background-color: #007bfc;
    color: white;
    border: none;
    padding: 10px 20px;
    font-size: 16px;
    border-radius: 5px;
    cursor: pointer;
}

button:hover {
    background-color: #0056b3;
}

#mensagem {
    margin-top: 20px;
    font-weight: bold;
}