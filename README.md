## I have finished the detection branch and am still training the model to verify its correctness. All the features will be published to develop branch, and keep master stable. 
 - ICDAR Dataset 
 - SynthText 800K Dataset
 - detection branch 
 - eval
 - multi-gpu training
 
 
## Questions

- Should I fix weights of the backbone network, resnet50 ?
  ```python
  for param in self.backbone.parameters():
      param.requires_grad = False
  ```
 
 

# Introduction

This is a PyTorch implementation of [FOTS](https://arxiv.org/abs/1801.01671).

# 李剑备注：
https://blog.csdn.net/zhangwl27/article/details/86544941
https://blog.csdn.net/qq_14845119/article/details/84635847
【论文翻译】2018一站式FOTS
