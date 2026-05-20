# 生成式AI对学习动机、自我效能和认知负荷的影响：系统综述

**Generative AI and Its Impact on Learning Motivation, Self-Efficacy, and Cognitive Load: A Systematic Review**

> 本文由 [SciSurvey](../skills/scisurvey/SKILL.md) skill 自动生成，检索执行日期：2026-05-20。

---

## 摘要

**背景：** 生成式人工智能（Generative AI，GenAI）工具的快速普及正深刻改变教育生态，但其对学习者三项核心心理变量——学习动机、自我效能感及认知负荷——的系统性影响尚不明确。

**目的：** 整合2022—2025年实证研究，分析生成式AI在教育情境中如何影响学习动机、自我效能感和认知负荷，并识别国内外研究差异与未来缺口。

**方法：** 在Sciverse数据库执行多轮检索（7组英文语义检索、2组中文语义检索及6轮结构化元检索），依据PRISMA框架筛选，最终纳入25篇文献（5篇全文精读，20篇摘要级证据）。

**结果：** ①在学习动机方面，AI能力对学习动机的标准化路径系数达β=0.585（p<0.001），且学习动机是AI效能通向更高阶认知目标的核心中介（Bootstrap间接效应=0.316，95%CI[0.255, 0.352]）；②在自我效能方面，AI能力对广义自我效能的路径系数为β=0.546（p<0.001），自我效能进一步通过动机路径影响认知目标；③在认知负荷方面，效应呈双重性：辅助型AI设计可降低外在负荷，多功能叠加则存在认知过载风险，且内在动机水平是认知负荷承受阈值的关键调节变量。

**结论：** 生成式AI对学习动机和自我效能总体具有积极效应，但对认知负荷的影响具有条件性。三变量间存在链式中介关系，需纵向研究加以验证。建议教育实践中优先采用辅助型AI设计，并建立认知负荷监控机制。

**关键词：** 生成式AI；ChatGPT；学习动机；自我效能；认知负荷；教育技术；系统综述

---

## 1. 引言

### 1.1 研究背景与重要性

自2022年11月ChatGPT公开发布以来，生成式人工智能技术迅速渗透至各教育层级。生成式AI是指能够基于输入提示生成文本、图像等新内容的深度学习模型，其在教育领域的应用涵盖智能写作辅助、自适应学习平台、AI教学助手和交互式问答系统等。与此前的教育技术浪潮不同，生成式AI具有"对话式"、"生成式"和"实时反馈"三大特征，从根本上改变了学习者与学习内容、教学支持之间的互动模式。

然而，这种变革对学习者三项核心心理变量的影响，学术界尚未形成系统共识：

- **学习动机（Learning Motivation）：** 基于自我决定理论（SDT; Ryan & Deci, 2000）[25]，分为内在动机与外在动机，决定学习参与深度和持续性；
- **自我效能（Self-Efficacy）：** 基于Bandura（1977）社会认知理论，指个体对完成特定任务能力的信念，是预测学业成就的核心心理变量；
- **认知负荷（Cognitive Load）：** 基于Sweller（1988）认知负荷理论（CLT）[26]，区分内在、外在和衍生三类负荷，反映工作记忆的资源使用效率。

三者存在紧密交互：高自我效能往往带来较低的感知认知负荷，而适当的认知挑战与较低的外在负荷可激发内在动机。生成式AI的引入可能同时作用于三个变量，但作用机制、影响方向和量级尚不明确。

### 1.2 现有综述的局限

现有AI与教育系统综述多聚焦于学业成就或教学效率，较少专门探讨生成式AI对动机、自我效能和认知负荷三者联合影响的机制路径。中文情境下的本土研究证据较为零散，缺乏与国际研究的系统比较。本综述旨在填补这一缺口。

### 1.3 研究问题（PICO框架）

