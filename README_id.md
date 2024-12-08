<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Screego untuk YunoHost

[![Tingkat integrasi](https://apps.yunohost.org/badge/integration/screego)](https://ci-apps.yunohost.org/ci/apps/screego/)
![Status kerja](https://apps.yunohost.org/badge/state/screego)
![Status pemeliharaan](https://apps.yunohost.org/badge/maintained/screego)

[![Pasang Screego dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=screego)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Screego secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

Screen sharing for developers.

### Features

- Multi User Screenshare
- Secure transfer via WebRTC
- Low latency / High resolution
- Simple Install via Docker / single binary
- Integrated TURN Server see NAT Traversal


**Versi terkirim:** 1.11.2~ynh1

**Demo:** <https://app.screego.net/>

## Tangkapan Layar

![Tangkapan Layar pada Screego](./doc/screenshots/screenshot.png)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://screego.net/#/>
- Dokumentasi admin resmi: <https://screego.net/#/>
- Depot kode aplikasi hulu: <https://github.com/screego/server>
- Gudang YunoHost: <https://apps.yunohost.org/app/screego>
- Laporkan bug: <https://github.com/YunoHost-Apps/screego_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/screego_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/screego_ynh/tree/testing --debug
atau
sudo yunohost app upgrade screego -u https://github.com/YunoHost-Apps/screego_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
