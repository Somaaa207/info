<!DOCTYPE html>
<html lang="hu">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Magyar Informatika Napja</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Magyar Informatika Napja</h1>
        <p>Január 21 - Az első magyar Neumann-elvű számítógép tiszteletére</p>
    </header>
    
    <nav>
        <ul>
            <li><a href="#tortenelmi-hatter">Történelmi háttér</a></li>
            <li><a href="#m3-szamitogep">Az M-3 számítógép</a></li>
            <li><a href="#jelentoseg">Jelentősége</a></li>
            <li><a href="#esemenyek">Kapcsolódó események</a></li>
            <li><a href="#alkotok">Megalkotói</a></li>
            <li><a href="#konferencia">Konferencia</a></li>
        </ul>
    </nav>
    
    <section id="tortenelmi-hatter">
        <h2>Történelmi háttér</h2>
        <p>1959. január 21-én a magyar sajtó hírt adott az M-3 számítógép működéséről...</p>
        <p>2022 óta január 21-én ünnepeljük a Magyar Informatika Napját, emlékezve az első magyar, Neumann-elvű elektronikus számítógép működésére. A sajtó 1959. január 21-én számolt be az M-3 számítógép működéséről, amely alapvető szerepet játszott a magyar számítástechnikai fejlődésben. Az MTA Kibernetikai Kutatócsoportja által kifejlesztett számítógép hatása a mai napig érezhető a hazai informatikai életben.</p>
        <img src="kep/history.jpg" alt="Történelmi számítógép">
    </section>
    
    <section id="m3-szamitogep">
        <h2>Az M-3 számítógép</h2>
        <p>Az M-3 az első magyar, Neumann-elvű elektronikus számítógép volt, amely a modern számítástechnika alapjait fektette le Magyarországon. Az MTA Kibernetikai Kutatócsoportja dolgozott a fejlesztésén, és az új gép jelentős előrelépést jelentett a számítástechnikai kutatások terén. A Neumann-elv alapvetően az elektronikus számítógépek működési elvét határozta meg, és azóta is a legtöbb modern számítógép ezen elv szerint működik.</p>
        <p>Az M-3 a Neumann-architektúra alapján készült...</p>
        <img src="kep/m3_computer.jpg" alt="M-3 számítógép">
    </section>
    
    <section id="jelentoseg">
        <h2>A Magyar Informatika Napjának jelentősége</h2>
        <p>A Magyar Informatika Napja nemcsak a történelmi jelentőségű eseményekre emlékezik, hanem lehetőséget ad arra is, hogy tisztelettel adózzunk mindazok előtt, akik hozzájárultak a magyar informatika fejlődéséhez. Ezen a napon szakemberek, kutatók és diákok gyűlnek össze, hogy megosszák tudományos eredményeiket, tapasztalataikat, és együtt ünnepeljék a magyar informatika eredményeit.</p>

        <p>Emlékeztet a múlt eredményeire, tisztelgés az alkotók előtt...</p>
        <img src="kep/importance.jpg" alt="Informatika ünnepe">
    </section>
    
    <section id="esemenyek">
        <h2>Kapcsolódó események</h2>
        <ul>
            <li>Tudományos előadások</li>
            <li>Oktatási programok</li>
            <li>Kitüntetések és elismerések</li>
        </ul>
        <img src="kep/event.jpg" alt="Kapcsolódó események">
    </section>
    
    <section id="alkotok">
        <h2>Az M-3 számítógép megalkotói</h2>
        <p>Kalmár László, Varga József, Rátz László, Simonyi Károly...</p>
        <img src="kep/creators.jpg" alt="Megalkotók képe">
    </section>
    
    <section id="konferencia">
        <h2>A konferencia programja</h2>
        <ul>
            <li>Megnyitó</li>
            <li>Előadások</li>
            <li>Workshopok</li>
            <li>Panelbeszélgetések</li>
            <li>Záróünnepség</li>
        </ul>
        <h3>Jelentkezés az eseményre</h3>
        <form>
            <label>Teljes név: <input type="text" name="nev"></label><br>
            <label>E-mail: <input type="email" name="email"></label><br>
            <label>Jegyek száma: <input type="number" name="jegyek"></label><br>
            <label>Kér ételt és szállást?
                <select name="szallas">
                    <option>Mindkettő</option>
                    <option>Csak étel</option>
                    <option>Csak szállás</option>
                    <option>Egyiket sem</option>
                </select>
            </label><br>
            <button type="submit">Jelentkezés</button>
        </form>
    </section>
    
    <footer>
        <p>&copy; 2025 Magyar Informatika Napja</p>
    </footer>
</body>
</html>
