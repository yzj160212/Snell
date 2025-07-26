### 一键snell（仅支持debian系统）
```
bash <(curl -fsSL snell-yy.vercel.app)
```

## 常用指令

| 命令                                     | 说明               |
|------------------------------------------|--------------------|
| `sudo systemctl stop snell`              | 停止 Snell 服务     |
| `sudo systemctl start snell`             | 启动 Snell 服务     |
| `sudo systemctl restart snell`           | 重启 Snell 状态     |
| `sudo systemctl status snell`            | 查看 Snell 服务     |
| `sudo journalctl -u snell.service -f`    | 查看 Snell 日志     |
| `sudo cat /etc/snell/snell-server.conf`  | 查看 Snell 配置     |
| `sudo vim /etc/snell/snell-server.conf`  | 修改 Snell 配置     |