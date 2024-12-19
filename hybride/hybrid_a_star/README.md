# Hybrid A*-Algorithmus

Der Hybrid A*-Algorithmus kombiniert Sampling-basierte und graphenbasierte Ansätze, um effizient Pfade in kontinuierlichen Räumen zu finden. 
Er dient in der Informatik der Berechnung eines kürzesten Pfades zwischen zwei Knoten in einem Graphen mit positiven Kantengewichten.

## Funktionsweise
1. Nutzt eine heuristische Funktion (z. B. Manhattan-Distanz) zur Pfadplanung.
2. Erweitert Knoten ähnlich wie A* in einem kontinuierlichen Raum.
3. Führt dynamische Kollisionsprüfungen und Verfeinerungen durch.

## Benötigte Daten
- **Start- und Zielposition:** Anfangs- und Endpunkt der Trajektorie.
- **Kollisionsmodell:** Darstellung der Hindernisse im Suchraum.
- **Bewegungsmodell:** Physikalische Beschränkungen des beweglichen Objekts (z. B. Wenderadius).
- **Heuristik:** Eine Funktion, die die Entfernung zwischen Punkten schätzt.

### Vorteile
- Liefert präzisere Ergebnisse als reine Sampling- oder Graphenansätze.
- Nutzt heuristische Optimierung zur Effizienzsteigerung.

### Nachteile
- Erhöhte Berechnungskosten durch die kontinuierliche Kollisionsprüfung.

### Relevante Repositories
- [Hybrid A*-Algorithmus in Python](https://github.com/jacobsayono/a-star-algorithm)
