# Neon Drift

Sito web statico realizzato per la verifica di Web Design.

## Descrizione del progetto
Neon Drift è una landing page per un videogioco arcade inventato.  
Il sito presenta il gioco con un'estetica cyberpunk/neon (sfondo scuro, colori ciano, rosa e viola).

## Struttura dei file
- `index.html` → struttura della pagina
- `style.css` → fogli di stile
- `pista.svg` → immagine del circuito (hero)
- `auto.svg` → immagine dell’auto da corsa

## Cosa ho fatto nel CSS
Ho creato da zero tutto lo stile perché il file `style.css` era vuoto.

### Principali scelte di design:
- Sfondo scuro (#0b1120) con gradienti leggeri neon
- Titolo con gradiente ciano → viola → rosa
- Pulsante CTA luminoso con effetto hover
- Schede (card) con bordo superiore a gradiente neon
- Effetti di ombra e glow sulle immagini
- Layout responsive:
  - su mobile le schede sono una sotto l’altra
  - da 768px in su diventano a griglia (3 colonne)
- Animazioni leggere al passaggio del mouse (hover) su immagini e pulsante

### Come ho provato il CSS
1. Ho aperto `index.html` nel browser (Chrome/Edge/Firefox)
2. Ho controllato che il layout fosse a posto sia su schermo grande che riducendo la finestra (simulazione mobile)
3. Ho verificato che i colori neon si vedessero bene e che gli effetti hover funzionassero
4. Ho controllato che le immagini SVG si caricassero correttamente
