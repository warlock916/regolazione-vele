# Banco di Regolazione Vele

Simulatore didattico di regolazione di randa e fiocco. Tutto il calcolo avviene nel browser: il server serve solo il file `index.html`.

## Prova in locale

    npm install
    npm start

Poi apri http://localhost:3000

## Pubblicazione su Railway da GitHub

1. Crea un repository su GitHub e carica il contenuto di questa cartella.
2. Su railway.com: New Project → Deploy from GitHub repo → scegli il repository.
3. Railway riconosce `package.json`, installa le dipendenze e lancia `npm start`. La porta arriva dalla variabile `PORT`, già gestita.
4. Nel servizio: Settings → Networking → Generate Domain per avere l'indirizzo pubblico.

Ogni push sul ramo principale ripubblica il sito.
