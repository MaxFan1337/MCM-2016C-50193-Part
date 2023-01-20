# B站视频内容解析

主要看了2022C获特奖的10篇论文

## 视频内容

### 结构

[【拿奖秘诀】22年O奖模仿了我的论文？｜2023美赛最新讲座（三）｜教你逐段对照模仿O奖论文_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV1TM411c7db/?spm_id_from=333.788&vd_source=85eceb8f104afd8d6b5458891e861249)

结合这个视频食用

**摘要的层次要清晰：概述模型->分段清晰叙述，展示结果->灵敏度和鲁棒性分析+总结**

> UP主：写论文要从模仿做起，通过深入研究2020A2001334的O奖论文，我们的论文的结构也是类似的：
>
> 其中第一二段：第三四五段：第六七段大致为1:2.5:1
>
> 第一段：背景描述（全球变暖，极端天气时常发生）->问题引出（为了解决野火问题，我们建立了无人机分布来达到平衡经济和效益的目的）->几个模型被建立起来(这里列举我们用到的模型)->
>
> 第二段：我们将研究的区域栅格化，能更好利用离散化的方法，同时我们使用了大量的可视化方法，使我们的结果更加直观（**这里是在模仿之前的O奖论文上的创新点**）
>
> 第三段：For Model I   热力图、多目标规划、建立了一个全新的XX模型，计算出了XX量，结果在Figure9上（有结果一定要说出来，有什么说什么）
>
> 第四段：For Model II  内容大致同上，值得一提的是可以把计算出来的一些数据什么的直接写在摘要上，让阅卷老师知道你们这个算法确实是跑通了的，更有说服力，也比较直观，结果什么的可以直接说it will be shown in section x.x，告诉他们后面还有的看的意思
>
> 第五段：For Model III  同上
>
> 第六段：In addition段，补充一些内容，作者的论文这一段写的是：考虑了其他的因素使得模型有很强的适用性（adaptability）
>
> 第七段：灵敏性分析＋鲁棒性分析，一些杂项（短）	

![image-20230117151242027](\2022C.assets\image-20230117151242027.png)

最后一段的套话

### 标题

美赛标题开放性很强

需要一个生动的标题，要让评审专家想读下去，尽量开脑洞（甚至可以放副标题引用名人名言啥的）![image-20230117152346027](D:\O奖论文分析\2022\2022C\2022C.assets\image-20230117152346027.png)

### 摘要

**重中之重，需要反复打磨！摘要是你的门面**

1. 简单概括建了什么名字（模型名字要直观，一眼知道干啥的）
2. 简述建模的过程，如果算法出彩，放在模型介绍后一并介绍
3. 说明结果
4. 关键词：问题、模型、算法等，一般5-6个



#### 模型起名

1. 有特点，精准、概括性强，常用的有“基于...的...模型"
2. 说明模型和算法的时候要挑重点，写的是关键步骤、关键变量、关键算法，语言越精炼越好
3. 模型结果，如果比较少就全写上去，比较多就举例说明。除非特殊情况，不然**不要出现表格、图片、公式**

#### 常加粗的内容

1. 模型名称
2. 算法名称
3. 关键变量
4. 模型结果

### 模型建立

![image-20230117152915290](D:\O奖论文分析\2022\2022C\2022C.assets\image-20230117152915290.png)

![image-20230117153108892](C:\Users\MaxFan\AppData\Roaming\Typora\typora-user-images\image-20230117153108892.png)

### 模型求解

好的算法可以直接提高模型和答卷的质量，一个花了相当时间想出来的算法，在论文中如果是一句话带过的，那么这一块的论文肯定是失败的，需要想出算法的同学充分表达出这个算法的优越性等特征

同时尽量不要用遗传退火之类的智能算法（PS：待考证，毕竟我也没怎么用过）

别人的模型算法不要直接搬



### 结果分析

图加对图的解释，反正所有我们得到的结果都应该加上合理的阐释去解释



### 灵敏度分析

**基本是图片+文字来展现**

![image-20230117154121689](D:\O奖论文分析\2022\2022C\2022C.assets\image-20230117154121689.png)

> UP：如果要考虑图的美观性，如果把两个图并排放，两个不同类型的图并排放，会显得非常紧凑，非常美观





# 2022C特奖论文整体分析

2022C的十篇O奖论文，这里侧重于从整体上去分析O奖论文长的样子

## 标题角度

十篇标题在这里：

**中规中矩型：**

Gold-Bitcoin Market Portfolio Investment Strategy **Model** and Its **Application**（以模型为主导）

Trading strategies based on voting systems

