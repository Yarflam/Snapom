# Snapom!

![Snapom](snapom.png)

Le concept de Snapom est de pouvoir transférer un fichier d'un PC à un autre sans se soucier de la sécurité.

Il utilise une seule version de fichier que l'utilisateur peut soit télécharger, soit actualiser.

Rien ne vous interdit de l'utiliser à plusieurs, mais il est fortement conseillé d'avoir une version du programme par personne.

Pour en avoir plusieurs sur le serveur, vous pouvez modifier le nom de fichier de stockage à la ligne 16 du script.

```
16 $this->filename = "snapom-data"; // FILE OF STORAGE
```

## Installation

Pour installer, rien de très compliqué.

Une fois sur votre serveur FTP, vous envoyez les deux fichiers "snapom.php" et "snapom-data".

Vous modifiez les droits d'accès du fichier "snapom-data" pour permettre l'écriture (chmod 666).

Ensuite vous supprimez "snapom-data".

Enjoy ! :)