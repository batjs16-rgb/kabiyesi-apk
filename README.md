# KABIYESI — distribution des applications Android

Ce dépôt ne contient **aucun code source**. Il sert uniquement à héberger les
fichiers APK signés de l'écosystème KABIYESI by OzelServices, afin de fournir
des URLs de téléchargement stables et publiques.

| Application | Fichier | Lien |
| --- | --- | --- |
| Client | `app-release.apk` | [`client-latest`](https://github.com/batjs16-rgb/kabiyesi-apk/releases/download/client-latest/app-release.apk) |
| Livreur | `livreur-app-release.apk` | [`livreur-latest`](https://github.com/batjs16-rgb/kabiyesi-apk/releases/download/livreur-latest/livreur-app-release.apk) |

## Installation sur Android

1. Télécharger le fichier `.apk` depuis la page de téléchargement du site
   KABIYESI (`/telecharger`).
2. Ouvrir le fichier téléchargé.
3. Android peut demander d'autoriser l'installation depuis cette source :
   autorisez, le fichier est signé.

## Sécurité

Les APK sont signés avec la clé d'upload du projet. La clé privée n'est **pas**
dans ce dépôt : elle est conservée hors ligne et injectée uniquement en CI.

En cas de doute sur un fichier, comparez le SHA-256 avec celui indiqué dans la
section « Notes de version » de la release.

## Licence

Applications proprietary — tous droits réservés.
