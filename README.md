Procédure de chargement de la nouvelle image :
Avant de recharger le AS IMAGE
Positionner les axes du robot comme suit => J1, J2, J3, J4, J5, J6 =0°

Sauvegarder toutes vos données actuelles de votre contrôleur par un « All Of Above » et un « Backup As Image »
MENU UTILITY/ FILES BACKUP/ FULL SYSTEM AND IMAGE BACKUP
Dans l’application de la tablette, restaurer le « Backup As Image »
MENU/UTILITY/IMAGE RESTORE
Réintégrer le backup « All Of Above » en controled start sans les fichiers « sysvars.sv» et « sysservo.sv » du robot fait précédemment.
MENU/UTILITY/CYCLE POWER/CTRL
MENU/FILE/RESTORE/All Of Above

Puis redémarrer en appuyant sur la touche FCTN puis START (COLD)

ATTENTION : Cette manipulation (« restore backup as image » envoyé) peut entrainer la perte de données telles que l’ensemble des paramétrages sous MENU 6-SETUP et MENU 0-NEXT / 6-SYSTEM (à savoir par exemple configuration de démarrage (MENU 6- SYSTEM CONFIG), 
la déclaration de l’angle de montage du robot, PROG SELECT, les PAYLOADS, Positions de référence, Space fonction, etc..)

Je reste à votre disposition pour tous renseignements complémentaires.
