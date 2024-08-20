<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# Hydrogen para Yunohost

[![Nivel de integración](https://dash.yunohost.org/integration/hydrogen.svg)](https://ci-apps.yunohost.org/ci/apps/hydrogen/) ![Estado funcional](https://ci-apps.yunohost.org/ci/badges/hydrogen.status.svg) ![Estado En Mantención](https://ci-apps.yunohost.org/ci/badges/hydrogen.maintain.svg)

[![Instalar Hydrogen con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=hydrogen)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarHydrogen rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

A minimal Matrix chat client, focused on performance, offline functionality, and broad browser support. This is work in progress and not yet ready for primetime.

### Features

- Work well on desktop as well as mobile browsers
- UI components can be easily used in isolation
- It is a standalone webapp, but can also be easily embedded into an existing website/webapp to add chat capabilities.
- Loading (unused) parts of the application after initial page load should be supported


**Versión actual:** 0.5.0~ynh1

**Demo:** <https://hydrogen.element.io/>

## Capturas

![Captura de Hydrogen](./doc/screenshots/hydrogen-large.png)

## Documentaciones y recursos

- Sitio web oficial: <https://matrix.org/ecosystem/clients/hydrogen/>
- Repositorio del código fuente oficial de la aplicación : <https://github.com/vector-im/hydrogen-web>
- Catálogo YunoHost: <https://apps.yunohost.org/app/hydrogen>
- Reportar un error: <https://github.com/YunoHost-Apps/hydrogen_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [`branch testing`](https://github.com/YunoHost-Apps/hydrogen_ynh/tree/testing

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/hydrogen_ynh/tree/testing --debug
o
sudo yunohost app upgrade hydrogen -u https://github.com/YunoHost-Apps/hydrogen_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
