# Recherche

[TOC]

## Quellen

### Allgemein

- https://arxiv.org/pdf/1010.5017.pdf
  - The Vicsek model
    - Generelle Betrachtung von Partikeln in kollektiver Bewegung
      - Vektor-Noise und Betrachtung in 3dim (2.2)
      - Veränderung durch Topologie statt direkter Nähe (3.2)

#### Erstellen von Untergruppen

- http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.435.2371&rep=rep1&type=pdf
  - Dynamic Task Assignment in Robot Swarms
    - Fünf Algorithmen werden vorgestellt, wie man einen großen Roboterschwarm in kleinere Schwärme aufteilt zwecks Aufgabenerfüllung

#### Erstellen von Strukturen/Formen

- https://ssr.seas.harvard.edu/files/ssr/files/ijcai05-werfel.pdf
  - Building Patterned Structures with Robot Swarms
    - Algorithmen, wie man einen Roboterschwarm in eine bestimmte Form bringt

### Flocking

- https://ieeexplore.ieee.org/abstract/document/1605401/
  - Flocking for multi-agent dynamic systems: algorithms and theory
    - Drei Algorithmen für flocking werden vorgestellt und analysiert. Einer davon führt zu Fragmentation, die anderen beiden zu einer erfolgreichen Schwarmbildung
- http://sci-hub.tw/10.1109/TAC.2008.2010897
  - Flocking of Multi-Agents With a Virtual Leader
    - Weiterführende Arbeit zu "Flocking for multi-agent dynamic systems: algorithms and theory"
- http://sci-hub.tw/10.1007/978-3-642-00644-9_19
  - Guiding a Robot Flock via Informed Robots
    - Ein Schwarm von Robotern wird durch ein paar "eingeweihte" Roboter dazu gebracht in eine bestimmte Richtung zu laufen, ohne dass explizite Kommunikation stattfindet
- https://www.sciencedirect.com/science/article/pii/S0921889099000846
  - Experiments in automatic flock control
    - Ein Roboter wurde dazu verwendet einen Schwarm von Enten gezielt in eine andere Richtung zu lenken

### Schwarmverhalten

#### Mit direkter Kommunikation (Stigmergy Schwamverhalten)

- http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.117.568
  - From local actions to global tasks: Stigmergy and collective robotics
    - Roboter wurden durch Schwarmverhalten dazu gebracht ein Zimmer aufzuräumen
- https://www.mitpressjournals.org/doi/abs/10.1162/106454699568737
  - Stigmergy, Self-Organization, and Sorting in Collective Robotics
    - Roboter wurden dazu gebracht "Brood Sorting" zu betreiben, also einen Haufen Frisbees zu sortieren. Dazu wurde ein "rule set simpler than any yet" entwickelt

#### Mit indirekter Kommunikation

- http://journals.sagepub.com/doi/abs/10.1177/105971239300200204
  - Collective Robotics: From Social Insects to Robots
    - Es wurde ein System von 5 Robotern konstruiert das einfache Aufgaben ohne direkte Kommunikation erledigen konnte
- https://hal.elte.hu/flocking/browser/trunk/public/references/vasarhelyi/viragh2014flocking.pdf?format=raw
  - Flocking algorithm for autonomous flying robots
    - Einfacher Algorithmus für kollektive Bewegung in Richtung eines bestimmten Ziels ohne Kontrolleinheit (3)
    - Algorithmus der einen weichen Übergang zwischen Bewegung und Stillstand eines Schwarmes erlaubt (4)

### Phase Transision

- https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.98.095702
  - Phase Transitions in Systems of Self-Propelled Agents and Related Network Models
    - Beschreibt wie Phase Transisions vom Noise Level abhängen
- https://sci-hub.tw/https://journals.aps.org/pre/abstract/10.1103/PhysRevE.77.061138
  - Intrinsic and extrinsic noise effects on phase transitions of network models with applications to swarming systems
    - Beschreibt die unterschiedlichen Effekte von "extrinsic noise" ("Umgebungs noise") und "intrinsic noise" ("freier Wille") auf die Phase Transistions eines Schwarms

### Sonstige

- https://tectogizmo.com/boids-a-computer-model-for-creating-the-swarm/
  - Boids: Three Simple Rules to Create a Computer Bird Swarm
- https://books.google.de/books?hl=de&lr=&id=J6mAK8oJio8C&oi=fnd&pg=PP1&dq=Collective+Robotics&ots=8kPFwNPmN8&sig=DwoHCrepYu4dwwwi5KkZE3i0ptM#v=onepage&q=Collective%20Robotics&f=false
  - Handbook of COLLECTIVE ROBOTICS, Fundamentals and Challenges
- https://sci-hub.tw/https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.76.3870
  - Collective Motion in a System of Motile Elements
    - Ein mathematisches Model für kollektive Bewegung
- https://sci-hub.tw/https://ieeexplore.ieee.org/abstract/document/1304923/
  - Coordinated collective motion of Groups of autonomous mobile robots: analysis of Vicsek's model
    - Untersuchung von Vicsek's Modell mit dem Ergebnis, dass ein unkoordinierter Schwarm mit der Zeit in viele kleine Schwärme "zerbricht", wobei sich die einzelnen Mitglieder eines Schwarmes in die selbe Richtung bewegen



## (Noch nicht vollständig berücksichtigte) Links

- [ ] http://sci-hub.tw/https://www.sciencedirect.com/science/article/pii/S037843710800109X?via%3Dihub
  - New tools for characterizing swarming systems: A comparison of minimal models
- [ ] http://sci-hub.tw/https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.92.025702
  - Onset of Collective and Cohesive Motion
- [ ] http://sci-hub.tw/https://www.sciencedirect.com/science/article/pii/S0167278903001027?via%3Dihub
  - Moving and staying together without a leader
- [ ] https://hal.elte.hu/flocking/wiki/public/en/projects/CollectiveMotionOfFlyingRobots
  Collective Motion of Flying Robots (Drones)
- [ ] https://hal.elte.hu/flocking/wiki/public/en/projects/ProjectGroupAnimals
  Leadership and Social Dynamics in Animal Collectives
  - [ ] https://hal.elte.hu/flocking/wiki/public/en/projects/ProjectHierarchyInPigeonFlocks
    Hierarchical group dynamics in pigeon flocks
  - [ ] https://hal.elte.hu/flocking/wiki/public/en/projects/ProjectContextDependentHierarchiesInPigeons
    Context-dependent Hierarchies in Pigeons
  - [ ] https://hal.elte.hu/flocking/wiki/public/en/projects/ProjectLeadershipAndDominanceInDogPacks
    Leadership and path charachteristics during walks are linked to dominance order and individual traits in dogs
  - [ ] https://hal.elte.hu/flocking/wiki/public/en/projects/ProjectHierarchyInWildHorses
    Leadership hierarchy in wild horses
- [ ] http://journals.sagepub.com/doi/10.1177/1059712312462248
  Self-organized flocking with a mobile robot swarm: a novel motion control method
- [ ] https://journals.aps.org/pre/abstract/10.1103/PhysRevE.79.021908
  Transitions in a self-propelled-particles model with coupling of accelerations
- [ ] https://www.sciencedirect.com/science/article/pii/S0370157312000968?via%3Dihub
  Collective motion
- [ ] https://dl.acm.org/citation.cfm?doid=37402
  ???
- [ ] General Puplications: https://hal.elte.hu/flocking/wiki/public/en/publications