<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Site de Vídeos</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #555;
        }
        nav a {
            color: #fff;
            padding: 14px 20px;
            text-decoration: none;
            text-transform: uppercase;
        }
        nav a:hover {
            background-color: #444;
        }
        .container {
            padding: 20px;
        }
        .video-section {
            margin-bottom: 40px;
        }
        .video-section h2 {
            border-bottom: 2px solid #ddd;
            padding-bottom: 10px;
        }
        .video {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }
        .video iframe {
            flex: 1;
            min-width: 300px;
            max-width: 45%;
            height: 200px;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

    <header>
        <h1>Meu Site de Vídeos</h1>
    </header>

    <nav>
        <a href="#pessoais">Vídeos Pessoais</a>
        <a href="#casuais">Vídeos Casuais</a>
    </nav>

    <div class="container">
        <section id="pessoais" class="video-section">
            <h2>Vídeos Pessoais</h2>
            <div class="video">
                <iframe src="https://www.youtube.com/embed/EXEMPLO1" frameborder="0" allowfullscreen></iframe>
                <iframe src="https://www.youtube.com/embed/EXEMPLO2" frameborder="0" allowfullscreen></iframe>
                <!-- Adicione mais vídeos pessoais aqui -->
            </div>
        </section>

        <section id="casuais" class="video-section">
            <h2>Vídeos Casuais</h2>
            <div class="video">
                <iframe src="https://www.youtube.com/embed/EXEMPLO3" frameborder="0" allowfullscreen></iframe>
                <iframe src="https://www.youtube.com/embed/EXEMPLO4" frameborder="0" allowfullscreen></iframe>
                <!-- Adicione mais vídeos casuais aqui -->
            </div>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 Meu Site de Vídeos. Todos os direitos reservados.</p>
    </footer>

</body>
</html>
