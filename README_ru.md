<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# Hydrogen для YunoHost

[![Уровень интеграции](https://apps.yunohost.org/badge/integration/hydrogen)](https://ci-apps.yunohost.org/ci/apps/hydrogen/)
![Состояние работы](https://apps.yunohost.org/badge/state/hydrogen)
![Состояние сопровождения](https://apps.yunohost.org/badge/maintained/hydrogen)

[![Установите Hydrogen с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=hydrogen)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить Hydrogen быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

A minimal Matrix chat client, focused on performance, offline functionality, and broad browser support. This is work in progress and not yet ready for primetime.

### Features

- Work well on desktop as well as mobile browsers
- UI components can be easily used in isolation
- It is a standalone webapp, but can also be easily embedded into an existing website/webapp to add chat capabilities.
- Loading (unused) parts of the application after initial page load should be supported


**Поставляемая версия:** 0.5.1~ynh1

**Демо-версия:** <https://hydrogen.element.io/>

## Снимки экрана

![Снимок экрана Hydrogen](./doc/screenshots/hydrogen-large.png)

## Документация и ресурсы

- Официальный веб-сайт приложения: <https://matrix.org/ecosystem/clients/hydrogen/>
- Репозиторий кода главной ветки приложения: <https://github.com/vector-im/hydrogen-web>
- Магазин YunoHost: <https://apps.yunohost.org/app/hydrogen>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/hydrogen_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/hydrogen_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/hydrogen_ynh/tree/testing --debug
или
sudo yunohost app upgrade hydrogen -u https://github.com/YunoHost-Apps/hydrogen_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
