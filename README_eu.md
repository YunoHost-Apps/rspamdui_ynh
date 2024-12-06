<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Rspamd Web UI YunoHost-erako

[![Integrazio maila](https://apps.yunohost.org/badge/integration/rspamdui)](https://ci-apps.yunohost.org/ci/apps/rspamdui/)
![Funtzionamendu egoera](https://apps.yunohost.org/badge/state/rspamdui)
![Mantentze egoera](https://apps.yunohost.org/badge/maintained/rspamdui)

[![Instalatu Rspamd Web UI YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=rspamdui)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Rspamd Web UI YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Rspamd UI is a simple control interface for Rspamd spam filtering system. It provides basic functions for setting metric actions, scores, viewing statistic and learning.

**Paketatutako bertsioa:** 1.0~ynh4

## Pantaila-argazkiak

![Rspamd Web UI(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://rspamd.com/webui>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/rspamd/rspamd>
- YunoHost Denda: <https://apps.yunohost.org/app/rspamdui>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/rspamdui_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/rspamdui_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/rspamdui_ynh/tree/testing --debug
edo
sudo yunohost app upgrade rspamdui -u https://github.com/YunoHost-Apps/rspamdui_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
