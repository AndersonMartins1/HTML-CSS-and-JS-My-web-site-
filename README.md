# HTML-CSS-and-JS-My-web-site-
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Meu Portfolio</h1>
    </header>
    <main>
        <section id="presentation">
            <h2>Apresentação Visual Impactante</h2>
            <!-- Conteúdo da apresentação visual -->
            <div class="logo">Logo Aqui</div>
        </section>
        <section id="ui-ux">
            <h2>Design UI/UX Imersivo</h2>
            <!-- Conteúdo do design UI/UX -->
            <p>Exemplos de layouts, esquemas de cores e fluxos de navegação.</p>
        </section>
        <section id="animations">
            <h2>Animações Encantadoras</h2>
            <!-- Conteúdo das animações -->
            <p>Exemplos de animações fluidas e expressivas.</p>
        </section>
        <section id="buttons-links">
            <h2>Botões e Links</h2>
            <!-- Conteúdo dos botões e links -->
            <button class="button" onclick="buttonClicked()">Clique Aqui</button>
            <a href="#" class="external-link">Link Externo</a>
            <button class="button" onclick="javascriptButtonClicked()">Botão JavaScript</button>
        </section>
        <section id="custom-pages">
            <h2>Páginas Personalizadas com Cores Vibrantes</h2>
            <!-- Conteúdo das páginas personalizadas -->
            <div class="custom-page">Conteúdo da Página Personalizada</div>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Meu Portfolio</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>


/* Estilos gerais */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f8f8f8;
}

header {
    background-color: #333;
    color: #fff;
    padding: 20px;
    text-align: center;
}

main {
    padding: 20px;
}

footer {
    background-color: #333;
    color: #fff;
    padding: 10px 20px;
    text-align: center;
}

/* Estilos específicos para cada seção */
section {
    margin-bottom: 30px;
}

/* Estilos para botões */
.button {
    padding: 10px 20px;
    background-color: #007bff;
    color: #fff;
    text-decoration: none;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    transition: background-color 0.3s ease;
}

.button:hover {
    background-color: #0056b3;
}

/* Estilos para links externos */
.external-link {
    display: inline-block;
    padding: 10px 20px;
    background-color: #28a745;
    color: #fff;
    text-decoration: none;
    border-radius: 5px;
    transition: background-color 0.3s ease;
}

.external-link:hover {
    background-color: #218838;
}

/* Estilos para páginas personalizadas */
.custom-page {
    background-color: #ffc107;
    padding: 20px;
    color: #333;
    border-radius: 5px;
}



