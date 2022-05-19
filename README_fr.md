# Hydrogen pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/hydrogen.svg)](https://dash.yunohost.org/appci/app/hydrogen) ![](https://ci-apps.yunohost.org/ci/badges/hydrogen.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/hydrogen.maintain.svg)  
[![Installer Hydrogen avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=hydrogen)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Hydrogen rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

A minimal Matrix chat client, focused on performance, offline functionality, and broad browser support. This is work in progress and not yet ready for primetime.

### Features

- Work well on desktop as well as mobile browsers
- UI components can be easily used in isolation
- It is a standalone webapp, but can also be easily embedded into an existing website/webapp to add chat capabilities.
- Loading (unused) parts of the application after initial page load should be supported


**Version incluse :** 0.2.29~ynh1

**Démo :** https://hydrogen.element.io/

## Captures d'écran

![](./doc/screenshots/hydrogen-large.png)

## Documentations et ressources

* Site officiel de l'app : https://matrix.org/docs/projects/client/hydrogen
* Dépôt de code officiel de l'app : https://github.com/vector-im/hydrogen-web
* Documentation YunoHost pour cette app : https://yunohost.org/app_hydrogen
* Signaler un bug : https://github.com/YunoHost-Apps/hydrogen_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/hydrogen_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/hydrogen_ynh/tree/testing --debug
ou
sudo yunohost app upgrade hydrogen -u https://github.com/YunoHost-Apps/hydrogen_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps