<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Loja de Roupas</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
        }
        nav {
            background-color: #444;
            text-align: center;
            padding: 10px;
        }
        nav a {
            color: #fff;
            margin: 0 15px;
            text-decoration: none;
        }
        section {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 20px;
        }
        .produto {
            background-color: #fff;
            margin: 15px;
            padding: 15px;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
            width: 250px;
            text-align: center;
        }
        .produto img {
            width: 100%;
            height: auto;
        }
        .produto h3 {
            margin: 10px 0;
            font-size: 18px;
        }
        .produto p {
            color: #666;
        }
        .produto a {
            background-color: #28a745;
            color: #fff;
            padding: 10px 15px;
            text-decoration: none;
            border-radius: 5px;
            display: inline-block;
            margin-top: 10px;
        }
        .produto a:hover {
            background-color: #218838;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
        }
    </style>
</head>
<body>

<header>
    <h1>Loja de Roupas</h1>
</header>

<nav>
    <a href="#">Início</a>
    <a href="#">Masculino</a>
    <a href="#">Feminino</a>
    <a href="#">Acessórios</a>
    <a href="#">Contato</a>
</nav>

<section>
    <div class="produto">
        <img src="https://via.placeholder.com/250x300" alt="Camisa Masculina">
        <h3>Camisa Masculina</h3>
        <p>R$ 49,90</p>
        <a href="link-para-compra-1">Comprar</a>
    </div>

    <div class="produto">
        <img src="https://via.placeholder.com/250x300" alt="Vestido Feminino">
        <h3>Vestido Feminino</h3>
        <p>R$ 89,90</p>
        <a href="link-para-compra-2">Comprar</a>
    </div>

    <div class="produto">
        <img src="https://via.placeholder.com/250x300" alt="Jaqueta Unissex">
        <h3>Jaqueta Unissex</h3>
        <p>R$ 129,90</p>
        <a href="link-para-compra-3">Comprar</a>
    </div>

    <div class="produto">
        <img src="https://via.placeholder.com/250x300" alt="Tênis Esportivo">
        <h3>Tênis Esportivo</h3>
        <p>R$ 199,90</p>
        <a href="link-para-compra-4">Comprar</a>
    </div>
</section>

<footer>
    <p>&copy; 2024 Loja de Roupas. Todos os direitos reservados.</p>
</footer>

</body>
</html>
