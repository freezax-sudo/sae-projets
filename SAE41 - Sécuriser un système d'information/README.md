Ce projet, réalisé dans le cadre d'une SAE scolaire, vise à sécuriser un système d'information en mettant en œuvre des technologies avancées. L'objectif était de renforcer la protection des réseaux internes, des serveurs, et des utilisateurs contre diverses menaces.

Infrastructure sécurisée :

 --- L'architecture repose sur une segmentation claire et une protection renforcée grâce à des équipements dédiés ---

        Déploiement et configuration de firewalls Stormshield pour protéger les réseaux internes et la DMZ.
        Mise en place de NAT et de règles de filtrage strictes pour restreindre les accès externes.
        Architecture VPN avec :
        VPN SSL pour les clients distants.
        VPN IPSEC site-à-site pour relier les réseaux LAN et DMZ.
        Authentification et supervision


 --- L'accent a été mis sur la gestion des accès et le monitoring de l'infrastructure ---

        Authentification par certificat SSL avec une autorité de certification locale.
        Implémentation de Single Sign-On (SSO) via Active Directory pour simplifier l'accès utilisateur.
        Supervision réseau avec Nagios et Cacti pour surveiller les services critiques et générer des rapports.
        Sécurisation avancée
 --- Les contre-mesures contre les attaques et la détection des menaces ont été prioritaires --- 

        Déploiement d'un IDS Snort pour détecter les intrusions (DoS, tentatives SSH, fragments anormaux).
        Réalisation d'attaques Wi-Fi (WEP et WPA) suivies de l'implémentation de solutions de protection.
        Tests d'attaques MiM et mise en place de contre-mesures avec ARP Watch et durcissement des commutateurs.
