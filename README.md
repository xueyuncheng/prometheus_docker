# 部署监控工具

```sh
docker-compose up -d
```

本 docker-compose.yaml 文件会自动部署 prometheus, alertmanager, grafana 和

mysqld_exporter，
并预设了两条 mysql 规则，需要提供数据库的用户名和密码
