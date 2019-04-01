# 基于ubuntu

## 注册地址 (最好是国内的邮箱,我用的是QQ邮箱)

[注册地址](https://www.vultr.com/?ref=7999972)

## 安装Shadowsocks 的命令

### 复制粘贴第一步

```
wget --no-check-certificate -O shadowsocks.sh https://raw.githubusercontent.com/teddysun/shadowsocks_install/master/shadowsocks.sh
```
### 复制粘贴第二步

```
chmod +x shadowsocks.sh
```


### 复制粘贴第三步

```
./shadowsocks.sh 2>&1 | tee shadowsocks.log
```

## 安装 Google 开源 BBR 拥塞控制算法命令 (由于 ubuntu 18.04内核已经集成了 BBR,这个命令也只是开启一下)

```
wget --no-check-certificate https://github.com/teddysun/across/raw/master/bbr.sh && chmod +x bbr.sh && ./bbr.sh
```

## shadowsocks 客户端下载地址

[Mac 版本下载链接](https://github.com/shadowsocks/shadowsocks-windows/releases/download/4.0.10/Shadowsocks-4.0.10.zip "Mac 版本下载链接")

[windows 版本下载链接](https://github.com/shadowsocks/shadowsocks-windows/releases/download/4.0.10/Shadowsocks-4.0.10.zip "windows 版本下载链接")

[安卓版本下载链接](https://github.com/shadowsocks/shadowsocks-android/releases)

[iOS 版本下载链接(使用的是 Potatso Lite)](https://itunes.apple.com/app/id1239860606?mt=8)
