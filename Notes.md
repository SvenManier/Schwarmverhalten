### Allgemein

- Warum lasse ich Roboter-Kollisionen außer acht?
  - Da die Simulation selbst nicht beschleunigt werden kann, ist meine einzige Möglichkeit die Geschwindigkeit zu erhöhen, die Bewegungsgeschwindigkeit höher zu stellen.
  - Diese Bewegungsgeschwindigkeit wäre im Realfall viel geringer und es würden viel mehr einzelne Iterationen oder Zwischeniterationen (während der Bewegung) stattfinden
  - Ich müsste also die Bewegungsgeschwindigkeit viel geringer einstellen um einen Roboter nicht innerhalb eines Schrittes zu durchschreiten
- Probleme mit Turtlesim
  - Genau ein Roboter  pro Versuch spawnt in der Regel erst garnicht, ein anderer verschwindet von der Grafik, scheint sich "unter der Oberfläche" aber dennoch zu bewegen und sendet seine Daten.
    - Beide male ohne Fehlermeldung

### Algorithmus

- "Mitte des Flocks" nicht die zentrale Mitte, sondern Mitte in Relation zur Anzahl der Roboter. Dh 2 Roboter ziehen die "Mitte" mehr in ihre Richtung als ein einzelner

### Schwarm allgemein

- Freier Wille: 225, zum Flock: 50%
  - Flocks die sich einmal gefunden haben trennen sich nicht mehr
  - Trotz dessen dass sich die Roboter stets zur Mitte bewegen bewegen sich die Flocks langsam über das Spielfeld
    - Dadurch kommt es zu Verschmelzungen von Flocks
    - Kleinere Flocks bewegen sich schneller als größere
- Freier Wille: 45, zu Flock: -50%
  - Roboter flocken nicht, Einteilung in Flock eher aus Platzmangel
  - Relativ homogene Verteilung über das Spielfeld

### Leadership

- Siehe Diagramme

###Harvard KiloRobot Swarm



- Roboter starten mit Bild der Form an unbestimmten Ort
- 4 spezielle Seed-Robots bilden den Anfang der Formation und dienen der Orientierung
- 