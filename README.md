# Serveur-Multimedia avec raspberry pi

1:

Lancer votre Raspberrypi avec une distribution Debian sans interface graphique (exemple : Raspberry Pi OS Lite)


2:

mettez à jour avec ceci:
sudo apt update && sudo apt upgrade -y


3:

tapez la commande pour utiliser le script prévu :
curl https://repo.jellyfin.org/install-debuntu.sh | sudo bash


4:

sur un autre ordinateur, taper http:// Adresse IP du Raspberry Pi:8096
(vous pouvez voir l'adresse IP de votre Raspberry Pi avec la commande : ip -a)


5:

bien joué, vous avez votre Netflix local sur votre réseau


(si problème regarder ce guide : https://raspberrytips.fr/jellyfin-raspberry-pi/)

(Jellyfin docs: https://jellyfin.org/docs/)

# télécharger un film


1:
prenez un DVD et, mettez-le dans un lecteur DVD


2:
utiliser VLC et utiliser l'option convertir/diffuser pour télécharger votre film sur votre ordinateur


3:
mettez votre film sur un disque dur


4: 
créez le répertoire pour pouvoir voir votre USB sur votre serveur à l'aide des commandes ci-dessous :
sudo mkdir -p /mnt/usb


6:
retourner sur votre Jellyfin sur votre écran de visionnage