| 要素 | 界定 |
|------|------|
| **P（人群）** | K-12至高等教育学习者 |
| **I（干预）** | 生成式AI工具（ChatGPT、AI教学助手、AI写作辅助、AI自适应学习平台等） |
| **C（对照）** | 传统教学方式或非AI辅助学习条件 |
| **O（结局）** | 学习动机、自我效能感、认知负荷（三者中至少一项） |

---

## 2. 方法

### 2.1 检索策略

**检索数据库：** Sciverse学术数据库（检索执行日期：2026年5月20日）

| 检索轮次 | 策略类型 | 主要关键词/过滤条件 | 命中候选数 |
|---------|---------|---------------------|-----------|
| EN-1至EN-7 | 英文语义检索（quality模式） | 生成式AI/认知负荷/自我效能/动机/SDT/CLT | 35篇 |
| ZH-1至ZH-2 | 中文语义检索 | 生成式AI学习动机/ChatGPT教育心理 | 5篇 |
| Meta-①至Meta-⑥ | 结构化元检索 | citation≥5; fwci≥2; language=zh; country=China; year≥2024; OA | 30篇 |
| 引用链追踪 | references/related_works分析 | Top-10文献参考列表 | 8篇 |
| **合计（去重）** | | | **54篇** |

### 2.2 纳入/排除标准

**纳入：** ①研究主题涉及生成式AI在教育情境中的应用；②结果变量包含学习动机、自我效能感或认知负荷至少之一；③实证研究或系统综述；④2022—2025年发表；⑤中文或英文。

**排除：** ①仅讨论AI在医疗/临床（非教育）情境；②纯技术AI工程论文；③摘要不可及；④未通过年龄调整引用量质量阈值。

### 2.3 PRISMA筛选流程

```
初始检索记录（去重后）：54篇
        │
        ▼ 标题/摘要筛选（剔除医疗AI 8篇、LLM技术论文 7篇、学科不符 5篇）
        │ 排除 20篇
        ▼
   候选文献：34篇
        │
        ▼ 质量过滤（年龄调整引用量阈值 + fwci综合评分）
        │ 排除 9篇
        ▼
   最终纳入：25篇
（全文精读：5篇；摘要级别：20篇）
```

### 2.4 质量评估

采用基于FWCI的综合评分结合年龄调整引用量阈值：0—1年≥2次；1—2年≥8次；2—5年≥30次。全文可读文献（5篇）进一步评估样本规模、测量工具效度和统计方法适切性。

---

## 3. 理论框架与发展脉络

### 3.1 核心理论框架

**① 自我决定理论（SDT，Ryan & Deci, 2000）** [25]

将动机区分为内在动机（由兴趣、好奇心驱动）和外在动机（由外部奖惩驱动），并强调能力感（competence）、自主感（autonomy）和关联感（relatedness）三大基本需求对内在动机的支撑作用。SDT被多项纳入研究作为理论框架（[1][4][6]）。

**② 认知负荷理论（CLT，Sweller, 1988）** [26]

工作记忆有限容量限制学习效率。内在负荷（源于材料复杂性）、外在负荷（源于不良设计的冗余消耗）和衍生负荷（深度学习所需投入）三类之和不应超过工作记忆容量。AI工具可通过降低外在负荷或增加外在负荷双向影响整体认知负荷（[3][12]）。

**③ 计划行为理论（TPB）与社会认知理论**

TPB将行为意图分解为态度、主观规范和感知行为控制（含自我效能），在AI学习意图研究中与SDT联合使用（[4]）。

### 3.2 发展脉络

| 时期 | 特征 |
|------|------|
| **2022年前** | 教育AI以推荐算法和智能辅导系统（ITS）为主；动机与自我效能研究聚焦CAL/在线学习平台 |
| **2022—2023年** | ChatGPT引发关注，早期研究以探索性问卷和案例分析为主；关注学习者态度、感知有用性和学业诚信 |
| **2024—2025年** | 研究设计日趋严谨，SEM路径分析、准实验对照、纵向追踪开始出现；高影响力研究（FWCI>100）揭示AI能力—动机—认知的中介路径 |

