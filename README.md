<!DOCTYPE html>
<html lang="sv">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Martas Julbutik</title>
    <style>
        /* Allmänna stilar */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            background-image: url('https://www.publicdomainpictures.net/pictures/20000/velka/christmas-tree-1412353584t1l.jpg'); /* Julig bakgrundsbild */
            background-size: cover;
            background-position: center;
            color: #fff;
        }

        /* Header */
        header {
            background-color: rgba(255, 99, 71, 0.8); /* Transparent tomatröd */
            color: white;
            text-align: center;
            padding: 50px 20px;
            border-bottom: 10px solid #b22222; /* Mörkröd kant */
            box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.2); /* Skugga för djup */
            background-image: url('https://www.publicdomainpictures.net/pictures/90000/velka/christmas-tree-1549049069zMc.jpg'); /* Julig bakgrundsbild */
            background-size: cover;
            background-position: center;
        }

        header h1 {
            font-size: 3.5em;
            margin: 0;
            font-weight: bold;
            text-shadow: 2px 2px 8px rgba(0, 0, 0, 0.5); /* Textskugga för bättre läsbarhet */
        }

        header p {
            font-size: 1.5em;
            margin-top: 10px;
            font-style: italic;
            font-weight: lighter;
        }

        /* Produkter */
        .products {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            margin: 40px 0;
            padding: 0 20px;
        }

        .product {
            background-color: #fff;
            border-radius: 15px;
            box-shadow: 0 6px 15px rgba(0, 0, 0, 0.1);
            padding: 30px;
            text-align: center;
            width: 30%;
            margin: 20px;
            transition: transform 0.3s ease-in-out;
            overflow: hidden;
            position: relative;
            background-color: #fffaf0; /* Ljusgul bakgrund för produkten */
            border: 2px solid #ff6347; /* Röd kant */
            animation: fadeIn 1s ease-out; /* Animering */
        }

        @keyframes fadeIn {
            0% { opacity: 0; }
            100% { opacity: 1; }
        }

        .product:hover {
            transform: translateY(-15px);
        }

        .product img {
            width: 100%;
            height: 250px;
            object-fit: cover;
            border-radius: 10px;
            transition: transform 0.3s ease-in-out;
            margin-bottom: 15px;
        }

        .product img:hover {
            transform: scale(1.1);
        }

        .product h2 {
            font-size: 1.8em;
            color: #8b0000; /* Mörkröd färg */
            margin-top: 15px;
            font-family: 'Georgia', serif;
        }

        .product p {
            font-size: 1.2em;
            color: #555;
            margin-top: 10px;
            padding: 0 10px;
            font-family: 'Verdana', sans-serif;
        }

        .product button {
            background-color: #ff4500; /* Orangeröd knapp */
            border: none;
            color: white;
            padding: 15px 30px;
            font-size: 1.2em;
            cursor: pointer;
            border-radius: 30px;
            margin-top: 20px;
            transition: background-color 0.3s ease;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .product button:hover {
            background-color: #b22222; /* Mörkare röd vid hover */
        }

        /* Footer */
        footer {
            background-color: #ff6347; /* Tomatröd bakgrund */
            color: white;
            text-align: center;
            padding: 25px;
            font-size: 1.3em;
            position: relative;
            bottom: 0;
            width: 100%;
            border-top: 10px solid #b22222; /* Mörkröd kant */
            box-shadow: 0px -4px 10px rgba(0, 0, 0, 0.1); /* Skugga */
            font-family: 'Verdana', sans-serif;
        }

        /* Responsiv design */
        @media (max-width: 768px) {
            .products {
                flex-direction: column;
                align-items: center;
            }

            .product {
                width: 80%;
                margin-bottom: 30px;
            }

            header h1 {
                font-size: 2.5em;
            }

            header p {
                font-size: 1.2em;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Välkommen till Martas Julbutik!</h1>
        <p>Hitta de bästa julklapparna till dina nära och kära</p>
    </header>
    <main>
        <section class="products">
            <div class="product">
                <img src="https://via.placeholder.com/200" alt="Produkt 1">
                <h2>Produkt 1</h2>
                <p>Den perfekta julklappen för alla</p>
                <button>Köp nu</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/200" alt="Produkt 2">
                <h2>Produkt 2</h2>
                <p>En present som sprider värme</p>
                <button>Köp nu</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/200" alt="Produkt 3">
                <h2>Produkt 3</h2>
                <p>Ge bort något speciellt denna jul</p>
                <button>Köp nu</button>
            </div>
        </section>
    </main>
    <footer>
        <p>© 2024 Martas Julbutik. Alla rättigheter förbehållna.</p>
    </footer>
</body>
</html>
