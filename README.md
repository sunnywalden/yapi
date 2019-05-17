# yapi v1.7.0
yapi v1.7.0 docker image

## description
Yapi v1.7.0 image



## deploy

1.start your mongo docker

2.init data

3.start your yapi docker run -d --name yapi --link mongo-yapi:mongo -v /data/yapi/config.json:/api/config.json --workdir /api/vendors -p 3000:3000 sunnywalden/yapi-1.7.0:latest server/app.js

## Thanks
thanks for Anoyi's instruction for build yapi image.
[使用 alpine 版 docker 镜像快速部署 yapi] (https://www.jianshu.com/p/a97d2efb23c5)
