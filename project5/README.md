# FINAL PROJECT: Docker

引言: 恭喜你来到了最后一步, 完成了这个项目, 那么我向你保证入门 course-se 的代码会相当轻松, 这次我们会将你的项目成果利用Docker打包成一个镜像, 有了这个镜像, 只要别的机器上配置了Docker环境, 就能随时运行.  
## Prerequisites
- 在本机上配置Docker Engine, 参考官网: https://www.docker.com/get-started


## 概念理解:
- 什么是Docker: Docker是一个开放平台，用于开发应用、交付（shipping）应用、运行应用。 具体一点讲，docker为我们提供了一种可以打包应用，并且在一个隔离环境之中运行应用的解决方案：容器。
- 为什么使用Docker: 做前面几个项目的时候大家也感受到了“配环境”这个繁琐的过程, 我们要去官网下载软件包, 安装后可能还有许多环境变量要配置, 稍有不慎都要搭上大把时间；好不容易完成了一个project, 一旦要移植到别的机器上运行, 我们还要一字一句的教用户如何搭出一个一模一样的环境. Docker可以解救我们于水火之中. 
- 怎么学习Docker: confluence上皓铧前辈编写了详细的Docker入门任务, 各位需要完成一下: https://confluence.vmatrix.org.cn/pages/viewpage.action?pageId=11862035。概念理解部分回答一下, 并写在各自的README中.


## 实践操作:
### 任务1
完成: https://confluence.vmatrix.org.cn/pages/viewpage.action?pageId=11862035 上的“实践操作”部分的1至8, 9可以暂缓

### 任务2
利用Dockerfile和docker-compose来打包运行project4。(hint: 将服务端代码打包成一个镜像, mysql服务和redis服务也转换成docker容器的形式, 最后用docker-compose统一启动)


