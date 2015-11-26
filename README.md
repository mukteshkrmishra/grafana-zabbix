Grafana-Zabbix [![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/alexanderzobnin/grafana-zabbix?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)
==============

###### Zabbix datasource for Grafana dashboard

- Touch a [live demo](http://play.grafana-zabbix.org)
- Download [latest release](https://github.com/alexanderzobnin/grafana-zabbix/releases/latest)
- [Install](https://github.com/alexanderzobnin/grafana-zabbix/wiki/Installation#grafana-21x-and-25x) datasource
- [RTFM](https://github.com/alexanderzobnin/grafana-zabbix/wiki) (read the docs)
- [Donate](https://www.paypal.me/alexanderzobnin)

Display your Zabbix data directly at [Grafana](http://grafana.org) dashboards!

![Dashboard](https://cloud.githubusercontent.com/assets/4932851/8269101/9e6ee67e-17a3-11e5-85de-fe9dcc2dd375.png)

Features
--------

#### Flexible metric editor
Select multiple graphs by one query. Use power of regex and filter hosts and items.
 
[![regex_filter](https://cloud.githubusercontent.com/assets/4932851/8312766/5eb34480-19e7-11e5-925f-452a99ec0ab6.gif)](https://cloud.githubusercontent.com/assets/4932851/8312766/5eb34480-19e7-11e5-925f-452a99ec0ab6.gif)

 * Custom scale for each target:

![Scale](https://cloud.githubusercontent.com/assets/4932851/8269207/212549be-17a9-11e5-9e33-90deb90ddc13.png)

#### Templated dashboards support
Group, host, application or item names can be replaced with a template variable. This allows you to create generic dashboards that can quickly be changed to show stats for a specific cluster, server or application.

[![templated_dashboard](https://cloud.githubusercontent.com/assets/4932851/8312492/7f286c38-19e5-11e5-8c19-1b9e97292b06.gif)](https://cloud.githubusercontent.com/assets/4932851/8312492/7f286c38-19e5-11e5-8c19-1b9e97292b06.gif)

#### Annotations support
 * Display zabbix events on graphs:
![Annotations](https://cloud.githubusercontent.com/assets/4932851/8269358/622ec3be-17ad-11e5-8023-eba137369cfe.png)
 * Show acknowledges for problems:  
![Acknowledges](https://cloud.githubusercontent.com/assets/4932851/8269375/e6d8706a-17ad-11e5-8e2d-2d707d8ee67f.png)

Read more about Grafana features at [grafana.org](http://grafana.org)
