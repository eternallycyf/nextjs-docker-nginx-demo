
## 本地运行
yarn dev

## 本地打包
yarn build

## 服务器部署
```js
# 1.使用sftp将除了node_modules的文件放在服务器 例如 ./home/blog
scp -r nextjs-docker-nginx-demo root@服务器地址:/home/blog/

# 2
# 2.1 在 ./home/blog 根目录运行
ssh 'root@服务器地址'  
cd /home/blog/nextjs-docker-nginx-demo
docker-compose up -d
# 2.2 停止命令 
docker-compose down 
```
