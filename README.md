# docker-compose 构建django web环境

### 下载 docker-compose.yml 等配置文件
> git clone https://github.com/JerryGaoyang/docker-django.git

### 拉取镜像并启动容器
> cd docker-python

> docker-compose up -d

### 注意
* redis 默认密码为 root
* 在 ./redis/redis.conf 搜索 requirepass root , 将 root 更改为你自己的密码

### 备注
* docker 镜像源: http://aad0405c.m.daocloud.io/
* linux下更改docker镜像源
> /etc/docker/default 
* windows下更改docker镜像源
> docker客户端setting下的Daemon
