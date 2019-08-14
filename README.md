# Awesome Tsuru [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[<img src="./tsuru.png" align="right" width="150">](https://tsuru.io/)

> Curated extensions and resources for Tsuru, the open source, extensible and Docker-based PaaS

A curated list of plugins, services, routers, platforms and learning resources for Tsuru.


## Contents

- [Extensions](#extensions)
  - [Platforms](#platforms)
  - [Plugins](#plugins)
  - [Routers](#routers)
  - [Services](#services)
- [Resources](#resources)
  - [Articles](#articles)
  - [Documentation](#documentation)
  - [Podcasts](#podcasts)
  - [Videos](#videos)


## Extensions

### Platforms

- [base-platform](https://github.com/tsuru/base-platform) ([docker image](https://hub.docker.com/r/tsuru/base-platform/))
- [official platforms](https://github.com/tsuru/platforms) (go, java, nodejs, python, ruby etc)

### Plugins

- [tsuru-bluegreen](https://github.com/emerleite/tsuru-bluegreen) - A blue-green deployment plugin for tsuru client
- [app-address](https://github.com/scorphus/tsuru-plugins/blob/master/app-address) - Display all the addresses of a given app
- [env-list](https://github.com/scorphus/tsuru-plugins/blob/master/env-list) - List environment variables of an app, including private ones
- [goreplay](https://github.com/scorphus/tsuru-plugins/blob/master/goreplay) - Sniff the network interface and replay requests on another app
- [admtools](https://github.com/tsuru/admtools) - Debugging tools for apps running in tsuru.

### Routers

- [planb](https://github.com/tsuru/planb)

### Services

- [rpaas](https://github.com/tsuru/rpaas) - Reverse Proxy as a Service
- [healthcheck-as-a-service](https://github.com/tsuru/healthcheck-as-a-service) - tsuru service API for on demand web application monitoring
- [autoscale](https://github.com/tsuru/tsuru-autoscale) - Autoscale as a service

### Components

- [tsuru-dashboard](https://github.com/tsuru/tsuru-dashboard) - The dashboard provides interesting features for both tsuru users (application information, metrics and logs for example) and tsuru admins (hosts metrics, healings and much more).

## Resources

### Articles

- [Running tsuru in production: scaling and segregating Docker containers](https://blog.tsuru.io/running-tsuru-in-production-scaling-and-segregating-docker-containers-d55f99c1603e)
- [Tsuru PaaS on Google Cloud Platform](https://blog.tsuru.io/tsuru-paas-on-google-cloud-platform-21640abb4386)

### Documentation

- [tsuru documentation](https://docs.tsuru.io/stable/) - official documentation
- [tsuru-client documentation](https://tsuru-client.readthedocs.io/en/latest/) - tsuru CLI official documentation

### Videos

- [Tsuru PaaS - Service industrialization at scale](https://www.youtube.com/watch?v=GiMsS0vGmn4) (English)
- [Tsuru: Serve it yourself](https://www.youtube.com/watch?v=jBRjb6-DIsA&t) (English)
- [Microservicios con Tsuru, un PaaS extensible y open source](https://www.youtube.com/watch?v=ZLHptOpWw2I) (Spanish)
- [Tsuru Live Code](https://www.youtube.com/watch?v=dC79RpifEQI) (Portuguese)


## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, Rafael Eyng has waived all copyright and
related or neighboring rights to this work.
