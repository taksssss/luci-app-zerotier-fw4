# luci-app-zerotier

OpenWrt 23.05 正常运行

form https://downloads.immortalwrt.org/snapshots/packages/mipsel_24kc/luci/

```shell
wget --no-check-certificate https://gh-proxy.com/https://github.com/TakcC/luci-app-zerotier/releases/download/v0/luci-app-zerotier_git-23.137.55137-42dce6a_all.ipk
wget --no-check-certificate https://gh-proxy.com/https://github.com/TakcC/luci-app-zerotier/releases/download/v0/luci-i18n-zerotier-zh-cn_git-22.210.52708-c5136c2_all.ipk
opkg install luci-app-zerotier*.ipk luci-i18n-zerotier*.ipk
```

如果提示`wants to install file /etc/init.d/zerotier But that file is already provided by package  * zerotier`

先执行`rm /etc/init.d/zerotier`再重新安装。
