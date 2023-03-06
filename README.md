# 常用 nvidia docker cuda环境集锦

## nvidia docker 深度学习框架 
 - [nvidia docker](nvidia_docker.MD)

## 第三方 nvidia docker
### 1. docker cuda 镜像环境
 
| name | cuda | cudnn |  nccl | tensorrt   |
|------|------|-------|------|------------|
| cuda:11.3.1  | 11.3.1  | 8.2.1 |  2.9.9 | 8.0.1 未安装  |
| cuda:11.6.2  | 11.6.2 | 8.4   |  2.12 | 8.4    未安装 |
| cuda:11.7.1   | 11.7.1   | 8.5   |  2.13 | 8.4 未安装    |
| cuda:11.8.0  | 11.8.0   | 8.7   |  2.15 | 8.5.3 未安装  |
| cuda:11.8.0  | 11.8.0   | 8.8   |  2.15 | 8.5.3 未安装  |


### 2. cuda运行时镜像
  - docker pull ssdog/cuda:11.3.1-runtime-ubuntu18.04
  - docker pull ssdog/cuda:11.3.1-runtime-ubuntu20.04
  - docker pull ssdog/cuda:11.6.2-runtime-ubuntu18.04
  - docker pull ssdog/cuda:11.6.2-runtime-ubuntu20.04
  - docker pull ssdog/cuda:11.7.1-runtime-ubuntu18.04
  - docker pull ssdog/cuda:11.7.1-runtime-ubuntu20.04
  - docker pull ssdog/cuda:11.7.1-runtime-ubuntu22.04
  - docker pull ssdog/cuda:11.8.0-cudnn8.7.0-runtime-ubuntu20.04
  - docker pull ssdog/cuda:11.8.0-cudnn8.7.0-runtime-ubuntu22.04
  - docker pull ssdog/cuda:11.8.0-runtime-ubuntu18.04
  - docker pull ssdog/cuda:11.8.0-runtime-ubuntu20.04
  - docker pull ssdog/cuda:11.8.0-runtime-ubuntu22.04

### 3. cuda开发镜像
  - docker pull ssdog/cuda:11.3.1-dev-ubuntu20.04
  - docker pull ssdog/cuda:11.3.1-dev-ubuntu18.04
  - docker pull ssdog/cuda:11.6.2-dev-ubuntu18.04
  - docker pull ssdog/cuda:11.6.2-dev-ubuntu20.04
  - docker pull ssdog/cuda:11.7.1-dev-ubuntu18.04
  - docker pull ssdog/cuda:11.7.1-dev-ubuntu20.04
  - docker pull ssdog/cuda:11.7.1-dev-ubuntu22.04
  - docker pull ssdog/cuda:11.8.0-cudnn8.7.0-dev-ubuntu20.04
  - docker pull ssdog/cuda:11.8.0-cudnn8.7.0-dev-ubuntu22.04
  - docker pull ssdog/cuda:11.8.0-dev-ubuntu18.04
  - docker pull ssdog/cuda:11.8.0-dev-ubuntu20.04
  - docker pull ssdog/cuda:11.8.0-dev-ubuntu22.04



    
## 第三方神经网络框架安装包
    
 - [tensorflow](tensorflow.MD)
 - [torch](torch.MD)
 - [paddlepaddle](paddle.MD)
 - [mxnet](mxnet.MD)
    
    

  



     
     
- 博客：ssdog.cn/blog
