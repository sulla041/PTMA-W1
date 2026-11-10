# DAC 2027 Paper Title & Abstract (Concise Circuit Metric Prediction Edition)

## 1. Title Candidates (精炼版论文题目)

- **Option 1 (Yihan's Original · 纯粹原版旗舰)** 🏆:  
  **Beyond Message Passing: Element Interaction Dynamics for Circuit Representation Learning**  
  *(超越消息传递：面向电路表征学习的元素相互作用动力学)*

- **Option 2 (Metric-Prediction Focused · 明确指标预测版)**:  
  **Beyond Message Passing: Element Interaction Dynamics for Circuit Metric Prediction**  
  *(超越消息传递：面向电路指标预测的元素相互作用动力学)*

- **Option 3 (Comprehensive · 表征与指标双驱版)**:  
  **Beyond Message Passing: Element Interaction Dynamics for Circuit Representation and Metric Prediction**  
  *(超越消息传递：面向电路表征与指标预测的元素相互作用动力学)*

---

## 2. Submission Portal Plaintext Abstract (规范学术纯文本版, 212 words)

In electronic design automation, modeling circuits with neural networks is critical for fast and accurate circuit metric prediction. While circuits are naturally represented as graphs, conventional paradigms face fundamental dilemmas. Node and edge features are difficult to align into a unified modality, which forces existing models to discard edge parasitics or compress them into scalars. Furthermore, deep aggregation along multi-hop logic chains induces severe over-smoothing and representation collapse.

To resolve these challenges, we propose an Element Interaction Dynamics framework that models circuit behavior from the perspective of particle interaction physics. We first project heterogeneous circuit components, including standard cells, pins, and wire interconnects, into a unified point set of homogeneous physical elements. Within this set, every element pair with an electrical relationship evolves through a learnable interaction field. Specifically, a pairwise displacement operator takes the joint states and continuous physical impedances, such as wire resistance, parasitic capacitance, and driver loads, to compute unconstrained vector displacements in a continuous latent space. Concurrently, a localized sibling-competition mechanism dynamically arbitrates multi-fanin drive contention, preserving causal monotonicity along deep combinational chains without feature decay.

Extensive evaluations on industrial circuit designs demonstrate that by directly simulating how fundamental elements interact and accumulate physical effects, our framework eliminates over-smoothing, preserves full relational physics, and achieves superior accuracy across diverse circuit metric prediction tasks.

---

## 3. Bilingual Abstract & Methodological Deep Dive (中英双语严谨学术句式)

### [Part 1: Context & Core Dilemmas / 背景与两大死穴]
- **EN**: In electronic design automation, modeling circuits with neural networks is critical for fast and accurate circuit metric prediction. While circuits are naturally represented as graphs, conventional paradigms face fundamental dilemmas. Node and edge features are difficult to align into a unified modality, which forces existing models to discard edge parasitics or compress them into scalars. Furthermore, deep aggregation along multi-hop logic chains induces severe over-smoothing and representation collapse.
- **ZH**: 在电子设计自动化领域，利用神经网络对电路建模以实现指标的快速准确预测至关重要。尽管电路天然可以表示为图，但传统图建模范式面临根本性困境。节点与边的高维特征难以对齐为统一模态，迫使现有模型忽略走线寄生参数或将其粗暴压缩为标量权重。此外，沿着深层多跳逻辑链的反复聚合必然引发特征过平滑与表征崩溃。

### [Part 2: Method Detail 1 · 元素点集统合 / Unified Physical Element Set]
- **EN**: To resolve these challenges, we propose an Element Interaction Dynamics framework that models circuit behavior from the perspective of particle interaction physics. We first project heterogeneous circuit components, including standard cells, pins, and wire interconnects, into a unified point set of homogeneous physical elements.
- **ZH**: 为破解这些困境，我们提出元素相互作用动力学框架，从粒子相互作用物理的第一性原理出发对电路行为进行建模。我们首先将电路中包括标准单元门、引脚端口与走线互连在内的异构实体，统合投影为单一且均质的物理元素点集。

### [Part 3: Method Detail 2 · 成对位移矢量场与物理阻抗 / Pairwise Displacement Fields]
- **EN**: Within this set, every element pair with an electrical relationship evolves through a learnable interaction field. Specifically, a pairwise displacement operator takes the joint states and continuous physical impedances, such as wire resistance, parasitic capacitance, and driver loads, to compute unconstrained vector displacements in a continuous latent space.
- **ZH**: 在该点集中，存在电气关联的每一对元素都在可学习的相互作用场中向前演化。具体而言，成对位移算子结合双方的联合状态与连续物理阻抗，如导线电阻、寄生电容与驱动负载，在连续隐空间中直接计算不受人为截断约束的高维自由位移矢量。

### [Part 4: Method Detail 3 · 局部同伴竞争与因果单调性 / Sibling Competition Arbitration]
- **EN**: Concurrently, a localized sibling-competition mechanism dynamically arbitrates multi-fanin drive contention, preserving causal monotonicity along deep combinational chains without feature decay.
- **ZH**: 与此同时，框架引入局部同伴竞争机制，对多扇入引脚的驱动争夺进行排他性动态仲裁，在超深组合逻辑长链中严格捍卫时间因果单调性，彻底杜绝特征衰退。

### [Part 5: Overall Impact / 总体效果与物理自发涌现]
- **EN**: Extensive evaluations on industrial circuit designs demonstrate that by directly simulating how fundamental elements interact and accumulate physical effects, our framework eliminates over-smoothing, preserves full relational physics, and achieves superior accuracy across diverse circuit metric prediction tasks.
- **ZH**: 在工业级电路设计上的系统评测表明，通过直接模拟基本物理元素之间的相互作用与物理效应的累加自发涌现，我们的框架天然消除了过平滑，完整保全了连续关系物理特性，并在各类电路指标预测任务中取得了大幅超越传统方法的卓越精度。

---

## 4. Metadata for Submission Portal (投稿系统元信息)
- **Primary Subject Area**: CAD2. Physical Design and Machine Learning for CAD (Timing, Power, and PPA Optimization)
- **Alternative Subject Area**: CAD1. Logic, High-Level Synthesis and Circuit Representation
- **Keywords**: Deep Learning for CAD, Static Timing Analysis, Hierarchical Graph Reduction, Circuit Dynamics, Physics-Informed ML, Physical Design PPA.
