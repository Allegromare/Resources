Navbar Inferiore con Bootstrap
https://www.petanikode.com/img/cover/bottom-nav.png

Introduzione

In questo tutorial, impareremo come creare una navbar (barra di navigazione) inferiore con Bootstrap. Una navbar inferiore è un'ottima soluzione per visualizzare menu importanti o azioni di navigazione su dispositivi mobili, posizionandola in modo da essere facilmente raggiungibile con i pollici.

Prerequisiti

Prima di iniziare, assicurati di avere:

Conoscenza base di HTML, CSS e JavaScript
Bootstrap incluso nel tuo progetto (puoi usare un CDN o scaricarlo)
Un editor di testo o IDE (Integrated Development Environment)
Passaggi

1. Struttura HTML di Base

Inizia creando la struttura HTML di base per la tua pagina. Aggiungeremo poi la navbar inferiore.

<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Navbar Inferiore con Bootstrap</title>
    <!-- Includi Bootstrap CSS (tramite CDN o file locale) -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
</head>
<body>

    <!-- Qui andrà il tuo contenuto -->

    <!-- Includi jQuery e Bootstrap JS (necessari per alcune funzionalità) -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.3/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>

2. Creare la Navbar Inferiore

Ora creiamo la navbar inferiore utilizzando le classi di Bootstrap.

<nav class="navbar fixed-bottom navbar-expand-sm navbar-dark bg-dark">
    <a class="navbar-brand" href="#">Petani Kode</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarBottom" aria-controls="navbarBottom" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarBottom">
        <ul class="navbar-nav ml-auto">
            <li class="nav-item active">
                <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">Features</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">Pricing</a>
            </li>
        </ul>
    </div>
</nav>


- navbar fixed-bottom: Fissa la navbar in fondo alla pagina.
- navbar-expand-sm: Mostra il menu espanso su schermi piccoli (sm) e superiori.
- navbar-dark bg-dark: Applica un tema scuro alla navbar.

3. Aggiungere Contenuto alla Pagina

Per rendere più chiara la visualizzazione della navbar inferiore, aggiungiamo un po' di contenuto alla pagina:

<div class="container">
    <div class="jumbotron">
        <h1 class="display-4">Navbar Inferiore con Bootstrap</h1>
        <p class="lead">Questo è un esempio di navbar inferiore creata con Bootstrap.</p>
        <hr class="my-4">
        <p>Questo è un po' di testo di esempio per riempire la pagina e mostrare la navbar inferiore fissa in fondo.</p>
        <p>Continua ad aggiungere testo qui...</p>
        <p>...</p>
        <p>...</p>
        <p>...</p>
        <p>...</p>
        <p>...</p>
        <p>Questo è il fondo della pagina.</p>
    </div>
</div>


4. Esempio Completo

Ecco l'esempio completo del codice:

<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Navbar Inferiore con Bootstrap</title>
    <!-- Includi Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
</head>
<body>

    <div class="container">
        <div class="jumbotron">
            <h1 class="display-4">Navbar Inferiore con Bootstrap</h1>
            <p class="lead">Questo è un esempio di navbar inferiore creata con Bootstrap.</p>
            <hr class="my-4">
            <p>Questo è un po' di testo di esempio per riempire la pagina e mostrare la navbar inferiore fissa in fondo.</p>
            <p>Continua ad aggiungere testo qui...</p>
            <p>...</p>
            <p>...</p>
            <p>...</p>
            <p>...</p>
            <p>...</p>
            <p>Questo è il fondo della pagina.</p>
        </div>
    </div>

    <nav class="navbar fixed-bottom navbar-expand-sm navbar-dark bg-dark">
        <a class="navbar-brand" href="#">Petani Kode</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarBottom" aria-controls="navbarBottom" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarBottom">
            <ul class="navbar-nav ml-auto">
                <li class="nav-item active">
                    <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Features</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Pricing</a>
                </li>
            </ul>
        </div>
    </nav>

    <!-- Includi jQuery e Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.3/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>


Conclusione

Congratulazioni! Hai creato con successo una navbar inferiore con Bootstrap. Puoi personalizzarla ulteriormente aggiungendo icone, cambiando colori e regolando la reattività per adattarla al tuo design.

