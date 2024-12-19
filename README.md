# Lokale Planungsalgorithmen
Dieses Repository enthält eine Sammlung von lokalen Planungsalgorithmen, die in der Robotik und Bewegungsplanung eingesetzt werden. Die Algorithmen sind in Kategorien unterteilt und jeder Algorithmus wird in einem eigenen Unterordner präsentiert.

---

# Kategorien der Algorithmen

# 1. Graphenbasierte Algorithmen
- **[Dijkstra](graphenbasiert/dijkstra)**: Sucht den kürzesten Weg in einem gewichteten Graphen.

# 2. Sampling-basierte Algorithmen
- **[RRT (Rapidly-exploring Random Tree)](samplingbasiert/rrt)**: Nutzt zufällige Punkte zur Pfadfindung.


# 3. Hybride Algorithmen
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
├── samplingbasiert/
│   ├── rrt/
│   │   ├── README.md
│   │   └── links.md
├── hybride/
│   ├── hybrid_a_star/
│       ├── README.md
│       └── links.md
