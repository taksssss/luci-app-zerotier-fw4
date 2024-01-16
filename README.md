# luci-app-zerotier

OpenWrt 23.05 正常运行

from https://downloads.immortalwrt.org/snapshots/packages/mipsel_24kc/luci/

```shell
wget --no-check-certificate https://github.com/TakcC/luci-app-zerotier/releases/download/v0/luci-app-zerotier_git-23.137.55137-42dce6a_all.ipk
wget --no-check-certificate https://github.com/TakcC/luci-app-zerotier/releases/download/v0/luci-i18n-zerotier-zh-cn_git-22.210.52708-c5136c2_all.ipk
opkg install luci-app-zerotier*.ipk luci-i18n-zerotier*.ipk --force-overwrite
```


TIPS: 可自行添加代理服务器，如

```shell
wget --no-check-certificate https://gh.api.99988866.xyz/https://github.com/TakcC/luci-app-zerotier/releases/download/v0/luci-app-zerotier_git-23.137.55137-42dce6a_all.ipk
wget --no-check-certificate https://gh.api.99988866.xyz/https://github.com/TakcC/luci-app-zerotier/releases/download/v0/luci-i18n-zerotier-zh-cn_git-22.210.52708-c5136c2_all.ipk
opkg install luci-app-zerotier*.ipk luci-i18n-zerotier*.ipk --force-overwrite
```
