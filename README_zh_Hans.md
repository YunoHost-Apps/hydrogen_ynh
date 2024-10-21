<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Hydrogen

[![集成程度](https://dash.yunohost.org/integration/hydrogen.svg)](https://ci-apps.yunohost.org/ci/apps/hydrogen/) ![工作状态](https://ci-apps.yunohost.org/ci/badges/hydrogen.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/hydrogen.maintain.svg)

[![使用 YunoHost 安装 Hydrogen](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=hydrogen)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Hydrogen。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

A minimal Matrix chat client, focused on performance, offline functionality, and broad browser support. This is work in progress and not yet ready for primetime.

### Features

- Work well on desktop as well as mobile browsers
- UI components can be easily used in isolation
- It is a standalone webapp, but can also be easily embedded into an existing website/webapp to add chat capabilities.
- Loading (unused) parts of the application after initial page load should be supported


**分发版本：** 0.5.1~ynh1

**演示：** <https://hydrogen.element.io/>

## 截图

![Hydrogen 的截图](./doc/screenshots/hydrogen-large.png)

## 文档与资源

- 官方应用网站： <https://matrix.org/ecosystem/clients/hydrogen/>
- 上游应用代码库： <https://github.com/vector-im/hydrogen-web>
- YunoHost 商店： <https://apps.yunohost.org/app/hydrogen>
- 报告 bug： <https://github.com/YunoHost-Apps/hydrogen_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/hydrogen_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/hydrogen_ynh/tree/testing --debug
或
sudo yunohost app upgrade hydrogen -u https://github.com/YunoHost-Apps/hydrogen_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
