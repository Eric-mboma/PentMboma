# PentMboma
<h1>PentMbo</h1>

-----------------
Tutoriel PenTMboma
-----------------

https://www.kalilinux.in/2019/05/honeypot.html

<b>Ce référentiel est très ancien. Je ne l'ai même pas essayé pendant des années. J'espère que quelqu'un enverra un bon PR dans Hacktoberfest2021 pour le mettre à jour. [Pas de correction de faute de frappe, VRAIE mise à jour]</b>

<b> PentMbo est un kit de sécurité contenant divers outils pour rationaliser PenTest en effectuant facilement un travail. Il est programmé en Ruby et orienté vers GNU/Linux, avec un support pour Windows, MacOS et tous les systèmes où Ruby est installé.</b>

-----------------
Comment installer
-----------------

Vériier si Ruby est installé, sinon fait : sudo apt-get install ruby-full ou bien sudo apt install ruby 
si vous êtes sur windows copier ce lien sur le navigateur pour télécharger : https://rubyinstaller.org/
git clone https://github.com/technicaldada/pentbox

cd pentMbo

unzip pentMbo.zip

cd pentMbo

./pentMbo.rb

-----------------
Journal des modifications PenTBox
-----------------

Version 1.0
-----------
Nouvelles fonctionnalités:
- Exécution de commandes dans les get (STDIN) implémentées. (!commande)
- Honeypot affiche maintenant l'adresse IP et le port de l'attaquant (thx Shyish)
- Ciblage direct d'Ip grabber à partir d'e-mails : Yahoo, Gmail, Hotmail et des sites tels que Facebook, Gmail, etc.
- Options de journal incluses.
- La liste de mots est plus grande maintenant.
- Option "retour" incluse dans les menus.
Nouveaux outils :
- Nouvelle zone incluse, outils Web.
- Inclus nouveau module géolocalisation d'adresse MAC (samy.pl).
- Inclus le nouveau module de répertoire HTTP bruteforce.
- Inclus le nouveau module HTTP fichiers communs bruteforce.
- Exploits inclus pour DoS
[autre/http] DoS du commutateur SuperStack de 3Com
[autre/http] DoS des routeurs OfficeConnect 3Com (type de contenu)
[windows/ftp] Windows 7 IIS7.5 FTPSVC UNAUTH'D DoS
[windows/ftp] Serveur FTP solaire 2.1 DoS
[windows/pptp] MS02-063 PPTP Malformé Control Data Kernel DoS
[windows/smb] Windows Vista/7 SMB2.0 Negotiate Protocol Request DoS BSOD
- Inclus pb_update.rb pour mettre à jour PenTBox à partir du référentiel SVN.
Correction de bogues :
- Correction d'un problème avec l'API SHODAN.
- Suppression de la parole l33t et du menu supplémentaire.
- Amélioration de la vérification des autorisations, maintenant c'est fait par euid, pas par nom d'utilisateur (thx r4mosg)
