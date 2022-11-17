<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Kavita for YunoHost

[![Integration level](https://dash.yunohost.org/integration/kavita.svg)](https://dash.yunohost.org/appci/app/kavita) ![Working status](https://ci-apps.yunohost.org/ci/badges/kavita.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/kavita.maintain.svg)  
[![Install Kavita with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=kavita)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Kavita quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Kavita is a fast, feature rich, cross platform reading server. Built with a focus for manga and the goal of being a full solution for all your reading needs. Setup your own server and share your reading collection with your friends and family.

### Features

- Extensive File support
    - Manga/Comics: ZIP, RAR, CBR, CBZ, CB7, CBT, TAR.GZ, 7ZIP/7Z
    - Books: EPUB2, EPUB3, PDF
    - Raw Images: JPG/JPEG, PNG, WEBP
- Manga/Comic Reader
    - Image Scaling to fit your device screen or override for what feels best to you
    - Image Splitting for those joined page spreads, don't scroll on your tablet, just split
    - Apply a custom dark or sepia tone to your images to make it easier to read at night
    - Reading Direction: Left/Right, Up/Down, Webtoon
    - Webtoon reader built-in
    - Read across archives without closing the reader
- Book Reader
    - Interactive reader - can interact with text, run javascript
    - Dark mode persists between page load
    - Can tap to paginate or use dedicated buttons
    - Customize your reading experience with custom Font, Font Size, Margin, Reading Direction, Dark Mode
    - Table of Content just a click away
    - Remember line position and resume where you left off, no matter the device
    - Read across books without closing the reader
- User Management and Sharing
        Create users and share your libraries with them
        Grant users permissions to view libraries or see different mixed-media collections
        Built-in ratings and reviews for each of your users
- Cross Platform with no dependencies - Everything in the box
- Responsive and Fast!
- Full-text search to quickly find what you want to read
- Mixed media Libraries - Light Novels and Manga can be right next to each other
- Fast and efficient library scans. Don't perform I/O if the underlying file hasn't changed.
- Accessibility first - audits for color contrast, screen reader, and keyboard only
- OPDS-PS Support
- Frequent updates with new features



**Shipped version:** 0.6.1~ynh1

**Demo:** https://demo.kavitareader.com/

## Screenshots

![Screenshot of Kavita](./doc/screenshots/screenshot.gif)

## Documentation and resources

* Official app website: <www.kavitareader.com>
* Official admin documentation: <https://wiki.kavitareader.com/en>
* Upstream app code repository: <https://github.com/Kareadita/Kavita>
* YunoHost documentation for this app: <https://yunohost.org/app_kavita>
* Report a bug: <https://github.com/YunoHost-Apps/kavita_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/kavita_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/kavita_ynh/tree/testing --debug
or
sudo yunohost app upgrade kavita -u https://github.com/YunoHost-Apps/kavita_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>