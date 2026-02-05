<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ARCANJO PERALTA | CURSO</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap');

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            background-color: #0f0f0f;
            color: #ccc;
            font-family: 'Inter', sans-serif;
            line-height: 1.5;
            padding: 20px;
        }

        .main-card {
            max-width: 1100px;
            margin: 0 auto;
            background-color: #161616;
            border: 1px solid #2a2a2a;
            padding: 40px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.5);
        }

        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            border-bottom: 1px solid #333;
            padding-bottom: 20px;
            margin-bottom: 30px;
        }

        .logo {
            font-weight: 700;
            font-size: 1.2rem;
            letter-spacing: 1px;
            color: #fff;
        }

        nav a {
            color: #666;
            text-decoration: none;
            margin-left: 20px;
            font-size: 0.8rem;
            text-transform: uppercase;
        }

        .intro-grid {
            display: flex;
            gap: 40px;
            margin-bottom: 50px;
            flex-wrap: wrap;
        }

        /* --- AQUI VOCÊ MUDA A FOTO --- */
        .profile-img {
            min-width: 320px;
            height: 350px;
            background-color: #222;
            /* COLOQUE O LINK DA SUA IMAGEM ABAIXO */
            background-image: url('SUA_IMAGEM_AQUI.jpg'); 
            background-size: cover;
            background-position: center;
            border-radius: 4px;
        }

        .intro-text {
            flex: 1;
            min-width: 300px;
        }

        .intro-text h1 {
            font-size: 2.8rem;
            color: #fff;
            margin-bottom: 15px;
            border-bottom: 1px solid #333;
            padding-bottom: 10px;
        }

        .intro-text h3 {
            color: #fff;
            margin-top: 20px;
            margin-bottom: 10px;
            font-size: 1.1rem;
            text-transform: uppercase;
        }

        .section-title {
            font-size: 0.9rem;
            color: #fff;
            text-transform: uppercase;
            letter-spacing: 2px;
            margin: 40px 0 20px 0;
            display: flex;
            align-items: center;
            border-top: 1px solid #333;
            padding-top: 20px;
        }

        .section-title span {
            color: #555;
            margin-right: 15px;
            font-weight: bold;
        }

        .codigo-q-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            font-size: 0.85rem;
        }

        .codigo-item {
            list-style: none;
            padding: 6px 0;
            border-bottom: 1px solid #222;
        }

        .rules-list li {
            list-style: none;
            margin-bottom: 10px;
            padding-left: 20px;
            position: relative;
            color: #aaa;
            font-size: 0.9rem;
        }

        .rules-list li::before {
            content: "➢";
            position: absolute;
            left: 0;
            color: #666;
        }

        .patrol-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }

        .patrol-item b {
            display: block;
            color: #fff;
            margin-bottom: 5px;
        }

        .highlight-red {
            color: #ff4d4d;
            font-weight: bold;
        }

        footer {
            margin-top: 60px;
            padding-top: 20px;
            border-top: 1px solid #333;
            display: flex;
            justify-content: space-between;
            font-size: 0.7rem;
            color: #555;
        }
    </style>
</head>
<body>

    <div class="main-card">
        <header>
            <div class="logo">▲ ARCANJO PERALTA</div>
            <nav>
                <a href="#">Sobre</a>
                <a href="#">Patentes</a>
                <a href="#">Regras</a>
                <a href="#">Contato</a>
            </nav>
        </header>

        <section class="intro-grid">
            <div class="profile-img"></div>
            <div class="intro-text">
                <h1>ARCANJO PERALTA</h1>
                <h3>Curso de Modulação</h3>
                <p>Seja bem-vindo ao Curso de Modulação, este curso é de extrema importância para aprender / relembrar o modo correto de modular na rádio.</p>
                <p>Como não é um curso opcional, <b>quem quiser subir sua patente terá que ter os cursos para cada patente.</b></p>
                <p>Estamos disponíveis para dúvidas, não tenha medo de perguntar!</p>
            </div>
        </section>

        <h2 class="section-title"><span>01</span> Código Q</h2>
        <div class="codigo-q-grid">
            <ul>
                <li class="codigo-item"><b>QAP</b> – Na escuta</li>
                <li class="codigo-item"><b>QRR</b> – Pedido de reforço</li>
                <li class="codigo-item"><b>QTH</b> – Localização</li>
                <li class="codigo-item"><b>QRA</b> – Nome e patente</li>
                <li class="codigo-item"><b>QRL</b> – Estou ocupado</li>
            </ul>
            <ul>
                <li class="codigo-item"><b>QRX</b> – Prioridade (Silenciar)</li>
                <li class="codigo-item"><b>QTA</b> – Abortar</li>
                <li class="codigo-item"><b>TKS</b> – Obrigado</li>
                <li class="codigo-item"><b>QRV</b> – A disposição</li>
                <li class="codigo-item"><b>QSJ</b> – Dinheiro Sujo</li>
            </ul>
        </div>

        <h2 class="section-title"><span>02</span> Regras sobre a Modulação</h2>
        <ul class="rules-list">
            <li>Não usar palavras inadequadas (xingamentos, "ah", "ééé", "matei um...").</li>
            <li>Sempre prezar por uma modulação breve e rápida.</li>
            <li>Caso queira conversar em paralelo, utilizar o <b>/pd</b>.</li>
            <li>Manter a calma na rádio mesmo sob pressão.</li>
        </ul>

        <h2 class="section-title"><span>03</span> Código de Patrulha</h2>
        <div class="patrol-grid">
            <div class="patrol-item"><b>Código 5:</b> <span class="highlight-red">➥ FOGO LIBERADO (Atire para matar).</span></div>
            <div class="patrol-item"><b>Código 7:</b> <span class="highlight-red">➥ QRR MÁXIMO, CHAMAR FORÇA TÁTICA.</span></div>
        </div>

        <footer>
            <div>© 2024 ARCANJO PERALTA</div>
            <div>TRANSMISSÃO CRIPTOGRAFADA</div>
        </footer>
    </div>

</body>
</html>
