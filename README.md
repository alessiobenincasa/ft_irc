Description
ft_irc est un projet qui consiste à développer un serveur IRC en C++ 98. Ce serveur permettra à des clients de se connecter, de rejoindre des canaux et d’échanger des messages en temps réel.

Fonctionnalités
Gestion simultanée de plusieurs clients sans blocage.
Authentification par mot de passe.
Commandes IRC de base : KICK, INVITE, TOPIC, MODE.
Gestion des rôles d’opérateurs et d’utilisateurs basiques.
Prérequis
C++ 98.
Gestion non bloquante des entrées/sorties avec poll() ou équivalent.
Compilation avec g++ et les flags -Wall -Wextra -Werror.
Installation
Clonez le dépôt :

bash
Copier le code
git clone <url-du-depot>
cd ft_irc
Compilez le projet :

bash
Copier le code
make
Utilisation
Lancer le serveur IRC :

bash
Copier le code
./ircserv <port> <password>
port : Le port d’écoute du serveur.
password : Le mot de passe que les clients doivent fournir pour se connecter.
Tests
Vous pouvez utiliser un client IRC comme HexChat ou WeeChat pour tester votre serveur.

Exemple de connexion :

bash
Copier le code
/server localhost <port>
/pass <password>
/nick <votre_nick>
/user <votre_username>
/join #channel
