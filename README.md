# Befragungen
Fragebögen für ÜLU Kursleiter und Teilnehmende

## CI

- bei jedem push auf `main` wird ein build getriggered
- wir schauen nach ob sich eine markdown Datei (die nicht README.md ist) geändert hat
- wenn ja, werden SCORM Pakete erstellt und Release erstellt
- versions-nummer incrementieren wenn Änderungen an den Kursen durchgeführt werden
    - sonst schlägt der build fehl
    - weil gleicher Release-Name nicht erlaubt ist
