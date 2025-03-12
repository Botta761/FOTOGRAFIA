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
        .about, .contact {
            max-width: 800px;
            margin: 50px auto;
            padding: 20px;
            text-align: left;
            font-size: 18px;
            line-height: 1.6;
        }
        .contact form {
            display: flex;
            flex-direction: column;
        }
        .contact form input, .contact form textarea {
            margin-bottom: 15px;
            padding: 10px;
            font-size: 16px;
            border: none;
            border-radius: 5px;
            background-color: #333;
            color: #f5f5f5;
        }
        .contact form input[type="submit"] {
            background-color: #ff5722;
            color: white;
            cursor: pointer;
            transition: background-color 0.3s ease-in-out;
        }
        .contact form input[type="submit"]:hover {
            background-color: #e64a19;
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
        <p>Benvenuto nel mio portfolio fotografico. Sono un appassionato di fotografia e amo catturare momenti speciali.</p>
        <p>Mi occupo di fotografia di paesaggi, ritratti e street photography. La mia missione è raccontare storie attraverso immagini, immortalando emozioni e dettagli unici.</p>
        <p>Ho iniziato il mio viaggio nella fotografia diversi anni fa e nel tempo ho affinato la mia tecnica, esplorando nuove prospettive e migliorando il mio stile personale.</p>
        <p>Amo viaggiare e scoprire nuove culture, il che mi permette di catturare immagini uniche che raccontano storie da ogni angolo del mondo.</p>
        <p>Credo che la fotografia sia un potente strumento di comunicazione, capace di trasmettere emozioni e creare connessioni profonde tra le persone.</p>
    </section>
    <section class="contact">
        <h2>Contattami</h2>
        <p>Se desideri collaborare con me o semplicemente vuoi saperne di più sul mio lavoro, non esitare a contattarmi.</p>
        <form>
            <input type="text" placeholder="Il tuo nome" required>
            <input type="email" placeholder="La tua email" required>
            <textarea placeholder="Il tuo messaggio" rows="5" required></textarea>
            <input type="submit" value="Invia">
        </form>
    </section>
    <footer>
        &copy; 2025 Portfolio Fotografico - Tutti i diritti riservati
    </footer>
</body>
</html>
