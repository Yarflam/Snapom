# Snapom

Le concept de Snapom est de pouvoir transférer un fichier d'un PC à un autre sans se soucier de la sécurité.

Il utilise une seule version de fichier que l'utilisateur peut soit télécharger, soit actualiser.

Rien ne vous interdit de l'utiliser à plusieurs, mais il est fortement conseillé d'avoir une version du programme par personne.

Pour en avoir plusieurs sur le serveur, vous pouvez modifier le nom de fichier de stockage à la ligne 16 du script.

```
16 $this->filename = "snapom-data"; // FILE OF STORAGE
```

## Installation

Pour installer, rien de très compliqué.

Une fois sur le serveur FTP de votre hébergeur, vous envoyez les deux fichiers "snapom.php" et "snapom-data".

Ensuite vous modifiez les droits d'accès du fichier "snapom-data" pour la ré-écriture (chmod 666).

Pour terminer, vous n'avez plus qu'à supprimer "snapom-data" du serveur.

Let's go ! :)