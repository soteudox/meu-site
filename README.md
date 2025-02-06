<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Download do Arquivo</title>
    <style>
        /* Define o fundo cinza e o texto branco */
        body {
            background-color: #808080; /* cinza */
            color: white; /* letras brancas */
            font-family: Arial, sans-serif; /* Fonte legível */
            margin: 0;
            padding: 0;
        }

        /* Estilos para o cabeçalho */
        header {
            text-align: center;
            padding: 20px;
            background-color: #333; /* cor mais escura para o cabeçalho */
        }

        /* Estilo para as seções */
        section {
            padding: 20px;
            text-align: center;
        }

        /* Estilo do rodapé */
        footer {
            text-align: center;
            padding: 10px;
            background-color: #4d3535;
            position: fixed;
            width: 100%;
            bottom: 0;
        }

        /* Estilo do link */
        a {
            color: #f2f2f2; /* cor clara para o link */
            text-decoration: none;
            padding: 10px 20px;
            border: 1px solid #fff;
            border-radius: 5px;
            transition: background-color 0.3s ease;
        }

        /* Mudança de cor ao passar o mouse */
        a:hover {
            background-color: #016999;
        }

        /* Estilo para o texto "by souteX" */
        .creditos {
            font-weight: bold; /* deixa o texto em negrito */
            margin-top: 40px; /* espaçamento maior acima do texto */
            color: black; /* cor preta */
            font-size: 24px; /* aumenta o tamanho do texto */
        }
    </style>
</head>
<body>
    <header>
        <h1>Bem-vindo ao site de download</h1>
    </header>

    <section>
        <h2>Faça o Download aqui!</h2>
        <p>Clique no link abaixo para baixar o arquivo e seguir as instruções de instalação.</p>
        <!-- Link para o arquivo de instalação -->
        <a href="https://www.mediafire.com/file/w6f79tcvxico62d/midia.zip/file" download>Download Aqui</a>
        <!-- Texto "by souteX" em negrito e cor preta -->
        <p class="creditos">by: souteX</p>
    </section>

    <footer>
        <p>&copy; 2025 Meu Site. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
