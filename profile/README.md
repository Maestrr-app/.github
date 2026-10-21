<p align="center"><strong><a href="https://maestrr-app.github.io/">Découvrir Maestrr sur le site officiel →</a></strong></p>

<h1 align="center">Maestrr — Votre multimédia, chez vous</h1>
<p align="center">Installez votre serveur. Découvrez vos médias. Pilotez vos applications.</p>
<p align="center"><strong>Auto-hébergé · Windows · Linux · TrueNAS SCALE 24.10+ · Mobile et tablette</strong></p>

## Télécharger Maestrr

| Canal | Installateur Windows x64 |
| --- | --- |
| **Bêta publique · 1.6.0-beta.8** | **[⬇ Télécharger Maestrr Setup (.exe)](https://github.com/Maestrr-app/maestrr-releases/releases/download/v1.6.0-beta.8/Maestrr-Setup-1.6.0-beta.8-win-x64.exe)** |
| **Stable** | Pas encore publiée — [consulter les versions](https://github.com/Maestrr-app/maestrr-releases/releases) |

[Notes de version](https://github.com/Maestrr-app/maestrr-releases/releases/tag/v1.6.0-beta.8) · [Empreinte SHA256 du setup](https://github.com/Maestrr-app/maestrr-releases/releases/download/v1.6.0-beta.8/Maestrr-Setup-1.6.0-beta.8-win-x64.exe.sha256) · [Toutes les versions](https://github.com/Maestrr-app/maestrr-releases/releases)

Le setup se lance sur **Windows** : il installe sur ce PC ou prépare votre serveur **Linux / TrueNAS par SSH**. Il n'existe pas d'EXE distinct pour Linux ou TrueNAS.

> **Version bêta :** testez d'abord sur une installation non critique et sauvegardez vos configurations. L'installateur actuel n'est pas signé : Windows peut afficher un avertissement SmartScreen. Téléchargez uniquement depuis les publications officielles et vérifiez l'empreinte.

![Le dashboard Maestrr : demandes, disponibilité, qualité et accès Jellyfin](https://raw.githubusercontent.com/Maestrr-app/maestrr-releases/main/images/dashboard.png)

## Votre serveur, une seule interface

Films, séries, animés et albums : recherchez, découvrez, demandez et retrouvez les médias de votre collection. Maestrr rassemble le suivi des services que vous configurez ; Jellyfin assure la lecture.

### Découvrir films, séries, animés et musique

Explorez les bannières de découverte et les catalogues par catégorie, studio ou genre. Les fiches regroupent les métadonnées disponibles et les actions de votre installation.

![Découverte des films et navigation dans les affiches](https://raw.githubusercontent.com/Maestrr-app/maestrr-releases/main/images/decouverte.png)

### Demander un média et suivre sa disponibilité

Choisissez la qualité et le dossier de destination. Retrouvez le statut, les fichiers disponibles et le bouton de lecture lorsque le média est reconnu dans Jellyfin.

![Fiche de film et disponibilité dans Jellyfin](https://raw.githubusercontent.com/Maestrr-app/maestrr-releases/main/images/fiche-media.png)

### Choisir les saisons et les épisodes

Les séries et séries animées disposent d'une sélection par saison, avec accès aux épisodes.

![Sélection des saisons et épisodes d'une série animée](https://raw.githubusercontent.com/Maestrr-app/maestrr-releases/main/images/saisons-episodes.png)

### Suivre les téléchargements

Consultez la progression, les débits et les contrôles individuels ou groupés depuis le dashboard, selon vos droits.

![Suivi des téléchargements et commandes qBittorrent](https://raw.githubusercontent.com/Maestrr-app/maestrr-releases/main/images/telechargements.png)

### Piloter les applications

Accédez aux applications et à leurs commandes, aux notifications, aux comptes, aux journaux et aux mises à jour.

![Menu des applications et contrôles des services](https://raw.githubusercontent.com/Maestrr-app/maestrr-releases/main/images/applications.png)

| Application | Rôle |
| --- | --- |
| Jellyfin | Médiathèque et lecture |
| Radarr / Sonarr / Lidarr | Films, séries et albums |
| Prowlarr / qBittorrent / Bazarr | Indexeurs, téléchargements et sous-titres |
| Listenarr | Livres audio, avec configuration propre à l'application |
| Immich | Gestion de vos photos et vidéos |
| Nginx Proxy Manager | Gestion de proxy inverse |
| Tailscale | Accès distant privé |
| Gluetun | VPN optionnel pour les téléchargements |
| Dockge | Gestion des stacks sur les parcours compatibles ; TrueNAS utilise ses Apps natives |

Vous choisissez les applications à installer. Les logiciels tiers conservent leurs propres prérequis et conditions.

### Accéder à votre serveur à distance

Connectez vos appareils au même réseau Tailscale et configurez vos liens HTTPS. Le dashboard s'utilise dans un navigateur sur ordinateur, iPad ou téléphone et peut être ajouté à l'écran d'accueil.

![Tailscale : connexion et appareils de démonstration](https://raw.githubusercontent.com/Maestrr-app/maestrr-releases/main/images/tailscale.png)

### Comparer la connexion avec et sans VPN

Lancez le test de débit intégré pour observer votre connexion. La capture ci-dessous montre l'interface avant mesure, sans résultat de performance annoncé.

![Test de débit sans VPN et avec VPN, avant mesure](https://raw.githubusercontent.com/Maestrr-app/maestrr-releases/main/images/test-debit.png)

