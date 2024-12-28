<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# Hydrogen voor Yunohost

[![Integratieniveau](https://apps.yunohost.org/badge/integration/hydrogen)](https://ci-apps.yunohost.org/ci/apps/hydrogen/)
![Mate van functioneren](https://apps.yunohost.org/badge/state/hydrogen)
![Onderhoudsstatus](https://apps.yunohost.org/badge/maintained/hydrogen)

[![Hydrogen met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=hydrogen)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je Hydrogen snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

A minimal Matrix chat client, focused on performance, offline functionality, and broad browser support. This is work in progress and not yet ready for primetime.

### Features

- Work well on desktop as well as mobile browsers
- UI components can be easily used in isolation
- It is a standalone webapp, but can also be easily embedded into an existing website/webapp to add chat capabilities.
- Loading (unused) parts of the application after initial page load should be supported


**Geleverde versie:** 0.5.1~ynh1

**Demo:** <https://hydrogen.element.io/>

## Schermafdrukken

![Schermafdrukken van Hydrogen](./doc/screenshots/hydrogen-large.png)

## Documentatie en bronnen

- Officiele website van de app: <https://matrix.org/ecosystem/clients/hydrogen/>
- Upstream app codedepot: <https://github.com/vector-im/hydrogen-web>
- YunoHost-store: <https://apps.yunohost.org/app/hydrogen>
- Meld een bug: <https://github.com/YunoHost-Apps/hydrogen_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/hydrogen_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/hydrogen_ynh/tree/testing --debug
of
sudo yunohost app upgrade hydrogen -u https://github.com/YunoHost-Apps/hydrogen_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
