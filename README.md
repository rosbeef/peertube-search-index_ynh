<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# PeerTube search-index for YunoHost

[![Integration level](https://dash.yunohost.org/integration/peertube-search-index.svg)](https://dash.yunohost.org/appci/app/peertube-search-index) ![](https://ci-apps.yunohost.org/ci/badges/peertube-search-index.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/peertube-search-index.maintain.svg)  
[![Install PeerTube search-index with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=peertube-search-index)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install PeerTube search-index quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

A search engine for [PeerTube](https://joinpeertube.org/) videos and channels, developed by Framasoft.


**Shipped version:** 2021.12.28~ynh1

**Demo:** https://search.joinpeertube.org/

## Screenshots

![](./doc/screenshots/sepia-search-screenshot.png)

## Disclaimers / important information

## Important points to read before installing

1. **PeerTube search-index** requires a dedicated **root domain**, e.g. search.domain.tld

## Configuration

To configure this app: modify the file `/var/www/peertube-search-index/config/production.yaml` with SSH.

## Documentation and resources

* Official app website: https://search.joinpeertube.org/
* Official admin documentation: https://framagit.org/framasoft/peertube/search-index
* Upstream app code repository: https://framagit.org/framasoft/peertube/search-index
* YunoHost documentation for this app: https://yunohost.org/app_peertube-search-index
* Report a bug: https://github.com/YunoHost-Apps/peertube-search-index_ynh/issues

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/peertube-search-index_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/peertube-search-index_ynh/tree/testing --debug
or
sudo yunohost app upgrade peertube-search-index -u https://github.com/YunoHost-Apps/peertube-search-index_ynh/tree/testing --debug
```

**More info regarding app packaging:** https://yunohost.org/packaging_apps