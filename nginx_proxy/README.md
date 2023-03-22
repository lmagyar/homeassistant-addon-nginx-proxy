# Home Assistant Add-on: NGINX Home Assistant SSL proxy with certificate renewal detection

![Warning][warning_stripe]

> This is a **fork** of the [official add-on][official_addon]! This reloads
> NGINX when the certificate is renewed.
>
> Updates are released when the official add-on changes (changes are merged).

![Warning][warning_stripe]

Sets up an SSL proxy with NGINX and redirects traffic from port 80 to 443.

[![GitHub Release][releases-shield]][releases]
[![Last Updated][updated-shield]][updated]
![Reported Installations][installations-shield]
![Project Stage][project-stage-shield]
[![License][license-shield]][licence]

![Supports aarch64 Architecture][aarch64-shield]
![Supports amd64 Architecture][amd64-shield]
![Supports armhf Architecture][armhf-shield]
![Supports armv7 Architecture][armv7-shield]
![Supports i386 Architecture][i386-shield]

[![Github Actions][github-actions-shield]][github-actions]
![Project Maintenance][maintenance-shield]
[![GitHub Activity][commits-shield]][commits]

## About

Sets up an SSL proxy with NGINX web server. It is typically used to forward SSL
internet traffic while allowing unencrypted local traffic to/from a Home
Assistant instance.

Make sure you have generated a certificate before you start this add-on. The
[Duck DNS](https://github.com/home-assistant/addons/tree/master/duckdns) add-on
can generate a Let's Encrypt certificate that can be used by this add-on.

[aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[i386-shield]: https://img.shields.io/badge/i386-yes-green.svg
[commits-shield]: https://img.shields.io/github/commit-activity/y/lmagyar/homeassistant-addon-nginx-proxy.svg
[commits]: https://github.com/lmagyar/homeassistant-addon-nginx-proxy/commits/master
[github-actions-shield]: https://github.com/lmagyar/homeassistant-addon-nginx-proxy/workflows/Publish/badge.svg
[github-actions]: https://github.com/lmagyar/homeassistant-addon-nginx-proxy/actions
[installations-shield]: https://img.shields.io/badge/dynamic/json?label=reported%20installations&query=$[%27fb76f677_nginx_proxy%27].total&url=https%3A%2F%2Fanalytics.home-assistant.io%2Faddons.json
[license-shield]: https://img.shields.io/github/license/lmagyar/homeassistant-addon-nginx-proxy.svg
[licence]: https://github.com/lmagyar/homeassistant-addon-nginx-proxy/blob/master/LICENSE
[maintenance-shield]: https://img.shields.io/maintenance/yes/2023.svg
[project-stage-shield]: https://img.shields.io/badge/project%20stage-production%20ready-green.svg
[releases-shield]: https://img.shields.io/github/tag/lmagyar/homeassistant-addon-nginx-proxy.svg?label=release
[releases]: https://github.com/lmagyar/homeassistant-addon-nginx-proxy/tags
[updated-shield]: https://img.shields.io/github/last-commit/lmagyar/homeassistant-addon-nginx-proxy/master?label=updated
[updated]: https://github.com/lmagyar/homeassistant-addon-nginx-proxy/commits/master
[warning_stripe]: https://github.com/lmagyar/homeassistant-addon-nginx-proxy/raw/master/images/warning_stripe_wide.png
[official_addon]: https://github.com/home-assistant/addons/tree/master/nginx_proxy
