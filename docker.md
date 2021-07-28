# docker相关的命令
1. 安装docker:
   ```
    curl -fsSL https://get.docker.com | bash -s docker --mirror Aliyun
   ```

2. docker 拉取镜像
   ```   
      docker pull mysql:latest
   ```
3. docker 运行镜像
   ```
      docker run -itd mysql --name mysqlDB -p 3306:3306
   ```
4. docker安装各软件  
   kafka:   https://blog.csdn.net/qq_41122834/article/details/108471054