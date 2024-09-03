<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Screego

[![集成程度](https://dash.yunohost.org/integration/screego.svg)](https://ci-apps.yunohost.org/ci/apps/screego/) ![工作状态](https://ci-apps.yunohost.org/ci/badges/screego.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/screego.maintain.svg)

[![使用 YunoHost 安装 Screego](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=screego)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Screego。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Screen sharing for developers.

### Features

- Multi User Screenshare
- Secure transfer via WebRTC
- Low latency / High resolution
- Simple Install via Docker / single binary
- Integrated TURN Server see NAT Traversal


**分发版本：** 1.10.5~ynh1

**演示：** <https://app.screego.net/>

## 截图

![Screego 的截图](./doc/screenshots/screenshot.png)

## 文档与资源

- 官方应用网站： <https://screego.net/#/>
- 官方管理文档： <https://screego.net/#/>
- 上游应用代码库： <https://github.com/screego/server>
- YunoHost 商店： <https://apps.yunohost.org/app/screego>
- 报告 bug： <https://github.com/YunoHost-Apps/screego_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/screego_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/screego_ynh/tree/testing --debug
或
sudo yunohost app upgrade screego -u https://github.com/YunoHost-Apps/screego_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
