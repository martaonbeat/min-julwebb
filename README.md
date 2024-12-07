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
            background-image: url('https://www.example.com/your-christmas-background.jpg');  no-repeat center center fixed;
    background-size: cover;
            background-size: cover;
            background-position: center;
            color: #fff;
        }

        .container {
            width: 90%;
            margin: 0 auto;
            text-align: center;
        }

        /* Header styles */
        .header {
            background-color: rgba(255, 0, 0, 0.6); /* Transparent röd */
            padding: 80px 0;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.2);
        }

        .header h1 {
            font-size: 4rem;
            margin-bottom: 15px;
            text-shadow: 3px 3px 5px rgba(0, 0, 0, 0.5);
        }

        .header p {
            font-size: 1.4rem;
            margin-bottom: 20px;
            font-style: italic;
        }

        .btn-main {
            padding: 15px 30px;
            font-size: 1.4rem;
            background-color: #fff;
            color: #d40000;
            border: none;
            cursor: pointer;
            text-transform: uppercase;
            font-weight: bold;
            border-radius: 5px;
            box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
        }

        .btn-main:hover {
            background-color: #d40000;
            color: white;
            transform: scale(1.1);
            transition: transform 0.2s ease-in-out;
        }

        /* Product section styles */
        .products {
            display: flex;
            justify-content: space-between;
            flex-wrap: wrap;
            margin-top: 70px;
            padding: 50px 0;
            background-color: rgba(0, 0, 0, 0.4); /* Lätt mörkare bakgrund för kontrast */
        }

        .product {
            background-color: rgba(255, 255, 255, 0.9); /* Lätt bakgrund för produktkort */
            border-radius: 15px;
            padding: 25px;
            width: 30%;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.2);
            margin-bottom: 40px;
            transition: transform 0.3s ease;
        }

        .product:hover {
            transform: scale(1.05);
        }

        .product img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.3);
        }

        .product h2 {
            font-size: 1.8rem;
            margin: 15px 0;
        }

        .product p {
            font-size: 1.2rem;
            margin-bottom: 20px;
        }

        .btn-buy {
            padding: 12px 25px;
            font-size: 1.2rem;
            background-color: #d40000;
            color: white;
            border: none;
            cursor: pointer;
            text-transform: uppercase;
            font-weight: bold;
            border-radius: 5px;
            transition: background-color 0.3s ease;
        }

        .btn-buy:hover {
            background-color: #9c0000;
            transform: scale(1.05);
        }

        /* Footer styles */
        footer {
            text-align: center;
            background-color: #222;
            padding: 30px;
            color: #fff;
            font-size: 1rem;
        }

        footer p {
            margin: 0;
        }

        /* Responsive design */
        @media (max-width: 768px) {
            .products {
                flex-direction: column;
                align-items: center;
            }

            .product {
                width: 80%;
                margin-bottom: 30px;
            }
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
                <p>Beskrivning av produkt 1. Perfekt för att skapa julstämning!</p>
                <button class="btn-buy">Köp nu</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/300" alt="Produkt 2">
                <h2>Produkt 2</h2>
                <p>Beskrivning av produkt 2. En julklapp som sprider glädje!</p>
                <button class="btn-buy">Köp nu</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/300" alt="Produkt 3">
                <h2>Produkt 3</h2>
                <p>Beskrivning av produkt 3. För den perfekta julhelgen!</p>
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
