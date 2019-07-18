# 使用说明
- **启动**：service caddy start
- **停止**：service caddy stop
- **重启**：service caddy restart
- **查看状态**：service caddy status
- **查看Caddy启动日志**： tail -f /tmp/caddy.log
- **Caddy配置文件位置**：/usr/local/caddy/Caddyfile

# 安装Caddy
```shell
wget -N --no-check-certificate https://raw.githubusercontent.com/Tyrant-2017/Caddy/master/caddy_install.sh && chmod +x caddy_install.sh && bash caddy_install.sh
```

# 卸载Caddy
```shell
wget -N --no-check-certificate https://raw.githubusercontent.com/Tyrant-2017/Caddy/master/caddy_install.sh && bash caddy_install.sh uninstall
```
