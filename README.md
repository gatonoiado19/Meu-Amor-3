# Meu-Amor-3
Um site feito para que eu possa demonstrar que eu amo minha mulher.
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>Nosso Amor</title>

    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500;700&family=Poppins:wght@300;400&display=swap" rel="stylesheet">

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Poppins', sans-serif;
            background: linear-gradient(135deg, #ffdde1, #ee9ca7);
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .card {
            background: #ffffff;
            width: 90%;
            max-width: 700px;
            border-radius: 20px;
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.15);
            padding: 40px;
            text-align: center;
        }

        h1 {
            font-family: 'Playfair Display', serif;
            font-size: 2.5rem;
            color: #c44569;
            margin-bottom: 10px;
        }

        h2 {
            font-weight: 300;
            color: #555;
            margin-bottom: 30px;
        }

        .couple {
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 30px;
            margin-bottom: 30px;
            flex-wrap: wrap;
        }

        .person {
            text-align: center;
        }

        .person img {
            width: 140px;
            height: 140px;
            border-radius: 50%;
            object-fit: cover;
            border: 4px solid #ee9ca7;
            margin-bottom: 10px;
        }

        .person h3 {
            font-size: 1.2rem;
            color: #333;
        }

        .heart {
            font-size: 2.5rem;
            color: #e84393;
        }

        .story {
            font-size: 1rem;
            color: #666;
            line-height: 1.6;
        }

        footer {
            margin-top: 25px;
            font-size: 0.9rem;
            color: #999;
        }
    </style>
</head>

<body>

    <div class="card">
        <h1>Nosso Amor</h1>
        <h2>Te amo meu amor</h2>

        <div class="couple">
            <div class="person">
                <img src="c:\Users\gaton\Downloads\Captura de tela 2026-01-30 014522.png" alt="Pessoa 1">
                <h3>Geovanna</h3>
            </div>

            <div class="heart">❤️</div>

            <div class="person">
                <img src="c:\Users\gaton\Downloads\Captura de tela 2026-01-30 013825.png" alt="Pessoa 2">
                <h3>Bruno</h3>
            </div>
        </div>

        <p class="story">
            Graças a Deus, desde que conheci você minha vida só melhorou, fui crescendo como pessoa
            e aprendendo cada dia mais sobre você e eu.

            Eu te amo mais que tudo meu amor!
        </p>

        <footer>
            Desde 2018 ✨
        </footer>
    </div>

</body>
</html>
