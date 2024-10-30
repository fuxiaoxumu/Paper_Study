# Grounding DINO Marrying DINO with Grounded Pre-Training for Open-Set Object Detection
阅读时间：10.23


## Motivation
- Referring expression comprehension (REC)理解和识别与特定表达（如名词短语）相关的图像区域。
- Image Grounding 是一种计算机视觉任务，旨在将图像中的特定区域与文本描述或语义标签对齐。
- 利用区域输出和语言特征在颈部和/或头部输出之间的对比损失。为什么能实现这个任务？
- 三个阶段都搞的融合语义方式
- sub-sentence level text features.为什么能解决全类名的干扰信息，怎么做到mask掉无用的

## Idea
刚看完yolov11就出了
