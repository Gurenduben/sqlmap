# sqlmap

[![.github/workflows/tests.yml](https://github.com/gurenduben/sqlmap/actions/workflows/tests.yml/badge.svg)](https://github.com/gurenduben/sqlmap/actions/workflows/tests.yml) [![Python 2.7|3.x](https://img.shields.io/badge/python-2.7|3.x-yellow.svg)](https://www.python.org/) [![License](https://img.shields.io/badge/license-GPLv2-red.svg)](https://raw.githubusercontent.com/gurenduben/sqlmap/master/LICENSE) [![x](https://img.shields.io/badge/x-@sqlmap-blue.svg)](https://x.com/sqlmap)

sqlmap sql injection açıklarını otomatik olarak tespit ve istismar etmeye yarayan açık kaynak bir penetrasyon aracıdır. sqlmap gelişmiş tespit özelliğinin yanı sıra penetrasyon testleri sırasında gerekli olabilecek birçok aracı, uzak veritabanından, veri indirmek, dosya sistemine erişmek, dosya çalıştırmak gibi işlevleri de barındırmaktadır.


Ekran görüntüleri
----

![Screenshot](https://raw.github.com/wiki/gurenduben/sqlmap/images/sqlmap_screenshot.png)


İsterseniz özelliklerin tanıtımının yapıldığı [ekran görüntüleri](https://github.com/gurenduben/sqlmap/wiki/Screenshots) sayfasını ziyaret edebilirsiniz.


Kurulum
----

[Buraya](https://github.com/gurenduben/sqlmap/tarball/master) tıklayarak en son sürüm tarball'ı veya [buraya](https://github.com/gurenduben/sqlmap/zipball/master) tıklayarak zipball'ı indirebilirsiniz.

Veya tercihen, [Git](https://github.com/gurenduben/sqlmap) reposunu klonlayarak indirebilirsiniz

    git clone --depth 1 https://github.com/gurenduben/sqlmap.git sqlmap-dev

sqlmap [Python](https://www.python.org/download/) sitesinde bulunan **2.7** ve **3.x** versiyonları ile bütün platformlarda çalışabilmektedir.

Kullanım
----


Bütün basit seçeneklerin listesini gösterir

    python sqlmap.py -h

Bütün seçenekleri gösterir

    python sqlmap.py -hh

Program ile ilgili örnekleri [burada](https://asciinema.org/a/46601) bulabilirsiniz. Daha fazlası için sqlmap'in bütün açıklamaları ile birlikte bütün özelliklerinin, örnekleri ile bulunduğu [manuel sayfamıza](https://github.com/gurenduben/sqlmap/wiki/Usage) bakmanızı tavsiye ediyoruz

Bağlantılar
----

* Anasayfa: https://sqlmap.org
* İndirme bağlantıları: [.tar.gz](https://github.com/gurenduben/sqlmap/tarball/master) veya [.zip](https://github.com/gurenduben/sqlmap/zipball/master)
* Commitlerin RSS beslemeleri: https://github.com/gurenduben/sqlmap/commits/master.atom
* Hata takip etme sistemi: https://github.com/gurenduben/sqlmap/issues
* Kullanıcı Manueli: https://github.com/gurenduben/sqlmap/wiki
* Sıkça Sorulan Sorular(SSS): https://github.com/gurenduben/sqlmap/wiki/FAQ
* X: [@sqlmap](https://x.com/sqlmap)
* Demolar: [https://www.youtube.com/user/inquisb/videos](https://www.youtube.com/user/inquisb/videos)
* Deneme alanı: https://sekumart.sekuripy.hr
* Araştırma: https://www.sekuripy.hr/labs/sqlmap/#research
* Ekran görüntüleri: https://github.com/gurenduben/sqlmap/wiki/Screenshots
