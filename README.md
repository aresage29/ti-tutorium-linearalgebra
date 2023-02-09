# Lineare Algebra Tutorium
## Allgemeine Informationen
Hochschule: DHBW Ravensburg Campus Friedrichshafen  
Studiengang: Informatik  
Modul: Mathematik I (T3INF1001)  
Dozent: Christoph Spandl  
Semester: 2023 Q1

## Tutoren
- [Tobias Goetz](https://github.com/TobiasGoetz)
- Mario Schwartz
- Felix Schladt

## Wie kompiliere ich das Projekt?
### Voraussetzungen
Stelle sicher, dass [latexmk](https://mg.readthedocs.io/latexmk.html) installiert ist.
#### Linux
- Perl sollte schon installiert sein.
- Es muss eventuell das Paket latexmk installiert werden.

#### MacOS mit MacTeX
- Wahrscheinlich schon installeirt
- Falls nicht, öffne “TeX Live Utility”, suche nach “latexmk” und installiere es.
- Wenn du das Terminal bevorzugst: `sudo tlmgr install latexmk`

#### Windows mit MikTeX
- Wahrscheinlich muss Perl installiert werden, z.B. von: https://strawberryperl.com/.
- Falls noch nicht installiert, öffne den  MikTeX Paket Manager und installiere das latexmk Paket.

### Latexmk ausführen
```sh
latexmk
```
