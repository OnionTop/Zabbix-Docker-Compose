# Zabbix-Docker-Compose
### 介绍
#### 开箱即用的Zabbix-6.0 LTS
#### 采用Docker compose管理部署各个组件

### 运行依赖
#### 只需要安装docker即可，目前实际使用了两个docker版本均无问题，docker 18.09.0和20.10.*，其余版本应该没有问题，欢迎测试
#### docker-compose bin文件已放在仓库中，版本中为：Docker Compose version v2.15.1

### 启动方式
```bash
# 将该仓库克隆或者下载之后，解压并进入该仓库
# 先给仓库内的docker-compose文件增加可执行权限
chmod + x ./docker-compose

# 直接启动，当启动完成后，便可访问你的主机ip或域名机可
./docker-compose up -d
```
