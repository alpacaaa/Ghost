---
lang: it
layout: installation
meta_title: How to Install Ghost on Your Server - Ghost Docs
meta_description: Everything you need to get the Ghost blogging platform up and running on your local or remote environement.
heading: Installing Ghost &amp; Getting Started
subheading: The first steps to setting up your new blog for the first time.
permalink: /it/installation/windows/
chapter: installation
section: windows
prev_section: mac
next_section: linux
---
# Installazione su Windows <a id="install-windows"></a>

### Installare Node.js

*   Su [http://nodejs.org](http://nodejs.org) clicca installa, per scaricare il file '.msi'.
*   Clicca sul file scaricato per aprire il programma di installazione; così installi sia node.js che npm.
*   Prosegui con le istruzioni mostrate dal programma di installazione, fino a quando sullo schermo non comparirà un messaggio che conferma l'installazione per Node.js.

Se hai problemi in questa fase, guarda tutto [questo video](https://s3-eu-west-1.amazonaws.com/ghost-website-cdn/install-node-win.gif "Install node on Windows"), ti può aiutare.

### Scarica ed estrai Ghost

*   Registrati su [http://ghost.org](http://ghost.org), e quindi clicca sul pulsante blu 'Download Ghost Source Code' (Scarica codice sorgente di Ghost).
*   Nella pagina dei download, premi sul pulsante per scaricare l'ultimo file zip.
*   Clicca sulla freccia 'next' (avanti) per scaricare il file più recente, e scegli 'mostra nella cartella'.
*   Quando si apre la cartella, clicca con il pulsante destro del mouse sul file zip scaricato e scegli 'Estrai tutto'.

Se hai problemi, guarda il video per l'intero [processo passo dopo passo](https://s3-eu-west-1.amazonaws.com/ghost-website-cdn/install-ghost-win.gif "Install Ghost on Windows Part 1").

### Installa ed Esegui Ghost

*   Nel tuo menu Start, cerca 'Node.js' e scegli la voce 'Node.js Command Prompt' (Prompt dei comandi Node.js).
*   Nel prompt dei comandi di Node, devi posizionarti all'interno della cartella dove hai estratto Ghost. Digita: `cd Downloads/ghost-#.#.#` (sostituisci gli hash con la versione di Ghost che hai scaricato).
*   Ora, nel prompt dei comandi, digita `npm install --production` <span class="note">fai atttenzione ai due trattini</span>.
*   Quando npm ha terminato di installare, digita `npm start` per avviare Ghost in modalità sviluppo (development mode).
*   Nel browser, digita nella barra dell'url <code class="path">127.0.0.1:2368</code> per vedere il tuo blog Ghost funzionante
*   Nella barra dell'url, digita <code class="path">127.0.0.1:2368/ghost</code> e crea il tuo utente amministratore per loggarti e gestire la tua installazione di Ghost, in modalità sviluppo.
*   Vedi la [documentazione di riferimento](/usage) per altre istruzioni successive.

{<1>}![](https://s3-eu-west-1.amazonaws.com/ghost-website-cdn/install-ghost-win-2.gif "Installare Ghost su Windows - Parte 2")
