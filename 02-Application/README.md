# 02-Application / 技术应用

本目录收录量子计算的工作原理、系统设计、工程实现方案等技术应用相关内容。

## 分类说明

- **工作原理** — 量子比特的物理机制、量子门操作原理
- **系统设计** — 量子处理器架构、量子算法设计、纠错方案
- **工程实现** — 硬件实现、量子编程、算法优化

## 文件命名规范

`[年份]-[作者/机构]-[标题].pdf`

## 资料索引

### 系统设计与实现

- [Qiskit 电路构建](https://docs.quantum.ibm.com/build/circuit-gallery) - 使用 Qiskit SDK 构建量子电路的详细指南
- [Qiskit 优化转换](https://docs.quantum.ibm.com/transpile/optimize) - 构建高保真度量子电路的优化技术
- [Qiskit 错误缓解](https://docs.quantum.ibm.com/verify/error-mitigation) - 错误缓解和抑制技术文档
- [Qiskit Runtime 执行](https://docs.quantum.ibm.com/execute/runtime) - 在 IBM Quantum 硬件上运行量子电路
- [Cirq 电路模拟](https://quantumai.google/cirq/simulation) - 内置模拟器（波函数、密度矩阵）使用指南
- [Cirq 噪声建模](https://quantumai.google/cirq/noise) - 噪声通道模拟和硬件设备建模

### 量子硬件架构

#### 超导量子计算
- IBM、Google 采用的量子比特技术路线
- 量子比特类型：Transmon 量子比特
- 冷却温度：接近绝对零度（15mK）
- 优势：扩展性好、门速度快
- 代表处理器：IBM Eagle、Heron、Google Sycamore

#### 离子阱量子计算
- IonQ、Quantinuum 采用的量子比特技术路线
- 量子比特类型：电离镱原子（Yb+）或钡离子
- 囚禁方式：线性离子阱
- 优势：全连接架构、高保真度（99.99%+）、长相干时间
- 代表系统：IonQ Aria、Forte、Quantinuum H 系列

#### 中性原子量子计算
- Infleqtion、Pasqal、QuEra 采用的可扩展技术路线
- 量子比特类型：里德堡原子
- 优势：可扩展至数百万量子比特、可编程连接
- 应用：量子计算与量子传感

#### 光量子计算
- PsiQuantum 采用的技术路线
- 量子比特类型：光子
- 优势：室温运行、量子比特不易退相干

### 量子算法应用

#### 量子算法实现平台
- [Shor 算法实现](https://quantumalgorithmzoo.org/) - 质因数分解算法
- [Grover 算法实现](https://quantumalgorithmzoo.org/) - 量子搜索算法
- [QAOA 实现](https://quantumai.google/cirq/examples#qaoa) - 组合优化算法
- [HHL 算法](https://arxiv.org/abs/0811.3171) - 线性方程组求解

#### 量子机器学习
- [TensorFlow Quantum](https://www.tensorflow.org/quantum) - 量子与深度学习结合
- [PennyLane QML](https://pennylane.ai) - 量子机器学习框架
- [量子生成模型](https://pennylane.ai/blog/) - 量子增强的生成式 AI

#### 量子化学与材料科学
- [OpenFermion](https://github.com/quantumlib/OpenFermion) - 量子化学计算开源工具
- [分子模拟](https://pennylane.ai) - 药物研发和材料设计

### 错误纠正与容错

#### 最新研究进展
- [量子 LDPC 码快速解码](https://ionq.com/blog) - IonQ 关于量子 LDPC 码的快速软件解码研究
- [Walking Cat 架构](https://ionq.com/blog) - 容错离子阱量子计算架构蓝图（2026年4月）
- [双物种原子纠错](https://www.infleqtion.com) - Infleqtion 先进纠错平台技术

#### 容错路线图
- IBM Quantum 路线图：2028 年实现 100,000 物理量子比特
- Infleqtion 路线图：2028 年实现 100+ 逻辑量子比特
- IonQ：99.99% 双量子比特门保真度

### 实际应用场景

#### 金融行业
- [量子投资组合优化](https://ionq.com/blog) - IonQ 与华尔街头部公司合作
- [量子蒙特卡洛方法](https://ionq.com/blog) - 金融建模

#### 汽车与物流
- [量子优化调度](https://ionq.com/blog) - IonQ 与 Einride 合作优化电动货运
- [自动驾驶优化](https://ionq.com/blog) - 量子计算在自动驾驶中的应用

#### 航空航天
- [量子计算流体动力学](https://pennylane.ai/blog/) - PennyLane 与 Rolls-Royce、AMD 合作
- [量子导航](https://www.q-ctrl.com) - Q-CTRL Ironstone Opal GPS 拒止环境导航

#### 化学与制药
- [分子模拟](https://pennylane.ai) - 药物发现和材料科学
- [催化剂设计](https://pennylane.ai) - 工业化学优化

### 量子云平台

- [IBM Quantum Platform](https://quantum.cloud.ibm.com) - 云端量子计算服务
- [IonQ Cloud](https://ionq.com/cloud) - IonQ 量子云平台
- [Amazon Braket](https://aws.amazon.com/braket) - AWS 量子云服务
- [Azure Quantum](https://azure.microsoft.com/quantum) - 微软 Azure 量子云服务

---

*最后更新: 2026-05-07*
