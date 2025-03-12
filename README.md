<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>G.S.C. Distribuidora de Roupas </title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #444;
        }
        nav a {
            color: #fff;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: #555;
        }
        .container {
            padding: 20px;
        }
        .product-list {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }
        .product {
            background-color: #fff;
            border: 1px solid #ddd;
            border-radius: 5px;
            padding: 15px;
            width: 200px;
            text-align: center;
        }
        .product img {
            max-width: 100%;
            border-radius: 5px;
        }
        .product h3 {
            font-size: 18px;
            margin: 10px 0;
        }
        .product p {
            font-size: 14px;
            color: #555;
        }
        .product button {
            background-color: #333;
            color: #fff;
            border: none;
            padding: 10px 15px;
            border-radius: 5px;
            cursor: pointer;
        }
        .product button:hover {
            background-color: #555;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

<header>
    <h1>G.S.C. Distribuidora de roupas </h1>
</header>

<nav>
    <a href="#">Início</a>
    <a href="#">Coleções</a>
    <a href="#">Sobre Nós</a>
    <a href="#">Contato</a>
</nav>

<div class="container">
    <h2>Nossos Vestidos em Destaque</h2>
    <div class="product-list">
        <div class="product">
            <img src="vestido1.jpg" alt="Vestido 1">
            <h3>Vestido Elegante</h3>
            <p>R$ 199,99</p>
            <button>Comprar</button>
        </div>
        <div class="product">
            <img src="vestido2.jpg" alt="Vestido 2">
            <h3>Vestido de Festa</h3>
            <p>R$ 299,99</p>
            <button>Comprar</button>
        </div>
        <div class="product">
            <img src="vestido3.jpg" alt="Vestido 3">
            <h3>Vestido Casual</h3>
            <p>R$ 149,99</p>
            <button>Comprar</button>
        </div>
        <!-- Adicione mais produtos aqui -->
    </div>
</div>

<footer>
    <p>&copy; 2023 G.S.C Distribuidoras de vestidos. Todos os direitos reservados.</p>
</footer>

</body>
</html>
