MINUE’S — SOCIAL MEDIA MANAGEMENT | GUIDA AI FILE
=================================================

FILE DA APRIRE
- index.html  -> testi del sito, nome, prezzi, piani e link email. È il file da aprire nel browser per vedere il sito.
- style.css   -> colori, font, spaziature, dimensioni, layout e stile delle schede.
- script.js   -> piccole funzioni: menu mobile, comparsa leggera delle sezioni e anno automatico nel footer.
- README.txt  -> questa guida.

EMAIL OUTLOOK GIÀ CONFIGURATA
L’indirizzo impostato è: minueweb@outlook.it
I pulsanti di contatto aprono una nuova email tramite mailto:. I pulsanti principali hanno anche un oggetto precompilato; l’indirizzo visibile nella sezione contatti è cliccabile. È stata aggiunta una piccola icona email SVG direttamente nel codice, quindi non dipende da immagini esterne o da Google.
Per cambiare indirizzo in futuro, apri index.html e cerca minueweb@outlook.it (Ctrl+H), quindi sostituisci tutte le occorrenze con il nuovo indirizzo. Nei link non eliminare il prefisso mailto: né la parte ?subject=... quando presente.
I link mailto: aprono l’app di posta predefinita del visitatore. Non inviano email in automatico e non richiedono backend.

COME MODIFICARE I SERVIZI DEI PIANI
Apri index.html e cerca i commenti HTML:
- PIANO ESSENTIAL
- PIANO GROWTH
- PIANO PREMIUM
Subito sotto ogni commento trovi una lista <ul class="plan-features">. Modifica il testo di ogni <li> per cambiare ciò che il piano include. Puoi aggiungere una voce copiando una riga <li>...</li> e modificandone il testo.

ATTENZIONE: i numeri inseriti nei piani sono una PROPOSTA INIZIALE da confermare prima di pubblicare:
ESSENTIAL - 200 €/mese: 1 profilo social, fino a 8 contenuti, copy/didascalie, calendario, programmazione e riepilogo mensile.
GROWTH - 375 €/mese: fino a 2 profili, 12 contenuti, 4 Reel/video da materiali forniti, 8 contenuti Stories, copy, calendario, programmazione e report.
PREMIUM - 500 €/mese: fino a 3 profili, 16 contenuti, 8 Reel/video da materiali forniti, 12 contenuti Stories, copy, calendario, programmazione, report e call di revisione.
Verifica che quantità, tempi di consegna, piattaforme e responsabilità siano sostenibili e corrispondano al servizio che vuoi realmente offrire. Non pubblicare dettagli non confermati.

COME CAMBIARE PREZZI E TESTI
Nel file index.html cerca “Essential”, “Growth”, “Premium” o gli importi “200”, “375” e “500”. Modifica il testo visibile nella scheda corrispondente. Se fai sostituzioni globali, controlla il risultato per evitare modifiche involontarie.

COME CAMBIARE COLORI E FONT
Apri style.css. All’inizio del file trovi le variabili CSS:
--white, --paper, --ink, --red, --rose e --cream.
Il rosso del brand è #B55151. Cambia il valore di --red se vuoi un’altra tonalità. I font principali sono Gliker (titoli), Nunito Sans (testi) e Forum (dettagli); i link a Google Fonts si trovano nell’head di index.html e all’inizio di style.css.

LOGO, IMMAGINI E LINK
- Il nome “minue’s.” è testo HTML, non un’immagine logo. Per cambiare il nome, cerca “minue’s” in index.html.
- Per aggiungere un logo immagine, inserisci un tag <img> nel punto desiderato in index.html e definisci dimensioni in style.css. Metti il file immagine nella stessa cartella del sito e usa un percorso relativo, per esempio src="images/logo.png".
- Per cambiare i link del menu, modifica gli href che iniziano con # (devono corrispondere all’id della sezione).
- Per aggiungere un link esterno, usa <a href="https://...">Testo del link</a>.
- Attualmente non sono inseriti link a profili social, come richiesto.

CURSORE
Il sito usa il puntatore standard del browser. Il vecchio cerchio e il puntino personalizzati sono stati rimossi. Se vuoi aggiungere un effetto in futuro, il punto da modificare è indicato da commenti in style.css e script.js.

PUBBLICAZIONE
Per provare il sito, apri index.html nel browser. Per pubblicarlo online, carica index.html, style.css, script.js e gli eventuali asset mantenendo la stessa struttura di cartelle sul servizio di hosting statico scelto. Google Sites non ospita direttamente questi file come un normale hosting HTML.

NOTA CONTRATTUALE E FISCALE
Il testo del sito è volutamente prudente: la prestazione d’opera occasionale non è adatta automaticamente a ogni collaborazione continuativa. Forma contrattuale, ricevuta e obblighi fiscali dipendono dalla situazione effettiva. Verifica la formulazione con un professionista prima della pubblicazione.
