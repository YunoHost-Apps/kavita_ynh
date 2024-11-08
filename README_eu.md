<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Kavita YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/kavita.svg)](https://ci-apps.yunohost.org/ci/apps/kavita/) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/kavita.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/kavita.maintain.svg)

[![Instalatu Kavita YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=kavita)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Kavita YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Kavita is a fast, feature rich, cross platform reading server. Built with a focus for manga and the goal of being a full solution for all your reading needs. Setup your own server and share your reading collection with your friends and family.

### Features

- Extensive File support
- Manga/Comic Reader
- Book Reader
- User Management and Sharing
- Cross Platform with no dependencies - Everything in the box
- Full-text search to quickly find what you want to read
- Mixed media Libraries - Light Novels and Manga can be right next to each other
- Fast and efficient library scans. Don't perform I/O if the underlying file hasn't changed.
- OPDS-PS Support


**Paketatutako bertsioa:** 0.8.3.2~ynh2

**Demoa:** <https://demo.kavitareader.com/>

## Pantaila-argazkiak

![Kavita(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## :red_circle: Ezaugarri zalantzagarriak

- **Ordainpeko edukia**: Ordainpeko zerbitzu bat sustatzen du edo bere mende dago, osorik edo neurri batean.

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://www.kavitareader.com/>
- Administratzaileen dokumentazio ofiziala: <https://wiki.kavitareader.com/en>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/Kareadita/Kavita>
- YunoHost Denda: <https://apps.yunohost.org/app/kavita>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/kavita_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/kavita_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/kavita_ynh/tree/testing --debug
edo
sudo yunohost app upgrade kavita -u https://github.com/YunoHost-Apps/kavita_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
