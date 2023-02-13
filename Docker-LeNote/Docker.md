桌面版在 https://www.docker.com/
服务器版 https://docs.docker.com

|镜像|地址|
|:---|:---|
|1.Docker中国区官方镜像|https://registry.docker-cn.com
|2.网易|http://hub-mirror.c.163.com
|3.ustc |https://docker.mirrors.ustc.edu.cn
|4.中国科技大学|https://docker.mirrors.ustc.edu.cn

docker镜像：hub.docker.com

* docker run --fn date
  有关 run命令的运行参数文档：https://docs.docker.com/engine/reference/commandline/run/

  --p xxxx:8080 把container的8080暴露容器到宿主机的xxxx端口

  在浏览器输入 localhost:xxxx 访问web端口的数据

  -v 目录路径  挂载目录，实现containter与宿主机的实时交互
docker build --fn date



shift + 右键与当前目录打开Shell