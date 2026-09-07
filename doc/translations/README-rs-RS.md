# sqlmap

[![.github/workflows/tests.yml](https://github.com/gurenduben/sqlmap/actions/workflows/tests.yml/badge.svg)](https://github.com/gurenduben/sqlmap/actions/workflows/tests.yml) [![Python 2.7|3.x](https://img.shields.io/badge/python-2.7|3.x-yellow.svg)](https://www.python.org/) [![License](https://img.shields.io/badge/license-GPLv2-red.svg)](https://raw.githubusercontent.com/gurenduben/sqlmap/master/LICENSE) [![x](https://img.shields.io/badge/x-@sqlmap-blue.svg)](https://x.com/sqlmap)

sqlmap je alat otvorenog koda namenjen za penetraciono testiranje koji automatizuje proces detekcije i eksploatacije sigurnosnih propusta SQL injekcije i preuzimanje baza podataka. Dolazi s moćnim mehanizmom za detekciju, mnoštvom korisnih opcija za napredno penetracijsko testiranje te široki spektar opcija od onih za prepoznavanja baze podataka, preko uzimanja podataka iz baze, do pristupa zahvaćenom fajl sistemu i izvršavanja komandi na operativnom sistemu korištenjem tzv. "out-of-band" veza.

Slike
----

![Slika](https://raw.github.com/wiki/gurenduben/sqlmap/images/sqlmap_screenshot.png)

Možete posetiti [kolekciju slika](https://github.com/gurenduben/sqlmap/wiki/Screenshots) gde su demonstrirane neke od e se demonstriraju neke od funkcija na wiki stranicama.

Instalacija
----

Možete preuzeti najnoviji tarball klikom [ovde](https://github.com/gurenduben/sqlmap/tarball/master) ili najnoviji zipball klikom [ovde](https://github.com/gurenduben/sqlmap/zipball/master).

Opciono, možete preuzeti sqlmap kloniranjem [Git](https://github.com/gurenduben/sqlmap) repozitorija:

    git clone --depth 1 https://github.com/gurenduben/sqlmap.git sqlmap-dev

sqlmap radi bez posebnih zahteva korištenjem [Python](https://www.python.org/download/) verzije **2.7** i/ili **3.x** na bilo kojoj platformi.

Korišćenje
----

Kako biste dobili listu osnovnih opcija i prekidača koristite:

    python sqlmap.py -h

Kako biste dobili listu svih opcija i prekidača koristite:

    python sqlmap.py -hh

Možete pronaći primer izvršavanja [ovde](https://asciinema.org/a/46601).
Kako biste dobili pregled mogućnosti sqlmap-a, liste podržanih funkcija, te opis svih opcija i prekidača, zajedno s primerima, preporučen je uvid u [korisnički priručnik](https://github.com/gurenduben/sqlmap/wiki/Usage).

Linkovi
----

* Početna stranica: https://sqlmap.org
* Preuzimanje: [.tar.gz](https://github.com/gurenduben/sqlmap/tarball/master) ili [.zip](https://github.com/gurenduben/sqlmap/zipball/master)
* RSS feed promena u kodu: https://github.com/gurenduben/sqlmap/commits/master.atom
* Prijava problema: https://github.com/gurenduben/sqlmap/issues
* Korisnički priručnik: https://github.com/gurenduben/sqlmap/wiki
* Najčešće postavljena pitanja (FAQ): https://github.com/gurenduben/sqlmap/wiki/FAQ
* X: [@sqlmap](https://x.com/sqlmap)
* Demo: [https://www.youtube.com/user/inquisb/videos](https://www.youtube.com/user/inquisb/videos)
* Poligon: https://sekumart.sekuripy.hr
* Istraživanje: https://www.sekuripy.hr/labs/sqlmap/#research
* Slike: https://github.com/gurenduben/sqlmap/wiki/Screenshots
