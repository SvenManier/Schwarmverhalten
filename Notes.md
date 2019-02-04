### Allgemein

- Probleme mit Turtlesim
  - Genau ein Roboter pro Versuch spawnt in der Regel erst garnicht, ein anderer verschwindet von der Grafik, scheint sich "unter der Oberfläche" aber dennoch zu bewegen und sendet seine Daten.
    - Beide male ohne Fehlermeldung
- Verschiedene Arten von "Schwarm"
  - Ungelenkter Schwarm
    - Beachten nur die 4 Regeln eines Schwarm
    - Bewegung richtet sich meist an anderen Individuen aus
- Bau-System von ROS sehr verbuggt
  - manuelles touch notwendig

###Harvard Kilobot Swarm

- Algorithmus:
  - Roboter starten mit Bild der Form an unbestimmten Ort
  - 4 spezielle Seed-Robots bilden den Anfang der Formation und dienen der Orientierung
  - Nur Subset der anderen Roboter steigt in Algorithmus ein
  - Roboter umkreisen bestehende Formation und berechnen ihren Gradienten
    - Gradient vergleichbar mit der Höhe einer Baumstruktur
    - (min(RoboterInMeinerUmgebung.Gradient) + 1)
  - Roboter der seinen findet folgt der Kontur der bisher entstandenen Form bis:
    - Er dabei ist die Form wieder zu verlassen
    - Er auf einen anderen stehenden Roboter mit dem selben Gradienten trifft
- Notes:
  - Roboter spannen ein Koordinatensystem auf
  - Kein richtiges Schwarmverhalten, sondern gezielte (autonome) Bewegung
- ![1542641439052](D:\GitHub\Schwarmverhalten\assets\1542641439052.png)

### Simulationen

- 10 Roboter, 45°, 5%
  - Schwarm schoss öfter am Ziel vorbei, Leader musste dann Gegenlenken weswegen das Objekt öfter um das Ziel kreiste
  - Leader konnte manchmal nicht "überzeugen" und zog eher dem Schwarm hinterher als umgekehrt, bis der Schwarm "zufällig" in die richtige Richtung ging, von wo aus der Leader dann mit seinem wenigen Einfluss den "letzten Schliff" in der Richtung geben konnte
  - Mit 10 Robotern, darunter 1 Leader, schlicht ein Glücksspiel