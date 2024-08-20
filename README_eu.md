<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Hydrogen YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/hydrogen.svg)](https://ci-apps.yunohost.org/ci/apps/hydrogen/) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/hydrogen.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/hydrogen.maintain.svg)

[![Instalatu Hydrogen YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=hydrogen)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Hydrogen YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

A minimal Matrix chat client, focused on performance, offline functionality, and broad browser support. This is work in progress and not yet ready for primetime.

### Features

- Work well on desktop as well as mobile browsers
- UI components can be easily used in isolation
- It is a standalone webapp, but can also be easily embedded into an existing website/webapp to add chat capabilities.
- Loading (unused) parts of the application after initial page load should be supported


**Paketatutako bertsioa:** 0.5.0~ynh1

**Demoa:** <https://hydrogen.element.io/>

## Pantaila-argazkiak

![Hydrogen(r)en pantaila-argazkia](./doc/screenshots/hydrogen-large.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://matrix.org/ecosystem/clients/hydrogen/>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/vector-im/hydrogen-web>
- YunoHost Denda: <https://apps.yunohost.org/app/hydrogen>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/hydrogen_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/hydrogen_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/hydrogen_ynh/tree/testing --debug
edo
sudo yunohost app upgrade hydrogen -u https://github.com/YunoHost-Apps/hydrogen_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
