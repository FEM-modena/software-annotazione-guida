* TOC
{:toc}

Questo documento 

# Strumenti

Per Windows è consigliato l'uso di `Notepad++`, editor gratuito scaricabile da [questo link](https://notepad-plus-plus.org/downloads/)

# Accesso

# Annotazione

# Caricamento nuovi dati

È possibile caricare nuovi testi all'interno della piattaforma ed includerli o come un **nuovo dataset** oppure @@@. In entrambe i casi, il formato dei documenti è lo stesso, e viene descritto più sotto (sez. @@@.)

## Importare nuovi testi

> :bangbang: Per importare nuovi testi, è necessario che questi siano formattati in **file di testo semplice** (estensione `.txt`), dove **ogni riga rappresenta un diverso testo**.  

Ad esempio: decidiamo di importare una serie articoli di Umberto Eco (scritti per *La Bustina di Minerva*). Individuati gli articoli che ci interessano, per ogni articolo copiamo (<kbd>CTRL</kbd> + <kbd>c</kbd>) ed incolliamo (<kbd>CTRL</kbd> + <kbd>v</kbd>) il *titolo*, il *sottotitolo*, ed il *corpo* nell'editor di testo. Otterremo un testo simile a quanto mostrato di seguito (per motivi di spazio, ho incluso solo il primo paragrafo di [questo articolo](https://espresso.repubblica.it/opinioni/la-bustina-di-minerva/2015/12/22/news/la-civil-conversazione-1.244548), dove il titolo è marcato in grassetto, il sottotitolo in corsivo, ed il corpo non è marcato:

**La civil conversazione**  
*La trasmissione francese “Apostrophe” è stata un modello di discussione colta e pacata lontanissima dai talk-show sguaiati. In Italia niente di simile*  
“Le Magazine Littéraire” ha dedicato un supplemento alla rievocazione di “Apostrophe”, la celebre trasmissione condotta da Bernard Pivot tra il 1975 e il 1990, e che ha rappresentato un fenomeno abbastanza unico nella storia di quelli che abitualmente si chiamano “talk shows”. “Apostrophe” andava in onda in prima serata e, siccome vi ho partecipato varie volte, ricordo un episodio abbastanza significativo. Una mattina dopo la trasmissione, entrato in un bar per prendere un caffè, il barista non ha voluto essere pagato. Questo significa semplicemente che un barista (non un intellettuale che vive tra i libri) si metteva in prima serata a seguire una trasmissione dedicata esclusivamente ai libri. E credo che questo fosse dovuto al fascino e alla capacità comunicativa di Pivot.

A questo punto ci sono 2 operazioni da portare avanti:

1. Trasformare gli *a capo* in semplici spazi, in modo che tutto il testo dell'articolo occupi una sola riga.
2. (opzionale) Includere il *titolo* e il *sottotitolo* all'interno di un tag, identificato dai simboli *minore* <kbd><</kbd> e *maggiore* <kbd>></kbd>.

Il risultato finale apparirà simile a quanto riportato sotto:

> <La civil conversazione La trasmissione francese “Apostrophe” è stata un modello di discussione colta e pacata lontanissima dai talk-show sguaiati. In Italia niente di simile> “Le Magazine Littéraire” ha dedicato un supplemento alla rievocazione di “Apostrophe”, la celebre trasmissione condotta da Bernard Pivot tra il 1975 e il 1990, e che ha rappresentato un fenomeno abbastanza unico nella storia di quelli che abitualmente si chiamano “talk shows”. “Apostrophe” andava in onda in prima serata e, siccome vi ho partecipato varie volte, ricordo un episodio abbastanza significativo. Una mattina dopo la trasmissione, entrato in un bar per prendere un caffè, il barista non ha voluto essere pagato. Questo significa semplicemente che un barista (non un intellettuale che vive tra i libri) si metteva in prima serata a seguire una trasmissione dedicata esclusivamente ai libri. E credo che questo fosse dovuto al fascino e alla capacità comunicativa di Pivot.

:heavy_check_mark: **Suggerimento**: è possibile automatizzare la trasformazione degli *a capo* in *spazi semplici* usando un editor di testo che supporta le espressioni regolari. Nel caso di `Notepad++`
