# ansible

## 架构思想

[基于 Docker Swarm 项目部署架构](https://www.yuque.com/where/dib969/bg1cff)  

## 如何使用

```bash
git clone https://github.com/liuzhaowei55/ansible --depth=1  
cd ./ansible  
# 初始化服务器为 docker swarm manager  
ansible-playbook docker-swarm-manager-initialization.yml -e target_hosts=your_remote_server -e private_ip=your_server_private_ip  

# 初始化服务器为 docker swarm worker  
ansible-playbook docker-swarm-manager-initialization.yml -e target_hosts=your_remote_server  
```