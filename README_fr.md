<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Hydrogen pour YunoHost

[![Niveau d’intégration](https://apps.yunohost.org/badge/integration/hydrogen)](https://ci-apps.yunohost.org/ci/apps/hydrogen/)
![Statut du fonctionnement](https://apps.yunohost.org/badge/state/hydrogen)
![Statut de maintenance](https://apps.yunohost.org/badge/maintained/hydrogen)

[![Installer Hydrogen avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=hydrogen)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Hydrogen rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Un client de chat Matrix minimal, axé sur les performances, les fonctionnalités hors ligne et la prise en charge étendue du navigateur. C'est un travail en cours et pas encore prêt pour les heures de grande écoute.

### Caractéristiques

- Fonctionne sur les ordinateurs de bureau ainsi que sur les navigateurs mobiles
- Les composants de l'interface utilisateur peuvent être facilement utilisés isolément
- Il s'agit d'une application Web autonome, mais elle peut également être facilement intégrée à un site Web/une application Web existante pour ajouter des fonctionnalités de chat.
- Le chargement de parties (inutilisées) de l'application après le chargement initial de la page doit être pris en charge

**Version incluse :** 0.5.1~ynh1

**Démo :** <https://hydrogen.element.io/>

## Captures d’écran

![Capture d’écran de Hydrogen](./doc/screenshots/hydrogen-large.png)

## Documentations et ressources

- Site officiel de l’app : <https://matrix.org/ecosystem/clients/hydrogen/>
- Dépôt de code officiel de l’app : <https://github.com/vector-im/hydrogen-web>
- YunoHost Store : <https://apps.yunohost.org/app/hydrogen>
- Signaler un bug : <https://github.com/YunoHost-Apps/hydrogen_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/hydrogen_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/hydrogen_ynh/tree/testing --debug
ou
sudo yunohost app upgrade hydrogen -u https://github.com/YunoHost-Apps/hydrogen_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
