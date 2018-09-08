# 什么是PyTorch?

PyTorch是一个Python库，它主要提供了以下两个高级功能：

* GPU加速的张量计算\(Tensor Computation\)功能
* 构建在反向自动求导系统\(tape-based autodiff system\)上的深度神经网络功能

作为Python的库，PyTorch可以无缝的与其他你喜欢的Python库一起用，比如: NumPy, Scipy。 你也可以用Cython来扩展PyTorch, 就像其他的Python库一样。

更细粒度的看，PyTorch由以下组件构成：

| package | 描述 |
| :--- | :--- |
| torch | 支持GPU加速的Tensor计算库 |
|  torch.autograd | 基于反向求导策略的自动求导库 |
| torch.nn |  一个与autograd深度集成的，神经网络库 |
|  torch.optim  | 集成了大量优化算法的优化库，如 SGP，Adam |
| torch.multiprocessing | 能够共享Tensor的多进程库，用于数据加载等 |
|  torch.utils | 包含大量工具类，如：DataLoader，Trainer等 |
| torch.legacy\(.nn/.optim\) | 由于向下兼容而暂时保留的部分工具 |

一般来说，PyTorch用户把将PyTorch视为：

* 一个支持GPU的NumPy
* 一个灵活高效的深度学习研究平台

下表汇总了PyTorch的常用资源：

| Resources\(资源\) | URL\(链接\)  |
| :--- | :--- |
| Homepage\(主页\) | [pytorch.org](https://pytorch.org/) |
| Repository\(代码库\) | [github.com/PyTorch/PyTorch](https://github.com/PyTorch/PyTorch) |
|  Discussion\(社区\) | [discuss.pytorch.org](https://discuss.pytorch.org) |
| Docs\(文档\) | [pyrotch.org/docs ](https://pyrotch.org/docs%20) |
| Tutorials\(入门教程\) | [pyrotch.org/turorials](https://pyrotch.org/turorials) |
| Examples\(样例\)  | [github.com/PyTorch/examples](https://github.com/PyTorch/examples) |



