<!DOCTYPE html>
<html lang="sv">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Martas Julbutik</title>
    <style>
        /* Variabler för färger */
        :root {
            --header-red: #A43C3F; /* Mjuk röd nyans för header */
            --gold: #D5B194; /* Guldnyans för detaljer */
            --dark-green: #484037; /* Mörkgrön för bakgrund och text */
            --snow-white: #F9F5F2; /* Vit för huvudbakgrund */
        }

        /* Allmän styling */
        body {
            margin: 0;
            font-family: 'Arial', sans-serif;
            background-color: var(--snow-white);
            color: var(--dark-green);
            line-height: 1.6;
        }

        header {
            background-color: var(--header-red);
            color: var(--gold);
            text-align: center;
            padding: 30px 20px;
            border-bottom: 5px solid var(--gold);
        }

        header h1 {
            margin: 0;
            font-size: 2.8rem;
            text-shadow: 2px 2px var(--dark-green);
        }

        header p {
            font-size: 1.3rem;
            margin-top: 10px;
        }

        main {
            padding: 30px 20px;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        .products {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 25px;
            max-width: 1200px;
        }

        .product {
            background-color: var(--gold);
            color: var(--dark-green);
            border-radius: 15px;
            text-align: center;
            padding: 20px;
            width: 280px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .product:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.3);
        }

        .product img {
            width: 100%;
            border-radius: 10px;
            margin-bottom: 15px;
        }

        .product h2 {
            font-size: 1.5rem;
            margin-bottom: 10px;
        }

        .product p {
            font-size: 1rem;
            margin-bottom: 15px;
        }

        .product button {
            background-color: var(--header-red);
            color: var(--gold);
            border: none;
            padding: 10px 20px;
            border-radius: 10px;
            cursor: pointer;
            font-size: 1rem;
            transition: background-color 0.3s ease;
        }

        .product button:hover {
            background-color: var(--dark-green);
            color: var(--gold);
        }

        footer {
            text-align: center;
            background-color: var(--dark-green);
            color: var(--gold);
            padding: 20px;
            margin-top: 20px;
            border-top: 5px solid var(--header-red);
        }

        footer p {
            margin: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Välkommen till Martas Julbutik!</h1>
        <p>Hitta perfekta julklappar till dina nära och kära!</p>
    </header>
    <main>
        <section class="products">
            <div class="product">
                <img src="https://via.placeholder.com/150" alt="Produkt 1">
                <h2>Julgranskula</h2>
                <p>Elegant dekoration för din julgran.</p>
                <button>Köp nu</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/150" alt="Produkt 2">
                <h2>Doftljus</h2>
                <p>Sprider en mysig julkänsla i hemmet.</p>
                <button>Köp nu</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/150" alt="Produkt 3">
                <h2>Julstrumpa</h2>
                <p>Perfekt för små presenter och godis.</p>
                <button>Köp nu</button>
            </div>
        </section>
    </main>
    <footer>
        <p>© 2024 Martas Julbutik. Alla rättigheter förbehållna.</p>
    </footer>
</body>
</html>
