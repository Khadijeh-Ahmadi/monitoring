Surveillance avec Prometheus, Grafana et Nginx Exporter
Un projet de surveillance de NGINX à l'aide de Prometheus et Grafana
__________________________________________________________________________

Comment exécuter :

1. Cloner le projet :
   git clone https://github.com/Khadijeh-Ahmadi/monitoring.git
   cd monitoring

   
2. Démarrer les services avec Docker Compose :
      make up
   Ou manuellement :
      docker-compose up -d

   
3. Accéder aux services :

       Prometheus : http://localhost:9090

       Grafana : http://localhost:3000Se connecter à Grafana avec l'utilisateur admin et le mot de passe admin

       Metrics de Nginx Exporter : http://localhost:9113/metrics


4.Pour arrêter les services :

    make down

__________________________________________________________________________

Description du projet  :

  Ce projet utilise Prometheus pour collecter les métriques de Nginx et Grafana afin de les afficher graphiquement.
    La surveillance comprend :
    Le nombre de connexions actives de Nginx
    Le nombre de requêtes HTTP
    Les délais de traitement et de réponse du serveur

__________________________________________________________________________

 Créé par Khadijeh Ahmadi

