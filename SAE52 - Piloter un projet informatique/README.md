Ce projet, réalisé dans le cadre d'une SAE, consiste à concevoir et sécuriser le système d'information d'un hôpital.
Face à la menace croissante des cyberattaques, l’objectif est de protéger les données médicales sensibles, garantir la continuité des soins, et assurer la résilience du réseau face aux incidents.


Architecture réseau

 --- L'architecture réseau a été conçue pour garantir un cloisonnement strict des données et des responsabilités ---

        Segmentation en trois espaces : direction, administration et médical.
        Cloisonnement des accès avec un routeur Cisco gérant les droits inter-services.
        Standard 802.1X déployé sur les parties filaire et Wi-Fi pour l'authentification des utilisateurs.
        Validation de l’architecture sur GNS3 avant le déploiement en environnement réel.
        Sécurité et résilience
        

 --- Le projet inclut des mécanismes avancés pour sécuriser et maintenir la disponibilité des services ---

        VPN inter-hospitalier : Échange sécurisé des données médicales sans accès Internet direct.
        Authentification centralisée via un serveur Radius pour gérer les droits des utilisateurs.
        Accès restreint à la salle d’opération en fonction des plages horaires et des rôles.
        Sauvegarde automatisée des données critiques pour une restauration rapide.
        Procédure de bascule serveur principal/secondaire pour assurer la continuité des services.
        Réinstallation automatisée d’un serveur en cas de panne.
        Documentation et outils


 --- Pour favoriser la collaboration et la traçabilité, le projet intègre des outils modernes ---

        Création des bases de données des personnels et patients avec versionnage via GitHub.
        Centralisation des configurations réseau et des scripts d’automatisation dans des dépôts Git.