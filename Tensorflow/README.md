# 笔记


- 使用图表示计算任务
- 在被称之为会话(Session)的上下文(Context)中执行图
- 使用tensor表示数据
- 通过变量(Variable)维护状态
- 使用feed 和 fetch 为任意操作输入和输出数据

**图中的节点被称之为 op (operation 的缩写), 一个 op 获得 0 个或多个 Tensor , 执行计算, 产生 0 个或多个 Tensor . 每个 Tensor 是一个类型化的多维数组**
