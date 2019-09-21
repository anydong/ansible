# Ansible - 服务器初始化代码（适用于 Aliyun CentOS 7.6）

## 初始化内容

* 设置时区为 `Asia/Shanghai`
* 更新 `yum`
* 安装常用软件
  * vim
  * wget
  * mosh
  * git
  * screen 
  * python
  * pip
  * acme.sh
  * docker
  * docker-compose
* 配置 Dotfile
  * .inputrc
  * .vimrc

## 额外配置
* Mosh - [介绍](https://mosh.org/)
  `Mosh will log the user in via SSH, then start a connection on a UDP port between 60000 and 61000.`