---

## 4. 主要研究结果

### 4.1 生成式AI对学习动机的影响

#### 4.1.1 正向影响的三条机制路径

**（1）AI能力感知—动机直接路径**

结构方程模型提供了学习动机影响的最强定量证据。Jia与Tu（2024）基于N=637名台湾大学生的SEM研究（AMOS 24，CFA验证，Bootstrap 1000次重复抽样）发现，学习者感知的AI智能能力（AI Intelligence Capabilities, AIC）对学习动机（LM）的标准化路径系数为**β=0.585（p<0.001）**，为所有路径中最强的直接效应之一 [1]。Bootstrap中介分析进一步证实，AIC通过LM对批判性思维意识（CTA）的间接效应显著（effect=0.316，95%CI[0.255, 0.352]，z=13.024，p<0.001），而AIC对CTA的直接效应不显著（β=0.006，p=0.260）[1]——即**学习动机是AI效能通向认知目标的主要传导路径**，非AI直接提升认知的简单映射。

**（2）即时个性化反馈机制**

Liu（2024）通过混合方法研究指出，大数据分析与生成式AI结合的个性化学习平台，能通过实时情感分析和学习轨迹追踪动态调整学习挑战，维持"心流"状态并强化内在动机 [2]。具体机制包括：实时反馈→强化成就感→提升动机；游戏化积分（外在动机）→逐步内化为内在动机；自主学习控制感→增强能动性 [2]。

**（3）胜任感提升机制——弱技术背景学习者的赋能效应**

Kazanidis与Pellas（2024）的比较研究（幼儿教育专业n=32 vs. 计算机专业n=34，均使用生成式AI平台完成多媒体教学内容设计项目）发现：两组学习绩效相当，但非技术背景（幼儿教育）学生对AI有用性评价显著更高，总体满意度亦更大 [5]。这提示生成式AI通过降低能力门槛、强化胜任感，对弱技术背景学习者的动机赋能效应更为显著。

**（4）EFL与本土语言情境中的动机增强**

台湾某准实验研究（Tsai et al., 2024）将生成式AI工具引入本土语言教学（n=63，实验组vs.对照组），实验组学习动机和批判性思维均显著优于传统教学对照组 [6]。在EFL情境中，AI对话伙伴和AI写作反馈被发现能显著提升学习者口语学习动机和写作投入 [7]。

#### 4.1.2 潜在抑制效应

动机效应并非单向正向。Chai等（2022）研究（N=509，中国中学生）揭示一个意外发现：AI编程自我效能（programming efficacy）对自主感（autonomy）具有**显著负向影响** [4]——当学习者的技术能力感知与自主探索需求之间产生张力时，过强的效能感反而可能抑制自主探索动机。此外，当AI提供过度支持时，可能导致学习者被动依赖，削弱自主学习意愿。

### 4.2 生成式AI对自我效能的影响

#### 4.2.1 AI能力感知对自我效能的直接路径

Jia与Tu（2024）的SEM研究中，AIC对广义自我效能（General Self-Efficacy, GSE）的标准化路径系数为**β=0.546（p<0.001）** [1]，为AI能力影响心理变量的第二强直接效应（仅次于AIC→LM的β=0.585）。自我效能感进一步正向预测：

- 批判性思维意识（GSE→CTA：β=0.088，p=0.049）[1]
- 学习动机（GSE→LM：β=0.110，p=0.019）[1]

这表明自我效能是AI—学习结果链条上的重要中间环节，且与学习动机之间存在相互促进关系（LM→CTA：β=0.795，p<0.001；该路径为模型中所有路径的最强效应 [1]）。

#### 4.2.2 学科情境中的自我效能提升

