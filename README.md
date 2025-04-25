# Aula-CSS
CSS aplicado em aula 24/04
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aula CSS</title>

    <style>
        h1{
            font-family: cursive;
            font-size: 50px;
            color: blue;
            background-color: burlywood;
        }

        #paragrafoUnico{
            font-size: 40px;
            font-weight: 1900;
            color: #c7ec10;
        }
        
        .minhaClasse{
            font-family: sans-serif;
            font-style: italic;
            color: chocolate;  !important;
        }
        
        .grid-container{
            display: grid;
            grid-template-columns: 1fr 1fr 1fr;
            gap: 10px;
        }
        
        .grid-item{
            font-family: sans-serif;
            background-color: blue;
            color: white;
            padding: 10px;
            text-align: center;
        }
    </style>
</head>
<body>
    <h1>Aula CSS</h1>
    <h1>Aula CSS</h1>
    <h1>Aula CSS</h1>

    <h2 class="minhaClasse">Aula CSS h2</h2>
    <h2 id="paragrafoUnico">Aula CSS h2</h2>
    <h2>Aula CSS h2</h2>

    <p class="minhaClasse" style="color: black;">Feliz Torres expulso 14min sulamericana 14/04/2025</p>

    <div class="grid-container">
        <div class="grid-item">1</div>
        <div class="grid-item">2</div>
        <div class="grid-item">3</div>
        <div class="grid-item">4</div>
        <div class="grid-item">5</div>
        <div class="grid-item">6</div>
        <div class="grid-item">7</div>
        <div class="grid-item">8</div>
        <div class="grid-item">9</div>
        <div class="grid-item">#</div>
        <div class="grid-item">0</div>
        <div class="grid-item">*</div>
    </div>
</body>
</html>






<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Faculdade Tech</title>
    
    <link href="./CSS/style.css" rel="stylesheet">

</head>
<body>
    <header>
        <h1>Faculdade Tech</h1>
        <p>Construindo o Futuro com Tecnologia</p>
    </header>
    <nav>
        <a href="#cursos">Cursos</a>
        <a href="#sobre">Sobre</a>
        <a href="#contato">Contato</a>
    </nav>
    <main>
        <h2>Bem-vindo à Faculdade Tech</h2>
        <p>Explore nossos cursos e invista no seu futuro.</p>
        <a href="#cursos" class="btn">Saiba Mais</a>
    </main>
    <footer>
        <p>&copy; 2025 Faculdade Tech - Todos os direitos reservados.</p>
    </footer>
</body>
</html>





body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header{
    background-color: #333333;
    color: white;
    text-align: center;
    padding: 20px;
}

nav{
    display: flex;
    justify-content: center;
    color: #444;
    padding: 10px;
}

nav a {
    color: rgb(37, 29, 29);
    text-decoration: none;
    padding: 10px 20px;
}

main {
    width: 80%;
    margin: auto;
    padding: 20px;
    text-align: center;
}

footer{
    background-color: #33333396;
    color: white;
    text-align: center;
    padding: 10px;
    position: absolute;
    width: 98.98%;
    bottom:0;
}
