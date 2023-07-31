# inertix.cc
<!DOCTYPE html>
<html>
<head>
    <title>Mon site comme inertix.cc</title>
    <link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body>
    <header>
        <!-- Contenu de l'en-tête -->
    </header>

    <nav>
        <!-- Barre de navigation -->
    </nav>

    <main>
        <!-- Contenu principal du site -->
    </main>

    <footer>
        <!-- Pied de page -->
    </footer>

    <script src="script.js"></script>
</body>
</html>


/* Styles pour l'en-tête, la navigation et le pied de page */
header, nav, footer {
    /* styles ici */
}

/* Styles pour les sections et éléments spécifiques du contenu principal */
main {
    /* styles ici */
}

/* Autres styles spécifiques au site */


// Script pour ajouter des fonctionnalités dynamiques au site



<?php include 'header.php'; ?>

<!-- Contenu principal de la page -->

<?php include 'footer.php'; ?>


from flask import Flask, render_template

app = Flask(__name__)

@app.route('/')
def index():
    return render_template('index.html')

if __name__ == '__main__':
    app.run()


