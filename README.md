##### 工具路线

###### VS Code

* [VS Code Themes](http://vscodethemes.com/)
* [炫酷的VS Code毛玻璃效果](https://juejin.cn/post/6844903846871842823)
* [教你打造一款颜值逆天的 VS Code](https://toutiao.io/posts/7w5ixl/preview)
* [Visual Studio Code默认快捷键大全](https://www.jianshu.com/p/532231d3014d)
* [21 个VSCode 快捷键，让代码更快，更有趣](https://segmentfault.com/a/1190000019821154)  ——适合快速上手
* [VS Code中对Python程序进行断点调试/Debug ](https://blog.csdn.net/SeaBiscuitUncle/article/details/103917401)
* [修改 Visual Studio Code workspace颜色](https://marketplace.visualstudio.com/items?itemName=johnpapa.vscode-peacock)  --适用打开多个 `workspace`场景

###### GDB

* [Debugging with GDB](http://sourceware.org/gdb/current/onlinedocs/gdb.pdf) ——现阶段有中文翻译资源
* [CUDA-GDB](https://developer.download.nvidia.cn/compute/DevZone/docs/html/C/doc/cuda-gdb.pdf)

###### pdb

[`pdb` --- Python 的调试器](https://docs.python.org/zh-cn/3/library/pdb.html)

###### Vim

* [VIM快捷键速查表](https://linux.cn/article-8144-1.html)
* [Vim (vi) 编辑器快捷键大全](https://segmentfault.com/a/1190000016056004)

###### Xshell

- [高效使用XSHELL](https://www.jianshu.com/p/67b83d3f2e40)

###### Pycharm

- [Pycharm断点调试](https://www.jetbrains.com/help/pycharm/part-1-debugging-python-code.html#inline-debugging)

###### [Terminal](http://github.com/microsoft/terminal)

###### 指法练习

- home、end（行头、行尾）
- Word 单词、选单词、选整行
- IDE 的自动补全
- Top tips for `<IDE-NAME>`

###### Docker

###### git

- [git介绍](https://en.wikipedia.org/wiki/Git)
- [git 提交pr](https://www.atlassian.com/git/tutorials)
- [git 官网](https://git-scm.com/book/zh/v2)

  - [PDF版本](https://github.com/progit/progit2-zh/releases/download/2.1.55/progit_v2.1.55.pdf)
- [GIthub 官方文档](https://docs.github.com/cn)
- [血泪教训之请不要再轻视Git —— 我在工作中是如何使用 Git 的](https://zhuanlan.zhihu.com/p/250493093)  --记录的比较实用
- 奇奇怪怪的技能

  - [如何管理git项目中的密码等机密文件 -- Git-Secret](https://zhuanlan.zhihu.com/p/445987782)

## 高性能计算库

**指标：**

- [深度学习模型大小与模型推理速度的探讨](https://zhuanlan.zhihu.com/p/411522457)

**博客：**

- [profiling 与性能优化总结](https://zhuanlan.zhihu.com/p/362575905)

**论文：**

- [Performance Evaluation of cuDNN Convolution Algorithms on NVIDIA Volta GPUs](https://core.ac.uk/download/pdf/224976536.pdf)
- [TTLG - An Efficient Tensor Transposition Library for GPUs](https://changwanhong.com/publication/IPDPS18.pdf)
- [cuTT: A High-Performance Tensor Transpose Library for CUDA Compatible GPUs](https://arxiv.org/ftp/arxiv/papers/1705/1705.01598.pdf)
- 

**CUDA**

1. 指令

- [Volta/Turing GPU Architecture - I&amp;II](https://zhuanlan.zhihu.com/p/85974212?utm_source=wechat_session&utm_medium=social&utm_oi=720506832975560704&utm_campaign=shareopn)

## TVM路线

#### TVM架构与模型编译流程

#### TVM Runtime

#### TVM Runtime System Foundation

#### Relay图优化 Pass

#### TVM TE 与 TVM Schedule原语

#### TVM Pass

#### TVM下一代IR——Tensor IR

#### TVM Code Generation(LLVM)

#### TVM 开源社区代码规范

#### AutoTVM原理

#### Auto Scheduler原理（Ansor）

#### TVM异构原理实现

#### Auto Relay

#### LLVM IR与LLVM Backend

#### 量化与HAGO

#### MLIR

#### Polyhedral与自动化

#### TensorCore编程

**博客：**

- [MegEngine TensorCore 卷积算子实现原理](https://zhuanlan.zhihu.com/p/372973726)

**论文：**

- [Dissecting the NVIDIA Volta GPU Architecture via Microbenchmarking](https://arxiv.org/abs/1804.06826)
- [Parallel Thread Execution ISA Version 7.4](https://docs.nvidia.com/cuda/parallel-thread-execution/index.html#abstract)
- [Modeling Deep Learning Accelerator Enabled GPUs](https://arxiv.org/abs/1811.08309)
- [NVIDIA Tensor Core Programmability, Performance &amp; Precision](https://arxiv.org/abs/1803.04014)

#### TVM IR pass以及多输入、出介绍

## 框架路线

1. 简介
2. 深度学习训练框架的最小组成单元
3. 高效 Kernel 与计算机体系结构千丝万缕的关联
4. [多机多卡通讯](https://zhuanlan.zhihu.com/p/367327698)
5. 框架如何对给定计算进行优化
6. 面对设计问题如何取舍

#### Caffe/Caffe2

- [Paddle wikis](https://github.com/PaddlePaddle/Paddle/search?q=caffe2&type=wikis)

#### Tensofflow

#### Pytorch

- [一文搞懂 PyTorch 内部机制](https://zhuanlan.zhihu.com/p/338256656)
- [动手学深度学习](https://zhuanlan.zhihu.com/p/88402699)

#### ONNX

## 硬件架构

### GPU

[英伟达GPU架构演进近十年，从费米到安培](https://zhuanlan.zhihu.com/p/413145211)

### NPU

#### 主流手机平台NPU软件栈

1. 华为 HiAI Foundation
2. 1. IR在线/离线模型转换
   2. 与已有推理引擎的集成
3. 高通 NPE SDK
4. 联发科 NeuroPilot
5. 苹果 CoreML
6. 三星 Samsung Neural SDK

### DPU

[构建AI生态：除了GPU、DPU和CPU，还需要什么](https://www.eet-china.com/news/202104280905.html)

[NVIDIA英伟达中国](https://www.zhihu.com/org/nvidiaying-wei-da)

## 编码语言

### C++

### Python

- [Python 程序如何高效地调试](https://www.zhihu.com/question/21572891)

## 阅读论文

## 开源项目

OpenPPL

## 阅读书籍

《异类：不一样的成功启示录》* 马尔科姆.格拉德威尔

《刻意练习》

《认知天性：让学习变得轻而易举的心理学规律》

## 自己监督学习

- [如何阅读技术博客](https://zhuanlan.zhihu.com/p/115179058)
- [程序员如何系统学习新技术](https://zhuanlan.zhihu.com/p/104769413)

## 网络博客

[程序员最重要的能力是什么](https://www.zhihu.com/question/27263861/answer/2109861107)

## 职场沟通

- [职场年轻人应该如何学会表达](https://www.zhihu.com/question/483898547/answer/2109135773)
- [程序员职场实用沟通技巧](https://zhuanlan.zhihu.com/p/150613687)
  - 提供足够的信息
  - 有头有尾，有始有终  --**处理事情，要及时给相关的人（同事，组长或者其他组的人）做反馈**。
  - 友好的文字格式
  - 保持基本的礼貌态度 --多用**“请”“谢谢”“麻烦了”“不客气”** 这些礼貌用语，看似简单地多说几个字，可以让沟通保持舒适愉快。
- 等哈就
