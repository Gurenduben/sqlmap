# sqlmap

[![.github/workflows/tests.yml](https://github.com/gurenduben/sqlmap/actions/workflows/tests.yml/badge.svg)](https://github.com/gurenduben/sqlmap/actions/workflows/tests.yml) [![Python 2.7|3.x](https://img.shields.io/badge/python-2.7|3.x-yellow.svg)](https://www.python.org/) [![License](https://img.shields.io/badge/license-GPLv2-red.svg)](https://raw.githubusercontent.com/gurenduben/sqlmap/master/LICENSE) [![x](https://img.shields.io/badge/x-@sqlmap-blue.svg)](https://x.com/sqlmap)

sqlmap - это инструмент для тестирования уязвимостей с открытым исходным кодом, который автоматизирует процесс обнаружения и использования ошибок SQL-инъекций и захвата серверов баз данных. Он оснащен мощным механизмом обнаружения, множеством приятных функций для профессионального тестера уязвимостей и широким спектром скриптов, которые упрощают работу с базами данных, от сбора данных из базы данных, до доступа к базовой файловой системе и выполнения команд в операционной системе через out-of-band соединение.

Скриншоты
----

![Screenshot](https://raw.github.com/wiki/gurenduben/sqlmap/images/sqlmap_screenshot.png)

Вы можете посетить [набор скриншотов](https://github.com/gurenduben/sqlmap/wiki/Screenshots) демонстрируемые некоторые функции в wiki.

Установка
----

Вы можете скачать последнюю версию tarball, нажав [сюда](https://github.com/gurenduben/sqlmap/tarball/master) или последний zipball, нажав  [сюда](https://github.com/gurenduben/sqlmap/zipball/master).

Предпочтительно вы можете загрузить sqlmap, клонируя [Git](https://github.com/gurenduben/sqlmap) репозиторий:

    git clone --depth 1 https://github.com/gurenduben/sqlmap.git sqlmap-dev

sqlmap работает из коробки с [Python](https://www.python.org/download/) версии **2.7** и **3.x** на любой платформе.

Использование
----

Чтобы получить список основных опций и вариантов выбора, используйте:

    python sqlmap.py -h

Чтобы получить список всех опций и вариантов выбора, используйте:

    python sqlmap.py -hh

Вы можете найти пробный запуск [тут](https://asciinema.org/a/46601).
Чтобы получить обзор возможностей sqlmap, список поддерживаемых функций и описание всех параметров и переключателей, а также примеры, вам рекомендуется ознакомится с [пользовательским мануалом](https://github.com/gurenduben/sqlmap/wiki/Usage).

Ссылки
----

* Основной сайт: https://sqlmap.org
* Скачивание: [.tar.gz](https://github.com/gurenduben/sqlmap/tarball/master) или [.zip](https://github.com/gurenduben/sqlmap/zipball/master)
* Канал новостей RSS: https://github.com/gurenduben/sqlmap/commits/master.atom
* Отслеживание проблем: https://github.com/gurenduben/sqlmap/issues
* Пользовательский мануал: https://github.com/gurenduben/sqlmap/wiki
* Часто задаваемые вопросы (FAQ): https://github.com/gurenduben/sqlmap/wiki/FAQ
* X: [@sqlmap](https://x.com/sqlmap)
* Демки: [https://www.youtube.com/user/inquisb/videos](https://www.youtube.com/user/inquisb/videos)
* Песочница: https://sekumart.sekuripy.hr
* Исследования: https://www.sekuripy.hr/labs/sqlmap/#research
* Скриншоты: https://github.com/gurenduben/sqlmap/wiki/Screenshots
