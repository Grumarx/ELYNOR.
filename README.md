<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <title>ELYNOR - Streetwear Japonês</title>
    <style>
        body {
            margin: 0;
            font-family: 'Arial', sans-serif;
            background: #111;
            color: #fff;
        }

        /* HEADER */
        header {
            background: #000;
            color: #fff;
            padding: 80px 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 64px;
            letter-spacing: 4px;
            color: #e60000; /* Vermelho destaque */
        }
        header p {
            margin-top: 10px;
            font-size: 20px;
            color: #fff;
        }

        /* SOBRE A MARCA */
        .sobre {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            align-items: center;
            padding: 60px 20px;
            background: #111;
            gap: 40px;
        }
        .sobre img {
            width: 350px;
            border-radius: 12px;
            border: 2px solid #e60000;
        }
        .sobre-texto {
            max-width: 500px;
        }
        .sobre-texto h2 {
            margin-top: 0;
            color: #e60000;
            font-size: 36px;
        }
        .sobre-texto p {
            font-size: 18px;
            line-height: 1.6;
            color: #ddd;
        }

        /* CTA */
        .cta {
            text-align: center;
            padding: 60px 20px;
            background: #000;
        }
        .cta h2 {
            color: #e60000;
            font-size: 32px;
            margin-bottom: 20px;
        }
        .cta button {
            padding: 15px 40px;
            font-size: 18px;
            background: #e60000;
            color: #fff;
            border: none;
            cursor: pointer;
            border-radius: 6px;
            transition: 0.2s;
        }
        .cta button:hover {
            background: #fff;
            color: #000;
        }

        /* FOOTER */
        footer {
            text-align: center;
            padding: 20px;
            background: #111;
            color: #888;
            font-size: 14px;
            border-top: 1px solid #e60000;
        }

        /* RESPONSIVO */
        @media(max-width: 800px) {
            .sobre {
                flex-direction: column;
            }
            .sobre img {
                width: 80%;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>ELYNOR</h1>
    <p>Streetwear Japonês | Hoodies únicos com estilo urbano</p>
</header>

<section class="sobre">
    <img src="https://via.placeholder.com/350x450?text=Hoodie+ELYNOR" alt="Hoodie ELYNOR">
    <div class="sobre-texto">
        <h2>Sobre a ELYNOR</h2>
        <p>
            ELYNOR nasceu da paixão pela cultura urbana japonesa e pelo streetwear que combina conforto, design exclusivo e atitude. Nossos hoodies são feitos para quem quer se destacar sem abrir mão do estilo. Cada peça carrega a essência do Japão e da rua, com detalhes que fazem toda a diferença.
        </p>
    </div>
</section>

<div class="cta">
    <h2>Quer conhecer nossa coleção?</h2>
    <button>Entre em Contato</button>
</div>

<footer>
    © 2025 ELYNOR — Todos os direitos reservados
</footer>

</body>
</html>
