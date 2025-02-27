<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Fumacinha - Loja de Vapes</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #616161;
        }
        header {
            background-color: #333;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            background-color: #9c2323;
            padding: 10px 0;
            text-align: center;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 10px 20px;
            margin: 0 15px;
            font-size: 16px;
        }
        nav a:hover {
            background-color: #c72525;
        }
        section {
            padding: 30px;
            max-width: 1200px;
            margin: auto;
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            margin-top: 30px;
        }
        .products, .contact {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
        }
        .product-card, .contact-card {
            width: 30%;
            margin: 10px;
            background-color: #f8f8f8;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        .product-card img {
            width: 100%;
            border-radius: 10px;
        }
        .product-card h3, .contact-card h3 {
            text-align: center;
            color: #333;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 15px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Fumacinha</h1>
        <p>Sua Loja Virtual de Vapes e Acessórios</p>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#produtos">Produtos</a>
        <a href="#promocoes">Promoções</a>
        <a href="#contato">Contato</a>
    </nav>

    <section id="home">
        <h2>Bem-vindo à Fumacinha!</h2>
        <p>A melhor loja de vapes e acessórios. Aqui, você encontra os produtos mais inovadores e sabores incríveis para garantir a melhor experiência de vape.</p>
    </section>

    <section id="produtos">
        <h2>Produtos</h2>
        <div class="products">
            <div class="product-card">
                <img src="https://via.placeholder.com/300x200" alt="Produto 1">
                <h3>Vape Modelo X</h3>
                <p>Desfrute de uma experiência única com o Vape Modelo X. Compacto e eficiente!</p>
                <p><strong>R$ 299,90</strong></p>
            </div>
            <div class="product-card">
                <img src="https://via.placeholder.com/300x200" alt="Produto 2">
                <h3>Vape Modelo Y</h3>
                <p>Desempenho superior e design moderno. Perfeito para quem busca qualidade!</p>
                <p><strong>R$ 399,90</strong></p>
            </div>
            <div class="product-card">
                <img src="https://via.placeholder.com/300x200" alt="Produto 3">
                <h3>Vape Modelo Z</h3>
                <p>Com vários sabores e excelente duração de bateria. O modelo mais desejado!</p>
                <p><strong>R$ 499,90</strong></p>
            </div>
        </div>
    </section>

    <section id="promocoes">
        <h2>Promoções</h2>
        <p>Aproveite as nossas promoções incríveis! Descontos especiais em vários modelos de vapes e acessórios. Não perca essa oportunidade!</p>
    </section>

    <section id="contato">
        <h2>Entre em Contato</h2>
        <div class="contact">
            <div class="contact-card">
                <h3>Email</h3>
                <p>contato@fumacinha.com.br</p>
            </div>
            <div class="contact-card">
                <h3>Telefone</h3>
                <p>(11) 99999-9999</p>
            </div>
            <div class="contact-card">
                <h3>Endereço</h3>
                <p>Rua Fictícia, 123 - São Paulo, SP</p>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2025 Fumacinha - Todos os direitos reservados.</p>
    </footer>
</body>
</html>
