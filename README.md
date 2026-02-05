<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ARCANJO PERALTA | CURSO</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;700&display=swap');

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            background-color: #121212;
            color: #d1d1d1;
            font-family: 'Inter', sans-serif;
            line-height: 1.4;
            padding: 40px;
        }

        .main-card {
            max-width: 1000px;
            margin: 0 auto;
            background-color: #1a1a1a;
            border: 1px solid #333;
            padding: 40px;
            position: relative;
        }

        /* Header e Navegação */
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            border-bottom: 1px solid #444;
            padding-bottom: 15px;
            margin-bottom: 30px;
        }

        .logo {
            font-weight: bold;
            font-size: 1.2rem;
            letter-spacing: 1px;
            color: #fff;
        }

        nav a {
            color: #888;
            text-decoration: none;
            margin-left: 20px;
            font-size: 0.85rem;
        }

        /* Seção Perfil/Intro */
        .profile-section {
            display: flex;
            gap: 30px;
            margin-bottom: 40px;
        }

        .profile-img {
            width: 300px;
            height: 250px;
            background: #252525;
            /* Placeholder para a imagem da estátua/capuz */
            background-image: url('https://via.placeholder.com/300x250/252525/ffffff?text=IMAGEM+PERFIL'); 
            background-size: cover;
            background-position: center;
        }

        .intro-text h1 {
            font-size: 2.5rem;
            color: #fff;
            margin-bottom: 10px;
        }

        .intro-text p {
            font-size: 0.95rem;
            margin-bottom: 15px;
            color: #aaa;
        }

        .highlight-red {
            color: #ff3e3e;
            text-decoration: underline;
        }

        /* Blocos de Conteúdo */
        .content-grid {
            display: grid;
            grid-template-columns: 2fr 1fr;
            gap: 40px;
            border-top: 1px solid #333;
            padding-top: 30px;
        }

        h2 {
            font-size: 1rem;
            letter-spacing: 2px;
            margin-bottom: 20px;
            color: #fff;
            display: flex;
            align-items: center;
        }

        h2::before {
            content: "2"; /* Número da seção como na foto */
            margin-right: 10px;
            font-size: 0.8rem;
            color: #888;
        }

        .codigo-list {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 15px;
            font-size: 0.85rem;
        }

        .codigo-item {
            list-style: none;
            margin-bottom: 5px;
        }

        .regras-lista {
            font-size: 0.85rem;
            color: #aaa;
        }

        .regras-lista li {
            list-style: none;
            margin-bottom: 8px;
        }

        /* Rodapé Interno */
        footer {
            margin-top: 50px;
            border-top: 1px solid #444;
            padding-top: 20px;
            display: flex;
            justify-content: space-between;
            font-size: 0.75rem;
            color: #666;
        }

        .fogo-maximo {
            color: #ff3e3e;
            font-weight: bold;
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

        <section class="profile-section">
            <div class="profile-img"></div>
            <div class="intro-text">
                <h1>ARCANJO PERALTA</h1>
                <p>Seu portal para elevar a habilidade de modulação no rádio.</p>
                
                <h3>CURSO DE MODULAÇÃO</h3>
                <p>Seja bem-vindo! Este curso é crucial à <span class="highlight-red">Obrigação de patente</span>.</p>
                <p>Estamos disponíveis para dúvidas.<br>Não hesite em perguntar!</p>
            </div>
        </section>

        <div class="content-grid">
            <div>
                <h2>CÓDIGO Q</h2>
                <div class="codigo-list">
                    <ul>
                        <li class="codigo-item">QAP – Na escuta</li>
                        <li class="codigo-item">QRR – Reforço</li>
                        <li class="codigo-item">QRA – Local/Patente</li>
                        <li class="codigo-item">QSL – Entendido</li>
                    </ul>
                    <ul>
                        <li class="codigo-item">QRX – Prioridade</li>
                        <li class="codigo-item">QTA – Abortar</li>
                        <li class="codigo-item">QSJ – Dinheiro Sujo</li>
                    </ul>
                    <ul>
                        <li class="codigo-item">TKS - Obrigado</li>
                        <li class="codigo-item">QRV - À disposição</li>
                    </ul>
                </div>
            </div>

            <div>
                <h2>REGRAS DE RÁDIO</h2>
                <ul class="regras-lista">
                    <li>> Proibido xingamentos ou palavras "ah", "ééé".</li>
                    <li>> Conversas por calma apenas no /pd</li>
                </ul>
            </div>
        </div>

        <div style="margin-top: 40px;">
            <h2 style="font-size: 1rem;">3 CÓDIGOS DE PATRULHA</h2>
            <div class="codigo-list">
                <ul>
                    <li class="codigo-item">> Cod 0: Início</li>
                    <li class="codigo-item">> Cod 2: Baixa intensidade</li>
                    <li class="codigo-item">> Mantenha o calmo / Investigação</li>
                </ul>
                <ul>
                    <li class="codigo-item">> Modulação breve e rápida.</li>
                    <li class="codigo-item">> Conversas paralelas sem pressão.</li>
                    <li class="codigo-item">> Cod 6: <span class="fogo-maximo">- FOGO MÁXIMO</span></li>
                </ul>
            </div>
        </div>

        <footer>
            <div>© 2024 ARCANJO PERALTA</div>
            <div>TRANSMISSÃO CRIPTOGRAFADA</div>
        </footer>
    </div>

</body>
</html>
