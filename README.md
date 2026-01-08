# LLM-oprator-learning-path
LLM算子开发学习路径
1.理解大语言模型
要求了解主流LLM核心概念和结构。不需要追踪前沿模型算法，主要目标是理解模型结构到算子层面的映射。
重点掌握transformer、attention、MHA、GQA、MQA、MOE

(50 封私信 / 26 条消息) Transformer模型详解（图解最完整版） - 知乎

(50 封私信 / 26 条消息) 一文看懂 Attention（本质原理+3大优点+5大类型） - 知乎

(50 封私信 / 26 条消息) Transformer 工作原理：深入探索Transformer架构 - 知乎

The Illustrated Transformer – Jay Alammar – Visualizing machine learning one concept at a time.

The Illustrated GPT-2 (Visualizing Transformer Language Models) – Jay Alammar – Visualizing machine learning one concept at a time.

核心论文：
Attention is all you need: 1706.03762
Flash attention: 2205.14135

2.LLM核心算子
熟悉LLM结构对应的核心算子，理解核心算子原理与实现、常见优化。
注意力机制: flash attention, softmax, GEMM
前馈网络: Linear
归一化: RMS Norm, Layer Norm, 
激活:GELU, SiLU, Swish
融合算子：FUSED MOE，KV Cache update

