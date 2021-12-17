# 使用Heroku部署Xray高性能代理服务，通过ws传输的 (vmess、vless、trojan shadowsocks、socks)等协议

## 概述

用于在 Heroku 上部署 vless+websocket+tls，每次部署自动选择最新的 alpine linux 和 Xray core 。  
vless 性能更加优秀，占用资源更少。

