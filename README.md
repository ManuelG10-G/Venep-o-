<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Padaria Venepão | O Pão Mais Fresco</title>
    <style>
        /* Estilos Gerais */
        :root {
            --castanho: #4B2C20;
            --dourado: #D4AF37;
            --creme: #FDF5E6;
            --texto: #333;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            color: var(--texto);
            background-color: #fff;
        }

        /* Cabeçalho */
        header {
            background-color: var(--castanho);
            color: white;
            padding: 1rem 5%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        .logo {
            font-size: 1.5rem;
            font-weight: bold;
            color: var(--dourado);
        }

        nav a {
            color: white;
            text-decoration: none;
            margin-left: 20px;
            font-weight: 500;
        }

        /* Secção Hero (Destaque) */
        .hero {
            background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), 
                        url('https://images.unsplash.com/photo-1509440159596-0249088772ff?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80');
            background-size: cover;
            background-position: center;
            height: 60vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            color: white;
            text-align: center;
            padding: 0 20px;
        }

        .hero h1 { font-size: 3rem; margin-bottom: 10px; }
        .hero p { font-size: 1.2rem; margin-bottom: 20px; }

        .btn-encomenda {
            background-color: var(--dourado);
            color: var(--castanho);
            padding: 12px 25px;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            transition: 0.3s;
        }

        /* Produtos */
        .produtos {
            padding: 50px 5%;
            background-color: var(--creme);
            text-align: center;
        }

        .grid-produtos {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 30px;
        }

        .card {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }

        .card h3 { color: var(--castanho); }

        /* Rodapé */
        footer {
            background-color: var(--castanho);
            color: white;
            text-align: center;
            padding: 30px 5%;
        }

        .whatsapp-float {
            position: fixed;
            bottom: 20px;
            right: 20px;
            background-color: #25d366;
            color: white;
            padding: 15px 20px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: bold;
            box-shadow: 0 4px 10px rgba(0,0,0,0.3);
        }
    </style>
</head>
<body>

    <header>
        <div class="logo">VENEPÃO</div>
        <nav>
            <a href="#inicio">Início</a>
            <a href="#produtos">Produtos</a>
            <a href="#contacto">Contacto</a>
        </nav>
    </header>

    <section class="hero" id="inicio">
        <h1>O Sabor da Tradição</h1>
        <p>Pão quente e estaladiço todos os dias, feito com amor.</p>
        <a href="#contacto" class="btn-encomenda">Fazer Encomenda</a>
    </section>

    <section class="produtos" id="produtos">
        <h2>As Nossas Especialidades</h2>
        <div class="grid-produtos">
            <div class="card">
                <h3>🥖 Pão Artesanal</h3>
                <p>Cozido em forno de lenha com fermentação natural.</p>
            </div>
            <div class="card">
                <h3>🥐 Pastelaria</h3>
                <p>Croissants folhados e os melhores pastéis de nata da região.</p>
            </div>
            <div class="card">
                <h3>🎂 Bolos por Medida</h3>
                <p>Torne as suas festas mais doces com os nossos bolos caseiros.</p>
            </div>
        </div>
    </section>

    <footer id="contacto">
        <h2>Padaria Venepão</h2>
        <p>📍 Rua Principal, Nº 123 - Venda do Pinheiro (Exemplo)</p>
        <p>📞 Tel: 210 000 000</p>
        <p>⏰ Aberto todos os dias: 07:00 - 20:00</p>
        <hr style="border: 0.5px solid #666; width: 50%;">
        <p>&copy; 2024 Padaria Venepão - Todos os direitos reservados.</p>
    </footer>

    <a href="https://wa.me/351912345678" class="whatsapp-float" target="_blank">
        📱 Encomendar via WhatsApp
    </a>

</body>
</html>
