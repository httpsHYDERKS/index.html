<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ARCANJO ANIMADO | CURSO</title>
    <style>
        /* CONFIGURAÇÕES GERAIS */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            cursor: crosshair; /* Transforma o mouse em um X/Cruz */
        }

        body {
            background-color: #0a0a0a;
            color: #00ff41; /* Verde Matrix/Terminal */
            font-family: 'Courier New', Courier, monospace;
            line-height: 1.6;
            overflow-x: hidden;
            padding: 20px;
        }

        /* EFEITO GLITCH NO TÍTULO */
        .glitch-wrapper {
            text-align: center;
            margin-bottom: 50px;
            padding-top: 40px;
        }

        .glitch {
            font-size: 3.5rem;
            font-weight: bold;
            text-transform: uppercase;
            position: relative;
            text-shadow: 0.05em 0 0 #00fffc, -0.03em -0.04em 0 #fc00ff,
                         0.025em 0.04em 0 #fffc00;
            animation: glitch 725ms infinite;
        }

        @keyframes glitch {
            0% { text-shadow: 0.05em 0 0 #00fffc, -0.03em -0.04em 0 #fc00ff, 0.025em 0.04em 0 #fffc00; }
            14% { text-shadow: 0.05em 0 0 #00fffc, -0.03em -0.04em 0 #fc00ff, 0.025em 0.04em 0 #fffc00; }
            15% { text-shadow: -0.05em -0.025em 0 #00fffc, 0.025em 0.025em 0 #fc00ff, -0.05em -0.05em 0 #fffc00; }
            49% { text-shadow: -0.05em -0.025em 0 #00fffc, 0.025em 0.025em 0 #fc00ff, -0.05em -0.05em 0 #fffc00; }
            50% { text-shadow: 0.025em 0.05em 0 #00fffc, 0.05em 0 0 #fc00ff, 0 -0.05em 0 #fffc00; }
            99% { text-shadow: 0.025em 0.05em 0 #00fffc, 0.05em 0 0 #fc00ff, 0 -0.05em 0 #fffc00; }
            100% { text-shadow: -0.025em 0 0 #00fffc, -0.025em -0.025em 0 #fc00ff, -0.025em -0.05em 0 #fffc00; }
        }

        /* CONTEÚDO */
        .container {
            max-width: 900px;
            margin: 0 auto;
            background: rgba(0, 20, 0, 0.8);
            padding: 30px;
            border: 1px solid #00ff41;
            box-shadow: 0 0 15px rgba(0, 255, 65, 0.2);
        }

        h2 {
            color: #fff;
            border-bottom: 2px solid #00ff41;
            margin: 30px 0 15px 0;
            padding-bottom: 5px;
            text-transform: uppercase;
        }

        .highlight {
            color: #ff003c; /* Vermelho para alertas/importante */
            font-weight: bold;
        }

        ul {
            list-style: none;
        }

        li {
            margin-bottom: 8px;
            padding-left: 15px;
            border-left: 3px solid #00ff41;
        }

        .grid-codigos {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
            gap: 10px;
        }

        .footer {
            text-align: center;
            margin-top: 50px;
            font-size: 0.8rem;
            opacity: 0.6;
        }

        /* EFEITO DE LINHAS DE TV ANTIGA (SCANLINES) */
        body::before {
            content: " ";
            display: block;
            position: fixed;
            top: 0; left: 0; bottom: 0; right: 0;
            background: linear-gradient(rgba(18, 16, 16, 0) 50%, rgba(0, 0, 0, 0.25) 50%), 
                        linear-gradient(90deg, rgba(255, 0, 0, 0.06), rgba(0, 255, 0, 0.02), rgba(0, 0, 255, 0.06));
            z-index: 2;
            background-size: 100% 4px, 3px 100%;
            pointer-events: none;
        }
    </style>
</head>
<body>

    <div class="glitch-wrapper">
        <div class="glitch">ARCANJO ANIMADO</div>
        <p style="letter-spacing: 5px;">ESTILO GLITCH</p>
    </div>

    <div class="container">
        <h2>CURSO DE MODULAÇÃO</h2>
        <p>Seja bem-vindo ao Curso de Modulação, este curso é de extrema importância para aprender / relembrar o modo correto de modular na rádio, e como não é curso opcional <span class="highlight">quem quiser subir sua patente terá que de ter os cursos para cada patente.</span></p>
        <p>Estamos disponíveis para dúvidas, não tenha medo de perguntar!</p>

        <h2>Código Q</h2>
        <p>O código Q é formado por três siglas sendo sempre iniciado com o Q. Abaixo os principais utilizados em nossa guarnição:</p>
        <br>
        <div class="grid-codigos">
            <ul>
                <li><strong>QAP</strong> – Na escuta</li>
                <li><strong>QRR</strong> – Pedido de reforço</li>
                <li><strong>QTH</strong> – Localização</li>
                <li><strong>QRA</strong> – Nome e patente</li>
                <li><strong>QRL</strong> – Estou ocupado</li>
                <li><strong>QRQ</strong> – Transmita rápido</li>
                <li><strong>QRS</strong> – Transmita devagar</li>
                <li><strong>QRU</strong> – Ocorrência</li>
                <li><strong>QTX</strong> – Saindo de serviço</li>
            </ul>
            <ul>
                <li><strong>QSV/VTR</strong> – Viatura</li>
                <li><strong>QSL</strong> – Entendido</li>
                <li><strong>QSO</strong> – Info importante</li>
                <li><strong>QRX</strong> – Silêncio/Prioridade</li>
                <li><strong>QTA</strong> – Abortar</li>
                <li><strong>TKS</strong> – Obrigado</li>
                <li><strong>QSM</strong> – Repita</li>
                <li><strong>QRV</strong> – À disposição</li>
                <li><strong>QSJ</strong> – Dinheiro Sujo</li>
            </ul>
        </div>

        <h2>Regras de Modulação</h2>
        <ul>
            <li>Não usar gírias ou palavras inadequadas (xingamentos, "ah", "ééé").</li>
            <li>Seja breve e rápido: aprenda a ouvir antes de falar.</li>
            <li>Proibido conversas paralelas. Use o <strong>/pd</strong> para isso.</li>
            <li>Mantenha a calma sob pressão para que todos entendam.</li>
            <li>Em QRR, sempre informe seu QRA.</li>
            <li>Não atropele a modulação de outros oficiais.</li>
            <li>Modulação em VTRs feita pelo P2 (GTM o piloto pode modular).</li>
        </ul>

        <h2>Código de Patrulha</h2>
        <ul>
            <li><strong>Código 0:</strong> Iniciando patrulhamento.</li>
            <li><strong>Código 1:</strong> Intensidade baixa (trânsito).</li>
            <li><strong>Código 2:</strong> Intensidade média (Drogas/Assaltos).</li>
            <li><strong>Código 3:</strong> Uso não letal / Intensidade alta.</li>
            <li><strong>Código 4:</strong> Situação contida.</li>
            <li><strong>Código 5:</strong> <span class="highlight">FOGO LIBERADO.</span></li>
            <li><strong>Código 6:</strong> Perímetro / Investigação.</li>
            <li><strong>Código 7:</strong> QRR MÁXIMO (Força Tática).</li>
        </ul>
    </div>

    <div class="footer">
        SISTEMA ARCANJO © 2024 - TRANSMISSÃO CRIPTOGRAFADA
    </div>

</body>
</html>
