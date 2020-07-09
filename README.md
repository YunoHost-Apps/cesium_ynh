# Cesium package for YunoHost

[![Integration level](https://dash.yunohost.org/integration/cesium.svg)](https://dash.yunohost.org/appci/app/cesium) ![](https://ci-apps.yunohost.org/ci/badges/cesium.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/cesium.maintain.svg)  
[![Install Custom Webapp with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=cesium)


> *This package allow you to install Cesium quickly and simply on a YunoHost server.  
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

## Overview

[Cesium](https://cesium.app) is an [Unhosted webapp](https://unhosted.org) client for any [Duniter](https://duniter.org) crypto-currency.
It allows you to manage your wallet, certify your friends, and more !

**Shipped version:** v1.6.7

## Public or private status

Following the [decision of Cesium developers (in French)](https://forum.monnaie-libre.fr/t/cesium-evolue-aie-ca-va-piquer-mais/10015) to improve general safety of the Duniter blockchain by removing login capability on public instances of their app, this app follows the same pattern:
 - If the app is set to **public** in Yunohost: the version installed will **only allow the reading** of the blockchain and network, but no transaction or operation will be possible.
 - If the app is set to **private** in Yunohost: the version installed will allow one to login with Duniter credentials and make operations on the blockchain.

## Links

- [YunoHost website](https://yunohost.org)
- [Duniter website](https://duniter.org)
- [Cesium repository](https://github.com/duniter/cesium)

## License

This software is distributed under [GNU AGPL-3.0](https://raw.github.com/duniter/cesium/master/LICENSE).
