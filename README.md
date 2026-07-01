<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meow Café | O lugar mais fofo da cidade</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <div class="logo">🐾 Meow Café</div>
        <nav>
            <ul>
                <li><a href="#sobre">Sobre Nós</a></li>
                <li><a href="#gatos">Nossos Gatos</a></li>
                <li><a href="#cardapio">Cardápio</a></li>
                <li><a href="#contato">Contato</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero">
        <div class="hero-content">
            <h1>Café, Carinho e Ronrons</h1>
            <p>Venha tomar um café quentinho na companhia dos felinos mais adoráveis do pedaço.</p>
            <a href="#contato" class="btn">Reserve sua Visita</a>
        </div>
    </section>

    <section id="sobre" class="section">
        <h2>Sobre o Meow Café</h2>
        <p>Somos um espaço aconchegante criado para os amantes de café e de gatos. Aqui, você pode relaxar, trabalhar ou ler um livro enquanto nossos anfitriões de quatro patas andam pelo espaço e ganham carinho.</p>
    </section>

    <section id="cardapio" class="section cardapio-tags">
        <h2>Cardápio Temático</h2>
        <div class="menu-container">
            <div class="menu-item">
                <h3>☕ Gato-ccino</h3>
                <p>Cappuccino cremoso com arte de gatinho na espuma de leite.</p>
            </div>
            <div class="menu-item">
                <h3>🧁 Cupcake de Patinha</h3>
                <p>Cupcake de chocolate decorado com pegadas de gato.</p>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2026 Meow Café - Feito com ❤️ e muitos ronrons.</p>
    </footer>

</body>
</html>
/* Configurações Gerais */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

body {
    background-color: #fdfaf6; /* Bege clarinho */
    color: #4a3b32; /* Marrom café */
}

/* Cabeçalho */
header {
    background-color: #fff;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px 5%;
    box-shadow: 0 2px 5px rgba(0,0,0,0.05);
}

.logo {
    font-size: 24px;
    font-weight: bold;
    color: #ff9494; /* Rosa fofo */
}

nav ul {
    display: flex;
    list-style: none;
}

nav ul li {
    margin-left: 20px;
}

nav ul li a {
    text-decoration: none;
    color: #4a3b32;
    font-weight: 600;
    transition: color 0.3s;
}

nav ul li a:hover {
    color: #ff9494;
}

/* Banner Principal */
.hero {
    background: linear-gradient(rgba(0, 0, 0, 0.4), rgba(0, 0, 0, 0.4)), url('https://images.unsplash.com/photo-1514888286974-6c03e2ca1dba?q=80&w=1200') no-repeat center center/cover;
    height: 60vh;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    color: white;
}

.hero-content h1 {
    font-size: 48px;
    margin-bottom: 10px;
}

.hero-content p {
    font-size: 20px;
    margin-bottom: 20px;
}

.btn {
    display: inline-block;
    background-color: #ff9494;
    color: white;
    padding: 12px 24px;
    text-decoration: none;
    border-radius: 25px;
    font-weight: bold;
    transition: background 0.3s;
}

.btn:hover {
    background-color: #e08282;
}

/* Seções */
.section {
    padding: 60px 10%;
    text-align: center;
}

.section h2 {
    font-size: 32px;
    margin-bottom: 20px;
    color: #ff9494;
}

/* Cardápio */
.menu-container {
    display: flex;
    justify-content: center;
    gap: 30px;
    margin-top: 20px;
}

.menu-item {
    background-color: white;
    padding: 20px;
    border-radius: 15px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.05);
    width: 250px;
}

/* Rodapé */
footer {
    background-color: #4a3b32;
    color: white;
    text-align: center;
    padding: 20px;
    margin-top: 40px;
}
