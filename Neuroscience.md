# 神经科学 —— 《大脑总指挥》

## 前言

为了探明 AGI 之路的方向，我对神经科学展开了初步的研究。
我在图书馆随便找了一本 Goldberg 教授的《大脑总指挥》作为入门书籍。
本书对大脑整体结构进行了初步介绍，然后着重于大脑的额叶、认知展开了详细叙述，最后建立了一个启发式的神经网络数学模型进行建模
（Goldberg 教授毕竟主要负责临床的研究，对数学模型更多是启发式的设计）。

## 大脑的整体结构

在微观角度，人脑主要由许多神经元的连接组成。神经元之间通过电流传输信号，信号到达神经元后通过生化反应产生新的电流，最后组成了整个神经网络。
其中神经元之间突触接触的强度是动态变化的，或者说“可学习”的。

在宏观角度，大脑的结构总体上是一个层级结构，不过也有左右、前后的一定功能分化。
大脑层级大体上可以分为大脑皮质和皮质下组织。

皮质下组织较为原始，在演化中出现得非常早。皮质下组织有两组重要的结构：丘脑和基底核。
丘脑负责处理外在感觉信息，下丘脑负责处理体内的情况，丘脑和下丘脑合称间脑。
而基底核则负责发起动作和控制动作，其中有个叫杏仁核的结构较为特殊，其控制生物生存有关的决策，如攻击或逃跑、是否交配、是否摄取食物等。

小脑也是一个很重要的结构，在解剖上而言，小脑是整个大脑的缩小版。小脑的主要作用是协调感觉和动作，让生物能够以正确的时机做出精确的动作。

在进化后期皮质才开始出现。首先是原皮质和旧皮质，包括海马回和扣带回。
对于这些结构的作用并没有明确的结论。
不过可以知道的是海马回大概对记忆的形成起到激励的作用，而扣带回与情绪有关。
扣带回、海马回、杏仁核合称边缘系统。

最后是新皮质。新皮质是覆盖大脑上的很薄的一层，并且有许多褶皱。
新皮质剧烈改变了大脑处理信息的方式，赋予了大脑强有力的计算能力和复杂程度。
总体上，新皮质的前后分化为：前面负责动作，后面负责知觉。
相比于原始生物来说，我们人脑新皮质发达，执行决策更依赖于新皮质，而不是皮质下组织。
新皮质有四个主要的脑叶：枕叶处理视觉、颞叶处理听觉、顶叶处理触觉、额叶处理动作，其中，额叶位于新皮质的最前面，是认知的主要所在地，也是决策的中心。

## 大脑皮质

皮质作为人脑主要的决策制定者，一直是一个重要的课题。
早期，神经科学家一直相信人脑是“模块化的”：即大脑每个区域一定有其专门负责的功能。
但是随着人工神经网络的发展，和大量的实验表明，大脑的功能是分散的，并且每个人的大脑的功能分化都有所不同，这样的观点便不攻自破了。
例如语言，早期认为人脑一定有一个区域专门负责语言的处理。
但是从进化的角度来讲，只有人类使用语言，难道人类相比其他生物凭空多出来一个“语言模块”？ 这样的假设显然是不合理的。
事实上，实验表明，语言的表征在人脑中是分散的。
每个人皮质不同功能的分化应该是通过独立的学习得到的。
接下来，本文将会着重介绍大脑皮质，特别是额叶这一皮质中最重要的部分。

## 新颖性理论

