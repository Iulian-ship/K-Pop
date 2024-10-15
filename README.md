<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>K-Pop World</title>
    <style>
        /* Stilizarea generală */
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f5;
            margin: 0;
            padding: 0;
        }

        /* Stilizarea pentru header și meniul de navigare */
        header {
            background-color: #ff66b2;
            color: white;
            padding: 20px;
            text-align: center;
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: #ff3399;
            padding: 10px 0;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }

        nav a:hover {
            text-decoration: underline;
        }

        /* Stilizarea pentru secțiuni */
        section {
            padding: 20px;
            margin: 20px;
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        h2 {
            color: #ff3399;
        }

        /* Stilizare pentru galerie de imagini */
        .gallery {
            display: flex;
            gap: 10px;
            justify-content: center;
        }

        .gallery img {
            width: 200px;
            height: auto;
            border-radius: 10px;
            transition: transform 0.3s;
        }

        .gallery img:hover {
            transform: scale(1.1);
        }

        footer {
            background-color: #ff3399;
            color: white;
            text-align: center;
            padding: 10px 0;
        }
    </style>
</head>
<body>

<header>
    <h1>K-Pop World</h1>
    <p>Explorând lumea fascinantă a K-Pop-ului!</p>
</header>

<nav>
    <a href="#">Acasă</a>
    <a href="#trupe">Trupe celebre</a>
    <a href="#piese">Piese de succes</a>
    <a href="#contact">Contact</a>
</nav>

<!-- Pagina principală - introducerea -->
<section id="home">
    <h2>Bun venit în lumea K-Pop!</h2>
    <p>K-Pop-ul este un fenomen cultural global care combină muzică, dans și modă. Începând din Coreea de Sud, K-Pop-ul a cucerit inimi peste tot în lume cu trupe uimitoare, coregrafii spectaculoase și fandom-uri dedicate.</p>
</section>

<!-- Secțiunea Trupe celebre -->
<section id="trupe">
    <h2>Trupe K-Pop celebre</h2>
    <div class="gallery">
        <img src="https://upload.wikimedia.org/wikipedia/commons/0/09/BTS_logo_%282017%29.svg" alt="BTS">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/ae/Blackpink_Logo.png/800px-Blackpink_Logo.png" alt="BLACKPINK">
        <img src="https://upload.wikimedia.org/wikipedia/commons/e/e7/Exo_logo.png" alt="EXO">
    </div>
    <p><strong>BTS</strong>, <strong>BLACKPINK</strong> și <strong>EXO</strong> sunt doar câteva dintre trupele care au avut un impact uriaș asupra industriei muzicale la nivel mondial.</p>
</section>

<!-- Secțiunea Piese de succes -->
<section id="piese">
    <h2>Piese K-Pop de succes</h2>
    <ul>
        <li><a href="https://www.youtube.com/watch?v=gdZLi9oWNZg" target="_blank">BTS - Dynamite</a></li>
        <li><a href="https://www.youtube.com/watch?v=ioNng23DkIM" target="_blank">BLACKPINK - How You Like That</a></li>
        <li><a href="https://www.youtube.com/watch?v=m9J_lEadp8Y" target="_blank">EXO - Love Shot</a></li>
    </ul>
    <p>Aceste piese au fost hituri internaționale și au adus K-Pop-ul în atenția publicului global.</p>
</section>

<!-- Secțiunea Contact -->
<section id="contact">
    <h2>Contact</h2>
    <p>Ai întrebări despre K-Pop? Trimite-ne un mesaj!</p>
    <form>
        <label for="name">Nume:</label><br>
        <input type="text" id="name" name="name"><br><br>
        <label for="email">Email:</label><br>
        <input type="email" id="email" name="email"><br><br>
        <label for="message">Mesaj:</label><br>
        <textarea id="message" name="message" rows="4" cols="50"></textarea><br><br>
        <input type="submit" value="Trimite">
    </form>
</section>

<footer>
    <p>&copy; 2024 K-Pop World. Toate drepturile rezervate.</p>
</footer>

</body>
</html>
