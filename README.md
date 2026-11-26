# Girasoli

App per organizzare la vita di tutti i giorni in due: profilo con obiettivi, liste, wishlist e posti dove mangiare, più un calendario condiviso.

- Sito statico pubblicato con GitHub Pages (`index.html`).
- I dati stanno in Firebase (Firestore), non in questo repository.
- Le regole di accesso al database sono in `firestore.rules`: solo i due account indicati possono leggere e scrivere.
- Finché `FIREBASE_CONFIG` in `index.html` è `null`, il sito funziona in modalità prova e salva i dati solo sul dispositivo.
