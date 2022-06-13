[计算机技术.md](https://uploader.shimo.im/f/QVZHUU3pjeZ4pGTC.md?fileGuid=yKgKTQ6TjRGrJ39R)

## 工具路线

###### VS Code

* [VS Code Themes](http://vscodethemes.com/)  http://vscodethemes.com/

* [炫酷的VS Code毛玻璃效果](https://juejin.cn/post/6844903846871842823) https://juejin.cn/post/6844903846871842823

* [教你打造一款颜值逆天的 VS Code](https://toutiao.io/posts/7w5ixl/preview) https://toutiao.io/posts/7w5ixl/preview

* [Visual Studio Code默认快捷键大全](https://www.jianshu.com/p/532231d3014d) https://www.jianshu.com/p/532231d3014d

* [21 个VSCode 快捷键，让代码更快，更有趣](https://segmentfault.com/a/1190000019821154)  https://segmentfault.com/a/1190000019821154 ——适合快速上手

* [VS Code中对Python程序进行断点调试/Debug ](https://blog.csdn.net/SeaBiscuitUncle/article/details/103917401) https://blog.csdn.net/SeaBiscuitUncle/article/details/103917401
* [修改 Visual Studio Code workspace颜色](https://marketplace.visualstudio.com/items?itemName=johnpapa.vscode-peacock)  https://marketplace.visualstudio.com/items?itemName=johnpapa.vscode-peacock  --适用打开多个`workspace`场景

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
- Top tips for <IDE-NAME>

###### Docker

###### git

- [git介绍](https://en.wikipedia.org/wiki/Git) 
- [git 提交pr](https://www.atlassian.com/git/tutorials)
- [git 官网](https://git-scm.com/book/zh/v2)
  - [PDF版本](https://github.com/progit/progit2-zh/releases/download/2.1.55/progit_v2.1.55.pdf)
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
- [Volta/Turing GPU Architecture - I&II](https://zhuanlan.zhihu.com/p/85974212?utm_source=wechat_session&utm_medium=social&utm_oi=720506832975560704&utm_campaign=shareopn)



## TVM路线

### Buff学习路线

[深度学习编译器及TVM 介绍](https://zhuanlan.zhihu.com/p/358585143)

[TVM中的scheduler](https://zhuanlan.zhihu.com/p/360385060)

[基于ONNX模型结构了解TVM的前端](https://zhuanlan.zhihu.com/p/365800737)

[解析TVM算子](https://zhuanlan.zhihu.com/p/368940120)

[TVM Relay以及Pass简介](https://zhuanlan.zhihu.com/p/374914252)

[TVM的编译流程详解](https://zhuanlan.zhihu.com/p/376863322)

[万字长文入门TVM Pass](https://zhuanlan.zhihu.com/p/378739411)

[TVM的算符融合以及如何使用TVM Pass Infra自定义Pass](https://zhuanlan.zhihu.com/p/380630801)

[TVM的CodeGen流程](https://zhuanlan.zhihu.com/p/386942253)

### 项目组学习路线

#### TVM架构与模型编译流程

#### TVM Runtime

- [Design and Architecture](https://tvm.apache.org/docs/dev/index.html)
- [TVM Runtime System](https://tvm.apache.org/docs/dev/runtime.html)
- [Introduction to Module Serialization](https://tvm.apache.org/docs/dev/introduction_to_module_serialization.html)

#### TVM Runtime System Foundation

#### Relay图优化 Pass

- [Relay: A New IR for Machine Learning Frameworks](https://arxiv.org/pdf/1810.00952.pdf)
- [Introduction to Relay IR](https://tvm.apache.org/docs/dev/relay_intro.html)
- [Expressions in Relay](https://tvm.apache.org/docs/langref/relay_expr.html#closures)
- [TVM之设计模式解读--visitor模式](https://zhuanlan.zhihu.com/p/341334406)

#### TVM TE 与 TVM Schedule原语

- [Use Tensor Expression Debug Display (TEDD) for Visualization](https://tvm.apache.org/docs/tutorials/language/tedd.html)

##### Primitives

- [Schedule Primitives in TVM](https://tvm.apache.org/docs/tutorials/language/schedule_primitives.html)
- [Reduction](https://tvm.apache.org/docs/tutorials/language/reduction.html)
- [schedule详细举例](https://zhuanlan.zhihu.com/p/94846767)

##### A Operational Model of Schedules inTensor Expression

- [Document](https://docs.google.com/document/d/1nmz00_n4Ju-SpYN0QFl3abTHTlR_P0dRyo5zsWC0Q1k/edit)
- Talk Video 
- [Slides](https://tvmconf.org/slides/2019/E03-Yuan-Lin-Yongfeng-Gu.pdf)

#### TVM Pass 

- [Pass Infrastructure](https://tvm.apache.org/docs/dev/pass_infra.html#pass-infra)
- [TVM代码走读](https://www.zhihu.com/column/c_1254058636869603328)
- [FusionStitching: Boosting Memory Intensive Computations for Deep Learning Workloads](https://arxiv.org/abs/2009.10924)

#### TVM下一代IR——Tensor IR

#### TVM Code Generation(LLVM)
你这个问题我不懂，我外行信口开河一下，如果有误导请多多包涵哈。我调试疑难问题的时候，会用动态追踪技术看详细的调用情况，比如不涉及底层的可以试试python内置的trace，涉及底层的用Linux的strace。有了详细的日志之后，配合一些grep的技巧，可能可以找出等待的原因。

动态追踪技术讲得最好的文章是章亦春的漫谈系列：https://blog.openresty.com.cn/cn/dynamic-tracing/
要注意用了动态追踪技术后，必然会导致程序变慢，所以本身就会对调试性能问题带来一定的干扰，有时候这个干扰是成比例的，不会改变程序行为，但是有时候程序本身有竞争条件的bug的时候，在动态追踪的情况下可能反而就重现不了了，或者重现几率降低了
为了获得类似动态追踪技术的好处，又避免性能的损耗和执行上的微扰，Google 开发了LLVM/XRay，在编译的时候自动插入追踪代码。因为要重新编译，所以XRay用起来比较麻烦，没有strace这类技术这么普及。除非是整天跟底层打交道的，不然我也不推荐XRay，只是顺便提一下。

https://www.llvm.org/docs/XRay.html
xray不是编译的时候插入追踪代码，是插入nop，运行的时候按需要动态替换nop指令。。。

#### TVM 开源社区代码规范

#### AutoTVM原理

- [Learning to Optimize Tensor Programs](https://arxiv.org/pdf/1805.08166.pdf)

#### Auto Scheduler原理（Ansor）

- [Ansor: Generating High-Performance Tensor Programs for Deep Learning](https://www.usenix.org/conference/osdi20/presentation/zheng)

#### TVM异构原理实现

#### Auto Relay


#### LLVM IR与LLVM Backend 

#### 量化与HAGO

#### AdaQuant量化方法

- [AdaQuant：改进训练后神经网络量化：分层校准和整数编程](https://mp.weixin.qq.com/s?__biz=MzUxNDY2MDc4Ng==&mid=2247485303&idx=1&sn=2519339e7d58e26b307bcaf5e3422e65&chksm=f943c7aace344ebc7c8c3de8c962adaaf31b19bb7370018059cae88f6fd966e94932e8d70065&mpshare=1&scene=1&srcid=0327ruF0PjBp6GnqzK413Nqr&sharer_sharetime=1617589430404&sharer_shareid=74872d73ab7efab76a80798b1aaefe03&exportkey=AXmjijmW%2FlnJ8SoU%2BCyYRiw%3D&pass_ticket=RlJqwcjZS98Tr0OlzkUQO4BlWQXXz9enjHNjdd3CGvt6uupsszfaFCFp3pHWGsyt&wx_header=0#rd)

#### GEMM与Convlution常用优化策略
**GEMM优化**
- [基于how-to-optimize-gemm初探矩阵乘法优化](https://zhuanlan.zhihu.com/p/272208879)
- [高性能计算简介（二）：矩阵分块，性能分析](https://zhuanlan.zhihu.com/p/161684949)
- [TVM 算子集成到tensorflow中(TVMDSOop)](https://www.sxsbj.com/index.php/archives/3/)
#### MLIR

#### Polyhedral与自动化

- [PLuTo: A Practical and Fully Automatic Polyhedral Program Optimization System](https://www.ece.lsu.edu/jxr/Publications-pdf/tr70-07.pdf)
- [Tiramisu: A Polyhedral Compiler for Expressing Fast and Portable Code](https://arxiv.org/abs/1804.10694)

#### TensorCore编程

**博客：**

- [MegEngine TensorCore 卷积算子实现原理](https://zhuanlan.zhihu.com/p/372973726)

**论文：**

- [Dissecting the NVIDIA Volta GPU Architecture via Microbenchmarking](https://arxiv.org/abs/1804.06826)
- [Parallel Thread Execution ISA Version 7.4](https://docs.nvidia.com/cuda/parallel-thread-execution/index.html#abstract)
- [Modeling Deep Learning Accelerator Enabled GPUs](https://arxiv.org/abs/1811.08309)
- [NVIDIA Tensor Core Programmability, Performance & Precision](https://arxiv.org/abs/1803.04014)

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

[Training Deep Nets with Sublinear Memory Cost](https://arxiv.org/abs/1604.06174)

[Ansor: Generating High-Performance Tensor Programs for Deep Learning](https://www.usenix.org/conference/osdi20/presentation/zheng)

[Rammer: Enabling Holistic Deep Learning Compiler Optimizations with rTasks](https://www.usenix.org/system/files/osdi20-ma.pdf)

[Cambricon: An Instruction Set Architecture for Neural Networks](https://seal.ece.ucsb.edu/sites/default/files/publications/07551409.pdf)

Floridi, L., & Chiriatti, M. (2020). GPT-3: Its nature, scope, limits, and consequences. Minds and Machines, 30(4), 681-694.
J. Fang, H. Sips, L. Zhang, C. Xu, Y. Che, and A. L. Varbanescu, “Test-driving intel xeon phi,” in Proceedings of the 5th ACM/SPEC international conference on Performance engineering. ACM, 2014, pp. 137–148.
J. D. McCalpin, “Stream: Sustainable memory bandwidth in high performance computers,” University of Virginia, Charlottesville, Virginia, Tech. Rep., 1991-2007, a continually updated technical report. [Online]. Available: http://www.cs.virginia.edu/stream/
G. Juckeland, S. Borner, M. Kluge, S. Kolling, W. E. Nagel, S. Pflu ̈ger, H. Roding, S. Seidl, T. William, and R. Wloch, “Benchit-performance measurements and comparison for scientific applications.” in PARCO, 2003, pp. 501–508.
https://docs.nersc.gov/performance/arithmetic_intensity/ 
 Williams, S., Waterman, A., & Patterson, D. (2009). Roofline: an insightful visual performance model for multicore architectures. Communications of the ACM, 52(4), 65-76.
Lin, J., Xu, Z., Cai, L., Nukada, A., & Matsuoka, S. (2018). Evaluating the SW26010 many-core processor with a micro-benchmark suite for performance optimizations. Parallel Computing, 77, 128-143.

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

