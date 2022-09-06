# JSON API data source for Grafana

[![Build](https://github.com/marcusolsson/grafana-json-datasource/workflows/CI/badge.svg)](https://github.com/marcusolsson/grafana-json-datasource/actions?query=workflow%3A%22CI%22)
[![Release](https://github.com/marcusolsson/grafana-json-datasource/workflows/Release/badge.svg)](https://github.com/marcusolsson/grafana-json-datasource/actions?query=workflow%3ARelease)
[![Marketplace](https://img.shields.io/badge/dynamic/json?logo=grafana&color=F47A20&label=marketplace&prefix=v&query=%24.items%5B%3F%28%40.slug%20%3D%3D%20%22marcusolsson-json-datasource%22%29%5D.version&url=https%3A%2F%2Fgrafana.com%2Fapi%2Fplugins)](https://grafana.com/grafana/plugins/marcusolsson-json-datasource)
[![Downloads](https://img.shields.io/badge/dynamic/json?logo=grafana&color=F47A20&label=downloads&query=%24.items%5B%3F%28%40.slug%20%3D%3D%20%22marcusolsson-json-datasource%22%29%5D.downloads&url=https%3A%2F%2Fgrafana.com%2Fapi%2Fplugins)](https://grafana.com/grafana/plugins/marcusolsson-json-datasource)
[![License](https://img.shields.io/github/license/marcusolsson/grafana-json-datasource)](LICENSE)
[![Twitter](https://img.shields.io/twitter/follow/marcusolsson?color=%231DA1F2&label=twitter&style=plastic)](https://twitter.com/marcusolsson)

> **Maintenance**: As I'm no longer working at Grafana Labs, nor am I using Grafana where I'm at now, **I've decided to no longer maintain this plugin**. Instead, consider using the [Infinity](https://grafana.com/grafana/plugins/yesoreyeram-infinity-datasource/) data source.

A data source plugin for loading JSON APIs into [Grafana](https://grafana.com) using [JSONPath](https://goessner.net/articles/JsonPath/).

![Screenshot](https://github.com/marcusolsson/grafana-json-datasource/raw/main/src/img/dark.png)

## Documentation

Full documentation for the plugin is available on the [website](https://marcusolsson.github.io/grafana-json-datasource).

## Maintenance

I maintain [several plugins](https://marcus.se.net/projects/) for Grafana. While my employer allows me to spend some time on developing plugins, most of the work happens on evenings and weekends. At the moment, I'm prioritizing fixing bugs and reviewing PRs over introducing new features.

If you'd still like to propose a new feature, [create a new Discussion](https://github.com/marcusolsson/grafana-json-datasource/discussions/new?category=ideas). While I likely won't be able to work on features myself, I'd be happy to accept pull requests. If you'd like to contribute a feature, please let me know before you start working on it.
