# Blockchain-based data sharing 
---

Blockchain-based data sharing seems to be a current hot research topic, This repository aims to provide a curated list of research papers focusing on Blockchain-based data sharing

---
[Blockchain-Based Privacy-Preserving Positioning Data Sharing for IoT-Enabled Maritime Transportation Systems](https://ieeexplore.ieee.org/abstract/document/9843902)

2023 - IEEE Transactions on Intelligent Transportation Systems

Topics & Tools: Position Sharing, Maritime Transportation, Privacy Preserve, Merkle Commit, Zero Knowledge;

<details>

<summary>Abstract</summary>
Data-driven applications play an important role in modern-time maritime transportation systems, for instance in facilitating decision-making relating to communication and safety. One example application is position data sharing between vessels within the maritime Internet of Things (IoT)-enabled context. When designing such applications, we need to also consider how to ensure data accuracy as well as privacy in a large scale deployment. In this paper, we demonstrate the potential of using blockchain to facilitate privacy-preserving data sharing. Specifically, we develop a zero-knowledge proof-based scheme to protect vessel identities while allowing data sharing, and a commitment-based approach to ensure relationship-related privacy in data trading between participants. Our security and performance evaluations demonstrate the utility of the proposed approach.

</details>

---

[Privacy-preserving and efficient data sharing for blockchain-based intelligent transportation systems](https://www.sciencedirect.com/science/article/pii/S0020025523004462?casa_token=B0GENpL03yUAAAAA:7tHyLOmKQgS6VQ9jNCbJ7jJD6y39xyOIrIeRjegc_3iAUjbdkbnzAxZtrNzOqr2H-YiCT_cM)

2023 - Information Sciences

Topics & Tools: Data retrieval optimization, Bloom Filter;

<details>

<summary>Abstract</summary>

Recent years have witnessed the development and adoption of blockchain technology in intelligent transportation systems (ITS) because of its authenticity and traceability. However, increasing ITS devices impose grand challenges in privacy-preserving and efficient data sharing. Recent research has demonstrated that integrating searchable symmetric encryption in blockchain enables privacy-preserving data sharing among ITS devices. However, existing solutions focus only on single-keyword searches over encrypted ITS data on the blockchain and suffer from privacy and efficiency issues when extended to multi-keyword scenarios. This work proposes a bloom filter-based multi-keyword search protocol for ITS data with enhanced efficiency and privacy preservation. We design a bloom filter to select a low-frequency keyword from the multiple keywords input by the ITS data owner. The low-frequency keyword can filter out a large portion of the ITS data from the search result, thus significantly reducing the computational cost. Furthermore, each identifier-keyword pair is attached with a pseudorandom tag that enables the completion of a search operation in only one round. In this manner, privacy is preserved because there are no intermediate rounds and results. In addition to the multi-keyword search protocol, we specify the addition and deletion protocols to enable dynamic updates of data records. We conducted a comprehensive performance evaluation of the protocols. The experimental results indicate that the proposed multi-keyword search protocol saves 14.67% query time and 59.96% financial cost.

</details>

---

[EBSS: A secure blockchain-based sharing scheme for real estate financial credentials](https://link.springer.com/article/10.1007/s11280-022-01106-2)

2023 -   World Wide Web Journal 

Topics & Tools: Financial Credential, Commitment, Group signature;

<details>

<summary>Abstract</summary>

With the development of Internet finance, the real estate financial credentials have been extensively utilized in capital and trading markets. The extensive use of these private credentials, e.g., exchange, circulation or sharing on public clouds, can cause severe security and privacy problems. Existing security solutions for financial credentials may either introduce undesired overhead or fail to provide traceability and anonymity for data sharing. In this paper, we propose an enhanced blockchain-based secure sharing scheme for real estate financial credentials, providing the following three properties: credential confidentiality, anonymous authentication, identity tracking and transaction auditing. A comprehensive evaluation, including security analysis, efficiency analysis and simulation evaluation, is presented to show the security and feasibility of the proposed scheme.

</details>

---

[Secure and Distributed IoT Data Storage in Clouds Based on Secret Sharing and Collaborative Blockchain](https://ieeexplore.ieee.org/abstract/document/9947313)

2023 - IEEE/ACM Transactions on Networking

Topics & Tools: Consensus optimization, Data retrieval optimization, IoT scenarios, Secret sharing;

<details>

<summary>Abstract</summary>

With the rapid development of 5G/6G, most Internet of Things (IoT) devices will embrace wireless connection in the near future. A public concern is how to securely organize, store and retrieve data generated from IoT devices. Many cloud-based IoT data storage schemes have been proposed recently. However, for an untrusted or vulnerable cloud server, the stored IoT data can be easily accessed, modified and even destroyed given that the IoT data are stored in total centralization. Moreover, the servers in a cloud are generally homogeneous and thus vulnerable to attacks. For improvements, we design a novel framework for secure and efficient IoT data storage based on secret sharing and a collaborative blockchain. First, an ultra-lightweight secret sharing algorithm is designed to map original messages generated by IoT devices to a set of shorter message shares. Second, all the shares of IoT messages are separately delivered to different clouds for storage. To guarantee the security of shares, the delivery is notarized on a proposed blockchain. Specifically, both hash values of the shares and their information of location are embedded in blocks which are then chained to form a blockchain. Third, we create a balanced index structure about the shares for each cloud storage node based on the information in the blockchain, and we also propose a depth-first data search algorithm to improve IoT data retrieval efficiency. Theoretical analysis and simulation results illustrate that our scheme can store and retrieve the IoT data securely and efficiently.

</details>

---

[Blockchain-Based Fair and Fine-Grained Data Trading With Privacy Preservation](https://ieeexplore.ieee.org/abstract/document/10058012)

2023 - IEEE Transactions on Computers

Topics & Tools: Data Trading, Privacy Preservation, Attribute-based anonymous credentials, zero-knowledge proof;

<details>

<summary>Abstract</summary>

In this article, we propose a blockchain-based fair and privacy-preserving data trading scheme that supports fine-grained data selling. First, to achieve fairness for trading participants, by incorporating attribute-based credentials, encryption, and zero-knowledge proof, we design a data trading scheme where a buyer first publishes the required data attributes on the blockchain, and a data seller can demonstrate data availability in ciphertext by only disclosing the required attributes to a data buyer and proving the authenticity of data. A data buyer transfers funds only if the correct key material is uploaded to the blockchain. Second, to guarantee fine-grained data trading and preserve identity privacy, we build a Merkle hash tree on the ciphertexts of data with a signature on its root node, which allows a data seller to split data into blocks and remove the sensitive information from the data without affecting data availability verification. The public key of the data seller is not leaked to the data buyer during the trading. Moreover, different trading transactions from the same data seller cannot be linked. We formally prove that our scheme achieves the desired security properties: fairness and privacy preservation. Simulation results demonstrate the feasibility and efficiency of the proposed scheme.

</details>

---

[Blockchain-based decentralized data dissemination scheme in smart transportation](https://www.sciencedirect.com/science/article/pii/S1383762122002855?casa_token=mWgL_u5mVjEAAAAA:v7RLr8-e2ut6Ym1dc3fEHK16mBUJdvRBjgTNEkiUhQUMB54ryRzKpDsg8AJRJIIdd1NkuhH1)

2023 -   Journal of Systems Architecture

Topics & Tools: Consensus optimization, Internet of Vehicles, PoS, Group Signature;

<details>

<summary>Abstract</summary>

Data dissemination of safety messages in smart transportation allows vehicles to broadcast safety-related information about their surroundings to other vehicles within their proximity for early warnings of endangering events. Safety can only be achieved if the data transmitted are reliable. However, this may violate the privacy of a vehicle. At the same time, malicious or defective vehicles should be held accountable when misbehavior occurs. Utilizing blockchain technology, we propose a secure data dissemination scheme for smart transportation that solves the conflicting security requirements of reliability, privacy and accountability simultaneously, which provides a desirable level of security through its decentralized system. The analysis evaluation and simulation experiments signify our proposed scheme achieves security and performance efficiency, robust against adversarial attacks and practical for real world deployment.

</details>

---

[Blockchain Empowered Secure Video Sharing With Access Control for Vehicular Edge Computing](https://ieeexplore.ieee.org/abstract/document/10120606)

2023 - IEEE Transactions on Intelligent Transportation Systems

Topics & Tools: Access Control, Edge Computing, Attribute-based Encryption;

<details>

<summary>Abstract</summary>

The dramatically growing trend of vehicles equipped with driving camera recorders has allowed realizing real-time crowdsourced video sharing in vehicular edge computing (VEC). Such cameras can assist in monitoring objects directly in front of and behind the vehicles, enabling them to provide important visual information through real-time video streaming in case of possible accidents. Exploiting the on-board units (OBUs) for VEC can allow drivers and passengers to share and access on-road video surveillance services. However, data security and privacy concerns of video generators (owners) are two key challenges that can severely limit video sharing in a VEC environment. In this article, we propose a blockchain empowered publish/subscribe (P/S) scheme to enable one-to-many secure video sharing in the VEC scenario. Then, we design an attribute-based encryption algorithm with static and dynamic attributes (ABE-SD) to achieve fine-grained access control in a mobile environment. Finally, We utilize permissioned blockchain and smart contracts to record access policy and publish and subscribe events, thus resulting in user self-certification and event traceability. The numerical results indicate that our proposed scheme ABE-SD outperforms traditional centralized CP-ABE methods in terms of encryption and decryption performance. The simulation experiments demonstrated that the proposed video-sharing scheme is secure and efficient.

</details>

---

[Secure Crowdsensed Data Trading Based on Blockchain](https://ieeexplore.ieee.org/abstract/document/9521727)

2023 - IEEE Transaction on Mobile Computing

Topics & Tools: Crowd-sensed Data Trading, Reliability Assessment, Homomorphic Encryption;

<details>

<summary>Abstract</summary>

Crowdsensed Data Trading (CDT) is a novel data trading paradigm, in which each data consumer can publicize its data demand as some crowdsensing tasks, and some mobile users (i.e., data sellers) can compete for these tasks, collect the corresponding data, and sell the results to the consumers. Existing CDT systems generally depend on a data trading broker, which will inevitably cause data consumers’ concerns on the trustworthiness of the systems and truthfulness of the data. To address this problem, we propose a B lockchain-based C rowdsensed D ata T rading (BCDT) system, mainly containing a smart contract, called BCDToken. First, we replace the data trading broker with blockchain to guarantee the trustworthiness of the data trading. Meanwhile, BCDToken adopts Blockchain-based Reverse Auction (BRA) to assign sensing tasks to data sellers. The BRA mechansim holds truthfulness and individual rationality, which can ensure the data sellers to report data collection costs honestly and prevent sellers to manipulate the auction. Moreover, we implement a Secure Truth Discovery and reliability Rating (STDR) mechanism in BCDToken based on homomorphic cryptography, which can incentivize sellers to upload the truthful data and consumers to rate truthfully the reliabilities of sellers based on the collected data without revealing any privacy of data. Additionally, we also deploy BCDToken on an Ethereum test network to demonstrate its practicability and significant performances.

</details>

---

[ContractBox: Realizing accountable data sharing on the edge using a smallscale blockchain](https://www.sciencedirect.com/science/article/pii/S138912862300213X)

2023 -   Computer Networks

Topics & Tools: Trusted execution, Edge computing;

<details>

<summary>Abstract</summary>

The utilization of IoT devices is becoming omnipresent in industrial settings. However, adoption in more rural areas still poses challenges. Especially when processing data on the edge, privacy, data integrity, accountability and data ownership pose challenges since the devices may be easily accessed and manipulated.

We present ContractBox, a system that provides accountable and trusted data sharing based on a publisher–subscriber system, as well as trusted computing on the edge. ContractBox uses a Trusted Execution Environment to guarantee the confidentiality and integrity of clients’ data and code. Furthermore, it provides security by using WebAssembly to execute the smart contracts in their own sandboxed environment. This design protects the host as well as co-located smart contracts from misbehaving executions. Lastly, it ensures the immutability and accountability of the published data by storing it in a blockchain. We show that ContractBox can process several thousand publications per second with various payloads and host multiple smart contract runtimes on a single edge device. ContractBox also achieves up to 35 times higher throughput than a comparable deployment of Hyperledger Fabric.

</details>

---

[TRUCON: Blockchain-Based Trusted Data Sharing With Congestion Control in Internet of Vehicles](https://ieeexplore.ieee.org/abstract/document/9989338)

2023 - IEEE Transactions on Intelligent Transportation Systems

Topics & Tools: Trust assessment, Data retrieval optimization, Routing optimization, Internet of Vehicles, Kademlia, Cuckoo filter;

<details>

<summary>Abstract</summary>

The Internet of vehicles (IoV) has a substantial impact on traffic efficiency improvement and accidents avoidance. Due to restricted resources, vehicles must share observed data with RSUs and other vehicles to execute some time-tolerant computing tasks. However, data provided by vehicles cannot always be trusted due to the presence of attackers. Fake messages could have catastrophic ramifications, such as vehicle collisions. Furthermore, extensive data sharing might cause channel congestion, resulting in the loss of vital messages during delivery. To overcome the aforementioned issues, we propose TRUCON, a blockchain-based trusted data sharing mechanism with congestion control in IoV. Firstly, we propose a Kademlia algorithm-based traffic data forwarding method to control channel congestion state. By adjusting the bucket size and distance threshold, source vehicles can limit the number of reference vehicles forwarded. Secondly, we present a cuckoo filter-based traffic data deduplication and discrimination approach. To avoid repetitive sharing, vehicles and RSUs can check their local filters to verify if the current data report has been shared. Based on the foregoing, we propose a blockchain-based trust management mechanism with congestion control. RSUs serve as full nodes while vehicles are light nodes in the blockchain. Finally, we develop a trust management prototype system with congestion control that incorporates both on-chain and off-chain parts. It signifies that our scheme is both feasible and effective.

</details>

---

[Teegraph: A blockchain consensus algorithm based on TEE and DAG for data sharing in IoT](https://www.sciencedirect.com/science/article/pii/S1383762121002356?casa_token=UXeJlQLOiY0AAAAA:CXCNoOxdlxnRepk9aDhGPwlZJzB-Im9NXBTynvotj99pTYzge5REXeACt-wfvq7SZL18zfaK)

2022 - Journal of Systems Architecture

Topics & Tools: Consensus optimization;

<details>

<summary>Abstract</summary>

Blockchain offers new ways to the data sharing-based collaboration among IoT devices when a centralized IT infrastructure is unavailable. As one of the critical elements in a Blockchain system, the existing consensus algorithms still have some weaknesses, such as energy-wasting, low throughput, high latency, and increased network communication requirements. In this paper, we focus on designing a highly efficient Blockchain consensus algorithm for data sharing among IoT devices. We present the detailed design of Teegraph, which is a Trusted Execution Environment (TEE) and Directed Acyclic Graph (DAG)-based consensus algorithm. A proof-of-concept implementation of Teegraph is presented. The simulation results demonstrate that TEE usage in Teegraph is more efficient than that of the existing state of the art TEE-based consensus algorithms such as MinBFT and MinZyzzyva. Moreover, Teegraph outperforms Hashgraph, one of the most popular DAG-based consensus algorithms in throughput and latency.

</details>

---

[[LVBS: Lightweight vehicular blockchain for secure data sharing in disaster rescue](https://ieeexplore.ieee.org/abstract/document/9035635)]

2022 -  IEEE Transactions on Dependable and Secure Computing

Topics & Tools: Consensus optimization, Reinforcement learning;

<details>

<summary>Abstract</summary>

In disaster areas, a large amount of data (e.g., rescue commands, road damage, and rescue experience) should be delivered among ground rescuing vehicles for safe driving and efficient rescue. When communication infrastructures are destroyed by disasters, unmanned aerial vehicles (UAVs) can be employed to perform immediate rescue missions in destroyed areas and assist data sharing for ground Internet of vehicles (IoV). However, in such UAV-assisted IoV under disaster situation, there exist potential security threats on data sharing among vehicles and UAVs because of the untrusted network environment, unreliable misbehavior tracing, and low-quality shared data. To address these issues, in this article, we develop a lightweight vehicular blockchain-enabled secure (LVBS) data sharing framework in UAV-aided IoV for disaster rescue. First, we propose a novel UAV and blockchain-assisted collaborative aerial-ground network architecture in disaster areas. Second, we develop a credit-based consensus algorithm in the lightweight vehicular blockchain to securely and immutably trace misbehaviors and record data transactions for UAVs and vehicles with improved efficiency and security in reaching consensus. Third, since UAVs and vehicles have little explicit knowledge of the whole network, we develop reinforcement learning-based algorithms to optimally schedule the pricing and quality of data sharing strategies for both data contributor and data consumer via trial and error. Finally, extensive simulations are conducted, which demonstrate that LVBS can effectively improve the security of consensus phase and promote high-quality data sharing.

</details>

---

[Blockchain-based data sharing with key update for future networks](https://ieeexplore.ieee.org/abstract/document/9915412)

2022 -   IEEE Journal on Selected Areas in Communications

Topics & Tools: Updateable encryption, LESS, Zero-knowledge Proof;

<details>

<summary>Abstract</summary>

Future networks incorporate artificial intelligence to enable smart resource management and adaptive service provisioning. With a heterogeneous architecture and a large number of users in future networks, transparent and decentralized data sharing is required to promote data circulation and break data silos, for which blockchain is a potential solution to allow intelligent access permission control. However, it remains a challenging task to achieve flexible authorization management for blockchain-based data sharing and efficient key update for multi-users in case of key exposure. In this paper, we propose an intelligent blockchain-based data-sharing scheme with key update for future networks. First, we design a new encryption scheme, where keywords of data are extracted using machine learning algorithms that are published on the blockchain. Then, keywords of data and time validity are used to encrypt different types of data for flexible data authorization. Second, using hierarchical identity-based encryption, we construct an efficient key update mechanism, where update tokens are generated by invoking a smart contract deployed on the blockchain to facilitate key and ciphertext updates. We formally prove that the proposed scheme can guarantee three essential security properties: forward security, post-compromise security, and collusion attack resistance. On-chain and off-chain experiment results are provided to demonstrate that the proposed scheme can achieve computational and communication efficiency for key and ciphertext updates.

</details>

---

[CrowdMed-II: A blockchain-based framework for efficient consent management in health data sharing](https://link.springer.com/article/10.1007/s11280-021-00923-1)

2022 - World Wide Web

Topics & Tools: Medical scenarios, Smart contracts;

<details>

<summary>Abstract</summary>

The healthcare industry faces serious problems with health data. Firstly, health data is fragmented and its quality needs to be improved. Data fragmentation means that it is difficult to integrate the patient data stored by multiple health service providers. The quality of these heterogeneous data also needs to be improved for better utilization. Secondly, data sharing among patients, healthcare service providers and medical researchers is inadequate. Thirdly, while sharing health data, patients’ right to privacy must be protected, and patients should have authority over who can access their data. In traditional health data sharing system, because of centralized management, data can easily be stolen, manipulated. These systems also ignore patient’s authority and privacy. Researchers have proposed some blockchain-based health data sharing solutions where blockchain is used for consensus management. Blockchain enables multiple parties who do not fully trust each other to exchange their data. However, the practice of smart contracts supporting these solutions has not been studied in detail. We propose CrowdMed-II, a health data management framework based on blockchain, which could address the above-mentioned problems of health data. We study the design of major smart contracts in our framework and propose two smart contract structures. We also introduce a novel search contract for searching patients in the framework. We evaluate their efficiency based on the execution costs on Ethereum. Our design improves on those previously proposed, lowering the computational costs of the framework. This allows the framework to operate at scale and is more feasible for widespread adoption.

</details>

---

[A Blockchain-Based Decentralized, Fair and Authenticated Information Sharing Scheme in Zero Trust Internet-of-Things](https://ieeexplore.ieee.org/abstract/document/9732238)

2022 - IEEE Transactions on Computers

Topics & Tools: Trust assessment, IoT, Zero trust security, Consensus algorithm;

<details>

<summary>Abstract</summary>

Internet-of-Things (IoT) are increasingly operating in the zero-trust environments where any devices and systems may be compromised and hence untrusted. In addition, data collected by and sent from IoT devices may be shared with and processed by edge computing systems, in order to reduce the reliance on centralized (cloud) servers, leading to further security and privacy issues. To cope with these challenges, this paper proposes an innovative blockchain-enabled information sharing solution in zero-trust context to guarantee anonymity yet entity authentication, data privacy yet data trustworthiness, and participant stimulation yet fairness. This new solution is able to support filtering of fabricated information through smart contracts, effective voting, and consensus mechanisms, which can prevent unauthenticated participants from sharing garbage information. We also prove that the proposed solution is secure in the universal composability framework, and further evaluate its performance over an Ethereum-based blockchain platform to demonstrate its utility.

</details>

---

[Comments on “A blockchain-based attribute-based signcryption scheme to secure data sharing in the cloud“](https://www.sciencedirect.com/science/article/pii/S1383762122001989?casa_token=I1bb_Inxpp4AAAAA:LAHZsQprMo0_70AUGFu5laL_ZzvE2qmp2IfONGOO6VmqJ_xE7BPR4oJuJ5Dg1hOr83Oyxqe1)

2022 - Journal of Systems Architecture

Topics & Tools: Unauthorized access, Confidentiality attack, Attribute-based Signature;

<details>

<summary>Abstract</summary>

Secure data sharing deserves special attention in cloud computing since the operating environment is semi-trusted. Recently, Eltayieb et al. proposed a blockchain-based attribute-based signcryption scheme to secure data sharing in the cloud (Journal of Systems Architecture, doi: https://doi.org/10.1016/j.sysarc.2019.101653). However, after carefully revisiting this scheme, we found out that Eltayieb et al.’s scheme is not secure against confidentiality attack. Thus, the data confidentiality of this scheme is broken, and any data user can have unauthorized access control on outsourced data.

</details>

---

[Secure and Efﬁcient Data Sharing Among Vehicles Based on Consortium Blockchain](https://ieeexplore.ieee.org/abstract/document/9457110)

2022 - IEEE Transactions on Intelligent Transportation Systems

Topics & Tools: Trust evaluation, Consensus optimization, Medical scenarios, PoS;

<details>

<summary>Abstract</summary>

The large amount of driving data can help intelligent vehicles make decisions to drive safely, improve vehicular services and enhance driving experience. In traditional vehicular networks, data sharing needs to be done with roadside units (RSUs). However, RSUs cannot be entirely trusted and the data stored in the RSUs may be tampered with. In addition, the deployment of RSUs along roads consumes a large amount of social resources. Further, data sharing between vehicles lacks a trusted environment, and vehicles may be unwilling to share data with others because of data security and privacy concerns. Moreover, in the event of unauthorized data sharing, the source of the leaked data is difficult to trace. In this study, we exploit consortium blockchain technology to achieve traceable and anonymous vehicle-to-vehicle (V2V) data sharing, effectively preventing second-hand sharing of data. The combination of 5G and blockchain makes it possible to share data without using RSUs. We design an enhanced delegated proof-of-stake consensus algorithm to make it more suitable for applications in the distributed Internet of Vehicles (IoV). A comprehensive analysis shows that the proposed scheme is secure and efficient.

</details>

---

[Privacy preserving in blockchain-based government data sharing: A service-on-chain (SOC) approach](https://www.sciencedirect.com/science/article/pii/S0306457321001400?casa_token=TMy_Akveb3EAAAAA:0aCrf2XU5LKKE1k-nYHud0qFcZe5c4w0j66hjQ6lr2uSomCn9BoLzOoRofb_mb7lFX3725tJ)

2022 - Information Processing & Management

Topics & Tools: 

<details>

<summary>Abstract</summary>

Sharing government data is of great significance to social development, but insecure and inappropriate sharing may lead to privacy breaches. Data sharing in consortium blockchain has provided a promising direction for efficient privacy preserving government data sharing. However, since government data is not owned by a single person or any government employers, it is hard to attribute participants’ responsibility for motivating data sharing behavior in blockchain systems. Furthermore, the scope and scale of government data to be shared among departments is unclear, as the purposes for retrieving shared data are dynamically changing. In order to solve these problems, we propose a Service-On-Chain (or simply, SOC) approach. The SOC approach can effectively identify different departments’ data retrieving requirements while efficiently sharing government data with trustworthiness in data content and controllability in data ownership. In particular, we utilize smart contracts to provide an onchain service to define data sharing agreements between government departments, which can identify ambiguous data retrieving requirements and formalize the process logic. We apply the SOC approach to a real world scenario and demonstrate that the SOC approach provides a feasible solution for secure and efficient sharing of data among government departments.

</details>

---

[TraceChain: A blockchain-based scheme to protect data confidentiality and traceability](https://onlinelibrary.wiley.com/doi/abs/10.1002/spe.2753)

2022 - Software: Practice and Experience

Topics & Tools: Cloud environment, Ciphertext policy attribute-based encryption;

<details>

<summary>Abstract</summary>

The risk of sharing data in cloud computing has gathered increasing attention. After the owner of some confidential data outsources the data to cloud storage services and shares it with others, the data owner lost the control to the data to a large extent. To achieve data sharing while keeping data confidentiality, attribute-based encryption (ABE) can be employed by cloud storage services. However, ABE can only guarantee that outsourced data on the cloud is decrypted by attribute-satisfying users but cannot restrict data from being accessed by dishonest users whose attributes also satisfy the access-control policy. It is impossible for the data owner to control the shared data after it has been decrypted by dishonest users, especially when a set of attribute-satisfying dishonest users may collude. To address this concern, we propose a traceable data sharing scheme called TraceChain. In TraceChain, data is encrypted over a new CP-ABE scheme called E-CP-ABE. Furthermore, the system parameters for generating the private key in E-CP-ABE are uploaded to the private blockchain and transactions are performed on the chain. The data owner can obtain the identity of users by monitoring system parameters simultaneously and control data sharing on the blockchain. To prove the security of our scheme, the security analysis is given in this paper. Meanwhile, experimental results also show that our system is viable and efficient.

</details>

---

[Blockchain Based Non-repudiable IoT Data Trading: Simpler, Faster, and Cheaper](https://ieeexplore.ieee.org/abstract/document/9796857)

2022 - Software: Practice and Experience

Topics & Tools: Incentive mechanism, Internet of Things;

<details>

<summary>Abstract</summary>

Next-generation wireless technology and machine-to-machine technology can provide the ability to connect and share data at any time among IoT smart devices. However, the traditional centralized data sharing/trading mechanism lacks trust guarantee and cannot satisfy the real-time requirement. Distributed systems, especially blockchain, provide us with promising solutions. In this paper, we propose a blockchain based non-repudiation scheme for IoT data trading to resolve the credibility and real-time limits. The proposed scheme has two parts, i.e., a trading scheme and an arbitration scheme. The trading scheme employs a divide-and-conquer method and two commitment methods to support efficient IoT data trading, which runs in a two-round manner. The arbitration scheme first leverages a smart contract to solve disputes on-chain in real time. In case of on-chain arbitration dissatisfaction, the arbitration scheme also employs an off-line arbitration to make a final resolution. Short-term and long-term analysis show that the proposed scheme enforces non-repudiation among the data trading parties and runs efficiently for rational data owners and buyers. We implemented the proposed scheme. Experimental results confirm that the proposed scheme has an orders-of-magnitude performance speedup than the state-of-the-art scheme.

</details>

---

[Go-Sharing: A Blockchain-Based Privacy-Preserving Framework for Cross-Social Network Photo](https://ieeexplore.ieee.org/abstract/document/9901505)

2022 - IEEE Journal on Selected Areas in Communications

Topics & Tools: Social platform, Access control, Privacy Preserving, Two-stage separable deep learning TSDL, Multi-owner propagation tree;

<details>

<summary>Abstract</summary>

The evolution of social media has led to a trend of posting daily photos on online Social Network Platforms (SNPs). The privacy of online photos is often protected carefully by security mechanisms. However, these mechanisms will lose effectiveness when someone spreads the photos to other platforms. In this article, we propose Go-sharing, a blockchain-based privacy-preserving framework that provides powerful dissemination control for cross-SNP photo sharing. In contrast to security mechanisms running separately in centralized servers that do not trust each other, our framework achieves consistent consensus on photo dissemination control through carefully designed smart contract-based protocols. We use these protocols to create platform-free dissemination trees for every image, providing users with complete sharing control and privacy protection. Considering the possible privacy conflicts between owners and subsequent re-posters in cross-SNP sharing, we design a dynamic privacy policy generation algorithm that maximizes the flexibility of re-posters without violating formers’ privacy. Moreover, Go-sharing also provides robust photo ownership identification mechanisms to avoid illegal reprinting. It introduces a random noise black box in a two-stage separable deep learning process to improve robustness against unpredictable manipulations. Through extensive real-world simulations, the results demonstrate the capability and effectiveness of the framework across a number of performance metrics.

</details>

---

[Blockchain-empowered efficient data sharing in internet of things settings](https://ieeexplore.ieee.org/abstract/document/9916577)

2022 - IEEE Journal on Selected Areas in Communications

Topics & Tools: Expansion mechanism, Routing optimization, MPR multi-path routing, Homomorphic encryption, Payment Channels;

<details>

<summary>Abstract</summary>

Sharing data across various Internet of Things (IoT) devices has been a common challenge due to efficiency, security, and stability issues. Blockchain, with security features, is considered to be a potential solution for data sharing in IoT settings. However, traditional blockchain-based solutions cannot satisfy the efficiency requirement of high-frequency data sharing among IoT devices. In this paper, we propose an efficient IoT data sharing approach by adopting the Payment Channel Network (PCN)-extended blockchain. Besides, we develop a homomorphic hashing-based transaction segmentation scheme to solve the issue of low transaction success ratio caused by channel deposit restrictions in PCN. In addition, a Multi-point Relay (MPR)-based multi-path routing scheme has been developed to ensure high-frequency transaction forwarding. The communication overhead of maintaining the routing table is reduced by our proposed Multi-point Relay Selection algorithm, and multiple alternate paths generated by Multiple Routing Path algorithm can improve the transaction success rate. Experiment evaluations have demonstrated that that our proposed approach outperforms the baseline approaches in terms of the transaction efficiency and success ratio.

</details>

---

[Trustworthy and Efficient Crowdsensed Data Trading on Sharding Blockchain](https://ieeexplore.ieee.org/abstract/document/9927241)

2022 - IEEE Journal on Selected Areas in Communications

Topics & Tools: Crowdsensed Data Trading (CDT) , Hierarchical Sharding

<details>

<summary>Abstract</summary>

With the development of communications, networking, and information technology, Crowdsensed Data Trading (CDT) becomes a novel data trading paradigm. In CDT, the data requesters publish crowdsensing tasks with specific data requirements, and then workers complete these tasks, upload the data and obtain corresponding rewards. To efficiently deal with data trading, most of the existing CDT systems assume a trusted centralized platform. However, we argue that the platform may collude with workers or requesters to trick others for achieving more benefits. For example, according to the workers’ uploaded data, the platform can modify the reward functions by colluding with the requester. Similarly, the platform might collude with workers to let them know the reward function, then workers could forge data. Meanwhile, requesters and workers may also be malicious. For example, requesters may post tasks but fail to pay and workers can upload wrong data to mislead the system. To solve the above problems, we combine the Crowdsensed Data Trading system with intelligent Blockchain (CDT-B), which contains a smart contract called CDToken. As a credible third-party, the CDToken is used to record the requesters’ reward function and workers’ data uploading function to avoid targeted trick. At the same time, we not only design a Data Uploading and Preprocessing (DUP) mechanism in CDToken to collect and process the workers’ sensed data, but also propose a Grouping Truth Discovery (GTD) to evaluate their data quality for determining the payments. Moreover, to hold a large number of requesters and workers in CDT-B, we propose a Layered Sharding blockchain based on Membership Degree (LSMD) to solve the blockchain inefficiency problem. Finally, we deploy CDToken to an experimental environment based on Ethereum and demonstrate its efficient performance and practicability.

</details>

---

[A high-concurrency blockchain model for large-scale medical cohort data storage and sharing](https://ieeexplore.ieee.org/abstract/document/9995379)

2022 - IEEE International Conference on Bioinformatics and Biomedicine

Topics & Tools: Consensus optimization, Medical scenarios, Smart contracts

<details>

<summary>Abstract</summary>

In the medical scenarios, the demand for secure sharing of medical data and trusted federated computing continues to increase, and blockchain technology can provide secure, credible, and tamper-resistant capabilities, which makes it necessary to combine the two. However, the full application of blockchain to medical scenarios faces two issues. Medical assets such as medical cohort data with strong data correlation and large scale are difficult to be accurately described and safely operated by blockchain. Transactions such as disease diagnosis and hospitalization prediction with many parameters are difficult to execute concurrently in blockchain. Therefore, we propose MAA model, which closely associates patients with assets, separates the logic of asset operations from its storage. At the same time, we propose OPE model with double-layer pipeline concurrency. By constructing the Dependency Graph, and generating multiple blocks with low conflict rates, which are executed simultaneously among multiple Execute Groups, OPE supports the high concurrent execution of medical transactions with high computing power requirements such as trusted federated learning. Experiments show that our model supports multiple types of medical data on-chain compared to existing models, and the concurrency is increased by at least 40% in a high-conflict medical environment.

</details>

---

[Blockchain-based Fair and Decentralized Data Trading Model](https://academic.oup.com/comjnl/article/65/8/2133/6273372)

2022 - The Computer Journal

Topics & Tools: Data Trading, Arbitration mechanism;

<details>

<summary>Abstract</summary>

Data is a kind of important asset in the digital economy and is driving the rise of data markets. Meanwhile, data markets promote data trading efficiently and improve the utilization of data. However, several challenges about data trading need to be addressed. Here, we resolve these challenges via our blockchain-based fair and decentralized data trading model. Disputes about data correctness is settled by the decentralized arbitration mechanism in our model. To ensure the fairness of data trading, we integrate a sale contract and a deterministic public-key encryption algorithm. The decentralization feature of blockchain cuts off the single-point failure for the data trading platform. In addition, we prove that the proposed protocol achieves the desirable security properties that a secure data trading protocol should have. Moreover, utilizing the smart contract in Solidity and program in Java, we implement our model and then evaluate its performance.

</details>

---

[Sandbox Computing: A Data Privacy Trusted Sharing Paradigm Via Blockchain and Federated Learning](https://ieeexplore.ieee.org/abstract/document/9791849)

2022 - IEEE Transactions on Computers

Topics & Tools: Federated learning;

<details>

<summary>Abstract</summary>

As a new trusted data sharing pattern with privacy protection, the integration mechanism of blockchain and Federated Learning has attracted extensive attention. Generally, this mechanism uses blockchain technology to supervise the original data and calculation results, which ignores the supervision of the Federated Learning model and computing process. Therefore, we introduce the concepts of the sandbox and state channel to construct a new data privacy sharing paradigm via Blockchain and Federated Learning. Under this paradigm, we use state channel to connect Blockchain and Federated Learning. And state channel is used to create a “trusted sandbox” to instantiate Federated Learning tasks in the trustless edge computing environment. Meanwhile, we also mainly solve problems about data privacy sharing in Federated Learning and system performance degradation caused by data quality. The simulation results show that the proposed method has better performance and efficiency than the traditional data sharing method.

</details>

---

[A blockchain-based secure data-sharing framework for Software Defined Wireless Body Area Networks](https://www.sciencedirect.com/science/article/pii/S1389128622001670?casa_token=CT5m8yolUNoAAAAA:RiWiWkbFq1SwnVzQnKxPjGS1jfNJz5TT2AdH0pmNv-HW1MILSx3KK5gNJ4as0dzYi8Pn2TVp)

2022 - Computer Networks

Topics & Tools: SDN, Medical Scenario;

<details>

<summary>Abstract</summary>

In the past few years, blockchain has proven its necessity and unprecedented prospects in providing a secure environment for information exchange between two parties. The integration of the Internet of Things (IoT) with blockchain has enabled a digital transformation in many areas such as healthcare, supply chain, and financial services. Like blockchain, the programmable Software-Defined Network (SDN) is also achieving popularity due to its ability to reduce network management complexity. It is evident that incorporating SDNs with IoT-based healthcare systems can significantly improve healthcare management services. However, there are a number of challenges such as data confidentiality, user-centric design, integrity and privacy that makes it difficult to share sensitive information among different parties in a healthcare system. To overcome these challenges, we propose an architectural framework that incorporates blockchain with Software-Defined Wireless Body Area Networks (SDWBANs) to facilitate secure data sharing. We have also designed and integrated a smart contract based fine-grained access control policy to ensure that only data owners will have full control over their health data. The experimental outcomes show that the proposed model achieves good throughput and incurs a very low overhead in terms of latency compared to traditional cloud-based systems.

</details>

---

[Achieving privacy-preserving and verifiable data sharing in vehicular fog with blockchain](https://ieeexplore.ieee.org/abstract/document/9069253)

2022 - IEEE Transactions on Intelligent Transportation Systems

Topics & Tools: Data aggregation, Internet of Vehicles, Privacy Preserving, IBS, Homomorphic Encryption;

<details>

<summary>Abstract</summary>

Vehicular sensing is advocated to perform data collection by exploiting a plethora of vehicular on-board sensors; meanwhile, with the merging of vehicular sensing and fog computing, the deployed road side units (RSUs) can act as fog nodes to collect and share vehicular sensory data at the network edge. However, there are still several problems in terms of the secure and reliable sharing of sensory data in vehicular fog. To resolve these issues, in this paper, we present an efficient, privacy-preserving and verifiable sensory data collection and sharing scheme with a permissioned blockchain in vehicular fog. During the data collection phase, by combining the homomorphic 2-DNF (Disjunctive Normal Form) cryptosystem and an identity-based signcryption scheme, our proposed scheme achieves the secure and verifiable computation of the average and variance of the collected vehicular sensory data. Meanwhile, to achieve efficient and reliable data sharing, we exploit a permissioned blockchain to maintain an immutable and tamper-proof record of the derived sensory data. Security analysis demonstrates the security properties of the proposed scheme, in terms of location privacy preservation, verifiability and immutability. Performance evaluations are conducted to validate the efficiency of the proposed scheme, i.e., improvements in computation and communication efficiency in comparison with a scheme without exploiting blockchain.

</details>

---

[ProvNet: Networked bi-directional blockchain for data sharing with verifiable provenance](https://www.sciencedirect.com/science/article/pii/S0743731522000818?casa_token=hNskqHkgESYAAAAA:Ezio9wJL53JloxIv_nWD0YTQfh0OS-CUMilUb_M4AgAjq7dpeAUlwyFu4GohvTgN3NdDCLV0)

2022 - Journal of Parallel and Distributed Computing 

Topics & Tools: Copyright Protection MinHash, Chameleon Hash, Editable Blocks;

<details>

<summary>Abstract</summary>

Data sharing is increasingly popular especially for scientific research and business fields where large volume of datasets need to be used, but it involves data security and privacy concerns. This paper mitigates such concerns by tracking and logging the history of shared data (i.e., provenance records) while preserving data privacy. This is a challenging problem in the data sharing scenario in this paper because the environment is decentralized and internal logs are not accessible publicly due to privacy concerns. We present ProvNet, a decentralized data sharing platform that can detect malicious users and provide secure provenance records using the newly proposed networked blockchain without disclosing raw data contents. Valid sharing records are collected and stored in the blocknet and misbehavior is detected with the stored provenance records according to our accountable protocols. We give a proof-of-concept implementation, and evaluation results show that the overhead is acceptable.

</details>

---

[Blockchain for health IoT: A privacy‐preserving data sharing system](https://onlinelibrary.wiley.com/doi/abs/10.1002/spe.3114)

2022 - Software: Practice and Experience

Topics & Tools: Consensus optimization, Medical scenarios, Data retrieval optimization, Privacy Preserving, Content extraction signatures;

<details>

<summary>Abstract</summary>

Health Internet of Things (Health IoT) has been limited by isolated information and a lack of security. As the combination of blockchain and Health IoT could potentially address these two limitations, it has attracted significant interest. However, blockchain-based systems often fail to balance data sharing and privacy protection. Therefore, we proposed a Health IoT-based privacy-preserving data sharing blockchain system. We designed a privacy-preserving method based on the content extraction signature scheme to enable patients to establish fine-grained privacy protection. We designed a Byzantine fault-tolerant leader election mechanism that enhances the security of the Raft algorithm while providing efficiency in the data sharing. Furthermore, we designed a summary contract to ensure efficient data retrieval. The proposed mechanism was evaluated in terms of the efficiency and security. The simulation and analysis results demonstrate that our scheme offers a secure and effective technique for achieving privacy-preserving and efficient sharing of IoT medical data.

</details>

---

[SIoVChain: Time-Lock Contract Based Privacy-Preserving Data Sharing in SIoV](https://ieeexplore.ieee.org/abstract/document/9843920)

2022 - IEEE Transactions on Intelligent Transportation Systems 

Topics & Tools: Anonymous sharing, Internet of Vehicles, privacy Preserving,  Payment Channels, Time locks;

<details>

<summary>Abstract</summary>

Social Internet of Vehicles (SIoV) is an emerging technology in the smart city environment, enabling smart vehicles to form social groups and exchange data among themselves. SIoV facilitates many applications aiming to improve driving safety and traffic monitoring by sharing data among vehicles. It ensures a safe and comfortable drive. However, privacy, data confidentiality, and data integrity are the major challenges during multi-hop data transfer that must be addressed for the wide adoption of SIoV. The existing solutions do not provide anonymity and consume more network resources. To address these issues, we propose SIoVChain, a time-lock contract-based privacy-preserving data sharing scheme with incentives for SIoV. It does not only enable data sharing between vehicles anonymously but incentivizes them also. In addition, the proposed framework imposes a penalty anonymously if a malicious vehicle disseminates false information. SIoVChain is shown to be secure against stealing processing fee attack while preserving sender-receiver privacy and path privacy. Universal Composability (UC) framework is used to verify user privacy. The feasibility and efficiency of the scheme are also demonstrated.

</details>

---

[A blockchain-based fine-grained data sharing scheme for e-healthcare system](https://www.sciencedirect.com/science/article/pii/S1383762122002168)

2022 - Journal of Systems Architecture

Topics & Tools: Medical scenarios, privacy Preserving, Proxy Re-encryption;

<details>

<summary>Abstract</summary>

The cloud-aided sharing of e-healthcare data has great positive significance for research. However, due to the privacy consideration, these data are usually encrypted before uploading to the cloud server which impedes data sharing between different medical institutions. Conditional proxy re-encryption (CPRE) allows the proxy to converse ciphertext, especially by specifying a condition embed in the re-encryption key to achieve fine-grained access control over the ciphertext. Unfortunately, existing CPRE schemes cannot ensure the privacy of the condition, which may contain some sensitive private information. Furthermore, a malicious proxy server may return part of the results and even false data to save its computation or bandwidth. To solve these problems, we propose a blockchain-based condition invisible proxy re-encryption scheme for the e-healthcare system. The proposed scheme guarantees the confidentiality of the data by hiding the condition in the re-encryption key so that the proxy cannot learn anything about the condition. Moreover, the ciphertext-searching algorithm is leveraged by executing the smart contract in the blockchain which ensures the results are correct and complete. Finally, experiment results demonstrate the practicability of the proposed scheme in applications.

</details>

---

[Blockchain-based data sharing system for sensing-as-a-service in smart cities](https://dl.acm.org/doi/abs/10.1145/3397202)

2022 - ACM Transactions on Internet Technology

Topics & Tools: 

<details>

<summary>Abstract</summary>

The sensing-as-a-service (SaaS) model has been explored to address the challenge of intractability of managing a large number of sensors faced by future smart cities. However, how to effectively share sensor data without compromising confidentiality, privacy protection, and fair trading without third parties is one of critical issues that must be solved in the SaaS in smart cities. While blockchain shows promise in solving these issues, the existing blockchain-based data sharing (BBDS) systems are difficult to apply to SaaS in smart cities because of many unresolved issues such as requiring a customized blockchain, huge storage, communication and computation costs, and dependence on a third party to achieve fair trading. We propose a BBDS system model with its security requirements before we present a concrete construction by combining -protocol, Paillier encryption scheme, and any secure symmetrical encryption and signature schemes. To demonstrate the utility of our proposed BBDS system, we present a security analysis and compare our system with other solutions. We implement the prototype in Remix to analyze the gas cost, and we conduct experiments to evaluate the communication and computation costs of the BBDS system using symmetric encryption (advanced encryption standard (AES)) and a signature scheme (elliptic curve digital signature algorithm (ECDSA)).

</details>

---

[MedShare: A Privacy-Preserving Medical Data Sharing System by Using Blockchain](https://ieeexplore.ieee.org/abstract/document/9547814)

2021 - IEEE Transactions on Services Computing

Topics & Tools: Medical scenarios, Data retrieval optimization, privacy-preserving, Searchable encryption, Attribute-based Encryption;

<details>

<summary>Abstract</summary>

Electronic Health Record (EHR) and its privacy have attracted widespread attention with the development of the healthcare industry in recent years. As locking medical data in a single healthcare center causes information isolation, healthcare centers are motivated to build medical data sharing systems. However, existing systems highly rely on the trusted centralized servers, which are vulnerable to distributed denial of service (DDoS) attacks and the single point of failure. Moreover, it is a non-trivial matter to authorize multiple users to search and access EHR in a privacy-preserving manner. In this article, we propose MedShare, a decentralized framework for secure EHR sharing. Our design utilizes the smart contract technique of blockchain to establish a trusted platform for healthcare centers to share their encrypted EHR. Considering that fine-grained access control is essential in practical EHR sharing service, we devise a constant-size attribute-based encryption (ABE) scheme, where the access policy is embedded in search result on the blockchain. Besides, we propose an efficient scheme that enables authorized MedShare users to perform multi-keyword boolean search operations over encrypted EHR. We formally analyze the security strengths and implement the system prototype on Ethereum. Evaluation results demonstrate that MedShare is efficient for EHR sharing.

</details>

---

[A secure and efficient authentication and data sharing scheme for Internet ofThings based on blockchain](https://www.sciencedirect.com/science/article/pii/S1383762121000862?casa_token=UHiMLDTGelsAAAAA:jwH7HsIGViIGlH6bB6uG0Wger3eLrid6FQLX7wfJaqYyIiZaNiFsRl1s5GN2Hid2Yzxx99jV)

2021 - Journal of Systems Architecture

Topics & Tools: IoT, IBS;

<details>

<summary>Abstract</summary>

Internet of Things (IoT) is a network convergence of multiple intelligent devices and advanced technologies aiming at connecting and exchanging data over the Internet. IoT is extensively applied in consumer, commercial, industrial, infrastructure and military spaces. With the prevalence of IoT applications, security issues such as identity authenticity and data privacy are increasingly become critical concerns. Authentication and confidential data sharing are the important measures towards secure IoT communication and applications. Blockchain is a burgeoning technology supporting for efficient authentication and secure data sharing. A secure and accountable data transmission scheme based on blockchain has been proposed by Hong et al. recently. But this scheme has security weaknesses of impersonation attack, man-in-the-middle attack, replay attack, denial of service attack (DoS) and key compromise attack. Thus we put forward an improved scheme to overcome the identified security flaws. Our scheme is provably secure and performance analysis shows that our scheme reduces 15.34% computation costs and 40.68% communication costs compared with Hong et al.’s scheme. Meanwhile, we also compare our scheme with other three recent and related researches, which finally indicates that our scheme realizes a well tradeoff between security and efficiency.

</details>

---

[Cross-domain secure data sharing using blockchain for industrial IoT](https://www.sciencedirect.com/science/article/pii/S074373152100112X?casa_token=6TMm_yjAH3gAAAAA:25qIUdCVFKx7y9zrixVBxvzTgi5MiummaVYwoNKH68jhpqS1U-KqL8JXpT1HGS0EKMpmYUni)

2021 - Journal of Parallel and Distributed Computing

Topics & Tools: IoT, IBS;

<details>

<summary>Abstract</summary>

The Industrial Internet of Things (IIoT) enhances smart manufacturing process that escalates productivity through revolutionary techniques. The manufacturing process is sophisticated and complex because of various IoT domains (e.g. industries). A final product is an outcome of the efforts of several departments from different industries. However, this raises the cross-domain communication's privacy and security issues. Cross-domain data sharing for product manufacturing is a challenging research direction. This paper proposes a centralized cloud-based cross-domain data sharing platform using multiple security gateways. The security gateways use the blockchain to store the information into the centralized cloud. Once the application reported a malicious activity, the centralized cloud verifies the concern from the blockchain. Further, an action is taken against the party that performs malicious activity in the security gateways. The algorithms are designed for authentication and transaction of data. The proposed framework is able the secure data movement among different domains globally. The experiment result demonstrates that the proposed security and privacy framework helps to maintain trust among the industries that collaborate on manufacturing across the domains.

</details>

---

[A blockchain-based trading system for big data](https://www.sciencedirect.com/science/article/pii/S138912862100116X?casa_token=gybnhwOYR6oAAAAA:O3rjD6GPbK9UHqi8kvjSrq-fQesWhVYvo3__jzwftpGYmsOBmIwPyQYKioTm7YLTp5Ccjo1M)

2021 - Computer Networks

Topics & Tools: Data trading, Data retrieval optimization, Smart contract, Proxy Re-encryption;

<details>

<summary>Abstract</summary>

Data are an extremely important asset. Governments around the world encourage big data sharing and trading to promote the big data economy. However, existing data trading platforms are not fully trusted. Such platforms face the problems of a [single point of failure](https://www.sciencedirect.com/topics/computer-science/single-point-of-failure) (SPOF), opaque transactions, [uncontrollability](https://www.sciencedirect.com/topics/computer-science/uncontrollability), untraceability, and issues of data privacy. Several blockchain-based big data trading methods have been proposed; however, they do not adequately address the security issues introduced by dishonesty in the data provider and data agent or the fairness of data revenue distribution and price bargaining. In this paper, we propose a blockchain-based decentralized data trading system in which data trading is completed by smart contract-based data matching, price negotiation, and reward assigning. Moreover, the proposed data trading system evaluates the data quality on the basis of three metrics, records the evaluation results in a side-chain, and distributes the data users’ application revenue to the data provider according to the evaluated data quality. We verify the security, usability, and efficiency of the proposed big data trading system.

</details>

---

[A blockchain-based access control scheme with multiple attribute authorities for secure cloud data sharing](https://www.sciencedirect.com/science/article/pii/S1383762120301405?casa_token=m2rnZtvEIG4AAAAA:LgiiotVRJmsP0bnbJaAxTOqUx5OXKa81NrR9OODfDW0FCifyzxGFqMzb6wFYAeBY6ySmP4yY)

2021 - Journal of Systems Architecture

Topics & Tools: Access control, Cross-domain, CP-ABE;

<details>

<summary>Abstract</summary>

Ciphertext-policy attribute-based encryption(CP-ABE) has been widely studied and used in access control schemes for secure data sharing. Since in most of the existing attribute-based encryption methods, all user attributes are managed by a single central authority, it is easy to cause a single point of failure. Therefore, several multi-authority CP-ABE schemes are proposed to manage user attributes by multiple authorities. However, these schemes still do not eliminate the single point of failure in essence or suffer from high computation and communication overhead on data users. In this paper, we propose a Blockchain-based Multi-authority Access Control scheme called BMAC for sharing data securely. Shamir secret sharing scheme and permissioned blockchain (Hyperledger Fabric) are introduced to implement that each attribute is jointly managed by multiple authorities to avoid single point of failure. In addition, we take advantage of blockchain technology to establish trust among multiple authorities and exploit smart contracts to compute tokens for attributes managed across multiple management domains, which reduces communication and computation overhead on the data user side. Moreover, blockchain helps to record the access control process in a secure and auditable way. Finally, we analyze the security of the proposed algorithm. Further analysis and comparison show the performance of the proposed method.

</details>

---

[A secure and trustworthy medical record sharing scheme based on searchable encryption and blockchain](https://www.sciencedirect.com/science/article/pii/S138912862100462X?casa_token=JKu2DrqCR10AAAAA:BOrhbT3rHFWG29UH4Ipjgz6iXyVoYrrzex7r3I_ITU2EztQIW7fSOM9SVwkiWnGchCvVXmP1)

2021 - Computer Networks 

Topics & Tools: Medical scenario, Data retrieval optimization, Access control, Searchable Encryption;

<details>

<summary>Abstract</summary>

In this paper, we demonstrate the potential of using both blockchain and searchable encryption to build a medical data-sharing platform. The latter is designed to allow one to uniformly search for patients' (encrypted) data in different medical institutions. Building on the assumption that medical records are stored locally by the hospital, we use smart contracts to build a global encrypted search index and a verification index for multiple data owners on the blockchain. In our approach, fully functional access control is provided to ensure that patients and medical institutions can control access to the data. This allows the user to promptly verify the integrity of the results after the search. Our approach also supports the addition, modification, and deletion of medical records, and it complies with the requirements of forward security. The experimental results on the local Ethereum network show that our scheme efficiently facilitates secure data sharing.

</details>

---

[SPChain: Blockchain-based medical data sharing and privacy-preserving eHealth system](https://www.sciencedirect.com/science/article/pii/S0306457321001011?casa_token=dtCvqAB9_LoAAAAA:h2qNggm5CmDMUJbOpLsqc_ojKdymuNPp9DuxPPAt5Mr4TvK5reisv5XC8wG-5YvzvSR4DMr6)

2021 - Information Processing and Management

Topics & Tools: Medical scenario, Data retrieval optimization, Privacy Preserving, Proxy Re-encryption, Chameleon Hash, Reliability Assessment;

<details>

<summary>Abstract</summary>

The sharing of electronic medical records (EMRs) has great positive significance for research on disease and epidemic prevention. Recently, blockchain-based eHealth systems have achieved great success in terms of EMRs sharing and management, but there still remain some challenges. Permissioned blockchain-based solutions provide high throughput and scalability, but may suffer from rollback attacks and lead to privacy leakage. Designs based on the public blockchain, on the other hand, are more open and secure, but sacrifice scalability and have no incentives for medical institutions to join into the systems. Moreover, data retrieval in blockchain-based eHealth systems is inefficient because of the basic blockchain structure. To solve the above problems, we propose a blockchain-based medical data sharing and privacy-preserving eHealth system named SPChain. To achieve quick retrieval, we devise special keyblocks and microblocks for patients to store their EMRs. A reputation system is also constructed to motivate medical institutions to participate in SPChain. By using proxy re-encryption schemes, SPChain achieves medical data sharing for patients in a privacy-preserving manner. To evaluate SPChain, we leverage the distribution of miners in the real world to test the system’s performance and ability to resist mentioned attacks. The results show that SPChain can achieve high throughput (220 TPS) with low storage overhead. Compared with the existing schemes, SPChain achieves lower time complexity in terms of data retrieving, and can resist proposed blockchain attacks as well as SPChain attacks.

</details>

---

[Blockchain-based trusted data sharing among trusted stakeholders in IoT](https://onlinelibrary.wiley.com/doi/full/10.1002/spe.2739)

2021 - Software: Practice and Experience

Topics & Tools: SDN, IoT, Consensus Algorithm;

<details>

<summary>Abstract</summary>

Sharing trusted data among trusted stakeholders is very important to large-scale Internet of Things (IoT) applications. However, the entities and organizations involved in IoT naturally lack trusted relationships, which poses significant challenges to the above vision. Specifically, the first challenge is to ensure that the data in the physical world can be objectively and truly injected into the information world of IoT. The second is to ensure the credibility of the entities' identities in IoT. The third is to ensure the authenticity of data, the credibility of identity, and the reliable transmission of data when a third trusted party is unable to provide the expected trusted services. In view of the above challenges, this paper proposes a secure and lightweight triple-trusting architecture (SLTA), which fully uses a blockchain-related supporting technology. The architecture includes an oracle-based data collection mechanism, which ensures that the data collected from edge devices of IoT cannot be modified, and the distributed identity management mechanism, which enhances personal privacy, security, and control of digital identities. Furthermore, a series of innovative designs for applying the blockchain to special large-scale cooperation scenario in IoT are proposed, which is also a part of the key mechanisms of the SLTA. The innovative design includes a new software-defined blockchain structure model and a lightweight Byzantine fault-tolerant algorithm that provides credible support for decentralized data collection, identity management, and data transfer, as well as low-overhead sequential storage mechanism.

</details>

---

[A blockchain-based scheme for privacy-preserving and secure sharing of medical data](https://www.sciencedirect.com/science/article/pii/S0167404820302832?casa_token=DYphc8ugmJ8AAAAA:xX5tplKokoB5AiPafURwrQiX91ZEVQ5a0DXbxwzDJ6XnDMaoIModpPDsj41rGM7_I33gLAOH)

2020 - Computers & Security 

Topics & Tools: Medical scenario, Privacy Preserving, Zero-knowledge Proof, Proxy Re-encryption;

<details>

<summary>Abstract</summary>

How to alleviate the contradiction between the patient's privacy and the research or commercial demands of health data has become the challenging problem of intelligent medical system with the exponential increase of medical data. In this paper, a blockchain-based privacy-preserving scheme is proposed, which realizes secure sharing of medical data between several entities involved patients, research institutions and semi-trusted cloud servers. And meanwhile, it achieves the data availability and consistency between patients and research institutions, where zero-knowledge proof is employed to verify whether the patient's medical data meets the specific requirements proposed by research institutions without revealing patients’ privacy, and then the proxy re-encryption technology is adopted to ensure that research institutions can decrypt the intermediary ciphertext. In addition, this proposal can execute distributed consensus based on PBFT algorithm for transactions between patients and research institutions according to the prearranged terms. Theoretical analysis shows the proposed scheme can satisfy security and privacy requirements such as confidentiality, integrity and availability, as well as performance evaluation demonstrates it is feasible and efficient in contrast with other typical schemes.

</details>

---

[PrivySharing: A blockchain-based framework for privacy-preserving and secure data sharing in smart cities](https://www.sciencedirect.com/science/article/pii/S016740481930197X?casa_token=E3opUMazQwYAAAAA:MfNB5r_NpGI247JYVcwY1ESttblNztmBsVE9hA4k8qdRQ7tNsyrOKvWJO3y5rXH2VgMMPd8N)

2020 - Computers & Security

Topics & Tools: Smart City, IoT;

<details>

<summary>Abstract</summary>

The ubiquitous use of Internet of Things (IoT) ranges from industrial control systems to e-Health, e-commerce, smart cities, agriculture, supply chain management, smart cars, cyber-physical systems and a lot more. However, the data collected and processed by IoT systems especially the ones with centralized control are vulnerable to availability, integrity, and privacy threats. Hence, we present “PrivySharing,” a blockchain-based innovative framework for privacy-preserving and secure IoT data sharing in a smart city environment. The proposed scheme is distinct from existing strategies on many aspects. The data privacy is preserved by dividing the blockchain network into various channels, where every channel comprises a finite number of authorized organizations and processes a specific type of data such as health, smart car, smart energy or financial details. Moreover, access to users’ data within a channel is controlled by embedding access control rules in the smart contracts. In addition, data within a channel is further isolated and secured by using private data collection and encryption respectively. Likewise, the REST API that enables clients to interact with the blockchain network has dual security in the form of an API Key and OAuth 2.0. The proposed solution conforms to some of the significant requirements outlined in the European Union General Data Protection Regulation. We also present a system of reward in the form of a digital token named “PrivyCoin” for users sharing their data with stakeholders/third parties. Lastly, the experimental outcomes advocate that a multi-channel blockchain scales well as compared to a single-channel blockchain system.

</details>

---

[Blockchain-Based Incentives for Secure and Collaborative Data Sharing in Multiple Clouds](https://ieeexplore.ieee.org/abstract/document/9069883)

2020 - IEEE Journal on Selected Areas in Communications

Topics & Tools: Cloud Environment, Incentive Mechanism;

<details>

<summary>Abstract</summary>

The prosperity of cloud computing has driven an increasing number of enterprises and organizations to store their data on private or public cloud platforms. Due to the limitation of individual data owners in terms of data volume and diversity, data sharing over different cloud platforms would enable third parties to take advantage of big data analysis techniques to provide value-added services, such as providing healthcare services for customers by gathering medical data from multiple hospitals. However, it remains a challenging task to design effective incentives that encourage secure and collaborative data sharing in multiple clouds. In this paper, we propose a reliable collaboration model consisting of three types of participants, which include data owners, miners, and third parties, where the data is shared via blockchain and recorded by a smart contract. In general, these participants may acquire and store the sharing of data using their private or public clouds. We analyze the topological relationships between the participants and develop some Shapley value models from simple to complicate in the process of revenue distribution. We also discuss the incentive effect of sharing security data and rationality of the designed solution through analysis towards distribution rules.

</details>

---

[A blockchain-based attribute-based signcryption scheme to secure data sharing in the cloud](https://www.sciencedirect.com/science/article/pii/S1383762119304606?casa_token=6vR-ug5mZV8AAAAA:6lFKNaJygMQHYGlsbTQ_eilx2fx4M99-6wRM6pAeqV_PK43pg0Ce2HDoT_CB_8EG6p0l0LwW)

2020 - Journal of Systems Architecture

Topics & Tools: Cloud Environment, Access control, ABSC;

<details>

<summary>Abstract</summary>

Traditional cloud data sharing schemes have relied on the architecture of the network and large storage providers. However, these storage providers work as trusted third parties to transfer and store data. This kind of cloud storage model has some weak points, such as data availability, centralized data storage, high operational cost, and security concern. In this paper, we combine the concept of blockchain with attribute-based signcryption to provide a secure data sharing in the cloud environment. The proposed scheme satisfies the security requirements of the cloud computing such as confidentiality and unforgeability. Further, the smart contract solves the problem of cloud storage such as returning wrong results as in the traditional cloud server. Finally, the performance comparisons and simulation results show that our proposed scheme is more efficient than others, and it is practical.

</details>

---

[SDTE: A Secure Blockchain-Based Data Trading Ecosystem](https://ieeexplore.ieee.org/abstract/document/8759960)

2019 - IEEE Transactions on Information Forensics and Security

Topics & Tools: Data trading, Smart contract, Trusted computing;

<details>

<summary>Abstract</summary>

Data, a key asset in our data-driven economy, has fueled the emergence of a new data trading industry. However, there are a number of limitations in conventional data trading platforms due to the existence of dishonest buyer/data broker. To mitigate these limitations, we posit the importance of a data processing-as-a-service model, which complements the conventional data hosting/exchange-as-a-service model. Specifically, in this paper, we introduce a secure data trading ecosystem and present a new blockchain-based data trading ecosystem (hereafter referred to as SDTE). In the ecosystem, both data broker and buyer are not able to obtain access to the seller’s raw data, as they are only getting access to the analysis findings that they require. In other words, we reduce the challenge of securing the dataset to the challenge to secure the data processing. We also build a security model to analyze the data trading market and describe a new set of trading protocols for the entire data trading market. To demonstrate utility, we implement our proposed secure data trading platform (SDTP) on Ethereum & Intel’s Software Guard Extensions (SGX) and perform an in-depth analysis.

</details>

---

[Blockchain-based platforms for genomic data sharing: a de-centralized approach in response to the governance problems?](https://academic.oup.com/jamia/article/26/1/76/5211361)

2019 - Journal of the American Medical Informatics Association 

Topics & Tools: Medical scenario;

<details>

<summary>Abstract</summary>

Blockchain-based platforms are emerging to provide solutions for technical and governance challenges associated with genomic data sharing. Providing capabilities for distributed data stewardship and participatory access control along with effective ways for enforcement of the data access agreements and data ownership are among the major promises of these platforms.

</details>

---

[Truthful Crowdsensed Data Trading Based on Reverse Auction and Blockchain](https://link.springer.com/chapter/10.1007/978-3-030-18576-3_18)

2019 - Database Systems for Advanced Applications 

Topics & Tools: Data trading, Smart contract;

<details>

<summary>Abstract</summary>

Crowdsensed Data Trading (CDT) is a novel data trading paradigm, in which each data consumer can publicize its demand as some crowdsensing tasks, and some mobile users can compete for these tasks, collect the corresponding data, and sell the results to the consumers. Existing CDT systems either depend on a trusted data trading broker or cannot ensure sellers to report costs honestly. To address this problem, we propose a Reverse-Auction-and-blockchain-based crowdsensed Data Trading (RADT) system, mainly containing a smart contract, called RADToken. We adopt a greedy strategy to determine winners, and prove the truthfulness and individual rationality of the whole reverse auction process. Moreover, we exploit the smart contract with a series of devises to enforce mutually untrusted parties to participate in the data trading honestly. Additionally, we also deploy RADToken on an Ethereum test network to demonstrate its significant performances. To the best of our knowledge, this is the first CDT work that exploits both auction and blockchain to ensure the truthfulness of the whole data trading process.

</details>

---

[SHAREChain: Healthcare data sharing framework using Blockchain-registry and FHIR](https://ieeexplore.ieee.org/abstract/document/8983415)

2019 - IEEE International Conference on Bioinformatics and Biomedicine

Topics & Tools: Medical Scenario;

<details>

<summary>Abstract</summary>

The amount of healthcare data is increasing. However, issues with unstandardized data formats and the reliability of provenance make the data challenging to share with other institutions. This paper proposes a standards-based sharing framework, SHAREChain, which incorporates two features to deal with reliability and interoperability issues. First, it improves reliability by using the data integrity of a Blockchain-registry and constitutes a Consortium Blockchain Network to share data solely between authenticated institutions. The second feature improves interoperability with standards relating to healthcare data sharing: Fast Healthcare Interoperability Resources and Cross-Enterprise Document Sharing.

</details>

---