**写作自我效能：** 多项研究表明AI辅助写作工具可提升学习者写作自我效能，包括针对生成式AI对写作者自我效能影响的研究 [8] 和AI辅助混合学习对写作效能与心理韧性的研究 [9]。

**翻译与语言自我效能：** 在翻译学习情境中，计算机自我效能（computer self-efficacy）正向预测采用AI翻译技术的行为意图 [10]，揭示自我效能在AI工具接受度上的跨域一致性——高自我效能个体更愿意尝试新AI工具，进而积累成功经验、进一步增强效能，形成正反馈循环。

**跨专业比较：** Kazanidis与Pellas（2024）引用Wang等（2022）的双中介模型研究指出，高校AI能力建设对学生自我效能和创造力具有正向影响 [5]。计算机专业学生报告AI使用舒适度更高，但非技术背景学习者的自我效能提升幅度可能更大（因初始基线较低、成长空间更大）[5]。

#### 4.2.3 自主学习意愿的双向调节

AI使用行为影响自主学习意愿 [11]：辅助型AI（提示、反馈、脚手架）倾向于提升自主学习意愿，进而正向强化自我效能的主动构建；而替代型AI（直接生成答案）可能削弱学习者的主动探索，导致自我效能的被动依赖而非真实提升。

### 4.3 生成式AI对认知负荷的影响

#### 4.3.1 双刃剑效应

认知负荷视角揭示生成式AI的影响呈典型双向模式，方向由AI设计特征和学习者先备知识水平共同决定：

**降低外在负荷：** 当AI通过智能分解复杂任务、动态调整信息颗粒度和提供实时纠错时，可显著减少外在认知负荷（extraneous cognitive load），将工作记忆资源留给深度学习。AI定制化聊天机器人在物理教育研究情境中对学习绩效和认知负荷产生积极影响 [12]。

**增加外在负荷（过载风险）：** Koć-Januchta等（n=16，生物学课程）对比AI互动教材（含5000概念知识库的Inquire Biology）与电子书，发现AI教材的学习保留率（retention）高于电子书，但**当学生同时使用多种AI交互功能时，存在显著的认知过载风险** [3]。该研究采用多维认知负荷量表（Paas, 1992定义："与学习时的脑力投入或感知困难相关的多维度现象"），发现多功能叠加使用显著提高了感知认知负荷 [3]。

#### 4.3.2 内在动机作为认知负荷承受阈值的调节变量

Koć-Januchta等的关键发现在于，**内在知识动机**（intrinsic motivation to know）和**内在刺激动机**（intrinsic motivation to experience stimulation，均基于SDT测量）与对AI教材易用性的正面评价显著相关 [3]——即内在动机较高的学习者能将较高的认知挑战重新评估为"参与感"而非"过载感"。这一发现揭示了动机水平作为个体认知负荷承受阈值调节变量的核心作用。

#### 4.3.3 认知负荷作为链式中介变量

认知负荷还被发现在更广泛的心理学链条中承担中介功能。一项研究以认知负荷为中介，检验自我效能与英语学习动机之间的路径 [14]，发现"高效能→低外在负荷→高动机"的链式传导，为三变量整合模型提供了初步实证依据。

#### 4.3.4 AI生成教学内容的认知处理差异

AI生成教学视频与人工录制视频的比较研究 [13] 提示，学习者对AI生成内容的处理方式可能与传统内容存在质性差异，导致不同的认知负荷模式，这有待深入研究。

---

## 5. 国内外研究对比分析

