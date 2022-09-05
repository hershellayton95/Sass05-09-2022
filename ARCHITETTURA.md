LA CARTELLA BASE
Qui troveremo il file di reset, qualche regola tipografica.
Se il progetto usa molto le animazioni CSS, si potrebbe pensare di aggiungere un file _animations.scss che contiene le definizioni dei @keyframes per le animazioni. Se si usano solo sporadicamente, meglio scriverle nei selettori che le usano.
LA CARTELLA LAYOUT
La cartella layout/ contiene tutto ciò che si occupa di creare i layout del sito. Questa cartella può raccogliere i fogli di stile per le parti principali del sito (header, footer, navigazione, sidebar, etc).
LA CARTELLA COMPONENTS
Per i piccoli componenti, c’è la cartella components/. Mentre layout/ è macro, components/ è più focalizzato sui widget. Contiene tutti i moduli specifici come uno slider, un loader, un widget, e via dicendo. 
LA CARTELLA PAGES
Se si hanno stili specifici per una pagina, è meglio raccoglierli in un file con lo stesso nome in una cartella pages/.
A seconda del processo di deploy, questi file possono essere richiamati indipendentemente nella pagina, piuttosto che essere raccolti col resto del foglio di stile in un unico file.
CARTELLA THEMES
In grossi siti, non è strano avere bisogno di differenti temi. Il bisogno di questa cartella dipende dal progetto. In molti progetti potrebbe non essercene la necessità.
A CARTELLA ABSTRACTS o UTILITIES
La cartella utilities/ raccoglie tutti gli strumenti e gli helper usati nel progetto. Tutte le variabili globali, le funzioni, i mixin e i placeholder dovrebbero essere messi qui dentro.
LA CARTELLA VENDORS
Ultima ma non ultima, la cartella vendors/ presente in molti progetti contiene tutti i file CSS che provengono da librerie e framework esterni.
IL FILE MAIN
Il file principale  dovrebbe essere l’unico file Sass nell’intera codebase a non iniziare per trattino basso (underscore). Questo file conterrà gli @import.
