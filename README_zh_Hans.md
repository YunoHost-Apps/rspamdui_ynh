<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Rspamd Web UI

[![集成程度](https://apps.yunohost.org/badge/integration/rspamdui)](https://ci-apps.yunohost.org/ci/apps/rspamdui/)
![工作状态](https://apps.yunohost.org/badge/state/rspamdui)
![维护状态](https://apps.yunohost.org/badge/maintained/rspamdui)

[![使用 YunoHost 安装 Rspamd Web UI](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=rspamdui)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Rspamd Web UI。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Rspamd UI is a simple control interface for Rspamd spam filtering system. It provides basic functions for setting metric actions, scores, viewing statistic and learning.

**分发版本：** 1.0~ynh4

## 截图

![Rspamd Web UI 的截图](./doc/screenshots/screenshot.png)

## 文档与资源

- 官方应用网站： <https://rspamd.com/webui>
- 上游应用代码库： <https://github.com/rspamd/rspamd>
- YunoHost 商店： <https://apps.yunohost.org/app/rspamdui>
- 报告 bug： <https://github.com/YunoHost-Apps/rspamdui_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/rspamdui_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/rspamdui_ynh/tree/testing --debug
或
sudo yunohost app upgrade rspamdui -u https://github.com/YunoHost-Apps/rspamdui_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
