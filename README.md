# Lokale-Planungsalgorithmen
Dieses Repository enthält eine Sammlung von lokalen Planungsalgorithmen, die in der Robotik und Bewegungsplanung verwendet werden. Jeder Algorithmus wird in einem eigenen Ordner präsentiert.

# Lokale Planungsalgorithmen

Dieses Repository enthält eine Sammlung von lokalen Planungsalgorithmen, die in der Robotik und Bewegungsplanung eingesetzt werden. Die Algorithmen sind in Kategorien unterteilt und jeder Algorithmus wird in einem eigenen Unterordner präsentiert.

---

# Kategorien der Algorithmen

# 1. Graphenbasierte Algorithmen
- **[Dijkstra](graphenbasiert/dijkstra)**: Sucht den kürzesten Weg in einem gewichteten Graphen.
- **[A* (A-Star)](graphenbasiert/a_star)**: Erweiterung von Dijkstra, die heuristische Funktionen verwendet.

# 2. Sampling-basierte Algorithmen
- **[RRT (Rapidly-exploring Random Tree)](samplingbasiert/rrt)**: Nutzt zufällige Punkte zur Pfadfindung.
- **[PRM (Probabilistic Roadmap)](samplingbasiert/prm)**: Erstellt eine Karte basierend auf zufälligen Knoten.

# 3. Hybride Algorithmen
- **[RRT*](hybride/rrt_star)**: Optimiert RRT mit kürzeren und effizienteren Pfaden.
- **[Hybrid A*](hybride/hybrid_a_star)**: Kombination aus Sampling- und graphenbasierten Methoden.

---

## Aufbau des Repositories

Die Struktur ist wie folgt organisiert:
```plaintext
lokale-planungsalgorithmen/
├── graphenbasiert/
│   ├── dijkstra/
│   │   ├── README.md
│   │   └── links.md
│   ├── a_star/
│       ├── README.md
│       └── links.md
├── samplingbasiert/
│   ├── rrt/
│   │   ├── README.md
│   │   └── links.md
│   ├── prm/
│       ├── README.md
│       └── links.md
├── hybride/
│   ├── rrt_star/
│   │   ├── README.md
│   │   └── links.md
│   ├── hybrid_a_star/
│       ├── README.md
│       └── links.md
