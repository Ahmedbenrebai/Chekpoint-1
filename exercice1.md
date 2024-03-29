1.1 Préparation du disque

Pour la première partition de type ext4 :

1. J'ai créé ma première partition "DATA" de 6 Go en utilisant la commande  fdisk /dev/sdb pour accéder à l'outil de création.

2. J'ai suivi les étapes suivantes :
   - Appuyé sur N  pour créer une nouvelle partition.
   - Choisi le type "primaire" et attribué le numéro 1 .
   - J'ai essayé de la renommer en appuyant sur C , mais j'ai rencontré un message d'erreur (indicateur de compatibilité DOS activé) et je n'ai pas réussi à la renommer.

Pour la deuxième partition "SWAP" avec le reste de l'espace :


sudo fdisk /dev/sdb


1.Appuyé sur n pour créer une nouvelle partition.

2.Choisi le type de partition 82 pour le swap Linux.


Je n'ai pas réussi à la renommer, mais la commande pour cela est c.

