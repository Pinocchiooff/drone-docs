# Essaims de drones (Drone Swarm)

## Définition

Un essaim de drones est un ensemble de drones autonomes qui travaillent ensemble pour atteindre un objectif commun. La coordination peut être centralisée ou décentralisée, mais les projets les plus avancés visent une approche distribuée dans laquelle chaque drone prend des décisions locales et contribue à l’objectif global.

## Pourquoi un essaim ?

Un essaim apporte plusieurs avantages :

- couverture plus large de zone
- amélioration de la redondance
- meilleure flexibilité face à des missions complexes
- capacité d’effectuer des tâches impossibles à un seul drone
- parallélisation des opérations
- meilleure résilience aux pannes partielles

## Concepts clés

### 1. Coordination distributive

Les drones ne travaillent pas seulement en parallèle : ils partagent l’information, prennent des décisions locales, et ajustent leur trajectoire en fonction du comportement des autres agents.

### 2. Évitement de collisions

La planification de trajectoires pour un essaim doit inclure :

- détection d’objets et d’obstacles
- gestion de la géométrie du groupe
- priorisation des trajectoires
- règles de séparation entre drones

### 3. Formation et contrôle de groupe

Les essaims peuvent conserver des formes :

- ligne
- triangle
- cercle
- nuage de coordonnées
- formation dynamique ingéniérée par mission

### 4. Communication réseau

Les systèmes d’essaim reposent sur :

- communication inter-drones
- communication drone-station sol
- partage de position et d’état
- synchronisation des missions

### 5. Intelligence collective

L’algorithme global peut émerger à partir de règles simples :

- adaptation locale
- réaction à l’environnement
- coordination par consensus
- comportement collectif stabilisé

## Usages typiques

- shows lumineux synchronisés
- surveillance de zone
- cartographie collaborative
- recherche et sauvetage
- inspection d’infrastructures
- environnement et agriculture de précision
- essais de systèmes multi-agents
- simulation de coordination autonome

## Technologies courantes

- PX4 ou ArduPilot pour le contrôle de vol
- ROS 2 ou micro-ROS pour les architectures distribuées
- MAVLink pour la télémétrie et les commandes
- Gazebo ou AirSim pour la simulation
- vision, lidar, GPS, IMU pour la perception
- IA multi-agent pour la planification et la prise de décision

## Projets représentatifs du topic drone-swarm

### alireza787b/mavsdk_drone_show

Plateforme open-source dédiée à la gestion d’essaims multi-drones avec MAVLink. Elle s’applique au show lumineux, aux validations de missions, et aux expérimentations de coordination.

- https://github.com/alireza787b/mavsdk_drone_show

### skybrush-io/skybrush-server

Serveur de gestion de drone shows synchronisés pour des scénarios artistiques. L’objectif est de piloter des formations très précises en coordination.

- https://github.com/skybrush-io/skybrush-server

### machmind-dev/drone-swarm-challenge-2026

Projet de compétition d’essaim de drones à cinq unités. Il met en œuvre une architecture ROS 2 et des mécanismes de coordination et de télémétrie pour un système multi-agent autonome.

- https://github.com/machmind-dev/drone-swarm-challenge-2026
- https://discourse.openrobotics.org/t/swarm-drone-challenge-2026-5-drone-swarm-open-sourced-uros-ros2/55467

### koesan/ORCUS

Projet multi-drone orienté surveillance autonome et vision intelligente, avec simulation ArduPilot, ROS + Gazebo, et modules de détection.

- https://github.com/koesan/ORCUS

### micros-uav/CoFlyers

Cadre d’étude et de simulation pour le vol coopératif et les comportements collectifs, avec un environnement MATLAB / Simulink.

- https://github.com/micros-uav/CoFlyers

### smshagor-dev/UVA-GPS-Denied-Navigation-in-Dynamic-Environments

Système d’essaim de drones conçu pour des environnements sans GPS, avec navigation distribuée et gestion de la dynamique du monde réel.

- https://github.com/smshagor-dev/UVA-GPS-Denied-Navigation-in-Dynamic-Environments

## Ressources pédagogiques

- Topic GitHub drone-swarm : https://github.com/topics/drone-swarm
- Topic droneswarm : https://github.com/topics/droneswarm
- Guide sur les essaims : https://markaicode.com/autonomous-drone-swarms-python-ros2-guide/
- Article scientifique sur l’architecture de systèmes hétérogènes : https://arxiv.org/pdf/2510.27327

## Architecture logicielle typique d’un essaim

Une architecture de swarm peut inclure :

- station sol
- coordinator / mission manager
- drones autonomes
- réseau de communication
- perception locale
- planification locale
- logique d’évitement de collision
- mécanismes de synchronisation

## Défis principaux

- synchronisation des drones
- latence réseau
- robustesse aux pannes
- gestion de l’énergie
- sécurité et intégrité des données
- concurrence des missions
- validation réelle en environnement dynamique

## Bonnes pratiques de conception

- commencer par un essaim réduit en simulation
- valider la communication et l’évitement de collisions
- tester les modes de secours avant les missions réelles
- limiter la complexité au début pour maîtriser le comportement
- documenter les séquences de mission et la logique de décision

## Conclusion

Les essaims de drones constituent l’un des domaines les plus actifs de la robotique autonome. Ils combinent contrôle, intelligence artificielle, planification, perception et réseau. Le topic GitHub `drone-swarm` regroupe une grande quantité de projets réels allant des shows lumineux aux plateformes de recherche scientifique et aux systèmes multi-agents avancés.

## Ressources utiles

- PX4 : https://docs.px4.io/main/
- ROS 2 : https://docs.ros.org/en/humble/
- MAVLink : https://mavlink.io/
- Gazebo : http://gazebosim.org/
- AirSim : https://github.com/microsoft/AirSim
- QGroundControl : https://qgroundcontrol.com/
- EASA : https://www.easa.europa.eu/en/domains/
- FAA UAS : https://www.faa.gov/uas/
