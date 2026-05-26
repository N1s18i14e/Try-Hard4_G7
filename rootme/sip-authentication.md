# SIP – Authentification-Root Me

Ce challenge de la plateforme "Root Me" porte sur l’analyse d’un trafic SIP entre un client et un serveur Asterisk.

On observe plusieurs échanges réseau, dont une phase d’enregistrement "REGISTER" permettant l’authentification de l’utilisateur.

En analysant la structure, on remarque que la méthode d’authentification utilisée lors du REGISTER est "PLAIN", ce qui signifie que le mot de passe est transmis en clair.

Cela permet de l’extraire directement sans avoir besoin de casser un hash ou de faire du brute force.

# Flag
1234
