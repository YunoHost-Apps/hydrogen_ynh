<!--
To README zostało automatycznie wygenerowane przez <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Nie powinno być ono edytowane ręcznie.
-->

# Hydrogen dla YunoHost

[![Poziom integracji](https://apps.yunohost.org/badge/integration/hydrogen)](https://ci-apps.yunohost.org/ci/apps/hydrogen/)
![Status działania](https://apps.yunohost.org/badge/state/hydrogen)
![Status utrzymania](https://apps.yunohost.org/badge/maintained/hydrogen)

[![Zainstaluj Hydrogen z YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=hydrogen)

*[Przeczytaj plik README w innym języku.](./ALL_README.md)*

> *Ta aplikacja pozwala na szybką i prostą instalację Hydrogen na serwerze YunoHost.*  
> *Jeżeli nie masz YunoHost zapoznaj się z [poradnikiem](https://yunohost.org/install) instalacji.*

## Przegląd

A minimal Matrix chat client, focused on performance, offline functionality, and broad browser support. This is work in progress and not yet ready for primetime.

### Features

- Work well on desktop as well as mobile browsers
- UI components can be easily used in isolation
- It is a standalone webapp, but can also be easily embedded into an existing website/webapp to add chat capabilities.
- Loading (unused) parts of the application after initial page load should be supported


**Dostarczona wersja:** 0.5.1~ynh1

**Demo:** <https://hydrogen.element.io/>

## Zrzuty ekranu

![Zrzut ekranu z Hydrogen](./doc/screenshots/hydrogen-large.png)

## Dokumentacja i zasoby

- Oficjalna strona aplikacji: <https://matrix.org/ecosystem/clients/hydrogen/>
- Repozytorium z kodem źródłowym: <https://github.com/vector-im/hydrogen-web>
- Sklep YunoHost: <https://apps.yunohost.org/app/hydrogen>
- Zgłaszanie błędów: <https://github.com/YunoHost-Apps/hydrogen_ynh/issues>

## Informacje od twórców

Wyślij swój pull request do [gałęzi `testing`](https://github.com/YunoHost-Apps/hydrogen_ynh/tree/testing).

Aby wypróbować gałąź `testing` postępuj zgodnie z instrukcjami:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/hydrogen_ynh/tree/testing --debug
lub
sudo yunohost app upgrade hydrogen -u https://github.com/YunoHost-Apps/hydrogen_ynh/tree/testing --debug
```

**Więcej informacji o tworzeniu paczek aplikacji:** <https://yunohost.org/packaging_apps>
