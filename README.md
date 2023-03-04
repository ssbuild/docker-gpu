# docker cuda 镜像


### docker cuda 环境
    cuda 11.8.0   
    cudnn 8.8   
    nccl 2.15   
    tensorrt: 8.5 未安装      


    cuda 11.7.1   
    cudnn 8.5   
    nccl 2.13   
    tensorrt: 8.4 未安装     
 
    
    cuda 11.6.2   
    cudnn 8.4   
    nccl 2.12   
    tensorrt: 8.4 未安装     


    cuda 11.3.1   
    cudnn 8.2.1   
    nccl 2.9.9  
    tensorrt: 8.0.1 GA 未安装

### cuda运行时环境
  - docker pull ssdog/cuda:11.3.1-runtime-ubuntu18.04
  - docker pull ssdog/cuda:11.3.1-runtime-ubuntu20.04
  - docker pull ssdog/cuda:11.6.2-runtime-ubuntu18.04
  - docker pull ssdog/cuda:11.6.2-runtime-ubuntu20.04
  - docker pull ssdog/cuda:11.7.1-runtime-ubuntu18.04
  - docker pull ssdog/cuda:11.7.1-runtime-ubuntu20.04
  - docker pull ssdog/cuda:11.7.1-runtime-ubuntu22.04
  - docker pull ssdog/cuda:11.8.0-runtime-ubuntu18.04
  - docker pull ssdog/cuda:11.8.0-runtime-ubuntu20.04
  - docker pull ssdog/cuda:11.8.0-runtime-ubuntu22.04
### cuda开发环境
  - docker pull ssdog/cuda:11.6.2-dev-ubuntu20.04
  - docker pull ssdog/cuda:11.3.1-dev-ubuntu20.04
  - docker pull ssdog/cuda:11.3.1-dev-ubuntu18.04
  - docker pull ssdog/cuda:11.6.2-dev-ubuntu18.04
  - docker pull ssdog/cuda:11.6.2-dev-ubuntu20.04
  - docker pull ssdog/cuda:11.7.1-dev-ubuntu18.04
  - docker pull ssdog/cuda:11.7.1-dev-ubuntu20.04
  - docker pull ssdog/cuda:11.7.1-dev-ubuntu22.04
  - docker pull ssdog/cuda:11.8.0-dev-ubuntu18.04
  - docker pull ssdog/cuda:11.8.0-dev-ubuntu20.04
  - docker pull ssdog/cuda:11.8.0-dev-ubuntu22.04



    
# 第三方神经网络框架安装包
    
    
# 一、 paddle
    # 支持算力 6.0 6.1 7.0 7.5 8.0 8.6 
    
#### 下载地址
  - 「paddle-gpu」[百度云](https://pan.baidu.com/s/1PXelYOJ2yqWfWfY7qAL4wA?pwd=rpxv )(提取码：rpxv)
  
# 二、 mxnet
    # 支持算力 6.0 6.1 7.0 7.5 8.0 8.6 
#### 依赖安装

    apt-get install libopenblas-base libopencv-dev -y or apt-get install libopenblas0 libopencv-dev -y
#### 下载地址
  - 「mxnet-gpu」[百度云](https://pan.baidu.com/s/1PXelYOJ2yqWfWfY7qAL4wA?pwd=rpxv )(提取码：rpxv)

# 三、  torch
    # 支持算力 6.0 6.1 7.0 7.5 8.0 8.6 

#### 依赖安装
    apt-get install libopenblas-base -y or apt-get install libopenblas0 -y
  
#### 下载地址
  - 「torch-gpu」[百度云](https://pan.baidu.com/s/1PXelYOJ2yqWfWfY7qAL4wA?pwd=rpxv )(提取码：rpxv)
     
      
      
# 四、  tensorflow

#### 下载地址
  - 「tensorflow」[百度云](https://pan.baidu.com/s/1PXelYOJ2yqWfWfY7qAL4wA?pwd=rpxv )(提取码：rpxv)
  - 「tf-gpu」(https://pypi.org/project/tf-gpu/#history)
 
#### tf-gpu
    windows 环境  cuda 11.6.2  cudnn 8.4  
  - tensorflow 1系列 , 支持window linux python3.6-python3.9
  - tensorflow 2系列 , linux python3.8-python3.10 , windows 支持一版 python3.8 tensorflow2.9

     

 tensorflow可以通过以下方式安装
 ```
  pip install tf-gpu==1.15.5.2204 # 支持算力 6.0 6.1 7.0 7.5 8.0 8.6 
  pip install tf-gpu==1.15.5.2205 # 支持算力 6.0 6.1 7.0 7.5 8.0 8.6 
  pip install tf-gpu==1.15.5.2206 # 支持算力 6.0 6.1 7.0 7.5 8.0 8.6 
  pip install tf-gpu==1.15.5.2301  # 支持算力 6.1 7.0 7.5 8.0 8.6 8.9
  pip install tf-gpu==2.6 # 支持算力 6.0 6.1 7.0 7.5 8.0 8.6 
  pip install tf-gpu==2.7 # 支持算力 6.0 6.1 7.0 7.5 8.0 8.6 
  pip install tf-gpu==2.8 # 支持算力 6.0 6.1 7.0 7.5 8.0 8.6 
  pip install tf-gpu==2.8.2 # 支持算力 6.0 6.1 7.0 7.5 8.0 8.6 
  pip install tf-gpu==2.9 # 支持算力 6.0 6.1 7.0 7.5 8.0 8.6 
  pip install tf-gpu==2.9.1 # 支持算力 6.0 6.1 7.0 7.5 8.0 8.6 
  pip install tf-gpu==2.9.2 # 支持算力 6.0 6.1 7.0 7.5 8.0 8.6 
  pip install tf-gpu==2.10 # 支持算力 6.0 6.1 7.0 7.5 8.0 8.6 
```
- 博客：ssdog.cn/blog
