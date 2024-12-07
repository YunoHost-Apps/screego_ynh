<!--
To README zostało automatycznie wygenerowane przez <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Nie powinno być ono edytowane ręcznie.
-->

# Screego dla YunoHost

[![Poziom integracji](https://apps.yunohost.org/badge/integration/screego)](https://ci-apps.yunohost.org/ci/apps/screego/)
![Status działania](https://apps.yunohost.org/badge/state/screego)
![Status utrzymania](https://apps.yunohost.org/badge/maintained/screego)

[![Zainstaluj Screego z YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=screego)

*[Przeczytaj plik README w innym języku.](./ALL_README.md)*

> *Ta aplikacja pozwala na szybką i prostą instalację Screego na serwerze YunoHost.*  
> *Jeżeli nie masz YunoHost zapoznaj się z [poradnikiem](https://yunohost.org/install) instalacji.*

## Przegląd

Screen sharing for developers.

### Features

- Multi User Screenshare
- Secure transfer via WebRTC
- Low latency / High resolution
- Simple Install via Docker / single binary
- Integrated TURN Server see NAT Traversal


**Dostarczona wersja:** 1.11.2~ynh1

**Demo:** <https://app.screego.net/>

## Zrzuty ekranu

![Zrzut ekranu z Screego](./doc/screenshots/screenshot.png)

## Dokumentacja i zasoby

- Oficjalna strona aplikacji: <https://screego.net/#/>
- Oficjalna dokumentacja dla administratora: <https://screego.net/#/>
- Repozytorium z kodem źródłowym: <https://github.com/screego/server>
- Sklep YunoHost: <https://apps.yunohost.org/app/screego>
- Zgłaszanie błędów: <https://github.com/YunoHost-Apps/screego_ynh/issues>

## Informacje od twórców

Wyślij swój pull request do [gałęzi `testing`](https://github.com/YunoHost-Apps/screego_ynh/tree/testing).

Aby wypróbować gałąź `testing` postępuj zgodnie z instrukcjami:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/screego_ynh/tree/testing --debug
lub
sudo yunohost app upgrade screego -u https://github.com/YunoHost-Apps/screego_ynh/tree/testing --debug
```

**Więcej informacji o tworzeniu paczek aplikacji:** <https://yunohost.org/packaging_apps>
