<!DOCTYPE html>
<html lang="sv">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Martas Julbutik</title>
    <style>
        /* Färger */
        :root {
            --cinnamon-milk: #D7B49E; /* Ljus, varm beige nyans */
            --jolly-berry: #D83A56;   /* Djup julröd färg */
            --yule-log: #705E4E;      /* Mörk träfärgad brun */
            --evergreen-mist: #5A6E58; /* Dämpad grön för en julig känsla */
        }

        /* Allmän styling */
        body {
            margin: 0;
            font-family: 'Arial', sans-serif;
            background-color: var(--cinnamon-milk);
            color: var(--yule-log);
            line-height: 1.6;
        }

        header {
            text-align: center;
            background-color: var(--evergreen-mist);
            color: var(--cinnamon-milk);
            padding: 20px;
            border-bottom: 5px solid var(--jolly-berry);
        }

        header h1 {
            font-size: 2.5rem;
            margin: 0;
            text-shadow: 2px 2px var(--yule-log);
        }

        header p {
            font-size: 1.2rem;
            margin-top: 10px;
        }

        main {
            padding: 20px;
        }

        .products {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
        }

        .product {
            background-color: var(--cinnamon-milk);
            color: var(--yule-log);
            border: 1px solid var(--evergreen-mist);
            border-radius: 10px;
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
            color: var(--jolly-berry);
        }

        .product p {
            font-size: 1rem;
            margin-bottom: 15px;
        }

        .product button {
            background-color: var(--jolly-berry);
            color: var(--cinnamon-milk);
            border: none;
            padding: 10px 20px;
            border-radius: 10px;
            cursor: pointer;
            font-size: 1rem;
            transition: background-color 0.3s ease;
        }

        .product button:hover {
            background-color: var(--evergreen-mist);
        }

        footer {
            text-align: center;
            background-color: var(--yule-log);
            color: var(--cinnamon-milk);
            padding: 20px;
            margin-top: 20px;
            border-top: 5px solid var(--jolly-berry);
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
                <img src="https://via.placeholder.com/300x200/D83A56/FFFFFF?text=Produkt+1" alt="Produkt 1">
                <h2>Produkt 1</h2>
                <p>Beskrivning av produkt 1</p>
                <button>Köp nu</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/300x200/5A6E58/FFFFFF?text=Produkt+2" alt="Produkt 2">
                <h2>Produkt 2</h2>
                <p>Beskrivning av produkt 2</p>
                <button>Köp nu</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/300x200/D7B49E/FFFFFF?text=Produkt+3" alt="Produkt 3">
                <h2>Produkt 3</h2>
                <p>Beskrivning av produkt 3</p>
                <button>Köp nu</button>
            </div>
        </section>
    </main>
    <footer>
        <p>© 2024 Martas Julbutik. Alla rättigheter förbehållna.</p>
    </footer>
</body>
</html>
