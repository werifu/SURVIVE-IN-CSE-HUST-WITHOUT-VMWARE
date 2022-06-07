# Docker

容器，可以理解为很轻量级的、与外界隔离的操作系统环境。

在计网安全课程使用到的**SeedUbuntu**中，只是在里面Docker组建子网，有没有外面这个虚拟机并不重要。

部分靶机环境也能使用Docker构建

## 优点/解决的问题：

1. 解放对SeedLab提供的SeedUbuntu虚拟机的依赖
2. 提供部分靶机环境（如metaspoitable）

## 指南

### 前情提要

这不是Docker教程，请自行上网学习Docker的基本使用

### SeedUbuntu

实际上大三做的那些SeedUbuntu系列实验都是源自国外的[SeedLab](https://seedsecuritylabs.org/)，SeedLab提供了一套Docker镜像的实验环境，使用Docker就可以不用每次都下老师给的SeedUbuntu了。

[SeedLab的Docker文档](https://github.com/seed-labs/seed-labs/blob/master/manuals/docker/SEEDManual-Container.md)

DockerHub就有SeedUbuntu的镜像，只需要以下命令就能下载

```bash
docker pull handsonsecurity/seed-ubuntu
```

### metasploitable靶机

Docker也能提供metasploitable靶机环境。

以下命令可以下载到镜像

```bash
docker pull tleemcjr/metasploitable2
```

可以参考以下博客：

[Unbuntu下用docker搭一个肉鸡（Metasploitable）来练靶(渗透测试)](https://www.jianshu.com/p/8c4d6fae5ad0)

### Kali in Docker

kali也可以在容器里跑，参考下面视频

[（油管）SetUp Kali and Metasploitable2 on Docker Containers](https://www.youtube.com/watch?v=QinRdVCDg-k)
