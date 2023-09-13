# Installation d'un serveur GLPI

________

Configuration réseau de la VM Glpi :   
Tout d'abord, arrête ta VM.   
Dans ton hyperviseur va modifier la carte réseau pour qu'elle ne soit plus en bridge mais en réseau interne.   
Redémarre ta VM.  
Mettre une adresse IP fixe :  
Choisi une adresse IP avec le masque associé et mets-là dans la configuration de ta machine.  
Démarre ton autre VM (client Windows ou Linux)  
Ping ta VM Ubuntu server pour vérifier que la configuration réseau est bonne.  

Si tout est correct,ouvre un navigateur web et entre l'adresse http://adresse IP du serveur glpi/glpi  
Dans les fenêtres graphique de configuration :  

Mettre Français en langue  
Accepter la licence GPL en cochant la case J'ai lu et accepté...  
Cliquer sur installer  
Si tout est ok sur la fenêtre cliquer sur continuer  
Configuration de la base de données MariaDB :  
serveur SQL : 127.0.0.1  
utilisateur : glpi  
Mot de passe : Mot de passe défini pendant la configuration de la base de données pour le compte glpi  
__________

**Installation**  
![image](https://github.com/techerbeatrice/installation_serveur_glpi/assets/138071140/ace1b2fa-198e-4234-8636-9f60119138f1)


**VM GLPI avec ip fixe**  

![image](https://github.com/techerbeatrice/installation_serveur_glpi/assets/138071140/4c1a4355-a92f-4399-9be5-b9f875f7aa05)

_______

**ping de la machine cliente vers ubuntu_server pour vérifier que la configuration réseau est bonne**

![image](https://github.com/techerbeatrice/installation_serveur_glpi/assets/138071140/24d01893-6ed0-4739-ac43-69e917d87fee)

_________

Sur la machine cliente, dans un navigateur web : l'adresse http://172.20.0.13/glpi   

![image](https://github.com/techerbeatrice/installation_serveur_glpi/assets/138071140/8b368930-9027-4920-8cf3-52321cfc6e39)


![image](https://github.com/techerbeatrice/installation_serveur_glpi/assets/138071140/2cb43f24-caa1-48af-9e36-e6b497eaba26)



















