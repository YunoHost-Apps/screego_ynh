<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Screego pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/screego.svg)](https://ci-apps.yunohost.org/ci/apps/screego/) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/screego.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/screego.maintain.svg)

[![Installer Screego avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=screego)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Screego rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

### Fonctionnalités

- Partage d'écran multi-utilisateurs
- Transfert sécurisé via WebRTC
- Faible latence / Haute résolution
- Installation simple via Docker / binaire unique
- Serveur TURN intégré voir Traversée NAT

**Version incluse :** 1.10.5~ynh1

**Démo :** <https://app.screego.net/>

## Captures d’écran

![Capture d’écran de Screego](./doc/screenshots/screenshot.png)

## Documentations et ressources

- Site officiel de l’app : <https://screego.net/#/>
- Documentation officielle de l’admin : <https://screego.net/#/>
- Dépôt de code officiel de l’app : <https://github.com/screego/server>
- YunoHost Store : <https://apps.yunohost.org/app/screego>
- Signaler un bug : <https://github.com/YunoHost-Apps/screego_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/screego_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/screego_ynh/tree/testing --debug
ou
sudo yunohost app upgrade screego -u https://github.com/YunoHost-Apps/screego_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
