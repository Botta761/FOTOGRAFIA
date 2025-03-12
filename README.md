<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio Fotografico</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;500&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Roboto', sans-serif;
            background-color: #f9f9f9;
            color: #333;
            text-align: center;
            line-height: 1.6;
        }
        header {
            background-color: #222;
            padding: 30px;
            font-size: 36px;
            font-weight: 500;
            color: #fff;
            text-transform: uppercase;
            letter-spacing: 2px;
        }
        header img {
            width: 150px;
            height: auto;
        }
        .hero {
            background-color: #e1e1e1;
            padding: 100px 20px;
            margin-bottom: 50px;
        }
        .hero h1 {
            font-size: 48px;
            font-weight: 600;
            color: #333;
        }
        .about, .services, .contact {
            max-width: 900px;
            margin: 50px auto;
            padding: 20px;
            text-align: left;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.1);
        }
        .about h2, .services h2, .contact h2 {
            font-size: 32px;
            margin-bottom: 20px;
            color: #222;
        }
        .about p, .services p, .contact p {
            font-size: 18px;
            color: #555;
        }
        .contact-info {
            margin-top: 20px;
            font-size: 16px;
            color: #777;
        }
        .contact-info a {
            color: #555;
            text-decoration: none;
        }
        .contact-info a:hover {
            text-decoration: underline;
        }
        footer {
            background-color: #222;
            padding: 15px;
            color: #fff;
            font-size: 14px;
            text-align: center;
            margin-top: 50px;
        }
    </style>
</head>
<body>
    <header>
        <img src="https://via.placeholder.com/150" alt="Logo"> Portfolio Fotografico
    </header>
    <section class="hero">
        <h1>Benvenuto nel mio portfolio fotografico</h1>
        <p>Immortalare momenti che durano per sempre.</p>
    </section>
    <section class="about">
        <h2>Chi sono</h2>
        <p>Sono un fotografo professionista con un'esperienza pluriennale, appassionato di catturare emozioni attraverso l'obiettivo. Il mio lavoro si concentra su ritratti, eventi speciali e fotografie creative.</p>
    </section>
    <section class="services">
        <h2>Servizi</h2>
        <p>Offro servizi di fotografia per matrimoni, ritratti professionali, eventi aziendali e creativi, con uno stile elegante e sofisticato, progettato per soddisfare ogni esigenza.</p>
    </section>
    <section class="contact">
        <h2>Contattami</h2>
        <p>Se desideri maggiori informazioni o vuoi pianificare una sessione fotografica, non esitare a contattarmi.</p>
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
****
