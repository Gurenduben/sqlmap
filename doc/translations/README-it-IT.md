# sqlmap

[![.github/workflows/tests.yml](https://github.com/gurenduben/sqlmap/actions/workflows/tests.yml/badge.svg)](https://github.com/gurenduben/sqlmap/actions/workflows/tests.yml) [![Python 2.7|3.x](https://img.shields.io/badge/python-2.7|3.x-yellow.svg)](https://www.python.org/) [![License](https://img.shields.io/badge/license-GPLv2-red.svg)](https://raw.githubusercontent.com/gurenduben/sqlmap/master/LICENSE) [![x](https://img.shields.io/badge/x-@sqlmap-blue.svg)](https://x.com/sqlmap)

sqlmap è uno strumento open source per il penetration testing. Il suo scopo è quello di rendere automatico il processo di scoperta ed exploit di vulnerabilità di tipo SQL injection al fine di compromettere database online. Dispone di un potente motore per la ricerca di vulnerabilità, molti strumenti di nicchia anche per il più esperto penetration tester ed un'ampia gamma di controlli che vanno dal fingerprinting di database allo scaricamento di dati, fino all'accesso al file system sottostante e l'esecuzione di comandi nel sistema operativo attraverso connessioni out-of-band.

Screenshot
----

![Screenshot](https://raw.github.com/wiki/gurenduben/sqlmap/images/sqlmap_screenshot.png)

Nella wiki puoi visitare [l'elenco di screenshot](https://github.com/gurenduben/sqlmap/wiki/Screenshots) che mostrano il funzionamento di alcune delle funzionalità del programma.

Installazione
----

Puoi scaricare l'ultima tarball cliccando [qui](https://github.com/gurenduben/sqlmap/tarball/master) oppure l'ultima zipball cliccando [qui](https://github.com/gurenduben/sqlmap/zipball/master).

La cosa migliore sarebbe però scaricare sqlmap clonando la repository [Git](https://github.com/gurenduben/sqlmap):

    git clone --depth 1 https://github.com/gurenduben/sqlmap.git sqlmap-dev

sqlmap è in grado di funzionare con le versioni **2.7** e **3.x** di [Python](https://www.python.org/download/) su ogni piattaforma.

Utilizzo
----

Per una lista delle opzioni e dei controlli di base:

    python sqlmap.py -h

Per una lista di tutte le opzioni e di tutti i controlli:

    python sqlmap.py -hh

Puoi trovare un esempio di esecuzione [qui](https://asciinema.org/a/46601).
Per una panoramica delle capacità di sqlmap, una lista delle sue funzionalità e la descrizione di tutte le sue opzioni e controlli, insieme ad un gran numero di esempi, siete pregati di visitare lo [user's manual](https://github.com/gurenduben/sqlmap/wiki/Usage) (disponibile solo in inglese).

Link
----

* Sito: https://sqlmap.org
* Download: [.tar.gz](https://github.com/gurenduben/sqlmap/tarball/master) or [.zip](https://github.com/gurenduben/sqlmap/zipball/master)
* RSS feed dei commit: https://github.com/gurenduben/sqlmap/commits/master.atom
* Issue tracker: https://github.com/gurenduben/sqlmap/issues
* Manuale dell'utente: https://github.com/gurenduben/sqlmap/wiki
* Domande più frequenti (FAQ): https://github.com/gurenduben/sqlmap/wiki/FAQ
* X: [@sqlmap](https://x.com/sqlmap)
* Dimostrazioni: [https://www.youtube.com/user/inquisb/videos](https://www.youtube.com/user/inquisb/videos)
* Campo di prova: https://sekumart.sekuripy.hr
* Ricerca: https://www.sekuripy.hr/labs/sqlmap/#research
* Screenshot: https://github.com/gurenduben/sqlmap/wiki/Screenshots
