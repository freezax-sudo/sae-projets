Ce projet, réalisé dans le cadre d'une SAE, consiste à construire une infrastructure réseau permettant le déploiement automatisé de systèmes d'exploitation. L'objectif est de centraliser et simplifier le déploiement, tout en garantissant la sécurité et l'efficacité des processus.

Infrastructure réseau

 ---  L'architecture repose sur des équipements réseau et serveurs configurés pour répondre aux besoins d'une petite structure ---

        Serveur PXE : pour le déploiement des systèmes via le réseau.
        Serveur DHCP avec réservation : pour associer les adresses IP aux équipements.
        Serveur TFTP : pour le transfert des fichiers d'amorçage.
        Partage NFS : pour la gestion des images système.
        Plan d’adressage IP segmenté pour une meilleure organisation des réseaux.
        Sécurisation et gestion


 --- La sécurité de l’infrastructure a été une priorité ---

        Configuration sécurisée des switches et routeurs Cisco.
        Cloisonnement des réseaux avec segmentation IP.
        Protection des équipements via SSH pour un accès sécurisé.
        Méthodologie et validation


 --- Le projet a été mené par étapes avec des validations régulières ---

        Tests sur simulateur GNS3 avant déploiement réel.
        Documentation complète incluant le plan IP, les configurations et les procédures.

Ce projet démontre une maîtrise des outils et des protocoles nécessaires pour construire une infrastructure réseau fiable et sécurisée.