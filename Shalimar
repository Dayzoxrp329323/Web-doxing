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
            background: white;
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

            /* PHOTO D'ENTRÉE */
            background-image.jpg:
                linear-gradient(rgba(0,0,0,0.45), rgba(0,0,0,0.45)),
                url("image.jpg");

            background-size: cover;
            background-position: center;
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

        /* SECTIONS */
        section {
            padding: 80px 8%;
        }

        .title {
            text-align: center;
            font-size: 40px;
            margin-bottom: 50px;
        }

        /* MENU */
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

        /* PHOTO DES PLATS */
        .card img {
            width: 100%;
            height: 220px;
            object-fit: cover;
            display: block;
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

        /* VIDÉO */
        .video-section {
            background: #f1e7dc;
            text-align: center;
        }

        .video-box {
            max-width: 900px;
            margin: auto;
        }

        .video-box video {
            width: 100%;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.15);
        }

        /* MUSIQUE */
        .music-section {
            text-align: center;
        }

        .music-box {
            max-width: 600px;
            margin: auto;
            padding: 35px;
            background: white;
            border-radius: 20px;
            box-shadow: 0 8px 25px rgba(0,0,0,0.1);
        }

        .music-box p {
            margin-bottom: 20px;
            font-size: 20px;
        }

        .music-box audio {
            width: 100%;
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

        /* TELEPHONE */
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


    <!-- ========================= -->
    <!-- MENU -->
    <!-- ========================= -->

    <nav>

        <div class="logo">
            SHALIMAR
        </div>

        <div>
            <a href="#accueil">Accueil</a>
            <a href="#menu">Menu</a>
            <a href="#video">Vidéo</a>
            <a href="#contact">Contact</a>
        </div>

    </nav>


    <!-- ========================= -->
    <!-- ACCUEIL -->
    <!-- ========================= -->

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


    <!-- ========================= -->
    <!-- MENU / PLATS -->
    <!-- ========================= -->

    <section id="menu">

        <h2 class="title">
            Nos plats
        </h2>

        <div class="menu">


            <!-- PLAT 1 -->
            <div class="card">

                <!-- PHOTO -->
                <img src="photot.jpg" alt="Photo du plat">

                <div class="card-content">

                    <h3>
                        Pizza Maison
                    </h3>

                    <p>
                        Pizza préparée avec des ingrédients frais.
                    </p>

                    <div class="price">
                        10 €
                    </div>

                </div>

            </div>


            <!-- PLAT 2 -->
            <div class="card">

                <!-- PHOTO -->
                <img src="photo.jpg" alt="Photo du plat">

                <div class="card-content">

                    <h3>
                        Salade Fraîche
                    </h3>

                    <p>
                        Une salade fraîche et pleine de saveurs.
                    </p>

                    <div class="price">
                        7 €
                    </div>

                </div>

            </div>


            <!-- PLAT 3 -->
            <div class="card">

                <!-- PHOTO -->
                <img src="logo.jpg" alt="Photo du plat">

                <div class="card-content">

                    <h3>
                        Pâtes
                    </h3>

                    <p>
                        Pâtes savoureuses préparées maison.
                    </p>

                    <div class="price">
                        9 €
                    </div>

                </div>

            </div>


            <!-- PLAT 4 -->
            <div class="card">

                <!-- PHOTO -->
                <img src="photo.jpg" alt="Photo du plat">

                <div class="card-content">

                    <h3>
                        Dessert
                    </h3>

                    <p>
                        Une douceur pour terminer votre repas.
                    </p>

                    <div class="price">
                        5 €
                    </div>

                </div>

            </div>


        </div>

    </section>


    <!-- ========================= -->
    <!-- VIDÉO -->
    <!-- ========================= -->

    <section class="video-section" id="video">

        <h2 class="title">
            Découvrez Shalimar 🎥
        </h2>

        <div class="video-box">

            <!-- METS TA VIDÉO ICI -->
            <video controls>

                <source
                    src="VIDEO-RESTAURANT.mp4"
                    type="video/mp4"
                >

                Votre navigateur ne peut pas lire cette vidéo.

            </video>

        </div>

    </section>


    <!-- ========================= -->
    <!-- MUSIQUE -->
    <!-- ========================= -->

    <section class="music-section">

        <h2 class="title">
            Notre ambiance 🎵
        </h2>

        <div class="music-box">

            <p>
                🎶 Musique de Shalimar
            </p>

            <!-- METS TA MUSIQUE ICI -->
            <audio controls>

                <source
                    src="MUSIQUE.mp3"
                    type="audio/mpeg"
                >

                Votre navigateur ne peut pas lire cette musique.

            </audio>

        </div>

    </section>


    <!-- ========================= -->
    <!-- CONTACT -->
    <!-- ========================= -->

    <section class="contact" id="contact">

        <h2 class="title">
            Nous trouver
        </h2>

        <p>
            📍 6 Place Saint Jean
        </p>

        <p>
            📞 0610700379
        </p>

        <p>
            🕐 Ouvert 7/7
        </p>

    </section>


    <!-- ========================= -->
    <!-- FOOTER -->
    <!-- ========================= -->

    <footer>

        © 2026 Shalimar — Tous droits réservés

    </footer>


</body>
</html>
