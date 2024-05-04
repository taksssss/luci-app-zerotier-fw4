# luci-app-zerotier

OpenWrt 23.05.2 正常运行


该版本使用nftables实现客户端NAT，完美兼容Firewall4

![fw4](https://github.com/TakcC/luci-app-zerotier/assets/26397391/345205b6-5e0d-46b3-b9db-0648e0d8f6a7)


from https://downloads.immortalwrt.org/snapshots/packages/mipsel_24kc/luci/

```shell
wget --no-check-certificate https://github.com/TakcC/luci-app-zerotier/releases/download/v0.1/luci-app-zerotier_24.008.36806.3ff4845_all.ipk
wget --no-check-certificate https://github.com/TakcC/luci-app-zerotier/releases/download/v0.1/luci-i18n-zerotier-zh-cn_24.011.35710.41c4436_all.ipk
opkg install luci-app-zerotier*.ipk luci-i18n-zerotier*.ipk --force-overwrite
```


TIPS: 可自行添加代理服务器，如

```shell
wget --no-check-certificate https://gh.api.99988866.xyz/https://github.com/TakcC/luci-app-zerotier/releases/download/v0.1/luci-app-zerotier_24.008.36806.3ff4845_all.ipk
wget --no-check-certificate https://gh.api.99988866.xyz/https://github.com/TakcC/luci-app-zerotier/releases/download/v0.1/luci-i18n-zerotier-zh-cn_24.011.35710.41c4436_all.ipk
opkg install luci-app-zerotier*.ipk luci-i18n-zerotier*.ipk --force-overwrite
```
