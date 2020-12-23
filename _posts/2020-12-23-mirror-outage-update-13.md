---
layout: post
title: 镜像服务故障 - 更新
action: incident-error
date: 2020-12-23 13:35:00 +0800
tags: [mirror]
---

由于镜像服务存储异常，目前北理工开源镜像站无法正常对内外网提供 HTTP、HTTPS、RSYNC 服务。

目前，有关部门老师正在处理故障中，我们已将部分热门镜像的 HTTP 服务 302 跳转至 mirrors.bfsu.edu.cn
（校内 IPv4 用户会跳转至 mirrors6.bfsu.edu.cn 以确保不被计费，如您的网络没有 IPv6 连接，则您将暂时无法使用本站镜像服务）。
如您有需要使用其它项目镜像，欢迎您在 [GitHub issue](https://github.com/BITNP/issues/issues/27) 留言，我们会尽快设置跳转。
