<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <title>Projeto Meio Ambiente</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background-color: #f4f4f4;
        }

        header {
            background-color: #2e8b57;
            color: white;
            padding: 20px;
            text-align: center;
        }

        nav {
            background-color: #1f5e3b;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }

        section {
            padding: 20px;
        }

        .card {
            background-color: white;
            padding: 15px;
            margin: 15px 0;
            border-radius: 8px;
            box-shadow: 0 0 5px rgba(0,0,0,0.1);
        }

        footer {
            background-color: #2e8b57;
            color: white;
            text-align: center;
            padding: 10px;
            margin-top: 20px;
        }

        button {
            background-color: #2e8b57;
            color: white;
            border: none;
            padding: 10px;
            cursor: pointer;
            border-radius: 5px;
        }

        button:hover {
            background-color: #1f5e3b;
        }
    </style>
</head>
<body>

<header>
    <h1>Projeto: Preservação do Meio Ambiente</h1>
    <p>Trabalho Escolar</p>
</header>

<nav>
    <a href="#sobre">Sobre</a>
    <a href="#importancia">Importância</a>
    <a href="#contato">Contato</a>
</nav>

<section id="sobre">
    <div class="card">
        <h2>Sobre o Meio Ambiente</h2>
        <p>O meio ambiente é o conjunto de elementos naturais que permitem a vida na Terra, como água, ar, solo e biodiversidade.</p>
    </div>
</section>

<section id="importancia">
    <div class="card">
        <h2>Por que preservar?</h2>
        <p>Preservar o meio ambiente é essencial para garantir qualidade de vida para as futuras gerações.</p>
        <button onclick="mostrarMensagem()">Clique para saber mais</button>
    </div>
</section>

<section id="contato">
    <div class="card">
        <h2>Contato</h2>
        <p>Email: aluno@escola.com</p>
    </div>
</section>

<footer>
    <p>© 2026 - Trabalho Escolar</p>
</footer>

<script>
    function mostrarMensagem() {
        alert("Preservar o meio ambiente é cuidar do nosso futuro!");
    }
</script>

</body>
</html>
