<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Screego YunoHost-erako

[![Integrazio maila](https://apps.yunohost.org/badge/integration/screego)](https://ci-apps.yunohost.org/ci/apps/screego/)
![Funtzionamendu egoera](https://apps.yunohost.org/badge/state/screego)
![Mantentze egoera](https://apps.yunohost.org/badge/maintained/screego)

[![Instalatu Screego YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=screego)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Screego YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Screen sharing for developers.

### Features

- Multi User Screenshare
- Secure transfer via WebRTC
- Low latency / High resolution
- Simple Install via Docker / single binary
- Integrated TURN Server see NAT Traversal


**Paketatutako bertsioa:** 1.11.2~ynh1

**Demoa:** <https://app.screego.net/>

## Pantaila-argazkiak

![Screego(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://screego.net/#/>
- Administratzaileen dokumentazio ofiziala: <https://screego.net/#/>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/screego/server>
- YunoHost Denda: <https://apps.yunohost.org/app/screego>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/screego_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/screego_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/screego_ynh/tree/testing --debug
edo
sudo yunohost app upgrade screego -u https://github.com/YunoHost-Apps/screego_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
