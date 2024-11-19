Ce projet, réalisé dans le cadre d'une SAE scolaire, consiste à concevoir une infrastructure réseau multisites sécurisée pour l’entreprise fictive Beerok, spécialiste de la chaussure sportive.
L'objectif principal était de répondre aux besoins de connectivité, de sécurité et de haute disponibilité à travers la mise en place d'un réseau performant et adapté.

 -- Cœur de réseau --
 L’architecture du cœur de réseau a été conçue pour garantir une connectivité optimale entre les sites, tout en assurant la redondance, l’isolation et la tolérance aux pannes.

 --- Protocoles utilisés ---
        
        OSPF pour le routage interne dynamique.
        BGP pour le routage externe et les connexions avec les sites distants.
        MPLS pour le transport des données via des VPN performants et sécurisés.
        VRF pour l’isolation des tables de routage et la segmentation des services.
        Fonctionnalités clés :
        Redondance assurée avec VRRP pour la haute disponibilité.
        Différenciation des flux grâce à des VLAN adaptés (ventes, administration, voix, Wi-Fi).



 -- Cybersécurité --
 La sécurité a été un enjeu clé dans ce projet, visant à protéger les données sensibles de l’entreprise fictive Beerok tout en garantissant une infrastructure résiliente.

 --- Audits et tests d’intrusion ---

        Analyse des vulnérabilités avec des outils comme Nmap, Nessus et Metasploit.
        Tests de sécurité sur le Wi-Fi avec Airmon-ng pour détecter les points faibles.


 --- Sécurisation des services ---

        Authentification centralisée via RADIUS et Active Directory.
        Portail captif sécurisé pour les connexions Wi-Fi.
        Certificats numériques pour sécuriser les services critiques comme la messagerie et le stockage.
        Durcissement des configurations réseau (filtrage des ports, limitation des accès).
        Mise en place de politiques de mots de passe sécurisées et contrôle d’accès rigoureux.


 --- Haute disponibilité ---

        Mise en place de VRRP pour la redondance des passerelles réseau.
        Configuration avancée de MPLS pour une connexion VPN stable et performante.
        Réduction de la surface d’attaque :
