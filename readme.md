# ctfs_docker repository description
## 1. why docker
When ctf server is down, all web and pwn challenge we cannot enjoy again. So, there's this repository.
We repeated challenge in the server before so that we can only share the source code. It's too troublesome, so we use docker.

ctf比赛中，官网一下线，web和pwn题型就做不了了。
以往我们复现题目都是复现在服务器上，想要共享的话只能共享源码，其他还得配置，太麻烦了。因此我们使用docker。

## 2. how to use ctfs_docker
### 2.1 get docker
[There's a tutorial for non-technical users who are interested in learning more about Docker.](https://docs.docker.com/engine/getstarted/)
### 2.2 pull image
Setup local environment of the challenge by pulling image. For examle, we build the environment of **seccon2016_web_biscuiti**.You can see all files at [linked github repository](https://github.com/ssst0n3/ctfs_docker/tree/master/seccon2016/web/docker_biscuiti)

## 3. ctfs collected
### 3.1 seccon2016
* web, crypto/biscuiti
