# Cesium package for YunoHost

[![Integration level](https://dash.yunohost.org/integration/cesium.svg)](https://dash.yunohost.org/appci/app/cesium) ![](https://ci-apps.yunohost.org/ci/badges/cesium.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/cesium.maintain.svg)  
[![Install Cesium with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=cesium)


> *This package allows you to install Cesium quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview
[Cesium](https://cesium.app) is an [Unhosted webapp](https://unhosted.org) client for any [Duniter](https://duniter.org) crypto-currency.
It allows you to manage your wallet, certify your friends, and more !

**Shipped version:** v1.6.12

## YunoHost specific features

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/cesium%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/cesium/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/cesium%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/cesium/)

## Links

 * Report a bug: https://github.com/YunoHost-Apps/cesium_ynh/issues
 * App website: https://duniter.org
 * Upstream app repository: https://github.com/duniter/cesium
 * YunoHost website: https://yunohost.org/

---

Developer info
----------------

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/cesium_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/cesium_ynh/tree/testing --debug
or
sudo yunohost app upgrade cesium -u https://github.com/YunoHost-Apps/cesium_ynh/tree/testing --debug
```
