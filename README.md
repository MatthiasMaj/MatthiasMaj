Bonjour, je m'appelle Matthias Majid.

Je développe ma propre passerelle GTC/GTB

J'utilise un siemens IOT 2050 que je raccorde aux automates. Avec Node-Red je récupere les points de donnée ce qui me permet de créer un dashboard technique pour visualiser les températures, modifier des points de consignes et tout ce qui est necessaire à la gestion de chaufferie.
Un historique est créer via influxDB sur un serveur distant pour permettre le suivi des sites sous contrats.
Via influxDB et Grafana je permet l'accès en lecture seule à la télérelève, et tous les points de températures dont le client à besoin.
Je gère la partie sécurité avec WireGuard et UFW.
Les dashboards techniques et clients sont accessibles via le web grace à des proxy que je gère.