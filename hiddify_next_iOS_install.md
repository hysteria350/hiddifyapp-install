# HiddifyApp (iOS) 安装与配置

## **⓿ 前置条件**

> 先进行 [**订阅购买**](https://vip02.stableconnect.cloud/#/plan) ，获取到订阅地址。订阅链接位于：仪表盘 > 一键订阅 , 然后复制订阅地址或者扫描二维码订阅。

## **❶ 客户端概述**

> HiddifyApp 是一款基于Sing-Box，旨在帮助互联网审查地区的用户自由享受互联网服务。Hiddify Next 支持 20 多种协议，可在所有平台操作系统上运行。它是一个开源、安全且无广告的项目，旨在提供功能强大、用户友好的客户端，允许用户连接到他们购买的节点服务器。本文将详细介绍如何配置 Hiddify Next Android 应用程序（iOS 具有类似的 UI）。

## **❷ 客户端下载**

> 点击下方按钮下载 v2.0.5 版本

[__**点击从这里下载**__](https://ghfast.top/https://github.com/hiddify/hiddify-next/releases/latest/download/Hiddify-iOS.ipa)

或者从 [![Download on the App Store](data:image/svg+xml;base64,CjxzdmcgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB3aWR0aD0iMjAwIiBoZWlnaHQ9IjYwIiB2aWV3Qm94PSIwIDAgNTEyIDE1MCI+CiAgPHJlY3Qgd2lkdGg9IjUxMiIgaGVpZ2h0PSIxNTAiIHJ4PSIyMCIgZmlsbD0iIzAwMCIvPgogIDx0ZXh0IHg9IjkwIiB5PSI5MCIgZm9udC1zaXplPSI1MCIgZmlsbD0iI2ZmZiIgZm9udC1mYW1pbHk9IkFyaWFsLCBzYW5zLXNlcmlmIj5BcHAgU3RvcmU8L3RleHQ+CiAgPGNpcmNsZSBjeD0iNTAiIGN5PSI3NSIgcj0iMzAiIGZpbGw9IiNmZmYiLz4KICA8cGF0aCBkPSJNNDUgNzUgTDU1IDc1IEw1MCA2MCBaIiBmaWxsPSIjMDAwIi8+Cjwvc3ZnPg==)](https://apps.apple.com/us/app/hiddify-proxy-vpn/id6596777532?platform=iphone) 下载

> （其他版本请访问 官方 [GithHub](https://github.com/hiddify/hiddify-app/releases/) 下载）

## **❸ 配置 Hiddify Next**

> 1.  回到Hiddify App**主页**,
> 
> 点击“New Profile”并导入您的订阅链接。 2. 将以下选项复制, 打开配置选项，选择从剪贴板导入选项

```plaintext
{
  "region": "cn",
  "block-ads": false,
  "use-xray-core-when-possible": false,
  "execute-config-as-is": false,
  "log-level": "warn",
  "resolve-destination": true,
  "ipv6-mode": "prefer_ipv4",
  "remote-dns-address": "udp://1.1.1.1",
  "remote-dns-domain-strategy": "",
  "direct-dns-address": "223.5.5.5",
  "direct-dns-domain-strategy": "",
  "mixed-port": 12334,
  "tproxy-port": 12335,
  "local-dns-port": 16450,
  "tun-implementation": "system",
  "mtu": 9000,
  "strict-route": true,
  "connection-test-url": "http://cp.cloudflare.com",
  "url-test-interval": 1080,
  "enable-clash-api": true,
  "clash-api-port": 16756,
  "enable-tun": false,
  "enable-tun-service": false,
  "set-system-proxy": true,
  "bypass-lan": false,
  "allow-connection-from-lan": false,
  "enable-fake-dns": false,
  "enable-dns-routing": true,
  "independent-dns-cache": true,
  "rules": [],
  "mux": {
    "enable": false,
    "padding": false,
    "max-streams": 8,
    "protocol": "h2mux"
  },
  "tls-tricks": {
    "enable-fragment": false,
    "fragment-size": "10-30",
    "fragment-sleep": "2-8",
    "mixed-sni-case": false,
    "enable-padding": false,
    "padding-size": "1-1500"
  },
  "warp": {
    "enable": false,
    "mode": "proxy_over_warp",
    "clean-ip": "auto",
    "clean-port": 0,
    "noise": "1-3",
    "noise-size": "10-30",
    "noise-delay": "10-30",
    "noise-mode": "m4"
  },
  "warp2": {
    "enable": false,
    "mode": "proxy_over_warp",
    "clean-ip": "auto",
    "clean-port": 0,
    "noise": "1-3",
    "noise-size": "10-30",
    "noise-delay": "10-30",
    "noise-mode": "m4"
  }
}
```

## **❹ 开始使用**

> 回到软件**主页**，即可看到已经导入的订阅链接，点击下方的 “Tap to Connect”， 选择节点，即可开始使用。
> 
> 您可在软件的 **代理** 页面看到所有的节点，可通过点击对应的节点进行上网
> 
> **建议您选择 香港、 新加坡、日本等亚洲节点，速度快**
