<!--
N.B.: Questo README è stato automaticamente generato da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON DEVE essere modificato manualmente.
-->

# Hydrogen per YunoHost

[![Livello di integrazione](https://dash.yunohost.org/integration/hydrogen.svg)](https://dash.yunohost.org/appci/app/hydrogen) ![Stato di funzionamento](https://ci-apps.yunohost.org/ci/badges/hydrogen.status.svg) ![Stato di manutenzione](https://ci-apps.yunohost.org/ci/badges/hydrogen.maintain.svg)

[![Installa Hydrogen con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=hydrogen)

*[Leggi questo README in altre lingue.](./ALL_README.md)*

> *Questo pacchetto ti permette di installare Hydrogen su un server YunoHost in modo semplice e veloce.*  
> *Se non hai YunoHost, consulta [la guida](https://yunohost.org/install) per imparare a installarlo.*

## Panoramica

A minimal Matrix chat client, focused on performance, offline functionality, and broad browser support. This is work in progress and not yet ready for primetime.

### Features

- Work well on desktop as well as mobile browsers
- UI components can be easily used in isolation
- It is a standalone webapp, but can also be easily embedded into an existing website/webapp to add chat capabilities.
- Loading (unused) parts of the application after initial page load should be supported


**Versione pubblicata:** 0.4.1~ynh1

**Prova:** <https://hydrogen.element.io/>

## Screenshot

![Screenshot di Hydrogen](./doc/screenshots/hydrogen-large.png)

## Documentazione e risorse

- Sito web ufficiale dell’app: <https://matrix.org/ecosystem/clients/hydrogen/>
- Repository upstream del codice dell’app: <https://github.com/vector-im/hydrogen-web>
- Store di YunoHost: <https://apps.yunohost.org/app/hydrogen>
- Segnala un problema: <https://github.com/YunoHost-Apps/hydrogen_ynh/issues>

## Informazioni per sviluppatori

Si prega di inviare la tua pull request alla [branch di `testing`](https://github.com/YunoHost-Apps/hydrogen_ynh/tree/testing).

Per provare la branch di `testing`, si prega di procedere in questo modo:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/hydrogen_ynh/tree/testing --debug
o
sudo yunohost app upgrade hydrogen -u https://github.com/YunoHost-Apps/hydrogen_ynh/tree/testing --debug
```

**Maggiori informazioni riguardo il pacchetto di quest’app:** <https://yunohost.org/packaging_apps>
