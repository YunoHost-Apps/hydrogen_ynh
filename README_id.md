<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Hydrogen untuk YunoHost

[![Tingkat integrasi](https://dash.yunohost.org/integration/hydrogen.svg)](https://ci-apps.yunohost.org/ci/apps/hydrogen/) ![Status kerja](https://ci-apps.yunohost.org/ci/badges/hydrogen.status.svg) ![Status pemeliharaan](https://ci-apps.yunohost.org/ci/badges/hydrogen.maintain.svg)

[![Pasang Hydrogen dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=hydrogen)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Hydrogen secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

A minimal Matrix chat client, focused on performance, offline functionality, and broad browser support. This is work in progress and not yet ready for primetime.

### Features

- Work well on desktop as well as mobile browsers
- UI components can be easily used in isolation
- It is a standalone webapp, but can also be easily embedded into an existing website/webapp to add chat capabilities.
- Loading (unused) parts of the application after initial page load should be supported


**Versi terkirim:** 0.5.1~ynh1

**Demo:** <https://hydrogen.element.io/>

## Tangkapan Layar

![Tangkapan Layar pada Hydrogen](./doc/screenshots/hydrogen-large.png)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://matrix.org/ecosystem/clients/hydrogen/>
- Depot kode aplikasi hulu: <https://github.com/vector-im/hydrogen-web>
- Gudang YunoHost: <https://apps.yunohost.org/app/hydrogen>
- Laporkan bug: <https://github.com/YunoHost-Apps/hydrogen_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/hydrogen_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/hydrogen_ynh/tree/testing --debug
atau
sudo yunohost app upgrade hydrogen -u https://github.com/YunoHost-Apps/hydrogen_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
