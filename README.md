<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AES Hôtel TV - Solution IPTV pour Hôtels & Auberges</title>
    <style>
        body {
            margin: 0;
            font-family: 'Segoe UI', sans-serif;
            background: #f8faff;
            color: #333;
        }
        header {
            background: #004080;
            color: white;
            padding: 20px;
            text-align: center;
        }
        h1 {
            margin: 0;
            font-size: 2.5em;
        }
        section {
            padding: 30px;
        }
        .intro {
            background: #e6f0ff;
            padding: 30px;
            border-radius: 10px;
        }
        .formulaire {
            background: #fff;
            border: 1px solid #ddd;
            padding: 25px;
            border-radius: 10px;
            margin-top: 20px;
        }
        label {
            display: block;
            margin: 10px 0 5px;
        }
        input, select {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border-radius: 5px;
            border: 1px solid #ccc;
        }
        button {
            background-color: #004080;
            color: white;
            border: none;
            padding: 12px 20px;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1em;
        }
        .tarifs {
            background: #f0f9ff;
            border: 1px solid #b3d1ff;
            padding: 20px;
            border-radius: 10px;
            margin-top: 20px;
        }
        .contact {
            margin-top: 30px;
            background: #e6f0ff;
            padding: 20px;
            border-radius: 10px;
            text-align: center;
        }
        .whatsapp-float {
            position: fixed;
            bottom: 20px;
            right: 20px;
            background: #25D366;
            color: white;
            border-radius: 50%;
            width: 60px;
            height: 60px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 30px;
            text-decoration: none;
            box-shadow: 0 2px 10px rgba(0,0,0,0.3);
            z-index: 1000;
        }
        @media (max-width: 768px) {
            h1 {
                font-size: 1.8em;
            }
            section {
                padding: 15px;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>AES Hôtel TV</h1>
        <p>IPTV Haut Débit pour Hôtels, Auberges & Résidences - Économisez sur la TV satellitaire !</p>
    </header><section class="intro">
    <h2>Pourquoi choisir AES Hôtel TV ?</h2>
    <ul>
        <li>Éliminez les coûts de la télévision par satellite</li>
        <li>Utilisez simplement votre connexion internet existante</li>
        <li>Installation rapide et facile</li>
        <li>Support client 24h/24</li>
    </ul>
</section>

<section class="formulaire">
    <h2>Demande de service</h2>
    <form action="mailto:aesipsaheltv@gmail.com" method="post" enctype="text/plain">
        <label for="type">Type de téléviseur</label>
        <select id="type" name="Type de téléviseur">
            <option>Android</option>
            <option>WebOS</option>
            <option>Autre</option>
        </select>

        <label for="marque">Marque du téléviseur</label>
        <input type="text" id="marque" name="Marque" placeholder="Ex. LG, Samsung...">

        <label for="chambres">Nombre de chambres</label>
        <input type="number" id="chambres" name="Nombre de chambres" min="1">

        <label for="wifi">WiFi haut débit disponible ?</label>
        <select id="wifi" name="WiFi haut débit">
            <option>Oui</option>
            <option>Non</option>
        </select>

        <label for="forfait">Choix du forfait</label>
        <select id="forfait" name="Forfait">
            <option>1 an - 30 000 FCFA</option>
            <option>2 ans - 55 000 FCFA</option>
            <option>À vie - 100 000 FCFA</option>
        </select>

        <label for="box">Ajouter une box Android certifiée (35 000 FCFA) ?</label>
        <select id="box" name="Box Android">
            <option>Oui</option>
            <option>Non</option>
        </select>

        <button type="submit">Soumettre la demande</button>
    </form>
</section>

<section class="tarifs">
    <h2>Nos Forfaits IPTV</h2>
    <ul>
        <li>Forfait 1 an : 30 000 FCFA</li>
        <li>Forfait 2 ans : 55 000 FCFA</li>
        <li>Forfait à vie : 100 000 FCFA</li>
        <li>Box Android certifiée (optionnelle) : 35 000 FCFA</li>
    </ul>
</section>

<section class="contact">
    <h2>Contactez-nous</h2>
    <p>Email : <a href="mailto:aesipsaheltv@gmail.com">aesipsaheltv@gmail.com</a></p>
    <p>WhatsApp : <a href="https://wa.me/22679949312" target="_blank">+226 79 94 93 12</a></p>
</section>

<a href="https://wa.me/22679949312" class="whatsapp-float" target="_blank" title="Écrivez-nous sur WhatsApp">💬</a>

</body>
</html>
