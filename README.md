<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Shalimar — Restaurant</title>

    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        html {
            scroll-behavior: smooth;
        }

        body {
            font-family: Arial, sans-serif;
            background: #fffaf4;
            color: #2b2118;
        }

        /* MENU */
        nav {
            position: fixed;
            top: 0;
            width: 100%;
            padding: 18px 8%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            background: rgba(255,255,255,0.95);
            z-index: 10;
            box-shadow: 0 2px 15px rgba(0,0,0,0.08);
        }

        .logo {
            font-size: 27px;
            font-weight: bold;
            letter-spacing: 2px;
        }

        nav a {
            color: #2b2118;
            text-decoration: none;
            margin-left: 25px;
            font-weight: bold;
        }

        /* ACCUEIL */
        .hero {
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            padding: 100px 20px 50px;

            background:
                linear-gradient(rgba(0,0,0,0.45), rgba(0,0,0,0.45)),
                url("https://images.unsplash.com/photo-1517248135467-4c7edcad34c4?auto=format&fit=crop&w=1600&q=80")
                center/cover;
        }

        .hero-content {
            color: white;
            max-width: 800px;
        }

        .hero h1 {
            font-size: clamp(55px, 10vw, 100px);
            margin-bottom: 10px;
            letter-spacing: 5px;
        }

        .hero p {
            font-size: 22px;
            margin-bottom: 35px;
        }

        .button {
            display: inline-block;
            padding: 16px 32px;
            background: #d69a45;
            color: white;
            text-decoration: none;
            border-radius: 50px;
            font-weight: bold;
            font-size: 17px;
            transition: 0.3s;
        }

        .button:hover {
            transform: translateY(-4px);
            background: #b87929;
        }

        /* PLATS */
        section {
            padding: 80px 8%;
        }

        .title {
            text-align: center;
            font-size: 40px;
            margin-bottom: 50px;
        }

        .menu {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
            max-width: 1100px;
            margin: auto;
        }

        .card {
            background: white;
            border-radius: 20px;
            overflow: hidden;
            box-shadow: 0 8px 25px rgba(0,0,0,0.1);
            transition: 0.3s;
        }

        .card:hover {
            transform: translateY(-8px);
        }

        .card img {
            width: 100%;
            height: 220px;
            object-fit: cover;
        }

        .card-content {
            padding: 22px;
        }

        .card h3 {
            font-size: 23px;
            margin-bottom: 8px;
        }

        .card p {
            color: #777;
            line-height: 1.5;
            margin-bottom: 15px;
        }

        .price {
            font-size: 21px;
            font-weight: bold;
            color: #c47f27;
        }

        /* CONTACT */
        .contact {
            text-align: center;
            background: #2b2118;
            color: white;
        }

        .contact p {
            margin: 12px;
            font-size: 18px;
        }

        footer {
            text-align: center;
            padding: 20px;
            background: #17110d;
            color: white;
        }

        @media (max-width: 600px) {
            nav {
                padding: 15px 5%;
            }

            nav a {
                margin-left: 10px;
                font-size: 13px;
            }

            .hero p {
                font-size: 18px;
            }
        }
    </style>
</head>

<body>

    <!-- MENU -->
    <nav>
        <div class="">SHALIMAR</div>

        <div>
            <a href="#accueil">Accueil</a>
            <a href="#menu">Menu</a>
            <a href="#contact">Contact</a>
        </div>
    </nav>

    <!-- ACCUEIL -->
    <section class="hero" id="accueil">
        <div class="hero-content">
            <h1>SHALIMAR</h1>

            <p>
                Une cuisine savoureuse, préparée avec passion.
            </p>

            <a class="button" href="#menu">
                Découvrir nos plats 🍽️
            </a>
        </div>
    </section>

    <!-- MENU -->
    <section id="menu">
        <h2 class="title">Nos plats</h2>

        <div class="menu">

            <div class="card">
                <img src="https://images.unsplash.com/photo-1565299624946-b28f40a0ae38?auto=format&fit=crop&w=900&q=80">

                <div class="card-content">
                    <h3>Pizza Maison</h3>
                    <p>Pizza préparée avec des ingrédients frais.</p>
                    <div class="price">10 €</div>
                </div>
            </div>

            <div class="card">
                <img src="https://images.unsplash.com/photo-1546069901-ba9599a7e63c?auto=format&fit=crop&w=900&q=80">

                <div class="card-content">
                    <h3>Salade Fraîche</h3>
                    <p>Une salade fraîche et pleine de saveurs.</p>
                    <div class="price">7 €</div>
                </div>
            </div>

            <div class="card">
                <img src="https://images.unsplash.com/photo-1551183053-bf91a1d81141?auto=format&fit=crop&w=900&q=80">

                <div class="card-content">
                    <h3>Pâtes</h3>
                    <p>Pâtes savoureuses préparées maison.</p>
                    <div class="price">9 €</div>
                </div>
            </div>

            <div class="card">
                <img src="https://images.unsplash.com/photo-1551024506-0bccd828d307?auto=format&fit=crop&w=900&q=80">

                <div class="card-content">
                    <h3>Dessert</h3>
                    <p>Une douceur pour terminer votre repas.</p>
                    <div class="price">5 €</div>
                </div>
            </div>

        </div>
    </section>

    <!-- CONTACT -->
    <section class="contact" id="contact">
        <h2 class="title">Nous trouver</h2>

        <p>📍 4ruejeantherond</p>
        <p>📞 0610700379 </p>
        <p>🕐 Ouvert tous les jours</p>
    </section>

    <footer>
        © 2026 Shalimar — Tous droits réservés
    </footer>

</body>
</html>
