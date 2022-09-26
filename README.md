# TP 6 - Services réseau
## Exercice 1. Adressage IP (rappels)
1. 172.16.0.0/23 - 255.255.254.0 - 0.0.1.255 - 172.16.1.255
	* Sous-réseau 1 : 172.16.0.0 | 172.16.0.1 | 172.16.0.38 | 172.16.0.63 | Pas VLSM
	* Sous-réseau 2 : 172.16.0.64 | 172.16.0.65 | 172.16.0.88 | 172.16.0.127 | Pas VLSM
	* Sous-réseau 3 : 172.16.0.128 | 172.16.0.129 | 172.16.0.181 | 172.16.0.191 | Pas VLSM
	* Sous-réseau 4 : 172.16.0.192 | 172.16.0.193 | 172.16.0.228 | 172.16.0.255 | Pas VLSM
	* Sous-réseau 5 : 172.16.1.0 | 172.16.1.1 | 172.16.1.34 | 172.16.1.63 | Pas VLSM
	* Sous-réseau 6 : 172.16.1.64 | 172.16.1.65 | 172.16.1.102 | 172.16.1.127 | Pas VLSM
	* Sous-réseau 7 : 172.16.1.128 | 172.16.1.129 | 172.16.1.154 | 172.16.1.191 | Pas VLSM

## Exercice 2. Préparation de l’environnement
1. VM éteintes, utilisez les outils de configuration de VirtualBox pour mettre en place l’environnement décrit ci-dessus.
2. Démarrez le serveur et vérifiez que les interfaces réseau sont bien présentes. A quoi correspond l’interface appelée lo ? `ls /sys/class/net` Permet de lister les interfaces réseaux. L'interafe `lo` est l'interface de `loopback`. 
	* "L'adresse loopback est l'interface réseau réservée utilisée par le système local pour permettre les communications entre processus. L'hôte utilise cette adresse pour s'envoyer des paquets à lui-même."
3. Pour désinstaller le packet il faut utiliser la commande `sudo apt remove cloud-init`.
4. Pour changer le domaine d'une machine il faut faire `sudo hostnamectl set-hostname tpadmin.local`. Pour rendre persistant même après redémarage il faut aller modifier le fichier `/etc/hosts` retirer la ligne du nom du serveur et changer par `127.0.1.1 server server.tpadmin.local` et `127.0.1.1 client client.tpadmin.local`.
## Exercice 3. Installation du serveur DHCP
1. Pour installer le paquet il faut faire `sudo apt install isc-dhcp-server`.
2. 
## Exercice 4. Donner un accès à Internet au client

## Exercice 5. Installation du serveur DNS

## Exercice 6. Configuration du serveur DNS pour la zone tpadmin.local