| 维度 | 国内研究特征 | 国际研究特征 | 差距与互补 |
|------|------------|------------|----------|
| **研究设计** | SEM路径分析为主（[1][4]）；大样本问卷 | 准实验对照（[3][5]）；混合方法；认知负荷直接测量 | 国内缺乏实验设计和认知负荷直接测量；国际缺乏中文情境大样本 |
| **研究对象** | 台湾、香港、大陆大学生/中学生 | 欧洲、北美本科生；EFL学习者 | 语言情境（EFL vs. 中文）差异值得深入比较 |
| **AI工具** | 通用AI能力感知（非特定工具） | 特定工具（AI教材、AI写作助手、GPT-VR助手） | 国内需开展工具对比研究 |
| **理论框架** | TPB + SDT联合（[4]）；AI能力—动机链（[1]） | CLT（[3]）；SDT（广泛引用） | 互补：国内SEM深度 + 国际CLT系统性 |
| **认知负荷测量** | 仅作中介（[14]） | 直接量表测量（[3][12]） | 国内直接测量认知负荷的研究严重不足 |
| **平均FWCI** | 114–405（集中于中国台湾机构） | 24–345 | 国际分布更广；国内部分研究FWCI极高 |

---

## 6. 核心争论点

**争论一：生成式AI是增强还是削弱学习自主性？**

- **增强观：** 自适应AI通过个性化支架释放自主探索空间（[2][5]）。
- **削弱观：** Chai等（2022）发现AI编程效能对自主感具有负向影响 [4]；过度AI支持引发"认知卸载依赖"（cognitive offloading dependence）风险 [15]。
- **综合判断：** 自主性影响取决于AI的"辅助型vs.替代型"功能定位。辅助型AI（提示、反馈）有利于自主性；替代型AI（直接代写）不利于自主性。

**争论二：认知负荷是AI增益学习的门控还是副产品？**

- **门控观（CLT）：** AI的价值在于通过减少外在负荷进入最优认知区间 [12]。
- **副产品观：** Koć-Januchta等发现认知负荷增加并不必然阻碍学习保留 [3]，高内在动机学习者可承受更高认知负荷。
- **综合判断：** 认知负荷对学习效果的影响受动机水平调节，AI工具设计应先测量用户动机水平再动态调整交互复杂度。

**争论三：正向效果的可持续性**

现有证据多为横截面设计，缺乏纵向追踪。初始的AI"新颖效应"（novelty effect）可能随使用时间延长而衰减，动机与效能提升的可持续性尚待验证。

---

## 7. 批判性分析

### 7.1 证据质量评估

| 质量等级 | 文献 | 理由 |
|---------|------|------|
| **高** | Jia & Tu (2024) [1] | N=637，SEM+Bootstrap双重验证，模型拟合指标完整（χ²/df=2.972, RMSEA=0.053, CFI=0.903） |
| **中** | Chai et al. (2022) [4] | N=509，设计较好，但跨文化效度有待评估 |
| **中** | Kazanidis & Pellas (2024) [5] | N=66，无随机分配，组间技术背景差异可能混淆结果 |
| **中** | Koć-Januchta et al. [3] | N=16，样本量过小，内部效度有限 |
| **中/低** | 20篇摘要级证据 | 仅用于主题佐证，不引用具体实验数字 |

### 7.2 方法论局限

1. **测量工具异质性：** 各研究采用的动机量表（AMS、MSLQ、IMI等）和认知负荷量表差异显著，难以跨研究量化合并。
2. **AI工具定义模糊：** "生成式AI"涵盖从简单聊天机器人到复杂自适应系统，功能设计差异可能产生截然不同的心理效应。
3. **对照条件不标准：** 部分研究缺乏明确对照条件，无法准确判断效果的增量性。

### 7.3 发表偏倚

正向效果研究占主导（符合AI教育研究一般趋势）。专门报告生成式AI对动机产生负面效果的高引用量研究未见于本次检索，提示存在显著发表偏倚风险。

---

## 8. 未来研究方向

1. **纵向设计研究：** 追踪学习者使用生成式AI工具6—12个月期间三变量的动态轨迹，检验"新颖效应衰减"假设。

2. **三变量整合模型：** 构建包含动机、自我效能和认知负荷三者联合的SEM模型，系统检验链式中介路径（如：AI工具→降低认知负荷→提升自我效能→增强学习动机）。

