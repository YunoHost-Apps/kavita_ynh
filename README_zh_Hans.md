<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Kavita

[![集成程度](https://dash.yunohost.org/integration/kavita.svg)](https://ci-apps.yunohost.org/ci/apps/kavita/) ![工作状态](https://ci-apps.yunohost.org/ci/badges/kavita.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/kavita.maintain.svg)

[![使用 YunoHost 安装 Kavita](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=kavita)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Kavita。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

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


**分发版本：** 0.8.3.2~ynh1

**演示：** <https://demo.kavitareader.com/>

## 截图

![Kavita 的截图](./doc/screenshots/screenshot.png)

## :red_circle: 负面特征

- **Paid content**: Promotes or depends, entirely or partially, on a paid service.

## 文档与资源

- 官方应用网站： <https://www.kavitareader.com/>
- 官方管理文档： <https://wiki.kavitareader.com/en>
- 上游应用代码库： <https://github.com/Kareadita/Kavita>
- YunoHost 商店： <https://apps.yunohost.org/app/kavita>
- 报告 bug： <https://github.com/YunoHost-Apps/kavita_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/kavita_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/kavita_ynh/tree/testing --debug
或
sudo yunohost app upgrade kavita -u https://github.com/YunoHost-Apps/kavita_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
