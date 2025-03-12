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
            grid-template-columns: 1fr;
            gap: 15px;
            padding: 50px;
            max-width: 800px;
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
    
    <section class="about">
        <h2>Chi Sono</h2>
        <p>Sono un fotografo professionista specializzato in ritratti, paesaggi e fotografia artistica. Con anni di esperienza, il mio obiettivo è catturare l'essenza di ogni momento attraverso l'obiettivo della mia fotocamera.</p>
        <p>Ho lavorato con numerosi clienti in tutto il mondo, offrendo servizi fotografici personalizzati per ogni esigenza. La mia passione
