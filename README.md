# For github:
github上面有项目源码 已经上传, this link: https://github.com/TiramisuQiao/Mindspore-in-MNIST
# Environment prepare

 - 需要安装 Anaconda或者Miniconda，参考https://zhuanlan.zhihu.com/p/123188004
- 安装华为的框架需要python 3.7,3.8,3.9 可以自行用conda配置环境，打开Anaconda Navigator,在里面找到environment,新建python = 3.8.18环境，命名可以是ms38, 当然，在这个工程文件里默认是 ys38....
- 安装MS框架
```
conda activate ms38 
conda install mindspore=2.2.0 -c mindspore -c conda-forge
```
