# TP 6 - Services réseau
## Exercice 1. Adressage IP (rappels)
1. 172.16.0.0/23 - 255.255.254.0 - 0.0.1.255 - 172.16.1.255
	* Sous-réseau 1 : 172.16.0.0 - 172.16.0.39 - 172.16.0.1 - 172.16.0.38 - Pas VLSM
	* Sous-réseau 2 : 172.16.0.40 - 172.16.0.74 - 172.16.0.41 - 172.16.0.73 - Pas VLSM
	* Sous-réseau 3 : 172.16.0.75 - 172.16.0.128 - 172.16.0.76 - 172.16.0.127 - Pas VLSM
	* Sous-réseau 4 : 172.16.0.129 - 172.16.0.165 - 172.16.0.130 - 172.16.0.164 - Pas VLSM
	* Sous-réseau 5 : 172.16.0.166 - 172.16.0.201 - 172.16.0.167 - 172.16.0.200 - Pas VLSM
	* Sous-réseau 6 : 172.16.0.202 - 172.16.0.240 - 172.16.0.203 - 172.16.0.239 - Pas VLSM
	* Sous-réseau 7 : 172.16.0.241 - 172.16.1.12 - 172.16.0.242 - 172.16.1.11 - Pas VLSM

## Exercice 2. Préparation de l’environnement
1. VM éteintes, utilisez les outils de configuration de VirtualBox pour mettre en place l’environnement décrit ci-dessus.
2. Démarrez le serveur et vérifiez que les interfaces réseau sont bien présentes. A quoi correspond l’interface appelée lo ?
3. Pour désinstaller le packet il faut utiliser la commande `sudo apt remove cloud-init`.
## Exercice 3. Installation du serveur DHCP

## Exercice 4. Donner un accès à Internet au client

## Exercice 5. Installation du serveur DNS

## Exercice 6. Configuration du serveur DNS pour la zone tpadmin.local
