<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Kavita pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/kavita.svg)](https://ci-apps.yunohost.org/ci/apps/kavita/) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/kavita.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/kavita.maintain.svg)

[![Installer Kavita avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=kavita)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Kavita rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Kavita est un serveur de lecture multiplateforme rapide et riche en fonctionnalités. Conçu en mettant l'accent sur les mangas et dans le but d'être une solution complète pour tous vos besoins de lecture. Configurez votre propre serveur et partagez votre collection de lectures avec vos amis et votre famille.

### Caractéristiques

- Prise en charge étendue des fichiers
- Lecteur de mangas/bandes dessinées
- Lecteur de livres
- Gestion et partage des utilisateurs
- Multiplateforme sans dépendances - Tout est dans la boîte
- Recherche en texte intégral pour trouver rapidement ce que vous voulez lire
- Bibliothèques multimédias - Les Light Novels et les Mangas peuvent être côte à côte
- Analyses de bibliothèque rapides et efficaces. N'effectuez pas d'E/S si le fichier sous-jacent n'a pas changé.
- Prise en charge OPDS-PS

**Version incluse :** 0.8.3.2~ynh1

**Démo :** <https://demo.kavitareader.com/>

## Captures d’écran

![Capture d’écran de Kavita](./doc/screenshots/screenshot.png)

## :red_circle: Anti-fonctionnalités

- **Contenu payant **: Promeut ou dépend, entièrement ou partiellement, d'un service payant.

## Documentations et ressources

- Site officiel de l’app : <https://www.kavitareader.com/>
- Documentation officielle de l’admin : <https://wiki.kavitareader.com/en>
- Dépôt de code officiel de l’app : <https://github.com/Kareadita/Kavita>
- YunoHost Store : <https://apps.yunohost.org/app/kavita>
- Signaler un bug : <https://github.com/YunoHost-Apps/kavita_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/kavita_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/kavita_ynh/tree/testing --debug
ou
sudo yunohost app upgrade kavita -u https://github.com/YunoHost-Apps/kavita_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
