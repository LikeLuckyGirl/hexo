---
title: docker
date: 2024-12-14 12:05:10
tags: docker
---
## docker基础
```
//下镜像    
docker pull 镜像名
//推镜像   
//参考阿里云的acr
//查看已下载镜像
docker images    
//启动停止的容器
docker start id/名称   
//停止容器
docker stop id/名称    
//重启容器
docker restart id/名称    
//查看容器状态
docker stats id/名称    
//查看容器运行日志
docker logs id/名称    
//进入容器
docker exec id/名称    
//删除停止容器
docker rm id/名称    
//删除容器
docker kill id/名称    
//强制删除镜像
docker rm -f 镜像名    
//创建网络段（类似局域网）
docker netwoek create 网络名    
//将启动的容器分配到特定网段
docker run --netwoek 网络名    
```

## 部署nginx
```
上传前端网页文件
//创建Dockerfile
touch  Dockerfile
//编辑Dockerfile
vim Dockerfile
//Dockerfile里的内容
# 使用 nginx 作为基础镜像
FROM nginx
# 将 HTML 文件复制到 nginx 默认的 HTML 目录下
# h5为网页文件
COPY h5 /usr/share/nginx/html/h5
//制作docker镜像 .表示在当前目录下
docker build -t 镜像名 .
//运行docker镜像 -d表示后台运行 -p端口：前要用的端口：后nginx的端口（默认80） --name起个名
docker run -d -p 8080:80 --name name1 镜像名

```

## docker部署jar
```
上传jar
//创建Dockerfile
touch  Dockerfile
//编辑Dockerfile
vim Dockerfile
//Dockerfile里的内容
FORM openjdk:jar使用jdk的版本
# 感觉用处不大可省略
MAINTAINER 作者名
# 给jar包改个名 感觉用处不大可省略
ADD 上传的jar app.jar
EXPOSE jar运行端口
# app.jar为jar包
ENTRYPOINT ["java","-jar","app.jar"]
//制作docker镜像 .表示在当前目录下
docker build -t 镜像名 .
//运行docker镜像 -d表示后台运行 -p端口：前要用的端口：后jar包运行端口） --name起个名
docker run -d -p 8080:80 --name name1 镜像名
```