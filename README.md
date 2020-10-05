# Timeoff Management for YunoHost

[![Integration level](https://dash.yunohost.org/integration/timeoff.svg)](https://dash.yunohost.org/appci/app/timeoff) ![](https://ci-apps.yunohost.org/ci/badges/timeoff.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/timeoff.maintain.svg)  
[![Install timeoff with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=timeoff)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install REPLACEBYYOURAPP quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview
Open source, simple yet powerful absence management software for small and medium sized businesses.

**Shipped version:** 1.0.0

## Screenshots

![](https://timeoff.management/img/screen_requests.png)

## Demo

* [Official demo](Link to a demo site for this app.)

## Configuration

How to configure this app: From an admin panel, a plain file with SSH, or any other way.

## Documentation

 * Official documentation: Link to the official documentation of this app
 * YunoHost documentation: If specific documentation is needed, feel free to contribute.

## YunoHost specific features

#### Multi-user support

 * Are LDAP and HTTP auth supported?
 * Can the app be used by multiple users?

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/timeoff%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/timeoff/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/timeoff%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/timeoff/)

## Limitations

* Any known limitations.

## Additional information

* Other info you would like to add about this app.

**More info on the documentation page:**  
https://yunohost.org/packaging_apps

## Links

 * Report a bug: https://github.com/YunoHost-Apps/REPLACEBYYOURAPP_ynh/issues
 * App website: https://timeoff.management/
 * Upstream app repository: https://github.com/timeoff-management/application
 * YunoHost website: https://yunohost.org/

---

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/timeoff_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/timeoff_ynh/tree/testing --debug
or
sudo yunohost app upgrade timeoff -u https://github.com/YunoHost-Apps/timeoff_ynh/tree/testing --debug
```
