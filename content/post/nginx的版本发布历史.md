---
author: "shadow"
date: 2019-12-19
title: "nginx版本发布年线"
tags: [
    "nginx"
]
categories: [
    "nginx"
]
---

### 版本发布年线
- nginx从2002年开始开发。

- 2004年10月4号，nginx发布第一个版本，0.1.0版本。

- 2005年，nginx做过一次大的重构， 重构了http反向代理，此后nginx的架构设计没有再发生过大的变动。

- 2009年发布的0.7.52版本开始支持windows系统。

- 2011年，nginx1.0版本发布，支持上游keepalive http长连接。同年，nginx商业公司Nginx Plus成立。

- 2013年，支持websocket、TFO等协议。

- 2015年，支持thread pool，提供stream四层反向代理，支持reuseport特性，支持httpv2协议。

- 2016年，支持动态模块。

- 2018年支持TLSv1.3。

### 版本发布特点
nginx版本发布有mainline主干版本和stable稳定版本两种。

通常，单数版本为主线版本（如1.15.12），双数版本为稳定版本（如1.16.0）。

主干版本会新增很多功能，但这些功能不一定稳定 。

nginx的版本发布日志通常包括五种类型Feature、Bugfix、Change、Workaround、Security。

- Feature表示新增了哪些功能。

- Bugfix 表示修复了哪些bug。

- Change表示做了哪些小的重构。

- Workaround表示一些潜在问题的描述及解决方案。

- Security表示一些特性在特定场景下可能会导致比较严重后果，如内存溢出、内存泄漏等。
