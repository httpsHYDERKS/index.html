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
            /* CURSOR EM FORMATO DE X */
            cursor: crosshair;
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

        /* FOTO NO QUADRADO */
        .profile-img {
            min-width: 320px;
            height: 380px;
            background-color: #222;
            /* Link da imagem ajustado para o formato CSS */
            background-image: url('https://github.com/user-attachments/assets/e6075cf1-58bd-4f05-b63a-b036cb3c6a00'); 
            background-size: cover;
            background-position: center;
            border: 1px solid #333;
        }

        .intro-text {
            flex: 1;
            min-width: 300px;
        }

        /* EFEITO GLITCH NO NOME */
        .glitch {
            font-size: 2.8rem;
            font-weight: 700;
            color: #fff;
            position: relative;
            text-transform: uppercase;
            margin-bottom: 10px;
        }

        .glitch::before, .glitch::after {
            content: "ARCANJO PERALTA";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
        }

        .glitch::before {
            left: 2px;
            text-shadow: -2px 0 #ff00c1;
            clip: rect(44px, 450px, 56px, 0);
            animation: glitch-anim 5s infinite linear alternate-reverse;
        }

        .glitch::after {
            left: -2px;
            text-shadow: -2px 0 #00fff9;
            clip: rect(44px, 450px, 56px, 0);
            animation: glitch-anim2 5s infinite linear alternate-reverse;
        }

        @keyframes glitch-anim {
            0% { clip: rect(31px, 9999px, 94px, 0); }
            20% { clip: rect(62px, 9999px, 42px, 0); }
            100% { clip: rect(2px, 9999px, 98px, 0); }
        }

        @keyframes glitch-anim2 {
            0% { clip: rect(65px, 9999px, 100px, 0); }
            50% { clip: rect(5px, 9999px, 87px, 0); }
            100% { clip: rect(77px, 9999px, 34px, 0); }
        }

        .intro-text h3 {
            color: #fff;
            margin-bottom: 15px;
            font-size: 1.1rem;
            text-transform: uppercase;
            border-bottom: 1px solid #333;
            padding-bottom: 5px;
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
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 15px;
            font-size: 0.85rem;
        }

        .codigo-item {
            list-style: none;
            padding: 5px 0;
            border-bottom: 1px solid #222;
        }

        .rules-list li {
            list-style: none;
            margin-bottom: 8px;
            padding-left: 25px;
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
            grid-template-columns: repeat(auto-fit, minmax(450px, 1fr));
            gap: 20px;
        }

        .patrol-item {
            background: #1d1d1d;
            padding: 10px;
            border-radius: 4px;
        }

        .patrol-item b {
            display: block;
            color: #fff;
            margin-bottom: 3px;
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
                <div class="glitch">ARCANJO PERALTA</div>
                <h3>CURSO DE MODULAÇÃO</h3>
                <p>Seja bem-vindo ao Curso de Modulação, este curso é de extrema importância para aprender / relembrar o modo correto de modular na rádio.</p>
                <p style="margin-top:10px;">Como não é curso opcional, <b>quem quiser subir sua patente terá que ter os cursos para cada patente.</b></p>
                <p style="margin-top:10px; color: #fff;">Estamos disponível para dúvidas, não tenha medo de perguntar!</p>
            </div>
        </section>

        <h2 class="section-title"><span>01</span> Código Q</h2>
        <p style="font-size: 0.85rem; color: #777; margin-bottom: 15px;">
            O código Q é formado por três siglas sendo sempre iniciado com o Q. Abaixo os principais códigos utilizados em nossa guarnição:
        </p>
        <div class="codigo-q-grid">
            <ul>
                <li class="codigo-item"><b>QAP</b> – Na escuta</li>
                <li class="codigo-item"><b>QRR</b> – Pedido de reforço</li>
                <li class="codigo-item"><b>QTH</b> – Localização</li>
                <li class="codigo-item"><b>QRA</b> – Nome e patente</li>
                <li class="codigo-item"><b>QRL</b> – Estou ocupado</li>
                <li class="codigo-item"><b>QRQ</b> – Transmita mais rápido</li>
            </ul>
            <ul>
                <li class="codigo-item"><b>QRS</b> – Transmita mais devagar</li>
                <li class="codigo-item"><b>QRU</b> – Ocorrência</li>
                <li class="codigo-item"><b>QTX</b> – Saindo de serviço</li>
                <li class="codigo-item"><b>QSV / VTR</b> – Viatura</li>
                <li class="codigo-item"><b>QSL</b> – Entendido</li>
                <li class="codigo-item"><b>QSO</b> – Comunicar algo importante</li>
            </ul>
            <ul>
                <li class="codigo-item"><b>QRX</b> – Prioridade no Rádio (Silenciar)</li>
                <li class="codigo-item"><b>QTA</b> – Abortar</li>
                <li class="codigo-item"><b>TKS</b> – Obrigado</li>
                <li class="codigo-item"><b>QSM</b> – Repita a mensagem</li>
                <li class="codigo-item"><b>QRV</b> – A disposição</li>
                <li class="codigo-item"><b>QSJ</b> – Dinheiro Sujo</li>
            </ul>
        </div>

        <h2 class="section-title"><span>02</span> Regras sobre a Modulação</h2>
        <ul class="rules-list">
            <li>Não usar palavras inadequadas (xingamentos, “ah”, “ééé...”, “aqui”, “lá”, “ali”, “matei um...”).</li>
            <li>Sempre prezar por uma modulação breve e rápida, aprenda a ouvir e depois falar.</li>
            <li>Não manter conversas paralelas na rádio. Caso queira, utilizar o <b>/pd</b>.</li>
            <li>Manter a calma na rádio mesmo sobre pressão. Module com calma e controle as emoções.</li>
            <li>Caso peça QRR diga qual seu QRA.</li>
            <li>Caso alguém peça QRX, silencie a rádio e aguarde a mensagem do operador.</li>
            <li>Não atropele a modulação de outros oficiais.</li>
            <li>Modulação em VTRs feita pelo P2 (GTM o piloto poderá modular).</li>
            <li>Perseguição: modulação pelo Steve na primária. Se der QTA, a secundária assume.</li>
            <li>Alterações no trajeto: modular apenas se tiver Steve a QTI.</li>
            <li>Não atropelar a modulação em caso de múltiplos acompanhamentos.</li>
        </ul>

        <h2 class="section-title"><span>03</span> Código de Patrulha</h2>
        <div class="patrol-grid">
            <div class="patrol-item"><b>Código 0:</b> ➥ Iniciando patrulhamento.</div>
            <div class="patrol-item"><b>Código 1:</b> ➥ Intensidade baixa (trânsito).</div>
            <div class="patrol-item"><b>Código 2:</b> ➥ Intensidade média (Drogas/Registradora/Caixa eletrônica/Mascarados).</div>
            <div class="patrol-item"><b>Código 3:</b> ➥ Uso não letal / Intensidade alta (armados).</div>
            <div class="patrol-item"><b>Código 4:</b> ➥ Situação contida / sob controle.</div>
            <div class="patrol-item"><b>Código 5:</b> <span class="highlight-red">➥ FOGO LIBERADO (Atire para matar).</span></div>
            <div class="patrol-item"><b>Código 6 ou 360º:</b> ➥ Fazer o perímetro no local / Investigar o local.</div>
            <div class="patrol-item"><b>Código 7:</b> <span class="highlight-red">➥ QRR MÁXIMO, CHAMAR A FORÇA TÁTICA.</span></div>
        </div>

        <footer>
            <div>© 2024 ARCANJO PERALTA</div>
            <div>TRANSMISSÃO CRIPTOGRAFADA</div>
        </footer>
    </div>

</body>
</html>
