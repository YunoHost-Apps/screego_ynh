<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# Screego для YunoHost

[![Уровень интеграции](https://dash.yunohost.org/integration/screego.svg)](https://ci-apps.yunohost.org/ci/apps/screego/) ![Состояние работы](https://ci-apps.yunohost.org/ci/badges/screego.status.svg) ![Состояние сопровождения](https://ci-apps.yunohost.org/ci/badges/screego.maintain.svg)

[![Установите Screego с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=screego)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить Screego быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

Screen sharing for developers.

### Features

- Multi User Screenshare
- Secure transfer via WebRTC
- Low latency / High resolution
- Simple Install via Docker / single binary
- Integrated TURN Server see NAT Traversal


**Поставляемая версия:** 1.10.5~ynh1

**Демо-версия:** <https://app.screego.net/>

## Снимки экрана

![Снимок экрана Screego](./doc/screenshots/screenshot.png)

## Документация и ресурсы

- Официальный веб-сайт приложения: <https://screego.net/#/>
- Официальная документация администратора: <https://screego.net/#/>
- Репозиторий кода главной ветки приложения: <https://github.com/screego/server>
- Магазин YunoHost: <https://apps.yunohost.org/app/screego>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/screego_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/screego_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/screego_ynh/tree/testing --debug
или
sudo yunohost app upgrade screego -u https://github.com/YunoHost-Apps/screego_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
