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

**VM GLPI avec ip fixe**  

![image](https://github.com/techerbeatrice/installation_serveur_glpi/assets/138071140/ba007515-a6a3-4b21-bd91-397555ab0c49)

_______

**ping de la machine cliente vers ubuntu_server pour vérifier que la configuration réseau est bonne**

![image](https://github.com/techerbeatrice/installation_serveur_glpi/assets/138071140/de3d1470-b916-437e-bf72-f4555f631af7)

_________

Sur la machine cliente, dans un navigateur web : l'adresse http://172.20.0.10/glpi




















