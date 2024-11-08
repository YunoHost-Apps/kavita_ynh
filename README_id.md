<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Kavita untuk YunoHost

[![Tingkat integrasi](https://dash.yunohost.org/integration/kavita.svg)](https://ci-apps.yunohost.org/ci/apps/kavita/) ![Status kerja](https://ci-apps.yunohost.org/ci/badges/kavita.status.svg) ![Status pemeliharaan](https://ci-apps.yunohost.org/ci/badges/kavita.maintain.svg)

[![Pasang Kavita dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=kavita)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Kavita secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

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


**Versi terkirim:** 0.8.3.2~ynh2

**Demo:** <https://demo.kavitareader.com/>

## Tangkapan Layar

![Tangkapan Layar pada Kavita](./doc/screenshots/screenshot.png)

## :red_circle: Antifitur

- **Paid content**: Promotes or depends, entirely or partially, on a paid service.

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://www.kavitareader.com/>
- Dokumentasi admin resmi: <https://wiki.kavitareader.com/en>
- Depot kode aplikasi hulu: <https://github.com/Kareadita/Kavita>
- Gudang YunoHost: <https://apps.yunohost.org/app/kavita>
- Laporkan bug: <https://github.com/YunoHost-Apps/kavita_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/kavita_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/kavita_ynh/tree/testing --debug
atau
sudo yunohost app upgrade kavita -u https://github.com/YunoHost-Apps/kavita_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
