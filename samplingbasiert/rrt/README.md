# RRT (Rapidly-exploring Random Tree)

RRT ist ein sampling-basierter Algorithmus, der zufällige Punkte im Suchraum generiert, um eine kollisionsfreie Bewegung zu finden.

## Funktionsweise
1. Wähle einen zufälligen Punkt im Suchraum.
2. Erzeuge eine Verbindung vom nächsten bekannten Punkt zum zufälligen Punkt.
3. Wiederhole den Prozess, bis das Ziel erreicht ist.

## Benötigte Daten
- **Startposition:** Die Anfangskoordinate des Objekts im Raum.
- **Zielposition:** Die gewünschte Endposition im Raum.
- **Begrenzungen des Suchraums:** Informationen über die Grenzen des Arbeitsraums.
- **Kollisionsmodell:** Hindernisgeometrie, um Kollisionen zu vermeiden.

### Vorteile
- Funktioniert gut in großen und komplexen Umgebungen.

### Nachteile
- Kann suboptimale Pfade liefern.

### Relevante Repositories
- [RRT-Algorithmus in Python](https://github.com/ArianJM/rapidly-exploring-random-trees/tree/master)
