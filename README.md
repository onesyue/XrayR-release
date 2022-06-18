# XRayR
A Xray backend framework that can easily support many panels.

一个基于Xray的后端框架，支持V2ay,Trojan,Shadowsocks协议，极易扩展，支持多面板对接

# 详细使用教程

[教程](https://crackair.gitbook.io/xrayr-project/)

```
# Docker 安装 && Docker compose 安装
```
1. `git clone https://github.com/onesyue/XrayR-release`
2. `cd XrayR-release`
3. 编辑config。
配置文件基本格式如下，Nodes下可以同时添加多个面板，多个节点配置信息，只需添加相同格式的Nodes item即可。
4. 启动docker：`docker-compose up -d`
```
