<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Hydrogen for YunoHost

[![Integration level](https://dash.yunohost.org/integration/hydrogen.svg)](https://dash.yunohost.org/appci/app/hydrogen) ![Working status](https://ci-apps.yunohost.org/ci/badges/hydrogen.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/hydrogen.maintain.svg)  
[![Install Hydrogen with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=hydrogen)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Hydrogen quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

A minimal Matrix chat client, focused on performance, offline functionality, and broad browser support. This is work in progress and not yet ready for primetime.

### Features

- Work well on desktop as well as mobile browsers
- UI components can be easily used in isolation
- It is a standalone webapp, but can also be easily embedded into an existing website/webapp to add chat capabilities.
- Loading (unused) parts of the application after initial page load should be supported


**Shipped version:** 0.3.4~ynh1

**Demo:** https://hydrogen.element.io/

## Screenshots

![Screenshot of Hydrogen](./doc/screenshots/hydrogen-large.png)

## Documentation and resources

* Official app website: <https://matrix.org/docs/projects/client/hydrogen>
* Upstream app code repository: <https://github.com/vector-im/hydrogen-web>
* YunoHost documentation for this app: <https://yunohost.org/app_hydrogen>
* Report a bug: <https://github.com/YunoHost-Apps/hydrogen_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/hydrogen_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/hydrogen_ynh/tree/testing --debug
or
sudo yunohost app upgrade hydrogen -u https://github.com/YunoHost-Apps/hydrogen_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
