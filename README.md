<!DOCTYPE html>
<html lang="sv">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Martas Julbutik</title>
    <style>
        /* Global styles */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            background-image: url('https://your-image-url.com/julbakgrund.jpg'); /* Lägg till din julbakgrundsbild */
            background-size: cover;
            background-position: center;
            color: #fff;
        }

        .container {
            width: 80%;
            margin: 0 auto;
            text-align: center;
        }

        /* Header styles */
        .header {
            background-color: rgba(255, 0, 0, 0.5); /* Transparent röd */
            padding: 50px 0;
            text-align: center;
        }

        .header h1 {
            font-size: 3rem;
            margin-bottom: 10px;
        }

        .header p {
            font-size: 1.2rem;
            margin-bottom: 20px;
        }

        .btn-main {
            padding: 10px 20px;
            font-size: 1.2rem;
            background-color: #fff;
            color: #d40000;
            border: none;
            cursor: pointer;
            text-transform: uppercase;
            font-weight: bold;
        }

        .btn-main:hover {
            background-color: #d40000;
            color: white;
        }

        /* Product section styles */
        .products {
            display: flex;
            justify-content: space-around;
            margin-top: 50px;
            padding: 50px 0;
            background-color: rgba(0, 0, 0, 0.3); /* Lätt mörkare bakgrund för kontrast */
        }

        .product {
            background-color: rgba(255, 255, 255, 0.8); /* Lätt bakgrund för produktkort */
            border-radius: 10px;
            padding: 20px;
            width: 250px;
            text-align: center;
        }

        .product img {
            max-width: 100%;
            height: auto;
            border-radius: 5px;
        }

        .product h2 {
            font-size: 1.5rem;
            margin: 10px 0;
        }

        .product p {
            font-size: 1rem;
            margin-bottom: 20px;
        }

        .btn-buy {
            padding: 10px 20px;
            font-size: 1rem;
            background-color: #d40000;
            color: white;
            border: none;
            cursor: pointer;
            text-transform: uppercase;
            font-weight: bold;
            border-radius: 5px;
        }

        .btn-buy:hover {
            background-color: #9c0000;
        }

        /* Footer styles */
        footer {
            text-align: center;
            background-color: #222;
            padding: 20px;
            color: #fff;
        }

        footer p {
            margin: 0;
            font-size: 1rem;
        }
    </style>
</head>
<body>
    <!-- Header Section -->
    <header class="header">
        <div class="container">
            <h1>Välkommen till Martas Julbutik!</h1>
            <p>Hitta perfekta julklappar till dina nära och kära!</p>
            <button class="btn-main">SHOPPA NU</button>
        </div>
    </header>

    <!-- Products Section -->
    <section class="products">
        <div class="container">
            <div class="product">
                <img src="https://via.placeholder.com/300" alt="Produkt 1">
                <h2>Produkt 1</h2>
                <p>Beskrivning av produkt 1</p>
                <button class="btn-buy">Köp nu</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/300" alt="Produkt 2">
                <h2>Produkt 2</h2>
                <p>Beskrivning av produkt 2</p>
                <button class="btn-buy">Köp nu</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/300" alt="Produkt 3">
                <h2>Produkt 3</h2>
                <p>Beskrivning av produkt 3</p>
                <button class="btn-buy">Köp nu</button>
            </div>
        </div>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>© 2024 Martas Julbutik. Alla rättigheter förbehållna.</p>
    </footer>
</body>
</html>
