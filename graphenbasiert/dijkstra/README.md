# Dijkstra-Algorithmus

Der Dijkstra-Algorithmus ist ein graphenbasierter Pfadplanungsalgorithmus. Er berechnet somit einen kürzesten Pfad zwischen dem gegebenen Startknoten und einem der (oder allen) übrigen Knoten in einem kantengewichteten Graphen. Für unzusammenhängende ungerichtete Graphen ist der Abstand zu denjenigen Knoten unendlich, zu denen kein Pfad vom Startknoten aus existiert. Dasselbe gilt auch für gerichtete nicht stark zusammenhängende Graphen. Dabei wird der Abstand synonym auch als Entfernung, Kosten oder Gewicht bezeichnet.

## Funktionsweise
- Starte von einem Ausgangspunkt.
- Aktualisiere die Kosten aller erreichbaren Nachbarn.
- Wähle den Knoten mit den niedrigsten Kosten.

## Benötigte Daten
- Ein gewichteter Graph (Adjazenzliste oder -matrix).
- Start- und Zielknoten.

## Relevante Repositories
-  [Dijkstra in Python (Gist von heckenmann)](https://gist.github.com/heckenmann/6a42de6413efa815dff0)
