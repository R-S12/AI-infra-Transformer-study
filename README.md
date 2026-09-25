# AI-infra-Transformer-study
学习AI infra的基础模型--Transformer--所有infra部署都是基于此模型
将Transformer模型拆解为**Mluti Head Attention--layernorm--FFN**三大块内容
1. Multi Head Attention组成--QKV矩阵--多头注意力
-  QKV矩阵理解：权重Q矩阵先将每个词表示的内容提取，权重K矩阵则是表示每个词之间的关系，两者相乘得两两词之间的对应关系。最后乘上权重V矩阵得到每个词具体表达出的“上下文”意思
-  ![Uploading image.png…]()

2.  
