# Windows 上安装与配置 HiddifyApp

## **⓿ 前置条件**

> 先进行 [**订阅购买**](https://github.com/proxyguide/jichang-recommend) ，获取到订阅地址。订阅链接位于：仪表盘 > 一键订阅 , 然后复制订阅地址或者扫描二维码订阅。

## **❶ 客户端概述**

> Hiddify Next 是一个基于 Sing-box 的跨平台自动客户端，用作通用代理工具链。它提供了丰富的功能，支持多种协议，是一个免费、无广告且开源的应用，旨在为用户提供安全且私密的互联网访问工具。

## **❷ 客户端下载**

> 点击下方按钮下载 v2.5.7 版本

[__**点击下载**__](https://ghfast.top/https://github.com/hiddify/hiddify-app/releases/latest/download/Hiddify-Windows-Setup-x64.Msix)

> （其他版本请访问 官方 [GithHub](https://github.com/hiddify/hiddify-app/releases/) 下载）

## **❸ 配置 Hiddify Next**

> 1.  完成下载并安装后双击软件图标打开HiddifyApp
>     
> 2.  选择语言为中文，区域为 **中国**（别选错）
>     
> 3.  导入订阅
>     
>     方法一：自动识别剪贴板中的 URL
>     
>     ```plaintext
>     复制好订阅链接，打开 HiddifyApp，App 会自动识别并提示导入。
>     
>     点击“导入”即可。
>     ```
>     
>     方法二：手动粘贴导入
>     
>     ```plaintext
>     在 HiddifyApp 首页点击 ➕（添加配置）
>     
>     粘贴您的订阅链接，命名，点击“导入”。
>     ```
>     
> 4.  将以下选项复制, 打开配置选项，选择从剪贴板导入选项
>     

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

> 回到软件**主页**，即可看到已经导入的订阅链接，点击下方的 **点击连接**，即可开始使用。
> 
> 您可在软件的 **代理** 页面看到所有的节点，可通过点击对应的节点进行上网
> 
> **建议您选择 香港、 新加坡、日本等亚洲节点，速度较快**
