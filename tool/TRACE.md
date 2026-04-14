# TRACE

## 主要内容

为了解决模型训练过程中，模型能力短板的问题。TRACE定义了:

- `Capability`: 能力，表示完成某个任务必须用到的动作。
- `Capability-targeted environment`: 为了训练某个短板，虚拟出来的环境。

自动寻找成功和失败的轨迹，找到短板生成训练环境。为每个能力训练一个Lora。推理时自动路由到对应到lora。
