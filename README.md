# Grundlagen XML und RDF 

Unterlagen und Material für die Vorlesung "Grundlagen XML und RDF" (BIM-108-01) der Hochschule Hannover.

## Veranstaltungsübersicht 

| #  | Tag  | Thema      |
| --:| ----:| ---------- |
|1.  | 5.3.  | Einführung in XML |
|2.  | 12.3. | XML: Fortgeschrittene Themen |
|3.  | 19.3. | XPath |
|4.  | 26.3. | Fällt aus |
|5.  | 9.4. | Schema: Document Type Definition (DTD) | 
|6.  | 16.4. | Schema: XML Schema |
|7.  | 23.4. | Einführung in RDF |
|8.  | 30.4. | RDF Syntax: Eine breite Wahl |
|9.  | 7.5. | RDF: Fortgeschrittene Themen |
|10.  | 14.5.  | SPARQL: Die RDF Abfragesprache |
|11. | 28.5. | SPARQL: Fortgeschrittene Themen |
|12. | 4.6. | Einführung in RDF Schema |
|13. | 11.6.  | Ontologien mit RDF Schema |
|14. | 18.6. | Tools für RDF |
|15. | 25.6. | XML und RDF: Rückschau und Ausblick |
|16. | 10.7. | Klausur |

## Übungen

Die Übungen werden als [Jupyter](http://jupyter.org) Notebooks ausgeliefert und können in eine von zwei Varianten durchgeführt und eingereicht werden. Variante I ist für den schnellen Einstieg. Variante II ist technisch anspruchsvoller dafür lernt man dabei zusätzlich wichtige Tools kennen.

### Variante I

#### Voraussetzungen

* Auf [notebooks.azure.com](https://notebooks.azure.com/) anmelden
* Teilen Sie die URL `https://notebooks.azure.com/USERNAME` dem Übungsleiter per Email mit (USERNAME ersetzen)
* Im Menu, wählen Sie den Punkt `Libraries`
* Wählen Sie `New Library` und benennen Sie Ihre neue Library `bim-108-01-solutions` (`Library Name` gleich wie `Library ID`, und setzen Sie den `Public library` Haken)

#### Übung NN Ausführen

* NN steht für die Übungsnummer: 01, 02, ...
* Laden Sie sich das `bim-108-01` Repository [als ZIP Datei auf Ihren Rechner](https://github.com/markusstocker/bim-108-01/archive/master.zip)
* Entpacken Sie die runtergeladene `bim-108-01-master.zip` ZIP Datei
* In Ihrer `bim-108-01-solutions` Library auf Azure, drücken Sie `New`
* Erstellen Sie den Ordner `lecture-NN` (Achtung: Item type = Folder)
* Wählen Sie nun den neu erstellten Ordner
* Drücken Sie `New` erneut und dann `From computer` und `Choose files`
* Selektieren Sie nun alle Dateien im Verzeichnis `notebooks/lecture-NN` der entpackten ZIP Datei 
* Drücken Sie dann `Upload` um die Dateien der Übung NN auf Azure hochzuladen
* Wählen Sie nun die Datei `lecture-NN.ipynb`
* Führen Sie die Übung durch. Viel Erfolg!
* Übung in Jupyter speichern (File -> Save and Checkpoint)
* Jupyter verlassen (File -> Close and Halt)

### Variante II

#### Voraussetzungen

* Anaconda: [https://www.anaconda.com/download/](https://www.anaconda.com/download/)
* Git Client: [https://git-scm.com/downloads](https://git-scm.com/downloads)
* [GitHub](https://github.com) Account eröffnen oder einloggen, falls vorhanden
* Teilen Sie die URL `https://github.com/USERNAME` dem Übungsleiter per Email mit (USERNAME ersetzen)
* Neues Repository `bim-108-01-solutions` erstellen
* "Git Bash Here" (Windows) auf Desktop mittels rechter Maustaste (Terminal auf Mac)
* In Git Bash, folgende Befehle ausführen (USERNAME ersetzen)

``` 
git clone https://markusstocker@github.com/markusstocker/bim-108-01.git
git clone https://USERNAME@github.com/USERNAME/bim-108-01-solutions.git
``` 

#### Übung NN Ausführen

* NN steht für die Übungsnummer: 01, 02, ...
* In Git Bash, folgende Befehle ausführen

```
mkdir bim-108-01-solutions/lecture-NN
cd bim-108-01/
git pull
cp notebooks/lecture-NN/* ../bim-108-01-solutions/lecture-NN/
```

* Anaconda Navigator/Prompt starten
* Jupyter Notebook starten (Befehl: jupyter notebook)
* In Jupyter Notebook, nach `bim-108-01-solutions/lecture-NN` navigieren 
* Das Notebook `lecture-NN.ipynb` öffnen
* Viel Erfolg!

#### Übung NN Einreichen

* Übung in Jupyter speichern (File -> Save and Checkpoint)
* Jupyter verlassen (File -> Close and Halt)
* In Git Bash, folgende Befehle ausführen

```
cd bim-108-01-solutions/
git add lecture-NN
git commit -a -m "solution to exercise NN"
git push
```

## Lizenz

Sofern nicht anderes angegeben sind die Inhalte under der [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/) (CC BY 4.0) lizenziert.
