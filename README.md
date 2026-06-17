<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Minha Primeira Página Web</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <main class="container">
        <h1>Bem-vindo à minha primeira página!</h1>
        <p>Este é um projeto prático do curso da Alura para aprender HTML, CSS e JavaScript do zero.</p>
        
        <button id="botaoInterativo">Clique aqui!</button>
        <p id="mensagemFeed" class="escondido">Parabéns! Você gerou a sua primeira interação na web! 🎉</p>
    </main>

    <script src="app.js"></script>
</body>
</html>
/* Configurações Gerais de Estilo */
body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background-color: #f4f7f6;
    color: #333;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
}

.container {
    text-align: center;
    background-color: #ffffff;
    padding: 40px;
    border-radius: 1