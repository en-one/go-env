# go-env

### GO 1.14.12环境<br>

DockerFile 构建命令： 
>    docker build -t godev .

镜像启动： 
>    docker run -v 文件夹:/home -it godev bash

镜像上传：

>    docker ps
>    
>    docker commit a7815314b1ce josiahzhang/go1.14.12-dev
>    
>    docker login
>    
>    docker push josiahzhang/go1.14.12-dev
