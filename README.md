<!DOCTYPE html>
<html lang="sv">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Martas Julbutik</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: 'Arial', sans-serif;
            color: #333;
            background: linear-gradient(to bottom, #ffecd2, #fcb69f); /* Mjuka julfärger */
        }

        header {
            text-align: center;
            background-color: #ffe5e0; /* Ljusrosa för värme */
            padding: 20px;
            border-bottom: 3px solid #d87c70;
            box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.2);
        }

        header h1 {
            font-size: 2.5rem;
            margin: 0;
            color: #d85740;
            text-shadow: 1px 1px 3px #fff;
        }

        header p {
            font-size: 1.2rem;
            margin: 10px 0 0;
            color: #994c3e;
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
            background-color: #fff6f0; /* Ljus bakgrund för kontrast */
            color: #5c4033;
            border-radius: 10px;
            text-align: center;
            box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.2);
            width: 280px;
            padding: 20px;
            transition: transform 0.2s ease, box-shadow 0.2s ease;
        }

        .product:hover {
            transform: translateY(-5px);
            box-shadow: 0px 8px 20px rgba(0, 0, 0, 0.3);
        }

        .product img {
            width: 100%;
            border-radius: 10px;
            margin-bottom: 15px;
        }

        .product h2 {
            font-size: 1.5rem;
            margin-bottom: 10px;
            color: #b84c34;
        }

        .product p {
            font-size: 1rem;
            margin-bottom: 15px;
            color: #6d3b27;
        }

        .product button {
            background-color: #f4a261; /* Ljus orange för värme */
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 10px;
            cursor: pointer;
            font-size: 1rem;
            transition: background-color 0.2s ease;
        }

        .product button:hover {
            background-color: #e76f51;
        }

        footer {
            text-align: center;
            background-color: #ffdccb; /* Ljus korallfärg för avslutning */
            padding: 20px;
            margin-top: 20px;
            color: #5a2f20;
            box-shadow: 0px -4px 10px rgba(0, 0, 0, 0.2);
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
                <img src="https://via.placeholder.com/300x200/ffccb3/fff?text=Produkt+1" alt="Produkt 1">
                <h2>Produkt 1</h2>
                <p>Beskrivning av produkt 1</p>
                <button>Köp nu</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/300x200/ffe0cc/fff?text=Produkt+2" alt="Produkt 2">
                <h2>Produkt 2</h2>
                <p>Beskrivning av produkt 2</p>
                <button>Köp nu</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/300x200/fbd1b7/fff?text=Produkt+3" alt="Produkt 3">
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
