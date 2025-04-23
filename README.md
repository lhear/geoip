# 简介

本项目每周四自动生成多种格式 GeoIP 文件，同时提供命令行界面（CLI）工具供用户自行定制 GeoIP 文件，包括但不限于 V2Ray `dat` 格式文件 `geoip.dat`、sing-box `SRS` 格式文件、mihomo `MRS` 格式文件、Clash ruleset 和 Surge ruleset。

## 与 MaxMind 官方 GeoIP 数据的区别

- 中国大陆 IPv4 地址数据使用了 [@misakaio/chnroutes2](https://github.com/misakaio/chnroutes2/blob/master/chnroutes.txt)
- 中国大陆 IPv6 地址数据使用了 [@gaoyifan/china-operator-ip](https://github.com/gaoyifan/china-operator-ip/blob/ip-lists/china6.txt)
  
## 下载地址与使用方法

本项目发布的所有 GeoIP 文件，请查看 [release 分支](https://github.com/lhear/geoip/tree/release)。以下是部分格式 GeoIP 文件的下载地址：

> *.sha256sum 为校验文件。

### V2Ray dat 格式文件

> 适用于 [V2Ray](https://github.com/v2fly/v2ray-core)、[Xray-core](https://github.com/XTLS/Xray-core)、[mihomo](https://github.com/MetaCubeX/mihomo/tree/Meta)、[hysteria](https://github.com/apernet/hysteria)、[Trojan-Go](https://github.com/p4gefau1t/trojan-go)。

> 此 dat 格式文件不能用于 Nginx。

- **geoip.dat**（只包含 `geoip:cn` 和 `geoip:private`）：
  - [https://raw.githubusercontent.com/lhear/geoip/release/geoip.dat](https://raw.githubusercontent.com/lhear/geoip/release/geoip.dat)
- **geoip.dat.sha256sum**：
  - [https://raw.githubusercontent.com/lhear/geoip/release/geoip.dat.sha256sum](https://raw.githubusercontent.com/lhear/geoip/release/geoip.dat.sha256sum)

## License

[CC-BY-SA-4.0](https://creativecommons.org/licenses/by-sa/4.0/) and [GPL-3.0](https://github.com/lhear/geoip/blob/master/LICENSE-GPL)
