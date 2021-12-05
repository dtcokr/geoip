# 简介

本项目每周四自动生成 GeoIP 文件，同时提供命令行界面（CLI）供用户自行定制 GeoIP 文件，包括但不限于 V2Ray dat 格式路由规则文件 `geoip.dat` 和 MaxMind mmdb 格式文件 `Country.mmdb`。

## 与官方版 GeoIP 的区别

- 中国大陆 IPv4 地址数据使用 [IPIP.net](https://github.com/17mon/china_ip_list/blob/master/china_ip_list.txt)
- 新增类别（方便有特殊需求的用户使用）：
  - `geoip:cloudflare`（`GEOIP,CLOUDFLARE`）
  - `geoip:cloudfront`（`GEOIP,CLOUDFRONT`）
  - `geoip:facebook`（`GEOIP,FACEBOOK`）
  - `geoip:fastly`（`GEOIP,FASTLY`）
  - `geoip:google`（`GEOIP,GOOGLE`）
  - `geoip:netflix`（`GEOIP,NETFLIX`）
  - `geoip:telegram`（`GEOIP,TELEGRAM`）
  - `geoip:twitter`（`GEOIP,TWITTER`）

## 下载地址

> *.sha256sum 为校验文件。

### V2Ray dat 格式路由规则文件

- **geoip.dat**：
  - [https://raw.githubusercontent.com/dtcokr/geoip/release/geoip.dat](https://raw.githubusercontent.com/dtcokr/geoip/release/geoip.dat)

- **geoip.dat.sha256sum**：
  - [https://raw.githubusercontent.com/dtcokr/geoip/release/geoip.dat.sha256sum](https://raw.githubusercontent.com/dtcokr/geoip/release/geoip.dat.sha256sum)

- **geoip-only-cn-private.dat**（精简版 GeoIP，只包含 `geoip:cn` 和 `geoip:private`）：
  - [https://raw.githubusercontent.com/dtcokr/geoip/release/geoip-only-cn-private.dat](https://raw.githubusercontent.com/dtcokr/geoip/release/geoip-only-cn-private.dat)

- **geoip-only-cn-private.dat.sha256sum**：
  - [https://raw.githubusercontent.com/dtcokr/geoip/release/geoip-only-cn-private.dat.sha256sum](https://raw.githubusercontent.com/dtcokr/geoip/release/geoip-only-cn-private.dat.sha256sum)

- **geoip-asn.dat**（精简版 GeoIP，只包含上述新增类别）：
  - [https://raw.githubusercontent.com/dtcokr/geoip/release/geoip-asn.dat](https://raw.githubusercontent.com/dtcokr/geoip/release/geoip-asn.dat)

- **geoip-asn.dat.sha256sum**：
  - [https://raw.githubusercontent.com/dtcokr/geoip/release/geoip-asn.dat.sha256sum](https://raw.githubusercontent.com/dtcokr/geoip/release/geoip-asn.dat.sha256sum)

- **cn.dat**（精简版 GeoIP，只包含 `geoip:cn`）：
  - [https://raw.githubusercontent.com/dtcokr/geoip/release/cn.dat](https://raw.githubusercontent.com/dtcokr/geoip/release/cn.dat)

- **cn.dat.sha256sum**：
  - [https://raw.githubusercontent.com/dtcokr/geoip/release/cn.dat.sha256sum](https://raw.githubusercontent.com/dtcokr/geoip/release/cn.dat.sha256sum)

- **private.dat**（精简版 GeoIP，只包含 `geoip:private`）：
  - [https://raw.githubusercontent.com/dtcokr/geoip/release/private.dat](https://raw.githubusercontent.com/dtcokr/geoip/release/private.dat)

- **private.dat.sha256sum**：
  - [https://raw.githubusercontent.com/dtcokr/geoip/release/private.dat.sha256sum](https://raw.githubusercontent.com/dtcokr/geoip/release/private.dat.sha256sum)

### MaxMind mmdb 格式文件

- **Country.mmdb**：
  - [https://raw.githubusercontent.com/dtcokr/geoip/release/Country.mmdb](https://raw.githubusercontent.com/dtcokr/geoip/release/Country.mmdb)

- **Country.mmdb.sha256sum**：
  - [https://raw.githubusercontent.com/dtcokr/geoip/release/Country.mmdb.sha256sum](https://raw.githubusercontent.com/dtcokr/geoip/release/Country.mmdb.sha256sum)

- **Country-only-cn-private.mmdb**（精简版 GeoIP，只包含 `GEOIP,CN` 和 `GEOIP,PRIVATE`）：
  - [https://raw.githubusercontent.com/dtcokr/geoip/release/Country-only-cn-private.mmdb](https://raw.githubusercontent.com/dtcokr/geoip/release/Country-only-cn-private.mmdb)

- **Country-only-cn-private.mmdb.sha256sum**：
  - [https://raw.githubusercontent.com/dtcokr/geoip/release/Country-only-cn-private.mmdb.sha256sum](https://raw.githubusercontent.com/dtcokr/geoip/release/Country-only-cn-private.mmdb.sha256sum)

## License

[CC-BY-SA-4.0](https://creativecommons.org/licenses/by-sa/4.0/)

This product includes GeoLite2 data created by MaxMind, available from [MaxMind](http://www.maxmind.com).
