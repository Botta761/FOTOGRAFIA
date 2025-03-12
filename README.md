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
            background-color: #1e1e1e;
            color: #f5f5f5;
            text-align: center;
        }
        header {
            background: #333;
            padding: 20px;
            font-size: 32px;
            font-weight: 600;
            letter-spacing: 2px;
            text-transform: uppercase;
        }
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 15px;
            padding: 50px;
            max-width: 1000px;
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
        .about, .services, .contact {
            max-width: 800px;
            margin: 50px auto;
            padding: 20px;
            text-align: left;
            font-size: 18px;
            line-height: 1.6;
        }
        .contact-info {
            margin-top: 20px;
            font-size: 18px;
        }
        .contact-info p {
            margin: 5px 0;
        }
        footer {
            background: #333;
            padding: 15px;
            margin-top: 20px;
            font-size: 14px;
        }
    </style>
</head>
<body>
    <header>Portfolio Fotografico</header>
    <section class="gallery">
        <img src="https://via.placeholder.com/300" alt="Foto 1">
        <img src="https://via.placeholder.com/300" alt="Foto 2">
        <img src="https://via.placeholder.com/300" alt="Foto 3">
        <img src="https://via.placeholder.com/300" alt="Foto 4">
        <img src="https://via.placeholder.com/300" alt="Foto 5">
        <img src="https://via.placeholder.com/300" alt="Foto 6">
    </section>
    <section class="about">
        <h2>Chi sono</h2>
        <p>Sono un fotografo appassionato di immortalare momenti unici e creare immagini emozionanti.</p>
    </section>
    <section class="services">
        <h2>Servizi</h2>
        <p>Offro servizi fotografici per eventi, ritratti, paesaggi e brand personali.</p>
    </section>
    <section class="contact">
        <h2>Contattami</h2>
        <p>Se desideri collaborare con me o hai domande sui miei servizi, contattami ai seguenti recapiti:</p>
        <div class="contact-info">
            <p>Email: <a href="mailto:esempio@email.com">esempio@email.com</a></p>
            <p>Telefono: +39 123 456 7890</p>
            <p>Instagram: <a href="https://instagram.com/esempio" target="_blank">@esempio</a></p>
        </div>
    </section>
    <footer>
        &copy; 2025 Portfolio Fotografico - Tutti i diritti riservati
    </footer>
</body>
</html>
