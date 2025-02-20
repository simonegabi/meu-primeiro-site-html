# meu-primeiro-site-html
<!DOCTYPE html><html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Primeiro Site</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }body {
        font-family: Arial, sans-serif;
        background: #ffe6f2;
        color: #333;
        padding: 20px;
    }

    header {
        background: #ff66b2;
        color: white;
        padding: 20px;
        text-align: center;
        border-radius: 15px;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    }

    nav ul {
        list-style: none;
        padding: 10px 0;
    }

    nav ul li {
        display: inline;
        margin: 0 15px;
    }

    nav ul li a {
        color: white;
        text-decoration: none;
        font-weight: bold;
        transition: color 0.3s;
    }

    nav ul li a:hover {
        color: #ffccdd;
    }

    main {
        margin: 20px 0;
    }

    section {
        background: white;
        padding: 20px;
        margin-bottom: 20px;
        border-radius: 15px;
        box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        border: 2px solid #ff66b2;
    }

    h1, h2 {
        color: #ff66b2;
        margin-bottom: 15px;
    }

    ul {
        list-style: disc;
        margin-left: 20px;
        color: #ff66b2;
    }

    footer {
        text-align: center;
        padding: 15px;
        background: #ff66b2;
        color: white;
        border-radius: 15px;
    }

    a {
        color: #ff66b2;
        text-decoration: none;
        font-weight: bold;
    }

    a:hover {
        color: #ff3385;
    }
</style>

</head><body>
    <header>
        <h1>Bem-vindo ao Meu Site Rosa!</h1>
        <nav>
            <ul>
                <li><a href="#sobre">Sobre</a></li>
                <li><a href="#servicos">Serviços</a></li>
                <li><a href="#contato">Contato</a></li>
            </ul>
        </nav>
    </header><main>
    <section id="sobre">
        <h2>Sobre Nós</h2>
        <p>Somos apaixonados por design e tecnologia, criando experiências visuais encantadoras.</p>
    </section>

    <section id="servicos">
        <h2>Nossos Serviços</h2>
        <ul>
            <li>Design de Sites</li>
            <li>Identidade Visual</li>
            <li>Marketing Digital</li>
        </ul>
    </section>

    <section id="contato">
        <h2>Contato</h2>
        <p>Entre em contato conosco pelo e-mail: <a href="simonegabipires@gmail.com">simonegabipires@gmail.com</a></p>
    </section>
</main>

<footer>
    <p>&copy; 2025 Meu Primeiro Site. Todos os direitos reservados.</p>
</footer>

</body>
