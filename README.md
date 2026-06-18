<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfólio - Davi Ferreira</title>
    <!-- Ícones modernos para as redes e tecnologias -->
    <link rel="stylesheet" href="https://cloudflare.com">
    
    <style>
        /* RESET E CONFIGURAÇÕES BASE (MOBILE-FIRST) */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #050a12; /* Fundo azul-escuro quase preto */
            color: #f8fafc;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            padding: 20px;
        }

        /* CONTAINER PRINCIPAL */
        .portfolio-container {
            width: 100%;
            max-width: 400px;
            background-color: #0b1426; /* Fundo do card em azul-escuro fechado */
            border-radius: 16px;
            padding: 40px 24px;
            text-align: center;
            box-shadow: 0 10px 30px rgba(138, 3, 3, 0.3); /* Sombra em tom vermelho-sangue */
            border: 2px solid #8a0303; /* Borda marcante em vermelho-sangue */
        }

        /* CABEÇALHO SEM FOTO */
        .profile-header {
            margin-bottom: 32px;
        }

        .profile-header h1 {
            font-size: 2rem;
            font-weight: 800;
            margin-bottom: 8px;
            color: #ffffff;
            text-shadow: 0 0 10px rgba(138, 3, 3, 0.6); /* Brilho sombrio no nome */
        }

        .subtitle {
            color: #af0606; /* Vermelho-sangue vivo para o cargo */
            font-size: 1.1rem;
            font-weight: 600;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        /* SEÇÕES DE CONTEÚDO */
        h2 {
            font-size: 1rem;
            color: #ef4444; /* Vermelho mais claro para leitura dos títulos */
            margin-bottom: 16px;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        .stack-section, .contact-section {
            margin-bottom: 32px;
        }

        /* BADGES DA STACK (TECNOLOGIAS) */
        .tech-badges {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 10px;
        }

        .badge {
            background-color: #111e38; /* Fundo azul-escuro contrastante */
            padding: 8px 16px;
            border-radius: 20px;
            font-size: 0.85rem;
            display: flex;
            align-items: center;
            gap: 6px;
            border: 1px solid rgba(138, 3, 3, 0.4);
            font-weight: 500;
        }

        .badge i {
            color: #af0606; /* Ícones em vermelho-sangue */
        }

        /* BOTÕES DE LINK VERTICAIS (CTA) */
        .buttons-container {
            display: flex;
            flex-direction: column;
            gap: 12px;
            width: 100%;
        }

        .btn {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
            color: #ffffff;
            text-decoration: none;
            padding: 14px;
            border-radius: 8px;
            font-weight: 600;
            width: 100%;
            transition: transform 0.2s ease, filter 0.2s ease, box-shadow 0.2s ease;
        }

        .btn:hover {
            transform: translateY(-2px);
            filter: brightness(1.2);
            box-shadow: 0 5px 15px rgba(138, 3, 3, 0.6);
        }

        /* Cores dos botões adaptadas ao tema sombrio */
        .btn-whatsapp { background-color: #25d366; }  /* Mantido padrão por usabilidade */
        .btn-linkedin { background-color: #0077b5; }  /* Mantido padrão corporativo */
        .btn-github { background-color: #8a0303; }    /* Vermelho-sangue escuro */
        .btn-instagram { background-color: #af0606; } /* Vermelho-sangue vivo */

        /* MEDIA QUERY PARA TELAS MAIORES */
        @media (min-width: 768px) {
            .portfolio-container {
                max-width: 450px;
                padding: 48px 40px;
            }
        }
    </style>
</head>
<body>

    <main class="portfolio-container">
        
        <!-- CABEÇALHO -->
        <header class="profile-header">
            <h1>Davi Ferreira</h1>
            <p class="subtitle">Desenvolvedor Front-end</p>
        </header>

        <!-- SEÇÃO DE TECNOLOGIAS (STACK) -->
        <section class="stack-section">
            <h2>Minha Stack</h2>
            <div class="tech-badges">
                <span class="badge"><i class="fa-brands fa-html5"></i> HTML</span>
                <span class="badge"><i class="fa-brands fa-css3-alt"></i> CSS</span>
                <span class="badge"><i class="fa-brands fa-js"></i> JavaScript</span>
                <span class="badge"><i class="fa-brands fa-react"></i> React</span>
            </div>
        </section>

        <!-- SEÇÃO DE CONTATOS E REDES PROFISSIONAIS -->
        <footer class="contact-section">
            <h2>Conecte-se Comigo</h2>
            
            <div class="buttons-container">
                <!-- LINK DEFINITIVO: Direcionado para o seu contato oficial -->
                <a href="https://wa.me/5519993596564" target="_blank" rel="noopener noreferrer" class="btn btn-whatsapp">
                    <i class="fa-brands fa-whatsapp"></i> Fale no WhatsApp 
                </a>

                <!-- Botão GitHub (Mude "seu-usuario" pelo seu @ real) -->
                <a href="https://github.com" target="_blank" rel="noopener noreferrer" class="btn btn-github">
                    <i class="fa-brands fa-github"></i> Visitar meu GitHub
                    
                </a>
            </div>
        </footer>
        
    </main>

</body>
</html>
