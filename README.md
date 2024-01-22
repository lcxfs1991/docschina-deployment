# docschina-deployment

## 构建镜像
docker build . -t rollupjs.org:0.0.1

## 推送镜像
docker tag [imageId] ccr.ccs.tencentyun.com/docschina/rollupjs.org:[tag]

docker push ccr.ccs.tencentyun.com/docschina/rollupjs.org:[tag]
