# BlockChain_Conference

1. [Network] Modeling the Impact of Network Connectivity on Consensus Security of Proof-of-Work Blockchain (InfoCom'20)
   - Proposing a novel **analytical model** to assess the impact of **network connectivity** on the **security** of PoW-based blockchain consensus systems. 
2. [Off-chain] Secure Balance Planning of Off-blockchain Payment Channel Networks (InfoCom'20)
   - Instead of struggling with consensus mechanism design, **payment channels** have been proposed to address the **scalability** challenge by creating a private channel between two blockchain nodes. 
   - A critical challenge in payment network construction is to decide **how many funds should be deposited into payment channels as initial balances**, which seriously **influences the performance of payment networks**, but has been seldom studied by existing work. 
   - Address this challenge by designing PnP, a balance planning service for payment networks. 
3. [Application] A Blockchain based Witness Model for Trustworthy Cloud Service Level Agreement Enforcement (InfoCom'19)
   - Prove the credibility of possible violations in the **SLA** before recording them onto the blockchain. 
   - To tackle this challenge, we propose **a witness model** using game theory and **the smart contract techniques**
4. [Scalability] ACCEL: Accelerating the Bitcoin Blockchain for High-throughput, Low-latency Applications (InfoCom'19)
   -  describes ACCEL, a new Bitcoin-compatible **consensus algorithm** that couples **high transaction throughput** with a low-latency and deterministic transaction and block confirmation mechanism.
5. [Security] Corking by Forking: Vulnerability Analysis of Blockchain
   - A well-known attack in Blockchain is the **forking attack**, where divergent blockchains are produced for inserting some new features to facilitate security
breaches. 
   -  To take precautions, we employ the large deviation theory to **study the vulnerability of blockchain networks incurred by intentional forks** from a micro point of view, boosting forward-looking and strategic planning mechanisms for resisting the forking attack. 
6. [Transaction] Understanding ethereum via graph analysis (InfoCom'18)
   - the first **systematic study on Ethereum** by leveraging **graph analysis** to characterize three major activities on Ethereum, namely money transfer, smart contract creation, and smart contract invocation.
7. [Network] Stochastic Models and Wide-Area Network Measurements for Blockchain Design and Analysis
   - As Blockchain networks evolve to industrial deployments with large numbers of geographically distributed nodes, **the block transfer and processing delays** arise as a critical issue 
   - analyze the impact of the block dissemination delay and hashing power of the member nodes on Blockchain performance in terms of **the overall block generation rate and required computational power for launching a successful attack**.

总结：以上为近几年InfoCom（计算机网络）在区块链领域的论文，大部分都是提出分析模型，少部分是针对某一个场景设计新的模型，或是全新的共识算法（个人以为这个要求的数学基础最高）。

8. [System] Monoxide: Scale out Blockchains with Asynchronous Consensus Zones (NSDI'19)
   - **low throughput** has significantly hindered the scalability and usability of cryptocurrency systems for increasing numbers of users and transactions.   
   - Another **obstacle to achieving scalability** is the requirement for every node to **duplicate the communication, storage, and state representation of the entire network**.
   - introduce **the Asynchronous Consensus Zones**, which scales blockchain system linearly without compromising decentralization or security. 
9. [Consensus] Bitcoin-NG: A Scalable Blockchain Protocol (NSDI'16)   
   - Bitcoin-derived blockchain protocols have inherent **scalability limits** that trade off between throughput and latency, which withhold the realization of this potential.
   - presents Bitcoin-NG (Next Generation), a new blockchain protocol designed to scale.

总结：近几年发表在NSDI上有关区块链的论文比较少，仅有的2篇基本都是关于解决可扩展性，低吞吐量的，设计机制或是新的协议。

