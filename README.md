# ProCom : 5GNetwork

L’objectif du projet est de déployer, en laboratoire, un réseau 5G complet et de démontrer, sur un ou plusieurs scénarios simples, la capacité du réseau à s’adapter aux variations de charge ou de service demandé.

Le réseau 5G sera constitué d’un ensemble de briques logicielles, soit libres, soit que le département SRCD a acquis. Plus précisément : une ou plusieurs stations de base 5G en `radio logiciel avec la solution Amarisoft permettant d’avoir de vraies liaisons radios, l’ensemble des fonctions réseaux cœur 5G de type Open5GS (libre) et UERANSIM pour la simulation de terminaux.

Les étapes du projet consisteront à :

- définir l’architecture 5G et les scénarios d’utilisation
- déployer Open5GS avec Kubernetes pour disposer d’un orchestrateur apte à démarrer ou arrêter des instances
- mettre en place les scénarios définis pour mettre en évidence les propriétés d’élasticité et de dynamicité de la 5G.

Il est possible d’étendre l’étude à des sujets connexes comme, par exemple, l’influence de la charge du réseau sur la consommation énergétique.

# Table des matières
[[_TOC_]]

# Getting Started & Documentation

Toute la documentation et le [Getting Started](https://gitlab.imt-atlantique.fr/b20stuck/mise-en-place-d-un-reseau-5g-dynamique/-/wikis/Getting%20started) se trouvent sur le [Wiki](https://gitlab.imt-atlantique.fr/b20stuck/mise-en-place-d-un-reseau-5g-dynamique/-/wikis/home)

# Features

- (Partiel) Déploiement d’un réseaux 5G cœur avec Kubernetes
- (Partiel) Déploiement d’un réseaux d’accès avec UERANSIM (GnodeB)
- (Partiel) Déploiement de terminaux virtuels avec UERANSIM (UE)

# Technologies

- Kubernetes
- Helm Chart
- GitLab
- Docker
- Open5GS
- UERANSIM
- MongoDB
- Node.js

# Organisation du dépot GitLab

- [Repository](https://gitlab.imt-atlantique.fr/b20stuck/mise-en-place-d-un-reseau-5g-dynamique/-/tree/master)
- [Issues/Boards](https://gitlab.imt-atlantique.fr/b20stuck/mise-en-place-d-un-reseau-5g-dynamique/-/boards)
- [Container Registry](https://gitlab.imt-atlantique.fr/b20stuck/mise-en-place-d-un-reseau-5g-dynamique/container_registry)
- [Wiki](https://gitlab.imt-atlantique.fr/b20stuck/mise-en-place-d-un-reseau-5g-dynamique/-/wikis/home)

# Contributeurs

Benjamin Stucki

Soufyen Karboul

Bilal El-Kbadi

Gabriel Vidal

(Etudiants IMT Atlantique Campus de Rennes)

# Superviseurs

Julien Saint-Martin 

Alberto Blanc

Xavier Lagrange
