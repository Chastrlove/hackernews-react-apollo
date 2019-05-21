
## Quickstart
####0.全局安装prisma
 ```
 yarn global add prisma
 ```
####1.启动本地Prisma服务器
 ```
 cd prisma
 docker-compose up -d
 ```
你的本地Prisma服务器现在在http://localhost:4466上运行。
####2.部署Prisma API
```
prisma deploy
```
你已成功设置Prisma（并隐性生成了schema）。你现在可以开始使用Prisma client 从代码与数据库通信

####3.启动node服务器
```
yarn install
yarn start
```
