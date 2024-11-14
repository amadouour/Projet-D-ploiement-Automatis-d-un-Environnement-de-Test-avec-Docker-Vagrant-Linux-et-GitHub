
### Explication de chaque section :

- **Dockerfile** : Décrit l'image Docker pour l'application Python avec Flask. Il installe les dépendances et expose le port 5000.
- **docker-compose.yml** : Orquestre l'application et la base de données MySQL. Le service principal dépend du service MySQL, et un réseau personnalisé est utilisé.
- **Automatisation avec systemd** : Le fichier de service systemd permet d'automatiser le démarrage des services Docker au démarrage de la VM. Vous utilisez `docker-compose up` pour démarrer les services et `docker-compose down` pour les arrêter.

Cette approche offre une méthode simple et efficace pour gérer une application Dockerisée et garantir son bon fonctionnement sur une machine virtuelle.
