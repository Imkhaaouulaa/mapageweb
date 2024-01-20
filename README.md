<html>
<head>
 
    <title>Portfolio de Photographie</title>
    <style>
    /* Ajoutez une classe spécifique à l'élément à masquer */
a[href="https://imkhaaouulaa.github.io/monportfolio/"] {
    /* Ajoutez vos styles CSS spécifiques pour ce lien ici */
    color: red; /* Exemple: Changez la couleur du texte en rouge */
    text-decoration: underline; /* Exemple: Ajoutez une soulignement */
    /* Autres styles */
}


        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            background-color: #f4f4f4;
        }
    
.professional-intro {
    margin-bottom: 20px; /* Ajoutez une marge en bas pour séparer du .gallery-container */
}
.paragraph {   display: -webkit-box;
    -webkit-box-orient: vertical;
    overflow: hidden;
    -webkit-line-clamp:3 ; 
    line-height: 1.5;
    height: 3em;
    }
    .professional-intro {
        margin-bottom: 20px;
    }

    .gallery-container {
        margin-top: 1cm;
    }

        header {
            background: linear-gradient(to right, #e4b67b, #c2ee6b, #daeeb3, #f3c3e3, #daeeb3, #c2ee6b, #e4b67b);
            height: 120px;
            text-align: center;
            font-size: 22px;
            color: #3f2b0c;
            padding: 19px;
            animation: gradientAnimation 5s infinite;
        }

        @keyframes gradientAnimation {
            0% {
                background-position: 0% 50%;
            }
            100% {
                background-position: 100% 50%;
            }
        }

        .scrollbar-container {
            overflow-x: hidden;
        }

        .gallery-container {
            display: flex;
            align-items: center;
            overflow-x: scroll;
            scroll-snap-type: x proximity;
            width: 100%;
            margin-bottom: 2em;
        }

        .gallery {
            display: flex;
            gap: 2cm;
            padding: 16px;
            scroll-snap-points-x: repeat(100%);
        }

       .image-container {
    position: relative;
    overflow: hidden;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease-in-out, box-shadow 0.3s ease-in-out;
    
    width: 300px;
    height: 400px;
}

.gallery img {
    max-height: 400px; /* Ajustez cette valeur selon vos besoins */
    width: auto;
    height: auto;
    scroll-snap-align: start;
    margin-right: 1cm;
    transition: transform 0.3s ease-in-out;
}

        .gallery img:hover {
            transform: scale(1.2);
        }

        .image-container:hover {
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
            transform: translateY(-5px);
        }

        .image-overlay {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.5);
            opacity: 0;
            transition: opacity 0.3s ease-in-out;
        }

        .image-container:hover .image-overlay {
            opacity: 1;
            transition-delay: 0.1s;
        }

        .image-description {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            width: 100%;
            text-align: center;
            padding: 20px;
            color: white;
            opacity: 0;
            transition: opacity 0.3s ease-in-out;
        }

        .image-container:hover .image-description {
            opacity: 1;
            transition-delay: 0.2s;
        }

        .footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1em;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        footer {
            background: #2b220b;
            color: white;
            text-align: center;
            padding: 1em;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        footer p {
            margin: 0;
            font-size: 18px;
        }

        .professional-intro {
            text-align: center;
            padding: 20px;
            background-color: #caf78f;
            margin-bottom: 2em;
            border-radius: 3px;
        }
       

        form {
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 10px;
        }

        .countdown {
            text-align: center;
            margin-top: 20px;
            background-color: #caf78f;
            border-radius: 3px;
            font-size: 32px;
            color: #20201f;
            margin-bottom: 70px;
        }

        .countdown span {
            display: inline-block;
            margin: 0 10px;
            padding: 15px;
            background-color: #1d1818;
            color: rgb(136, 46, 46);
            border-radius: 10px;
            box-shadow: 0 4px 8px rgb(49, 5, 5);
            border: 2px solid #333;
            position: relative;
        }

        .countdown span::before {
            content: '\231B';
            font-size: 20px;
            margin-right: 8px;
        }
      
    </style>
</head>
<body>
    <header>
        <h1>Mon Portfolio de Photographie</h1>
        <p div class="paragraph">Explorez l'essence de moments capturés, saisis à travers le regard unique de mon objectif photographique.</p>
    </header>

      <!-- Conteneur pour la barre de défilement et la galerie -->

   <div class="scrollbar-container">

    <div class="gallery-container">

      <div class="gallery">

        <div class="image-container" style="z-index: 0;">

          <img src="dd.jpg" alt="Image 1">

          <div class="image-overlay"></div>

          <div class="image-description">Sous le Toit d'une Canopée Florissante</div>

        </div>

        <div class="image-container">

          <img src="cc.jpg" alt="Image 2">

          <div class="image-overlay"></div>

          <div class="image-description">La fontaine, dépourvue d'eau, repose telle une sculpture d'éclat minéral dans le jardin</div>

        </div>

        <div class="image-container">

          <img src="IMG-20231221-WA0011.jpg" alt="Image 3">

          <div class="image-overlay"></div>

          <div class="image-description">Ballet des Flamants.</div>

        </div>

        <div class="image-container">

          <img src="IMG-20231221-WA0013.jpg" alt="Image 4">

          <div class="image-overlay"></div>

          <div class="image-description">Maison Douillette.</div>

        </div>

        <div class="image-container">

          <img src="IMG-20231221-WA0014.jpg" alt="Image 5">

          <div class="image-overlay"></div>

          <div class="image-description">À la rencontre du monde fascinant des singes.</div>

        </div>

        <div class="image-container">

          <img src="IMG-20231221-WA0015.jpg" alt="Image 6">

          <div class="image-overlay"></div>

          <div class="image-description">L'Élégance Imposante des Éléphants.</div>

        </div>

        <div class="image-container">

          <img src="IMG-20231221-WA0016.jpg" alt="Image 7">

          <div class="image-overlay"></div>

          <div class="image-description">Les Oiseaux en Harmonie dans le Ciel.</div>

        </div>

        <div class="image-container">

          <img src="IMG-20231221-WA0017.jpg" alt="Image 8">

          <div class="image-overlay"></div>

          <div class="image-description">La Beauté Intemporelle d'un Oiseau.</div>

        </div>

        <div class="image-container">

          <img src="aa.jpg" alt="Image 9">

          <div class="image-overlay"></div>

          <div class="image-description">Élégance et Couleurs Vibrantes.</div>

        </div>

        <div class="image-container">

          <img src="bb.jpg" alt="Image 10">

          <div class="image-overlay"></div>

          <div class="image-description">Les Arbres, Gardiens du Temps.</div>

        </div>

      </div>

    </div>

  </div>

    <footer>
        <p>© 2023 Mon Portfolio de Photographie</p>
    </footer>

    <div class="professional-intro">
        <p style="font-size: 22px; color: #000000; line-height: 1.5;">
            En tant que photographe passionné, j'ai développé une affinité particulière pour capturer la beauté éphémère de la nature.
            Mon objectif est de figer ces moments uniques et de les partager avec le monde, capturant l'essence même de la vie à travers mon objectif.
            Explorez mon portfolio et plongez dans un monde où chaque image raconte une histoire. C'est par amour pour ce domaine que je participe à ce concours.
        </p>
    </div>

    <div class="contest">
        <h2>Participez à notre concours et gagnez un shooting gratuit !</h2>
        <p>Remplissez le formulaire ci-dessous pour participer :</p>
        <form>
            <label for="first-name">Prénom: <input type="text" id="first-name" name="first-name" required=""></label>
            <label for="last-name">Nom: <input type="text" id="last-name" name="last-name" required=""></label>
            <label for="email">Email: <input type="email" id="email" name="email" required=""></label>
            <label for="gender">Genre:
                <input type="radio" id="female" name="gender" value="female">
                Femme
                <input type="radio" id="male" name="gender" value="male">
                Homme
            </label>
            <input type="submit" value="Participer au concours">
        </form>
    </div>

    <div class="countdown" id="countdown">Temps restant : 2 jours, 23 heures, 59 minutes, 37 secondes</div>

    <script>
        const gallery = document.querySelector('.gallery');

        gallery.addEventListener('mouseover', function (event) {
            const target = event.target.closest('.image-container');
            if (target) {
                target.style.zIndex = '1';
            }
        });

        gallery.addEventListener('mouseout', function (event) {
            const target = event.target.closest('.image-container');
            if (target) {
                target.style.zIndex = '0';
            }
        });
    </script>

    <script>
        const endDate = new Date();
        endDate.setDate(endDate.getDate() + 3);

        function updateCountdown() {
            const now = new Date();
            const difference = endDate - now;

            const days = Math.floor(difference / (1000 * 60 * 60 * 24));
            const hours = Math.floor((difference % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
            const minutes = Math.floor((difference % (1000 * 60 * 60)) / (1000 * 60));
            const seconds = Math.floor((difference % (1000 * 60)) / 1000);

            countdown.innerHTML = `Temps restant : ${days} jours, ${hours} heures, ${minutes} minutes, ${seconds} secondes`;

            if (difference <= 0) {
                countdown.innerHTML = "Le concours est terminé !";
            }
        }

        setInterval(updateCountdown, 1000);
    </script>
</body>
</html>



