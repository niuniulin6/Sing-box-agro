# 一键命令，已集成到ssh工具箱中
* 一键四协议安装脚本，支持纯v6，支持订阅，默认解锁GPT和奈飞
* 最好用的四协议组合vless-reality|vmess-ws-tls(argo)|hysteria2|tuic5
* 支持的系统：Ubuntu/Debian/CentOS/Alpine/Fedora/Rocky/Almalinux/kail
* 注意nat小鸡安装完一键脚本之后需手动更改订阅端口和节点端口在允许范围内的端口，否则节点不通
* 在脚本前添加PORT变量，随脚本一起运行，即可定义端口，需确保PORT端口后面的3个端口可用，否则节点不通
* 端口示例：VMESS_PORT=tcp端口 HY2_PORT=udp端口 TUIC_PORT=udp端口 

# 一键四协议安装脚本
```
bash <(curl -Ls https://raw.githubusercontent.com/niuniulin6/Sing-box-agro/main/sing-box.sh)
```
