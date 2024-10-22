# Adding Conditional Control to Text-to-Image Diffusion Models
阅读时间：0923
![alt text](image.png)

## Motivation
文生图比较有限，控制大型图像扩散模型以特定任务的输入（边缘、深度、姿势）进行学习。加旁支模块，并在模块前后增加 zero convolution层。

## Idea
无