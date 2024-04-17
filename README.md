## 安装步骤

### 1. 安装docker(如果安装过，跳过此步骤)

[docker安装](https://docs.docker.com/engine/install/)

### 2. 安装docker-compose(如果安装过，跳过此步骤)

[docker compose 安装](https://docs.docker.com/compose/install/linux/#install-the-plugin-manually)

### 3. 一键启动new-api

> 注意部署包含mysql、redis 如果不需要自行注释docker-compose.yaml文件中的配置

```shell
git clone https://github.com/xiangsx/new-api-deploy.git
cd new-api-deploy
docker compose up -d
```