Day Trading in Bitcoin and Gold

Finding the Best Strategy with Quantitative Models

Trading Strategy Model Based on Dynamic Programming（基于XX的XX模型，感觉比较普通）

An Improved Pairs Trading Strategy Based on Cointegration of Gold and Bitcoin

**生动形象型：**

Grid the profit: Adaptive Periodic Grid Model with ARIMA Prediction（有动作，比较形象，然后搭配模型）

**朗朗上口型：**

Gold Strategy for Gold & Bitcoin traders（考虑了押韵等）

**脑洞大开型：**

The Queen of Strategy: The Road to Counterattack With $1,000（一人一狗一千块钱，白手起家打天下的感觉）

**缩写装杯型：**

PADRRI: Prediction And Decision Models For Best Return And Risk With High Interpretability



> 我们的论文标题可以从生动形象的动作抽象成数学建模的过程这个角度来起



## 目录角度

### 引言

页数尽量控制在2-3页，少有4页5页的（一两篇），要加小标题的话基本都是

> Problem Background——问题背景，主打一个废话和抄题目
>
> Restatement of the Problem——问题重申，同上
>
> *或者加文件综述
>
>  Our Work——其中有八篇给出了流程图，有一篇直接改名Our Work为The Flow Chart



### 假设与理由

> Assumptions and Justifications

与“定义与符号"(若有的话)一起，合并成Assumptions and Notations篇章和Assumptions、Notations各成一篇章的比例大概在2:1，剩下有一两篇论文没有特地定义新符号，怎么写看个人喜好，毕竟目录部分没有那么重要:)



### 定义和符号

> Definitions and Justifications

见假设与理由一栏



### 主体内容

**从这十篇论文中能总结出一些常见的行文结构：**

1. 策略->建模过程->结果分析
2. 列举主要模型（多段）->模型评估分析
3. 模型建立过程->模型评估分析
4. 模型介绍->执行过程（＋结果）->模型评估分析

> 上述的模型评估分析主要体现在运行结果的细节、与其他模型的比较和最优性分析上



### 灵敏度分析

必须要写

其中有一篇异化表达为Validating the Model，区别不大

基本都是单独成一章节

> Transaction Cost Sensitivity Analysis .
>
> Sensitivity Analysis of Investment Model
>
> Sensitivity of Strategy to Transaction Cost 
>
> Sensitivity Analysis of Investment Model

具体内容（Investment Model）视题目背景变化



### 模型评估

7/10直接用《优缺点/模型优缺点》成一章节

> Strengths and weaknesses
>
> Model Evaluation
>
> Evaluation of Strengths and Weaknesses 

然后基本上都是这样的小标题：

>  Strengths
>
> Weaknesses

保留这种格式就OK



### 报告

> Memorandum to The XXX
>
> MEMO
>
> Memorandum

有一篇特立独行没写在目录上面，但在另外的地方提到了



# **2022C特奖论文单独分析**

## 2229059

### 摘要

![image-20230117162610788](D:\O奖论文分析\2022\2022C\2022C.assets\abstract.png)

这篇摘要比较中规中矩，不过该有的东西都有，结构也比较清晰，算是相对比较保守的一种写法。



### 目录

目录倒是看着很舒服，一眼能知道想干什么

![image-20230117163337901](D:\O奖论文分析\2022\2022C\2022C.assets\menu.png)

其中Assumption并入Introduction章节

这个目录主打一个条理清晰

### 引言

![image-20230117163838160](D:\O奖论文分析\2022\2022C\2022C.assets\introduction_1.png)

### 问题分析

专门对比了两种资产的价格波动情况，然后说明了建立了一个考虑到两种资产的收益率的模型





# 2016C

## 50193

### 背景

待解决的问题：

1. 数据量大且多，怎么做归一化
2. 缺失数据多，不方便批处理
3. 不同参数重要性如何衡量
4. 如何选择学校和分配投资
5. 投资持续五年，时间因素也要考虑



解决步骤：

1. 数据筛选，K均值聚类填补缺失值，数据归一化
2. 使用PCA选择决策变量，使用AHP赋予不同权重，使用经济学知识构建ROI模型，处理数据得到学校评级
3. 在现代资产投资理论（Modern Portfolio Theory）的基础上创建两个模型，第一个模型（混合整数线性规划）用来选择出一年内的最优投资策略，第二个模型考虑时间因素，将第一种模型提升，使用动态规划+灰色预测决定长期投资策略



### 重要假设

1. 钱价值不变，不增值不贬值
2. 时序算法中排除在模型外的影响忽略
3. 由于边际效用，尽量不把钱投到一个学校



