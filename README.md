# Grundlagen XML und RDF 

Unterlagen und Material für die Vorlesung "Grundlagen XML und RDF" (BIM-108-01) der Hochschule Hannover.

## Veranstaltungsübersicht 

| #  | Tag  | Thema      |
| --:| ----:| ---------- |
|1.  | 5.3  | Einführung in XML |
|2.  | 12.3 | XML: Fortgeschrittene Themen |
|3.  | 19.3 | XPath |
|4.  | 26.3 | Schema: Document Type Definition (DTD) |  
|5.  | 9.4  | Schema: XML Schema |
|6.  | 16.4 | Einführung in RDF |
|7.  | 23.4 | RDF Syntax: Eine breite Wahl |
|8.  | 30.4 | RDF: Fortgeschrittene Themen |
|9.  | 7.5  | SPARQL: Die RDF Abfragesprache |
|10. | 14.5 | SPARQL: Fortgeschrittene Themen |
|11. | 28.5 | Einführung in RDF Schema |
|12. | 4.6  | Ontologien mit RDF Schema |
|13. | 11.6 | Tools für RDF |
|14. | 18.6 | XML und RDF: Rückschau und Ausblick |
|15. | (?) 25.6 | Klausur |

## Übungen

### Voraussetzungen

* Anaconda: [https://www.anaconda.com/download/](https://www.anaconda.com/download/)
* Git Client: [https://git-scm.com/downloads](https://git-scm.com/downloads)

### Anleitung

#### Setup

* [GitHub](https://github.com) Account eröffnen oder einloggen, falls vorhanden
* Neues Repository `bim-108-01-solutions` erstellen
* "Git Bash Here" auf Desktop mittels rechter Maustaste
* In Git Bash, folgende Befehle ausführen (USERNAME entsprechend ersetzen)

``` 
git clone https://markusstocker@github.com/markusstocker/bim-108-01.git
git clone https://USERNAME@github.com/USERNAME/bim-108-01-solutions.git
``` 

#### Übung NN Ausführen

* NN steht für die Übungsnummer: 01, 02, ...
* In Git Bash, folgende Befehle ausführen

```
cd bim-108-01/
git pull
cp notebooks/lecture-NN/lecture-NN.ipynb ../bim-108-01-solutions/
```

* Anaconda Navigator starten
* Jupyter Notebook starten
* Nach `bim-108-01-solutions` navigieren und `lecture-NN.ipynb` öffnen

#### Übung NN Einreichen

* Übung in Jupyter Notebook speichern
* Jupyter Notebook verlassen
* In Git Bash, folgende Befehle ausführen

```
cd bim-108-01-solutions/
git add lecture-NN.ipynb
git commit -a -m "solution to exercise NN"
git push
```
