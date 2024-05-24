![手把手带你实战Transformers](./imgs/1.png)

### 测试环境

```shell
pip freeze > requirements.txt
conda create -n my-Transfomer python=3.11
conda activate my-Transfomer
pip install -r requirements.txt --proxy=127.0.0.1:10809
```


# 课程规划

- 基础入门篇：Transformers入门，从环境安装到各个基础组件的介绍，包括Pipeline、Tokenizer、Model、Datasets、Evaluate、Trainer，并通过一个最基本的文本分类实例将各个模块进行串讲

- 实战演练篇：Transformers实战，通过丰富的实战案例对Transformers在NLP任务中的解决方案进行介绍，包括命名实体识别、机器阅读理解、多项选择、文本相似度、检索式对话机器人、掩码语言模型、因果语言模型、摘要生成、生成式对话机器人

- 高效微调篇：Transformers模型高效微调，以PEFT库为核心，介绍各种常用的参数高效微调方法的原理与实战，包括BitFit、Prompt-tuning、P-tuning、Prefix-Tuning、Lora和IA3

- 低精度训练篇：Transformers模型低精度训练，基于bitsandbytes库，进行模型的低精度训练，包括LlaMA2-7B和ChatGLM2-6B两个模型的多个不同精度训练的实战演练，包括半精度训练、8bit训练、4bit训练（QLoRA）

- 分布式训练篇：Transformers模型分布式训练，基于accelerate库讲解transformers模型的分布式训练解决方案，介绍分布式训练的基本原理以及accelerate库的基本使用方式，包括与Deepspeed框架的集成

- 对齐训练篇: ...

- 性能优化篇: ...

- 系统演示篇: ...


# Star History

[![Star History Chart](https://api.star-history.com/svg?repos=zyds/transformers-code&type=Date)](https://star-history.com/#zyds/transformers-code&Date)
