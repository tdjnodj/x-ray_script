# Xray-script

原作者:misaka

Xray一键安装脚本，支持自动生成伪装站，支持和宝塔面板共存，支持IPv4、IPv6 VPS

由于纯IPv6 VPS不支持GitHub的访问，所以安装之前请先设置DNS64服务器或安装WARP脚本

使用说明：https://owo.misaka.rest/xray-script/

如对脚本不放心，可使用此沙箱先测一遍再使用：https://killercoda.com/playgrounds/scenario/ubuntu

近期待更新：内置分流规则，支持IPv4，IPv6和Socks5 WARP分流

## 使用方法

```shell
wget -N --no-check-certificate https://raw.githubusercontent.com/tdjnodj/x-ray_script/dev/xray.sh && bash xray.sh
```

快捷方式 `bash xray.sh`

## 支持协议

* Xray-VMESS
* Xray-VMESS+mKCP
* Xray-VMESS+TCP+TLS
* Xray-VMESS+WS+TLS(可过cdn)
* Xray-VLESS+mKCP
* Xray-VLESS+TCP+TLS
* Xray-VLESS+WS+TLS(可过cdn)
* Xray-VLESS+TCP+XTLS
* Trojan
* Trojan+XTLS

## 鸣谢

感谢网络跳越提供的源码及开放许可

## 交流

[Telegram 群组](https://t.me/misakanetcn)

## Stars 增长记录

[![Stargazers over time](https://starchart.cc/Misaka-blog/Xray-script.svg)](https://starchart.cc/Misaka-blog/Xray-script)
