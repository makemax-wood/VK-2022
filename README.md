# VK

## 概述

用于在 Hk。

**Hek 为我们提供了免费的容器服务，我们不应该滥用它，所以本项目不宜做为长期k使用。**

**可以部署两个以上的应用，实现 [负载均衡](https://toutyrater.github.io/routing/balance2.html)，避免长时间大流量连接某一应用而被k定为滥用。**

**Heroku 的网络并不稳定，部署前请三思。**

## 镜像

本镜像不会因为大量占用资源而被封号。

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://dashboard.heroku.com/new?template=https%3A%2F%2Fgithub.com%2Fbclswl0827%2Fv2ray-heroku)

## ENV 设定

### UUID

`UUID` > `一个 UUID，供用户连接时验证身份使用`。

## 节点优选IP工具

 [下载地址](https://chenhun.lanzous.com/b01o8y1sh)


WebSocket 路径为 `/`。

`alterId` 为 `64`。

V 将在部署时自动安装最新版本。

**出于安全考量，除非使用 CDN，否则请不要使用自定义域名，而使用 H分配的二级域名，以实现 V2Websocket + TLS。**

## CF代脚本
地址  https://chenhun88.com
 [在线预览](https://drive.google.com/file/d/1DVKOxQQBJBNAmCDb0exkVTUQUdHyHHCz/view?usp=sharing)

