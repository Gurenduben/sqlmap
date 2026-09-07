# sqlmap

[![.github/workflows/tests.yml](https://github.com/gurenduben/sqlmap/actions/workflows/tests.yml/badge.svg)](https://github.com/gurenduben/sqlmap/actions/workflows/tests.yml) [![Python 2.7|3.x](https://img.shields.io/badge/python-2.7|3.x-yellow.svg)](https://www.python.org/) [![License](https://img.shields.io/badge/license-GPLv2-red.svg)](https://raw.githubusercontent.com/gurenduben/sqlmap/master/LICENSE) [![x](https://img.shields.io/badge/x-@sqlmap-blue.svg)](https://x.com/sqlmap)

Το sqlmap είναι πρόγραμμα ανοιχτού κώδικα, που αυτοματοποιεί την εύρεση και εκμετάλλευση ευπαθειών τύπου SQL Injection σε βάσεις δεδομένων. Έρχεται με μια δυνατή μηχανή αναγνώρισης ευπαθειών, πολλά εξειδικευμένα χαρακτηριστικά για τον απόλυτο penetration tester όπως και με ένα μεγάλο εύρος επιλογών αρχίζοντας από την αναγνώριση της βάσης δεδομένων, κατέβασμα δεδομένων της βάσης, μέχρι και πρόσβαση στο βαθύτερο σύστημα αρχείων και εκτέλεση εντολών στο απευθείας στο λειτουργικό μέσω εκτός ζώνης συνδέσεων.

Εικόνες
----

![Screenshot](https://raw.github.com/wiki/gurenduben/sqlmap/images/sqlmap_screenshot.png)

Μπορείτε να επισκεφτείτε τη [συλλογή από εικόνες](https://github.com/gurenduben/sqlmap/wiki/Screenshots) που επιδεικνύουν κάποια από τα χαρακτηριστικά.

Εγκατάσταση
----

Έχετε τη δυνατότητα να κατεβάσετε την τελευταία tarball πατώντας [εδώ](https://github.com/gurenduben/sqlmap/tarball/master) ή την τελευταία zipball πατώντας [εδώ](https://github.com/gurenduben/sqlmap/zipball/master).

Κατά προτίμηση, μπορείτε να κατεβάσετε το sqlmap κάνοντας κλώνο το [Git](https://github.com/gurenduben/sqlmap) αποθετήριο:

    git clone --depth 1 https://github.com/gurenduben/sqlmap.git sqlmap-dev

Το sqlmap λειτουργεί χωρίς περαιτέρω κόπο με την [Python](https://www.python.org/download/) έκδοσης **2.7** και **3.x** σε όποια πλατφόρμα.

Χρήση
----

Για να δείτε μια βασική λίστα από επιλογές πατήστε:

    python sqlmap.py -h

Για να πάρετε μια λίστα από όλες τις επιλογές πατήστε:

    python sqlmap.py -hh

Μπορείτε να δείτε ένα δείγμα λειτουργίας του προγράμματος [εδώ](https://asciinema.org/a/46601).
Για μια γενικότερη άποψη των δυνατοτήτων του sqlmap, μια λίστα των υποστηριζόμενων χαρακτηριστικών και περιγραφή για όλες τις επιλογές, μαζί με παραδείγματα, καλείστε να συμβουλευτείτε το [εγχειρίδιο χρήστη](https://github.com/gurenduben/sqlmap/wiki/Usage).

Σύνδεσμοι
----

* Αρχική σελίδα: https://sqlmap.org
* Λήψεις: [.tar.gz](https://github.com/gurenduben/sqlmap/tarball/master) ή [.zip](https://github.com/gurenduben/sqlmap/zipball/master)
* Commits RSS feed: https://github.com/gurenduben/sqlmap/commits/master.atom
* Προβλήματα: https://github.com/gurenduben/sqlmap/issues
* Εγχειρίδιο Χρήστη: https://github.com/gurenduben/sqlmap/wiki
* Συχνές Ερωτήσεις (FAQ): https://github.com/gurenduben/sqlmap/wiki/FAQ
* X: [@sqlmap](https://x.com/sqlmap)
* Demos: [https://www.youtube.com/user/inquisb/videos](https://www.youtube.com/user/inquisb/videos)
* Χώρος δοκιμών: https://sekumart.sekuripy.hr
* Έρευνα: https://www.sekuripy.hr/labs/sqlmap/#research
* Εικόνες: https://github.com/gurenduben/sqlmap/wiki/Screenshots
