<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# Screego voor Yunohost

[![Integratieniveau](https://dash.yunohost.org/integration/screego.svg)](https://ci-apps.yunohost.org/ci/apps/screego/) ![Mate van functioneren](https://ci-apps.yunohost.org/ci/badges/screego.status.svg) ![Onderhoudsstatus](https://ci-apps.yunohost.org/ci/badges/screego.maintain.svg)

[![Screego met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=screego)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je Screego snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

Screen sharing for developers.

### Features

- Multi User Screenshare
- Secure transfer via WebRTC
- Low latency / High resolution
- Simple Install via Docker / single binary
- Integrated TURN Server see NAT Traversal


**Geleverde versie:** 1.10.5~ynh2

**Demo:** <https://app.screego.net/>

## Schermafdrukken

![Schermafdrukken van Screego](./doc/screenshots/screenshot.png)

## Documentatie en bronnen

- Officiele website van de app: <https://screego.net/#/>
- Officiele beheerdersdocumentatie: <https://screego.net/#/>
- Upstream app codedepot: <https://github.com/screego/server>
- YunoHost-store: <https://apps.yunohost.org/app/screego>
- Meld een bug: <https://github.com/YunoHost-Apps/screego_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/screego_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/screego_ynh/tree/testing --debug
of
sudo yunohost app upgrade screego -u https://github.com/YunoHost-Apps/screego_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
