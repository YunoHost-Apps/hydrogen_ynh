<!--
NOTA: Este README foi creado automáticamente por <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON debe editarse manualmente.
-->

# Hydrogen para YunoHost

[![Nivel de integración](https://dash.yunohost.org/integration/hydrogen.svg)](https://ci-apps.yunohost.org/ci/apps/hydrogen/) ![Estado de funcionamento](https://ci-apps.yunohost.org/ci/badges/hydrogen.status.svg) ![Estado de mantemento](https://ci-apps.yunohost.org/ci/badges/hydrogen.maintain.svg)

[![Instalar Hydrogen con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=hydrogen)

*[Le este README en outros idiomas.](./ALL_README.md)*

> *Este paquete permíteche instalar Hydrogen de xeito rápido e doado nun servidor YunoHost.*  
> *Se non usas YunoHost, le a [documentación](https://yunohost.org/install) para saber como instalalo.*

## Vista xeral

A minimal Matrix chat client, focused on performance, offline functionality, and broad browser support. This is work in progress and not yet ready for primetime.

### Features

- Work well on desktop as well as mobile browsers
- UI components can be easily used in isolation
- It is a standalone webapp, but can also be easily embedded into an existing website/webapp to add chat capabilities.
- Loading (unused) parts of the application after initial page load should be supported


**Versión proporcionada:** 0.5.1~ynh1

**Demo:** <https://hydrogen.element.io/>

## Capturas de pantalla

![Captura de pantalla de Hydrogen](./doc/screenshots/hydrogen-large.png)

## Documentación e recursos

- Web oficial da app: <https://matrix.org/ecosystem/clients/hydrogen/>
- Repositorio de orixe do código: <https://github.com/vector-im/hydrogen-web>
- Tenda YunoHost: <https://apps.yunohost.org/app/hydrogen>
- Informar dun problema: <https://github.com/YunoHost-Apps/hydrogen_ynh/issues>

## Info de desenvolvemento

Envía a túa colaboración á [rama `testing`](https://github.com/YunoHost-Apps/hydrogen_ynh/tree/testing).

Para probar a rama `testing`, procede deste xeito:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/hydrogen_ynh/tree/testing --debug
ou
sudo yunohost app upgrade hydrogen -u https://github.com/YunoHost-Apps/hydrogen_ynh/tree/testing --debug
```

**Máis info sobre o empaquetado da app:** <https://yunohost.org/packaging_apps>
