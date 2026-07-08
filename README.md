<!DOCTYPE html>
<html lang="pt-br">
<link rel="stylesheet" href="style.css">
<head>
    <meta charset="UTF-8">
    <title>Sobre Mim</title>
</head>
<body>
    <div class="container">

        <img src="https://via.placeholder.com/150" alt="Minha foto" class="foto-perfil">
        <h1>Ryan Hugo Viana de Oliveira</h1>
        <p>Tenho 20 anos, curso Análise e Desenvolvimento de Sistemas.</p>

        <h2>Minhas habilidades</h2>
        <ul>
            <li>HTML</li>
            <li>CSS</li>
            <li>Lógica de programação</li>
        </ul>

        <a href="https://github.com/ryanhugo070" class="botao-github">Meu GitHub</a>

    </div>
</body>

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Segoe UI', Arial, sans-serif;
    background-color: #f4f4f9;
    display: flex;
    justify-content: center;
    padding: 60px 20px;
}

.container {
    background-color: #ffffff;
    max-width: 500px;
    width: 100%;
    padding: 40px;
    border-radius: 12px;
    box-shadow: 0 4px 20px rgba(0, 0, 0, 0.08);
    text-align: center;
}

.foto-perfil {
    width: 130px;
    height: 130px;
    border-radius: 50%;
    object-fit: cover;
    margin-bottom: 20px;
    border: 4px solid #4a56e2;
}

h1 {
    color: #222;
    font-size: 24px;
    margin-bottom: 10px;
}

p {
    color: #555;
    line-height: 1.6;
    margin-bottom: 25px;
}

h2 {
    color: #333;
    font-size: 18px;
    margin-bottom: 12px;
    text-align: left;
}

ul {
    list-style: none;
    text-align: left;
    margin-bottom: 30px;
}

ul li {
    background-color: #f0f1fb;
    color: #4a56e2;
    padding: 8px 14px;
    border-radius: 6px;
    margin-bottom: 8px;
    font-weight: 500;
}

.botao-github {
    display: inline-block;
    background-color: #4a56e2;
    color: white;
    text-decoration: none;
    padding: 12px 28px;
    border-radius: 8px;
    font-weight: 600;
    transition: background-color 0.2s;
}

.botao-github:hover {
    background-color: #3844c4;
}
@media (max-width: 600px) {
    body {
        padding: 30px 15px;
    }

    .container {
        padding: 25px;
    }

    h1 {
        font-size: 20px;
    }
}
