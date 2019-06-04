# Shell Commands

# Wichtigsten Befehle  - 04.06.2019

Befehl    | Aktion| Zusammensetzung
---------|------|---------------
|rm    |    files löschen
|rm -r |   directory löschen
|mv   |   files in directorys verschieben
|ls   |   directory Inhalte auflisten
|ls -a| alle files inkl. verstecke anzeigen (in der akteullen directory)
|ls -l| alle files inkl. Details (volle länge) anzeigen
|ls -t| files werden geordnet nach letzten Änderungdatum (t)
|cd   | directory wechseln|
|cd .. | eine directory zurück/hoch
|mkdir | directory erstellen
|touch | neue file erstellen
|pwd | aktuelle directory anzeigen in der ich mich befinde
|cp | files kopieren     
|cp * | alle files in directory kopieren


\
\
\
\
\
\
\
\
\
\



# Cheat Sheet für **Shell Befehle** 

#### Wechseln zu anderen Ordnern / Inhalt anzeigen etc.:

- `cd [Ordnername]` change directory
- `..` Weiterleitung in übergeordnete Ordner
- `z neu` = `cd ~/neuefische` z lernt oft benutzte Ordner und bietet so Abkürzung
- `ls` Liste aller Dateien und Unterordner eines Ordners
- `ls -la` Liste mit Details `l` (=long; untereinander auflisten) und durch `a` (=all) werden auch versteckte Dateien angezeigt
- `tree` Verzeichnisbaum anzeigen
- `curl` lädt Objekt über eine URL
- `cat` zeigt den Inhalt einer Datei

#### Neu, verschieben, kopieren, löschen, öffnen:

- `mkdir` Ordner erstellen
- `mkdir [Ordner/Unterordner]` Unterordner erstellen
- `mkdir -p [Ordner/Unterordner/Unterunterordner/...]` Ordnerpfad wird erzeugt
- `touch [Dateiname]` Datei erstellen
- `mv [alter Name] [neuer Name]` Ordner/Datei umbenennen
- `mv [alter Pfad] [neuer Pfad]` Ordner/Datei verschieben
- `mv [Ordner] *` verschieben des Ordners in den aktuellen Ordner
- `cp -R [src-directory] [target-directory]` kopiert alles aus dem Quellverzeichnis in das Zielverzeichnis
- `pbcopy` speichert Eingabe in die Zwischenablage (Bsp.: `cat ~/.ssh/id_rsa.pub | pbcopy`)
- `rm` remove (geht nur bei Dateien)
- `rm -rf` Ordner löschen; `r` = rekursiv (alles in allen Unterordnern); `f` = force (nicht jede Datei einzeln bestätigen); uch **Rimraf** genannt
- `rm -rf *` löschen aller Ordner und Dateien im aktuellen Ordner
- `code .` aktueller Ordner wird bei VS Code aufgerufen
- `open [Datei]` öffnet Datei mit dem Standardprogramm eines Betriebssystems
- `open .` öffnet Ordner im Finder/Explorer


