A tool to auto-compile & install KCPTUN for SS/SSR on Linux
===========
##一键安装KCPTUN for SS/SSR on Linux。


##感谢[秋水逸冰](https://github.com/teddysun/shadowsocks_install)，一键安装脚本中很多代码都是从秋水的脚本中借鉴过来的，在此感谢大神们的付出。

脚本是业余爱好，英文属于文盲，写的不好，欢迎您批评指正。

已测试平台：CentOS 6/7、Debian、Ubuntu，其他平台未测试。

## 我自己也不会，哪来的教程

### 详细信息间脚本或者安装结束后看提示。

### Install
```Bash
yum -y install gcc automake autoconf libtool make unzip
```

```Bash
yum install wget
```

```Bash
wget --no-check-certificate https://raw.githubusercontent.com/floydaugus/onekey-install-shell/master/kcptun_for_ss_ssr/kcptun_for_ss_ssr-install.sh -O ./kcptun_for_ss_ssr-install.sh
chmod 700 ./kcptun_for_ss_ssr-install.sh
./kcptun_for_ss_ssr-install.sh install
```

### UnInstall
```Bash
    ./kcptun_for_ss_ssr-install.sh uninstall
```
### Update
```Bash
    ./kcptun_for_ss_ssr-install.sh update
```
