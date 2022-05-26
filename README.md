# tensorflow linux


## 介绍

## 环境

linux 以下环境测试通过
  cuda 11.6.2   
  cudnn 8.4   
  nccl 2.12   
  tensorrt: 8.4 可选安装     
  support nvidia Compute Capability 6.0 6.1 7.0 7.5 8.0 8.6  

  cuda 11.3.1   
  cudnn 8.2.1   
  nccl 2.9.9  
  tensorrt: 8.0.1 GA 可选安装
  nvidia Compute Capability 6.1 7.0 7.5 8.0 8.6
  
  也可以使用docker:
  - docker push ssdog/cuda:11.3.1-runtime-ubuntu18.04
  - docker push ssdog/cuda:11.3.1-runtime-ubuntu20.04
  - docker push ssdog/cuda:11.6.2-runtime-ubuntu18.04
  - docker push ssdog/cuda:11.6.2-runtime-ubuntu20.04

 docker为装有cuda cudnn nccl tensorrt的环境 ， 需要的tensorflow 可以从下面资源中获取。

## 安装

  pip install tf-gpu==1.15.5.2204
  
  pip install tf-gpu==2.8
  
  pip install tf-gpu==2.9




下载地址:


- 「tensorflow」[百度云](https://pan.baidu.com/s/1PXelYOJ2yqWfWfY7qAL4wA )(提取码：rpxv)





## 联系

- 博客：ssdog.cn/blog
