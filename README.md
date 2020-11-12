# Architecture-Linux

Dans la racine on a les dossiers suivants : 

- Bin : // Contient des programmes susceptibles d'être utilisés par tous les utilisateurs de la machine.
      
      ex : 
      - mkdir
      - lsmod
      - setfront
    
- Boot : // Contient les fichiers permétant démarrage de Linux.
      
      ex : 
      - config-4.19.0.11-amd64
      - config-4.19.0.12-amd64      
      - initrd.img-4.19.0-11-amd64
      - initrd.img-4.19.0-12-amd64   
      
 - Dev : // Fichiers contenant les périphériques.
      
       - disk
       - dvd
       - input 
 
- Etc : // Fichiers de configuration.
      
      ex : 
      - resolv.conf
      - reportbug.conf
      - debconf.conf
       
- Home : // Répertoires personnels des utilisateurs.
       
      ex : 
       - ex : louis 
       
 - initrd.img 
 - initrd.img.old
 
 - Lib : // Dossier contenant les bibliothèques partagées utilisées par les programmes.
 
       ex : 
       - os-prober
       - os-release
       
- Lib32
- Lib64
- Libx32
- Lost+found 

- Media : // Permet d'avoir accès au dossier lorsqu'un périphérique amovible est inséré
        
        ex : 
        - cdrom
        - cdrom0
           
- Mnt : // Idem que Media mais temporaire. 
- Opt : // Répertoire utilisé pour les add-ons de programmes.

- Proc : // Informations systèmes. 
       
       ex : 
       - filesystems
       - execdomains
      
- Root : // Dossier personnel de l'utilisateur « root ».

- Run : // Un fichier .run est normalement un programme sur mesure qui doit être exécuté pour installer un programme

- Sbin : // Contient des programmes système importants.
       
       ex : 
       - ldconfig 
       - pppd 
       - rmmod
- Sys : // Fichiers système. 
      
      ex : 
      - dev
      - firmware
      - bus

- Tmp : // Dossier temporaire utilisé par les programmes pour stocker des fichiers.
      
      ex : 
      - pulse-PKdhtXMmr18n 
      - tracker-extract-files.1000

- Usr : // Programmes demandés par l'utilisateur.
      
      ex :
      - bin
      - games
      - sbin 
      - local
- Var : // Ce dossier contient des données « variables », souvent des logs
      
      ex : 
      - backups
      - cache
      - log 
      - mail
- Vmlinuz
- Vmlinuz.old
