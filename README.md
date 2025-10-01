# Starter "Ringraziamenti tesi" (HTML/CSS statico)

Questo pacchetto contiene una struttura minimale per creare pagine statiche di ringraziamento
collegate da QR nella tua tesi.

## Come usarlo
1. Modifica i file `.html` con i tuoi testi.
2. Duplica una pagina per ogni ringraziamento (es. `grazie-mamma.html`, `grazie-papà.html`).
3. Mantieni i file nello stesso livello della `style.css`.
4. Pubblica online (GitHub Pages, Netlify, Cloudflare Pages, Neocities, ecc.).
5. Genera i QR con gli URL finali di ciascuna pagina.

## Hosting consigliato (GitHub Pages in 60 secondi)
- Crea un repository pubblico, ad esempio `tesi-ringraziamenti`.
- Carica tutti i file della cartella.
- Vai su **Settings → Pages** e seleziona **Deploy from a branch**, branch `main`, cartella `/root`.
- L'indirizzo sarà: `https://<tuo-username>.github.io/tesi-ringraziamenti/` (aggiungi il nome del file HTML).

## Suggerimenti
- Mantieni gli URL stabili (non rinominare i file dopo la stampa).
- Puoi aggiungere immagini nella cartella `assets/` e richiamarle con `<img src="assets/..." alt="">`.
- Il CSS è minimale e stampabile; puoi personalizzarlo senza rompere il layout.