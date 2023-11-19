# Hysteria2 一键安装脚本

## 安装Hysteria2
使用以下命令来安装Hysteria2:

```
wget -N --no-check-certificate https://raw.githubusercontent.com/josbu/one-hysteria2/main/hysteria.sh && bash hysteria.sh
```

## 配置私钥权限
赋予私钥读写权限：

```
chmod +rw /root/private.key
```

## Hysteria2服务管理命令
下面是一些管理Hysteria2服务的常用命令：

**启动Hysteria2**
```
systemctl start hysteria-server.service
```

**重启Hysteria2**
```
systemctl restart hysteria-server.service
```

**查看Hysteria2状态**
```
systemctl status hysteria-server.service
```

**停止Hysteria2**
```
systemctl stop hysteria-server.service
```

**设置Hysteria2开机自启**
```
systemctl enable hysteria-server.service
```

**查看Hysteria2日志**
```
journalctl -u hysteria-server.service
```
```
