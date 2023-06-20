# MedChat
Large-scale, Informative, considerate multi-round dialogue data for medical domain

医学领域对话数据有挺多，但是这些数据存在一个问题：在线问诊中，医生的回复有时候会非常口语化，回复简介甚至难懂。人类医学专家可以这样说话，但是采用这些数据对模型进行微调，会直接导致模型学习到不好的习惯，学习得到的模型是肯定不会得到患者/用户喜欢的。当然，这一问题是有其他方法解决，比如模型对齐。但是为了帮助开源社区获得更高质量的数据，从而方便大家可以直接fine-tune就可以获得一个高质量的医学chat-bot，我们现发布：

- 🚀 [MedChat](xxx)数据集，基于已有的开源的问诊数据，使用ChatGPT对医生的回答进行改写，在不改变回复关键的情况下，使其回答更贴心，具有共情能力

我们计划分两个步骤发布MedChat，
- ⏳ [MedChat-v0.1](xxx)，基于[MedDG](xxx)数据集，采用ChatGPT进行改造；
- ⏳ [MedChat-v0.2](xxx)，在v0.1版本基础上，添加更大规模数据集[](xxx); 
