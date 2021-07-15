# master-cup

PaddleOCR-learning

Baseline是在大名鼎鼎的百度开源OCR识别框架上更改的，首先，让我们了解下PaddleOCR。然后，学习如何白嫖这个框架进行OCR识别PaddlePaddleOCR安装教程。划重点：有了PaddleOCR，我再也不用去网上找那些所谓的免费在线文字识别，我所需要的就是把图片路径复制到代码里，运行就ok啦！


## 安装Paddle框架 ##

Anconda3(首先创建一个虚拟环境安装paddle以及后续所需要的库)

```conda create -n paddle_env python=3.8 #创建虚拟环境
activate paddle_env #进入虚拟环境
conda install paddlepaddle --channel https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/Paddle/ #安装paddle
```
安装完成后可以使用 python进入python解释器，输入import paddle ，再输入 paddle.utils.run_check()出现PaddlePaddle is installed successfully!已成功安装。
克隆项目

## 项目地址
https://gitee.com/coggle/tianchi-intel-PaddleOCR

## 关于baseline
![z](https://github.com/aaaaaa745/master-cup/blob/main/Snipaste_2021-07-15_23-56-42.png)
## 大佬的配置
