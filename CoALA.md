# 阅读随笔：Coginitive Architectures for Language Agents

Paper link: https://arxiv.org/abs/2309.02427

## 一些思考

阅读本篇论文主要也是为了了解一下认知架构（Cognitive Architecture）相关的研究。
相比于强化学习，我认为认知架构的发展更能让 AI 接近人类的思考方式。~~RL out!~~

本人认为，未来的 AI 应用应当是系统级的（表现为以下特征：模块化设计，状态机，异步线程推理，自主学习，数据库等）。
这也是我研究认知架构的原因。

如今 AI 的发展路径真的对吗？
纵观如今 AIGC 和 LLM 的发展：
AIGC 的可控性和稳定性是短板，为了弥补这些短板，甚至衍生出了诸多如提示词工程（Prompt Engineering）的工程（~~这明明就是语文工程~~；
而 LLM 仅仅作为语言模型，没有状态的设计（stateless），却靠 Special Token 和堆积历史记录的方式暴力解决状态的问题和一些任务。
我认为，我们需要一些更加结构化的设计，比如引入状态，推理，记忆设计。不过，我们也需要感谢如今的 AI 发展为我们创造了许多优秀的轮子（）

人类的思考永远是 AI 的研究可以借鉴的对象。AI 的研究并不像其他理科的研究一样无迹可循，至少目前来说，我们的发展目标是开发出接近人类的智能。

## Paper 简介

这篇论文总结了前人的 Symbolic Cognitive Architecture，并提出了一个新的概念性的认知架构框架：CoALA，并且就几个方面进行了介绍和讨论。


## CoALA 介绍

架构设计如下：

![coala-architecture.png](assets/coala-architecture.png)

决策过程如下：

![coala-decision.png](assets/coala-decision.png)

### Memory

### Actions

### Decision-Making
