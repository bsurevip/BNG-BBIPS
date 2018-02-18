# BBIPs & Roadmap

社区力量驱动Byteball 和 Bsure的持续改进和发展，下面是Bsure技术革新发展路线图的一部分：

1)	对于全数据节点（例如Witnesses见证人节点），增添SuperNode超级节点支持，引入分布式SQL数据引擎，在存储容量上达到PB级别，在计算能力上支持同步扩展，在速度上通过多实例计算资源和SQL表达式下推优化，成级数提升处理速度

2)	引入 POC （Proof of Contribution）贡献证明机制算法。利用POC机制可以实现Witness 自动推荐选举机制，最后决定依然由用户来确认，我们认为利用 PoC算法，可以做到在鼓励用户参加与贡献的同时，达到一定的攻击防范效果

3)	对于轻节点， 引入SQL表达式算法优化，提升轻节点处理速度；1和2两步改进将指数级提升DAG区块链的容量与速度扩展问题，初步实现区块链商用化处理和系统能力

4)	分离共识层、逻辑层与数据层， 改造Byteball现有的SQL紧耦合底层架构，提升系统架构的扩展能力

5)	增加“Instant Transaction”闪电支付类型，用于小额支付及时成交，小额支付将在得到1个见证人确认后返回

6)	引入抗量子计算密码 ，并实现够抵抗量子计算机攻击的密码体制。此类加密技术的开发采取传统方式,即基于特定数学领域的困难问题, 通过研究开发算法使其在网络通信中得到应用,从而实现保护数据安全的目的

7)	除了byteball 原生的强大安全的“可定义合约”，在逻辑层，BSURE将基于Chrome V8引擎、并引入webassembly技术，打造全新的虚拟机HVM与“图灵完备的智能合约”，实现 Bsure 安全完备的可编程商业智能基础

8)	在共识层， 设计部署“sharding-分片”机制，结合见证人同步和路由机制，彻底解决区块链的扩展和容量问题

9)	设计引入Hash Universe 跨链交易机制，通过HU来实现跨链交易（完全兼容Byteball）并通过HU来实现Byteball、IOTA等基于DAG链条的跨链交易（后继增加bitcoin, etherum跨链交易），从跨链角度解决互通和数据扩展问题

10)	 BNG将推出企业版EBB特性选项，取消Byte交易费，EBB 将成为免交易费的企业优化DAG DLT，增加Witness许可机制和身份认证机制，仅许可准入的witness可以被认可使用, 使其更适用与企业/商业机构应用要求

11)	 我们将定制一系列基础就绪的内置链上应用服务商店， 包括KYC 、Exchanges 、Oracles；

# Byteball Improvement Proposals and Bsure Development RoadMap

Community forces drive the continuous improvement and growth of Byteball ，Bsure as part of the roadmap for Bsure's technological innovation and development:

1) Add super-node support for Full data nodes (such as Witnesses  nodes), introduce distributed SQL data engine, achieve PB level in storage capacity, support synchronous expansion in computing power, and speed up multi-instance computation Resources and SQL expressions are pushed down to levels to increase processing speed

2) Introduce POC (Proof of Contribution) contribution proof mechanism algorithm. Witness POC mechanism can be used to automatically recommend the election mechanism, the final decision is still confirmed by the user, we believe that the use of PoC algorithm can be done to encourage users to participate in and contribute to achieve a certain degree of attack prevention effect

3) For light nodes, the algorithm of SQL expression is introduced to optimize the processing speed of light nodes; the improvement of 1 and 2 will exponentially increase the capacity and speed expansion of DAG blockchain, and the initial implementation of blockchain commercialization and system ability

4) Separation of the consensus layer, the logic layer and the data layer, transformation of Byteball existing SQL tightly coupled to the underlying architecture to enhance the scalability of the system architecture

5) Add "Instant Transaction" lightning payment type, which is used for prompt payment of small amount of payment. The small payment will be returned after receiving confirmation from 1 witness

6) The introduction of anti-quantum computing password, and to achieve enough to resist quantum computer attacks password system. The development of this kind of encryption technology adopts the traditional way, that is, based on the difficult problem in the specific math field, through the research and development of algorithms to make it be used in network communication, so as to achieve the goal of data security

7) In addition to the "definable contract" inherent in byteball's native security, at the logical level BSURE will build on the Chrome V8 engine and introduce webassembly technology to create a completely new virtual machine HVM and Turing Complete Smart Contract for Bsure Security Complete programmable business intelligence foundation

8) At the consensus level, the "sharding-fragmentation" mechanism is designed and deployed to fully address the expansion and capacity issues of the blockchain in conjunction with witness synchronization and routing mechanisms

9) Design Hash Universe cross-chain transaction mechanism, realize cross-chain transaction with HU (fully compatible with Byteball) and realize cross-chain transaction based on DAG chain (subsequent bitcoin and etherum cross-chain transactions) Solve interoperability and data expansion issues from a cross-chain perspective

10) BNG will launch Enterprise EBB Feature Options, cancel Byte transaction fees, EBB will become a transaction free enterprise optimization DAG DLT, increase Witness licensing mechanism and identity authentication mechanism, only allow access witness can be used to make it More applicable and business / commercial application requirements

11) We will customize a series of well-established built-in application service stores including KYC, Exchanges and Oracles;


