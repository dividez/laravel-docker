# laravel-docker

> 这是专注于 Laravel 的 Docker 开发环境，已更换成功中国镜像源

## 使用

1. 获取 Docker 环境

```
git clone https://github.com/DestinyLuo/laravel-docker.git
```

2. 开启环境

```
docker-compose up -d nginx mysql redis
```

## yml 文件分析

- `applications` 代码码转服务，设置映射目录
- `workspace` 为操作服务，执行 compose，npm, php 命令
- 其他设置为一些基本设置不懂看语法再来看文件