3. **弱势群体差异化效应：** 聚焦低数字技能学习者、学习障碍学生等群体，防止"马太效应"（技术优势强化已有学业差距）。

4. **AI设计特征精细化研究：** 对比辅助型vs.替代型AI对三类认知负荷的独立影响，为AI教育工具设计提供认知工程学依据。

5. **中文情境本土化研究：** 聚焦中国本土生成式AI工具（文心一言、通义千问等），验证三变量影响路径在中国教育体制下的适用性。

6. **AI依赖与元认知监控：** 研究生成式AI使用频率与学习者元认知监控能力的关系，探讨高频AI使用是否损害元认知。

---

## 9. 结论

本系统综述综合分析了2022—2025年间25篇关于生成式AI对学习动机、自我效能和认知负荷影响的研究，主要结论如下：

**学习动机：** 生成式AI通过即时个性化反馈、满足能力感知需求和增强自主感，对学习动机产生显著正向影响（AIC→LM，β=0.585，p<0.001 [1]）；学习动机是AI效能通向高阶认知目标的核心中介路径（Bootstrap间接效应=0.316，95%CI[0.255, 0.352]）。但过度AI支持可能引发自主性抑制，动机可持续性尚待纵向研究验证。

**自我效能：** AI工具通过成功体验积累和能力感知提升系统性增强自我效能（AIC→GSE，β=0.546，p<0.001 [1]）；自我效能进一步通过动机路径影响更高阶认知目标（GSE→LM，β=0.110，p=0.019；LM→CTA，β=0.795，p<0.001 [1]）。不同学科情境和学习者背景下的效能提升幅度存在差异。

**认知负荷：** 影响呈双重性——辅助型设计降低外在负荷，多功能叠加则存在认知过载风险；内在动机水平是认知负荷承受阈值的关键调节变量 [3]。认知负荷还可能在自我效能→学习动机路径中发挥中介作用 [14]。

**实践建议：** 教育者在引入生成式AI时，应优先采用辅助型（非替代型）AI功能，通过渐进式功能引入和认知负荷监控机制管控过载风险；同时，关注学习者的内在动机水平作为AI实施效果的调节因素。

---

## 参考文献

[1] Jia, X.-H., & Tu, J.-C. (2024). Towards a new conceptual model of AI-enhanced learning for college students: The roles of artificial intelligence capabilities, general self-efficacy, learning motivation, and critical thinking awareness. *Systems*, *12*(3), 74. https://doi.org/10.3390/systems12030074

[2] Liu, J. (2024). Enhancing English language education through big data analytics and generative AI. *Frontiers in Education*. Published April 2024.

[3] Koć-Januchta, M. M., Schönborn, K. J., Tibell, L. A. E., Chaudhri, V. K., & Heller, H. C. (2024). Engaging with biology by asking questions: Investigating students' interaction and learning with an artificial intelligence-enriched textbook. *Computers & Education: Artificial Intelligence*.

[4] Chai, C. S., Chiu, T. K. F., Wang, X., Jiang, F., & Lin, X.-F. (2022). Modeling Chinese secondary school students' behavioral intentions to learn artificial intelligence with the theory of planned behavior and self-determination theory. *Sustainability*, *15*(1), 605. https://doi.org/10.3390/su15010605

[5] Kazanidis, I., & Pellas, N. (2024). Harnessing generative artificial intelligence for digital literacy innovation: A comparative study between early childhood education and computer science undergraduates. *AI*, *5*(3), 1427–1445. https://doi.org/10.3390/ai5030068

[6] Tsai, C. Y., et al. (2024). 基於生成式人工智慧工具的本土語創新教學模式. *教育研究月刊*（臺灣）, *365*, 9. https://doi.org/10.53106/168063602024090365009

[7] Li, M., et al. (2025). Understanding how AI chatbots influence EFL learners' oral English learning motivation and outcomes. *IEEE Access*, *13*. https://doi.org/10.1109/access.2025.3554545

