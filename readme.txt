# Projet : Déploiement Automatisé d'un Environnement de Test avec Docker, Vagrant, Linux et GitHub

## Description
Ce projet permet de configurer un environnement de test automatisé pour une application, en utilisant Docker pour la conteneurisation, Vagrant pour la gestion des machines virtuelles, et GitHub pour le stockage du code source. L'objectif est de simuler un environnement de production léger, mais fonctionnel, qui peut être facilement déployé et utilisé pour les tests.

### Objectif du Projet
L'objectif de ce projet est de déployer une application simple dans un environnement de test basé sur une machine virtuelle avec Vagrant, et d'utiliser Docker pour gérer l'application et ses services (par exemple, un serveur web et une base de données).

---

## Prérequis
Avant de commencer, assurez-vous d'avoir installé les outils suivants :

- **Vagrant** : Pour la gestion des machines virtuelles.
- **Docker** : Pour la conteneurisation des services (web, base de données, etc.).
- **Git** : Pour le versionnement du code source.
- **SSH** : Pour se connecter à GitHub via SSH.

### Installation des Prérequis

1. **Vagrant** : Téléchargez et installez [Vagrant](https://www.vagrantup.com/downloads).
2. **Docker** : Suivez les instructions d'installation de Docker pour votre OS sur [Docker.com](https://www.docker.com/get-started).
3. **Git** : Téléchargez et installez [Git](https://git-scm.com/).
4. **Clé SSH pour GitHub** :
   - Générez une clé SSH avec la commande `ssh-keygen -t rsa`.
   - Ajoutez la clé SSH à votre compte GitHub via [les instructions officielles de GitHub](https://docs.github.com/en/authentication/connecting-to-github-with-ssh).

---

## Étapes d'Installation

1. **Cloner le Dépôt GitHub** :
   Clonez le projet depuis GitHub :
   ```bash
   git clone git@github.com:amadouour/Projet-D-ploiement-Automatis-d-un-Environnement-de-Test-avec-Docker-Vagrant-Linux-et-GitHub.git
