# 多服务集群发布

1. 配置docker-compose.yml，新添加docker可视化管理服务

2. 初始化 `docker swarm init`

3. 发布服务 `docker stack deploy -c docker-compose.yml muyu-demo-docker-stack`

4. 查看服务 `docker stack ps muyu-demo-docker-stack`

5. 删除服务 `docker stack rm muyu-demo-docker-stack`

6. 删除swarm集群节点 `docker swarm leave --force`

## 提示：docker --help
