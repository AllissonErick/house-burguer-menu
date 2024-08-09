# house-burguer-menu

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>House Burguer</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
        }
        header {
            background-color: #333;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            margin: 0;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
        }
        .container {
            width: 80%;
            margin: auto;
            padding: 20px;
        }
        .menu-section {
            margin-bottom: 30px;
        }
        h2 {
            background-color: #ddd;
            padding: 10px;
            border-radius: 5px;
        }
        .item {
            padding: 10px;
            border-bottom: 1px solid #ddd;
        }
        .item:last-child {
            border-bottom: none;
        }
        .item h3 {
            margin: 0;
            font-size: 18px;
        }
        .item p {
            margin: 5px 0;
        }
        .btn {
            background-color: #007bff;
            color: white;
            padding: 8px 15px;
            text-decoration: none;
            border-radius: 5px;
        }
        footer {
            background-color: #333;
            color: white;
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
    <h1>House Burguer</h1>
</header>

<nav>
    <a href="#menu">Menu</a>
    <a href="#sobre-nos">Sobre Nós</a>
    <a href="#contato">Contato</a>
</nav>

<div class="container">
    <section id="menu">
        <h2>Menu</h2>
        
        <div class="menu-section">
            <h3>Clássicos</h3>
            <div class="item">
                <h3>House Burger</h3>
                <p>Hambúrguer de carne bovina, queijo cheddar, alface, tomate, cebola roxa e molho especial.</p>
                <a href="#" class="btn">Adicionar ao Pedido</a>
            </div>
            <div class="item">
                <h3>Cheeseburger</h3>
                <p>Hambúrguer de carne bovina, queijo cheddar, cebola caramelizada e maionese.</p>
                <a href="#" class="btn">Adicionar ao Pedido</a>
            </div>
            <div class="item">
                <h3>Bacon Burger</h3>
                <p>Hambúrguer de carne bovina, queijo cheddar, bacon crocante, alface e tomate.</p>
                <a href="#" class="btn">Adicionar ao Pedido</a>
            </div>
        </div>
        
        <div class="menu-section">
            <h3>Gourmet</h3>
            <div class="item">
                <h3>Truffle Burger</h3>
                <p>Hambúrguer de carne bovina, queijo suíço, cogumelos salteados e molho de trufas.</p>
                <a href="#" class="btn">Adicionar ao Pedido</a>
            </div>
            <div class="item">
                <h3>BBQ Burger</h3>
                <p>Hambúrguer de carne bovina, queijo prato, cebola crocante, molho barbecue e picles.</p>
                <a href="#" class="btn">Adicionar ao Pedido</a>
            </div>
            <div class="item">
                <h3>Veggie Burger</h3>
                <p>Hambúrguer vegetariano de grão-de-bico, queijo provolone, alface, tomate e maionese de ervas.</p>
                <a href="#" class="btn">Adicionar ao Pedido</a>
            </div>
        </div>

        <div class="menu-section">
            <h3>Acompanhamentos</h3>
            <div class="item">
                <h3>Batata Frita</h3>
                <p>Batatas crocantes com sal.</p>
                <a href="#" class="btn">Adicionar ao Pedido</a>
            </div>
            <div class="item">
                <h3>Onion Rings</h3>
                <p>Anéis de cebola empanados e fritos.</p>
                <a href="#" class="btn">Adicionar ao Pedido</a>
            </div>
            <div class="item">
                <h3>Acompanhamento de Salada</h3>
                <p>Mix de folhas verdes, tomates cereja e cenoura ralada com molho a gosto.</p>
                <a href="#" class="btn">Adicionar ao Pedido</a>
            </div>
        </div>

        <div class="menu-section">
            <h3>Bebidas</h3>
            <div class="item">
                <h3>Refrigerante</h3>
                <p>Coca-Cola, Sprite, Fanta.</p>
                <a href="#" class="btn">Adicionar ao Pedido</a>
            </div>
            <div class="item">
                <h3>Suco Natural</h3>
                <p>Laranja, Manga, Abacaxi.</p>
                <a href="#" class="btn">Adicionar ao Pedido</a>
            </div>
            <div class="item">
                <h3>Água Mineral</h3>
                <a href="#" class="btn">Adicionar ao Pedido</a>
            </div>
        </div>

        <div class="menu-section">
            <h3>Sobremesas</h3>
            <div class="item">
                <h3>Milkshake</h3>
                <p>Sabor de chocolate, baunilha ou morango.</p>
                <a href="#" class="btn">Adicionar ao Pedido</a>
            </div>
            <div class="item">
                <h3>Brownie</h3>
                <p>Brownie de chocolate servido com uma bola de sorvete de baunilha.</p>
                <a href="#" class="btn">Adicionar ao Pedido</a>
            </div>
            <div class="item">
                <h3>Torta de Limão</h3>
                <p>Torta de limão com base crocante e cobertura de merengue.</p>
                <a href="#" class="btn">Adicionar ao Pedido</a>
            </div>
        </div>
    </section>
    
    <section id="sobre-nos">
        <h2>Sobre Nós</h2>
        <p>Conheça nossa história e missão! [Leia Mais](#)</p>
    </section>
    
    <section id="contato">
        <h2>Contato</h2>
        <p>Fale conosco através do e-mail contato@houseburguer.com ou pelo telefone (11) 1234-5678. [Envie uma Mensagem](#)</p>
    </section>
</div>

<footer>
    <p>&copy; 2024 House Burguer. Todos os direitos reservados.</p>
</footer>

</body>
</html>
```
