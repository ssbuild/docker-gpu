# docker 镜像
  - cuda运行时包
  - docker pull ssdog/cuda:11.3.1-runtime-ubuntu20.04.py38
  - docker pull ssdog/cuda:11.6.2-runtime-ubuntu20.04.py38
  - docker pull ssdog/cuda:11.3.1-runtime-ubuntu18.04
  - docker pull ssdog/cuda:11.3.1-runtime-ubuntu20.04
  - docker pull ssdog/cuda:11.6.2-runtime-ubuntu18.04
  - docker pull ssdog/cuda:11.6.2-runtime-ubuntu20.04
  - cuda开发包
  - docker pull ssdog/cuda:11.6.2-dev-ubuntu20.04
  - docker pull ssdog/cuda:11.3.1-dev-ubuntu20.04
  - docker pull ssdog/cuda:11.3.1-dev-ubuntu18.04
  - docker pull ssdog/cuda:11.6.2-dev-ubuntu18.04

 ##### 注 docker为装有cuda cudnn nccl 的环境 ，事实上只要安装 cuda11系列 cudnn8系列 nccl2.9以上系列 都可以正常驱动gpu资源。 
# 一、 paddle
#### linux

    cuda 11.6.2   
    cudnn 8.4   
    nccl 2.12   
    tensorrt: 8.4 可选安装     
    nvidia Compute Capability 6.0 6.1 7.0 7.5 8.0 8.6  

    cuda 11.3.1   
    cudnn 8.2.1   
    nccl 2.9.9  
    tensorrt: 8.0.1 GA 可选安装
    nvidia Compute Capability 6.0 6.1 7.0 7.5 8.0 8.6

#### 下载地址
  - 「paddle-gpu」[百度云](https://pan.baidu.com/s/1nv6z6NSYLdDnPSStobJS1w )(提取码：0000)


# 二、  tensorflow

#### 环境介绍
  - tensorflow 1系列 , 支持window linux python3.6-python3.9
  - tensorflow 2系列 , linux python3.8-python3.10 , windows 支持一版 python3.8 tensorflow2.9
  
#### 下载地址
  - 「tensorflow」[百度云](https://pan.baidu.com/s/1PXelYOJ2yqWfWfY7qAL4wA )(提取码：rpxv)
  - 「tf-gpu」(https://pypi.org/project/tf-gpu/#history)
  
#### linux
 
    cuda 11.6.2   
    cudnn 8.4   
    nccl 2.12   
    tensorrt: 8.4 可选安装     
    nvidia Compute Capability 6.0 6.1 7.0 7.5 8.0 8.6  

    cuda 11.3.1   
    cudnn 8.2.1   
    nccl 2.9.9  
    tensorrt: 8.0.1 GA 可选安装
    nvidia Compute Capability 6.0 6.1 7.0 7.5 8.0 8.6
  
  #### windows
    cuda 11.6.2   
    cudnn 8.4  
    nvidia Compute Capability 5.0,5.2,6.0 6.1 7.0 7.5 8.0 8.6
  
 ```
  pip install tf-gpu==1.15.5.2204
  pip install tf-gpu==1.15.5.2205
  pip install tf-gpu==1.15.5.2206
  pip install tf-gpu==2.6
  pip install tf-gpu==2.7
  pip install tf-gpu==2.8
  pip install tf-gpu==2.8.2
  pip install tf-gpu==2.9
  pip install tf-gpu==2.9.1
```




- 博客：ssdog.cn/blog