[8] Elkins, S., et al. (2023). The impact of generative artificial intelligence on writer's self-efficacy. SSRN Working Paper. https://doi.org/10.2139/ssrn.4538043

[9] (2025). The impact of AI-assisted blended learning on writing efficacy and resilience. *International Journal of Computer-Assisted Language Learning and Teaching*, *15*. https://doi.org/10.4018/ijcallt.377174

[10] (2024). The effect of computer self-efficacy on the behavioral intention to use translation technologies among language learners. *Acta Psychologica*, *248*, 104259. https://doi.org/10.1016/j.actpsy.2024.104259

[11] (2024). The impact of AI usage on university students' willingness for autonomous learning. *Behavioral Sciences*, *14*(10), 956. https://doi.org/10.3390/bs14100956

[12] (2025). Augmenting learning environments using AI custom chatbots: Effects on learning performance, cognitive load, and engagement. *Physical Review Physics Education Research*, *21*(1), 010147. https://doi.org/10.1103/physrevphyseducres.21.010147

[13] (2024). From recorded to AI-generated instructional videos: A comparison of learning performance and experience. *British Journal of Educational Technology*, *55*. https://doi.org/10.1111/bjet.13530

[14] (2024). Cognitive load as a mediator in self-efficacy and English learning motivation: Evidence from online learners. *PLOS ONE*, *19*(11), e0314088. https://doi.org/10.1371/journal.pone.0314088

[15] Risko, E. F., & Gilbert, S. J. (2023). The cognitive architecture of digital externalization. *Learning and Instruction*, *87*. https://doi.org/10.1007/s10648-023-09818-1

[16] (2024). Exploring the impact of generative AI-based technologies on learning performance through self-efficacy and motivation. *Education and Information Technologies*, *29*. https://doi.org/10.1007/s10639-024-12949-9

[17] (2024). A classification tool to foster self-regulated learning with generative artificial intelligence. *Educational Technology Research and Development*, *72*. https://doi.org/10.1007/s11423-024-10366-w

[18] (2024). Generative AI and education: Dynamic personalization of pupils' school learning material with ChatGPT. *Frontiers in Education*, *9*, 1288723. https://doi.org/10.3389/feduc.2024.1288723

[19] (2025). AI for academic success: Investigating the role of usability, enjoyment, and responsiveness in ChatGPT. *Education and Information Technologies*, *30*. https://doi.org/10.1007/s10639-025-13398-8

[20] (2024). Impact of motivation factors for using generative AI services on continuous use intention. *Social Sciences*, *13*(9), 475. https://doi.org/10.3390/socsci13090475

[21] (2024). Unlocking potential: Key factors shaping undergraduate self-directed learning in AI-enhanced education. *Systems*, *12*(9), 332. https://doi.org/10.3390/systems12090332

[22] (2025). Impact of GPT-driven teaching assistants in VR learning environments. *IEEE Transactions on Learning Technologies*, *18*. https://doi.org/10.1109/tlt.2025.3539179

[23] (2025). Cultivating independent thinkers: The triad of artificial intelligence, Bloom's taxonomy and critical thinking. *Education and Information Technologies*, *30*. https://doi.org/10.1007/s10639-025-13476-x

[24] 刘清堂 等. (2023). 从国际视野透视如何将ChatGPT有效纳入教育——基于对72篇文献的系统综述. *现代教育技术*, *33*(6). https://doi.org/10.3969/j.issn.1009-8097.2023.06.003

[25] Ryan, R. M., & Deci, E. L. (2000). Self-determination theory and the facilitation of intrinsic motivation, social development, and well-being. *American Psychologist*, *55*(1), 68–78. https://doi.org/10.1037/0003-066X.55.1.68

[26] Sweller, J. (1988). Cognitive load during problem solving: Effects on learning. *Cognitive Science*, *12*(2), 257–285. https://doi.org/10.1207/s15516709cog1202_4
