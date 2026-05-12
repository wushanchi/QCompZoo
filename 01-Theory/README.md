# 01-Theory / 理论基础

本目录收录量子计算相关的经典论文、学术资料和基础科普内容。

## 分类说明

- **经典论文** — 量子计算领域的开创性研究论文（PDF格式）
- **学术资料** — 综述文章、教材章节、课程讲义
- **基础科普** — 面向初学者的入门资料

## 文件命名规范

`[年份]-[作者/机构]-[标题].pdf`

## 资料索引

### 2026 年重大研究突破

#### 量子比特相干时间突破（Princeton, Nature 2026）
- **研究团队**：美国普林斯顿大学
- **发表期刊**：Nature
- **突破**：超导量子比特「寿命」（相干时间）提升至超过 **1 毫秒**
- **意义**：
  - 实验室最佳版本的 **3 倍**
  - 业界标准的 **近 15 倍**
  - 10 多年来量子比特寿命的**最大提升**
- **影响**：相干时间越长，量子计算越稳定，是实现实用量子计算的关键指标

#### 中科院物理研究所 RMD 技术（Nature 2026）
- **研究机构**：中国科学院物理研究所
- **技术**：随机多极驱动（RMD）技术
- **突破**：通过调节驱动序列的复杂度和节奏，成功实现对预热化平台持续时间的精准控制
- **意义**：为大规模量子计算提供了新的控制方法

#### 量子机器学习进展
- [Shadow Tomography](https://arxiv.org/abs/1709.06648) - Scott Aaronson 提出的量子态高效学习技术
- [Variational Quantum Algorithms](https://arxiv.org/abs/2012.00827) - 变分量子算法综述
- [Quantum Natural Language Processing](https://arxiv.org/abs/2106.07064) - 量子自然语言处理

### 综述与教程

- [Qiskit 官方文档](https://docs.quantum.ibm.com/) - IBM 官方 Qiskit 量子编程框架文档，包含快速入门、教程和 API 参考
- [Cirq 官方文档](https://quantumai.google/cirq) - Google 量子编程框架 Cirq 的完整文档和教程
- [Cirq GitHub 仓库](https://github.com/quantumlib/Cirq) - Python 框架，用于创建、编辑和运行 NISQ 量子电路，5k+ stars
- [PennyLane 官方网站](https://pennylane.ai) - 量子机器学习框架，支持多种量子计算平台
- [IBM 量子学习平台](https://quantum.cloud.ibm.com/learning) - IBM 官方量子计算学习资源

### 量子编程框架

- [Qiskit 文档](https://docs.quantum.ibm.com/) - 电路构建、优化、错误缓解、执行后处理等完整指南
- [Cirq 快速入门](https://quantumai.google/cirq/start/start) - Google Cirq 入门教程
- [Cirq 参考文档](https://quantumai.google/reference/python/cirq/all_symbols) - Cirq 全符号参考
- [TensorFlow Quantum](https://www.tensorflow.org/quantum) - 量子机器学习结合框架

### 算法与理论

#### 核心量子算法
- [Shor 算法](https://en.wikipedia.org/wiki/Shor%27s_algorithm) - 大数质因数分解的量子算法，1994年Peter Shor提出，多项式时间分解大整数
- [Grover 算法](https://en.wikipedia.org/wiki/Grover%27s_algorithm) - 量子搜索算法，1996年Lov Grover提出，将搜索复杂度从 O(N) 降至 O(√N)
- [HHL 算法](https://arxiv.org/abs/0811.3171) - 求解线性系统的量子算法
- [VQE (变分量子特征值求解器)](https://en.wikipedia.org/wiki/Variational_quantum_eigensolver) - 量子化学计算的经典-量子混合算法
- [QAOA (量子近似优化算法)](https://en.wikipedia.org/wiki/Quantum_approximate_optimization_algorithm) - 组合优化问题的量子算法

#### 前沿算法研究
- [QSVT (量子奇异值变换)](https://arxiv.org/abs/2209.14840) - 统一的量子算法范式，连接多种量子算法
- [Shadow Tomography](https://arxiv.org/abs/1709.06648) - Scott Aaronson 提出的量子态高效学习技术
- [Quantum Singular Value Transformation](https://arxiv.org/abs/1805.00609) - QSVT 基础论文

### 经典论文与开创性工作

- [BosonSampling](https://arxiv.org/abs/1010.1625) - Scott Aaronson 提出的展示量子优势的方案
- [PostBQP](https://arxiv.org/abs/quant-ph/0412187) - 后选择量子计算机可解决的问题类
- [BB84 量子密钥分发](https://ieeexplore.ieee.org/document/1055394) - Bennett 和 Brassard 的开创性量子密码协议，2026年获图灵奖
- [量子霸权论文](https://nature.com/articles/s41586-019-1666-3) - Google Sycamore 处理器实现量子霸权
- [Quantum Supremacy using Superconducting Processors](https://arxiv.org/abs/1910.09533) - Google 量子霸权实验详细论文

### 开源项目与工具

- [Qiskit GitHub](https://github.com/Qiskit) - IBM 量子计算开源项目集合
- [Cirq 相关项目 Qualtran](https://github.com/quantumlib/Qualtran) - 容错量子计算研究工具
- [Cirq 相关项目 Stim](https://github.com/quantumlib/Stim) - Clifford 运算模拟器
- [OpenFermion](https://github.com/quantumlib/OpenFermion) - 量子化学计算开源工具
- [Quantum Algorithm Zoo](https://quantumalgorithmzoo.org/) - 量子算法实现资源汇总

### 量子计算博客与专家

- [Scott Aaronson "Shtetl-Optimized"](https://scottaaronson.blog/) - "The Internet's Most Trusted Quantum Computing Blog Since 2005"，UT Austin 教授，量子信息领域权威
- [Q-CTRL 技术博客](https://www.q-ctrl.com/blog) - 量子控制技术博客，量子优势研究
- [IonQ 博客](https://ionq.com/blog) - 离子阱量子计算技术博客，100+ 篇技术文章
- [PennyLane 博客](https://pennylane.ai/blog/) - 量子机器学习博客
- [IBM Quantum 博客](https://quantum.cloud.ibm.com/) - IBM 量子计算博客

### 学术期刊与会议

- [Quantum - Open Journal for Quantum Science](https://quantum-journal.org/) - 开放获取量子科学期刊，已发表 2097+ 篇论文
- [NIPS/ NeurIPS Quantum Computing Workshop](https://neurips.cc/) - 神经信息处理系统大会量子计算工作坊
- [QIP (Quantum Information Processing) 2026](https://qip2026.info/) - 量子信息处理顶级会议，2026年举行

### 教科书与教材

- [Michael Nielsen & Isaac Chuang "Quantum Computation and Quantum Information"](http://mmrc.amss.cas.cn/tlb/201702/W020170224608149940813.pdf) - 量子计算经典教材（英文版）
- [Preskill 量子计算笔记](https://theory.caltech.edu/~preskill/ph219/) - Caltech John Preskill 教授的量子计算课程笔记

---

*最后更新: 2026-05-12*
