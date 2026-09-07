# sqlmap

[![.github/workflows/tests.yml](https://github.com/gurenduben/sqlmap/actions/workflows/tests.yml/badge.svg)](https://github.com/gurenduben/sqlmap/actions/workflows/tests.yml) [![Python 2.7|3.x](https://img.shields.io/badge/python-2.7|3.x-yellow.svg)](https://www.python.org/) [![License](https://img.shields.io/badge/license-GPLv2-red.svg)](https://raw.githubusercontent.com/gurenduben/sqlmap/master/LICENSE) [![x](https://img.shields.io/badge/x-@sqlmap-blue.svg)](https://x.com/sqlmap)

sqlmap je alat namijenjen za penetracijsko testiranje koji automatizira proces detekcije i eksploatacije sigurnosnih propusta SQL injekcije te preuzimanje poslužitelja baze podataka. Dolazi s moćnim mehanizmom za detekciju, mnoštvom korisnih opcija za napredno penetracijsko testiranje te široki spektar opcija od onih za prepoznavanja baze podataka, preko dohvaćanja podataka iz baze, do pristupa zahvaćenom datotečnom sustavu i izvršavanja komandi na operacijskom sustavu korištenjem tzv. "out-of-band" veza.

Slike zaslona
----

![Slika zaslona](https://raw.github.com/wiki/gurenduben/sqlmap/images/sqlmap_screenshot.png)

Možete posjetiti [kolekciju slika zaslona](https://github.com/gurenduben/sqlmap/wiki/Screenshots) gdje se demonstriraju neke od značajki na wiki stranicama.

Instalacija
----

Možete preuzeti zadnji tarball klikom [ovdje](https://github.com/gurenduben/sqlmap/tarball/master) ili zadnji zipball klikom [ovdje](https://github.com/gurenduben/sqlmap/zipball/master).

Po mogućnosti, možete preuzeti sqlmap kloniranjem [Git](https://github.com/gurenduben/sqlmap) repozitorija:

    git clone --depth 1 https://github.com/gurenduben/sqlmap.git sqlmap-dev

sqlmap radi bez posebnih zahtjeva korištenjem [Python](https://www.python.org/download/) verzije **2.7** i/ili **3.x** na bilo kojoj platformi.

Korištenje
----

Kako biste dobili listu osnovnih opcija i prekidača koristite:

    python sqlmap.py -h

Kako biste dobili listu svih opcija i prekidača koristite:

    python sqlmap.py -hh

Možete pronaći primjer izvršavanja [ovdje](https://asciinema.org/a/46601).
Kako biste dobili pregled mogućnosti sqlmap-a, liste podržanih značajki te opis svih opcija i prekidača, zajedno s primjerima, preporučen je uvid u [korisnički priručnik](https://github.com/gurenduben/sqlmap/wiki/Usage).

Poveznice
----

* Početna stranica: https://sqlmap.org
* Preuzimanje: [.tar.gz](https://github.com/gurenduben/sqlmap/tarball/master) ili [.zip](https://github.com/gurenduben/sqlmap/zipball/master)
* RSS feed promjena u kodu: https://github.com/gurenduben/sqlmap/commits/master.atom
* Prijava problema: https://github.com/gurenduben/sqlmap/issues
* Korisnički priručnik: https://github.com/gurenduben/sqlmap/wiki
* Najčešće postavljena pitanja (FAQ): https://github.com/gurenduben/sqlmap/wiki/FAQ
* X: [@sqlmap](https://x.com/sqlmap)
* Demo: [https://www.youtube.com/user/inquisb/videos](https://www.youtube.com/user/inquisb/videos)
* Vježbalište: https://sekumart.sekuripy.hr
* Istraživanje: https://www.sekuripy.hr/labs/sqlmap/#research
* Slike zaslona: https://github.com/gurenduben/sqlmap/wiki/Screenshots
