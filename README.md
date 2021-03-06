<!--
  Description: Toki Pona, Das Ziel der von Sonja Lang (2001) künstlich geschaffene Sprache ist der Minimalismus. 
  -->

[English](https://jan-lope.github.io/Toki_Pona_lessons_English/)

# Toki Pona - Lektionen und Wörterbuch 

Das Ziel der von Sonja Lang (2001) künstlich geschaffenen Sprache toki pona ist der Minimalismus. toki pona besteht aus nur etwa 120 Wörtern, die in ihrer Form auch nicht verändert werden. 

Diese Lektionen basieren auf den Lektionen (2003) von jan Pije ( [tokipona.net/tp/janpije](http://tokipona.net/tp/janpije/) ) und dem offiziellen Toki Pona Buch (first English edition 2014) von Sonja Lang ( [tokipona.org](http://tokipona.org) ).  


## Lektionen 

Diese Lektionen können in unterschiedlichen Formaten herunter geladen werden. 
Erscheint der Fehler 404, drücke die Shift-Taste und den Reload-Button des Browsers. 

[pdf (A4)](https://github.com/jan-Lope/Toki_Pona_Lektionen_Deutsch/raw/gh-pages/toki-pona-lessons_de.pdf) | 
[pdf (letter)](https://github.com/jan-Lope/Toki_Pona_Lektionen_Deutsch/raw/gh-pages/toki-pona-lessons_de-letter.pdf) 


[pdf (booklet A5)](https://github.com/jan-Lope/Toki_Pona_Lektionen_Deutsch/raw/gh-pages/toki-pona-lessons_de-booklet.pdf) | 
[pdf (booklet letter)](https://github.com/jan-Lope/Toki_Pona_Lektionen_Deutsch/raw/gh-pages/toki-pona-lessons_de-booklet-letter.pdf) 
Bei der Booklet-Version werden jeweils zwei Seiten auf eine A4/Letter-Seite abgebildet, so dass ein daraus ein Booklet erstellt werden kann. Dazu werden erst alle ungeraden Seiten ausgedruckt. Dann legt man die Blätter wieder ins Papierfach zurück und druckt alle geraden Seiten in absteigender Reihenfolge aus. 


eBook [epub](https://github.com/jan-Lope/Toki_Pona_Lektionen_Deutsch/raw/gh-pages/toki-pona-lessons_de.epub) | 
[mobi](https://github.com/jan-Lope/Toki_Pona_Lektionen_Deutsch/raw/gh-pages/toki-pona-lessons_de.mobi) | 
[azw3](https://github.com/jan-Lope/Toki_Pona_Lektionen_Deutsch/raw/gh-pages/toki-pona-lessons_de.azw3)

[Online-Version](https://htmlpreview.github.io/?https://raw.githubusercontent.com/jan-Lope/Toki_Pona_Lektionen_Deutsch/gh-pages/toki-pona-lessons_de/index.html) Erscheint der Fehler 404, drücke die Shift-Taste und den Reload-Button des Browsers.  


## Liste der offiziellen Toki Pona Wörter

[txt](https://github.com/jan-Lope/Toki_Pona_Lektionen_Deutsch/raw/gh-pages/nimi_pi_toki_pona.txt)  | 
[csv](https://github.com/jan-Lope/Toki_Pona_Lektionen_Deutsch/raw/gh-pages/nimi_pi_toki_pona.csv)  | 
[rtf](https://github.com/jan-Lope/Toki_Pona_Lektionen_Deutsch/raw/gh-pages/nimi_pi_toki_pona.rtf)  |
[otm-json](https://github.com/jan-Lope/Toki_Pona_Lektionen_Deutsch/raw/gh-pages/nimi_pi_toki_pona.json) 

[dict](https://github.com/jan-Lope/Toki_Pona_Lektionen_Deutsch/raw/gh-pages/nimi_pi_toki_pona-dict.dict)  | 
[index](https://github.com/jan-Lope/Toki_Pona_Lektionen_Deutsch/raw/gh-pages/nimi_pi_toki_pona-dict.index) 
DICT Dateiformat

[unix man page](https://github.com/jan-Lope/Toki_Pona_Lektionen_Deutsch/raw/gh-pages/toki-pona.6.gz) 
Unix, Linux und Mac OS X: sudo cp toki-pona.6* /usr/share/man/man6/ ; man toki-pona


## Toki Pona - Deutsch Wörterbuch

[Online-Version](https://htmlpreview.github.io/?https://raw.githubusercontent.com/jan-Lope/Toki_Pona_Lektionen_Deutsch/gh-pages/dictionary.html) 

[csv](https://raw.githubusercontent.com/jan-Lope/Toki_Pona_Lektionen_Deutsch/gh-pages/toki-pona_deutsch.csv) 

[otm-json](https://raw.githubusercontent.com/jan-Lope/Toki_Pona_Lektionen_Deutsch/gh-pages/toki-pona-lessons_de.json) 

[txt](https://raw.githubusercontent.com/jan-Lope/Toki_Pona_Lektionen_Deutsch/gh-pages/toki-pona_deutsch.txt) für die Software [ding](http://www-user.tu-chemnitz.de/~fri/ding/).

![ding](ding01.png?raw=true "ding")



## Source Codes

Die PDF-, HTML-, EBook- und TXT-Dateien werden automatisch aus den Latex-Dateien per [travis-ci.org](https://travis-ci.org/jan-Lope/Toki_Pona_Lektionen_Deutsch) generiert.

Die Latex-Datei und die anderen Dateien sind in [Github](https://github.com/jan-Lope/Toki_Pona_Lektionen_Deutsch) veröffentlicht.  

Mit dem Git-Client holte man sich die Quellen.

	git clone https://github.com/jan-Lope/Toki_Pona_Lektionen_Deutsch.git
	

## Manuelles Generieren

Das manuelle Generieren der Dateien kann unter Ubuntu erfolgen. Dazu sind folgende Pakete zu installieren:


    sudo apt-get install texlive texlive-base texlive-latex-base texlive-extra-utils texlive-binaries texlive-extra-utils texlive-font-utils texlive-pictures texlive-pstricks texlive-latex-extra 
    sudo apt-get install latex2html latex-xcolor npm nodejs coffeescript calibre latex2rtf dictfmt



Lade alle Dateien in ein Verzeichnis und wechsle in diese Verzeichis. Unter Linux (Ubuntu) starte folgendes Script:


    ./make.sh



  
[jan Lope](https://jan-lope.github.io)
