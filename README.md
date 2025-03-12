<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio Fotografico</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Poppins', sans-serif;
            background-color: #121212;
            color: white;
            text-align: center;
        }
        header {
            background: rgba(0, 0, 0, 0.8);
            padding: 20px;
            font-size: 32px;
            font-weight: 600;
            letter-spacing: 2px;
            text-transform: uppercase;
        }
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 15px;
            padding: 50px;
            max-width: 1200px;
            margin: auto;
        }
        .gallery img {
            width: 100%;
            height: auto;
            border-radius: 10px;
            transition: transform 0.3s ease-in-out, box-shadow 0.3s ease-in-out;
        }
        .gallery img:hover {
            transform: scale(1.05);
            box-shadow: 0 10px 20px rgba(255, 255, 255, 0.2);
        }
        .about {
            max-width: 800px;
            margin: 50px auto;
            padding: 20px;
            text-align: left;
            font-size: 18px;
            line-height: 1.6;
        }
        footer {
            background: rgba(0, 0, 0, 0.8);
            padding: 15px;
            margin-top: 20px;
            font-size: 14px;
        }
    </style>
</head>
<body>
    <header>Portfolio Fotografico</header>
    
    <section class="about">
        <h2>Chi Sono</h2>
        <p>Sono un fotografo professionista specializzato in ritratti, paesaggi e fotografia artistica. Con anni di esperienza, il mio obiettivo è catturare l'essenza di ogni momento attraverso l'obiettivo della mia fotocamera.</p>
    </section>
    
    <div class="gallery">
        <img src="foto1.jpg" alt="Foto 1">
        <img src="foto2.jpg" alt="Foto 2">
        <img src="foto3.jpg" alt="Foto 3">
        <img src="foto4.jpg" alt="Foto 4">
        <img src="foto5.jpg" alt="Foto 5">
        <img src="foto6.jpg" alt="Foto 6">
    </div>
    
    <footer>&copy; 2025 Nome Fotografo - Tutti i diritti riservati</footer>
</body>
</html>
