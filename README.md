# Anfora for YunoHost

[![Integration level](https://dash.yunohost.org/integration/anfora.svg)](https://dash.yunohost.org/appci/app/anfora) ![](https://ci-apps.yunohost.org/ci/badges/anfora.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/anfora.maintain.svg)  
[![Install Anfora with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=anfora)

> *This package allow you to install Anfora quickly and simply on a YunoHost server.  
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

## Overview
Self-hosted photo gallery federated social network.

**Shipped version:** 0.1-2019-05-18

**Package and project status**: Anfora is under developement and rework, it is not considered as stable and not recommanded for production right now. See: https://github.com/anforaProject/anfora/issues/54#issuecomment-732168373

## Important points to read before installing

1. **Anfora** require a dedicated **root domain**, eg. anfora.domain.tld

## Screenshots

![](https://raw.githubusercontent.com/anforaProject/anfora/master/images/profile_view.png)

## Documentation

 * Official documentation: https://anfora.app/documentation/

## YunoHost specific features

#### Supported architectures

* x86-64b - [![Build Status](https://ci-apps.yunohost.org/ci/logs/anfora%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/anfora/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/anfora%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/anfora/)


## Links

 * Report a bug: https://github.com/YunoHost-Apps/anfora_ynh/issues
 * App website: https://anfora.app/
 * Git website: https://github.com/anforaProject/anfora
 * YunoHost website: https://yunohost.org/

---

Developers info
----------------

Please do your pull request to the [testing branch](https://github.com/YunoHost-Apps/anfora_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/anfora_ynh/tree/testing --debug
or
sudo yunohost app upgrade anfora -u https://github.com/YunoHost-Apps/anfora_ynh/tree/testing --debug
```
