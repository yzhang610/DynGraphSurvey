# A Comprehensive Survey on Dynamic Graph Processing Storage and Analytics
This project reviews relevant work on dynamic graph storage and graph analytics. Dynamic graph storage covers both dynamic storage systems and graph databases, while dynamic graph analytics includes dynamic graph processing (streaming processing based on incremental computation and snapshot-based evolutionary processing), dynamic graph mining, and dynamic graph neural networks (model design, training, and interpretability). Due to space constraints, this paper provides only a brief overview of dynamic graph mining and dynamic graph neural networks. For a comprehensive review, please refer to **"A Comprehensive Survey on Dynamic Graph Processing, Storage, and Analytics."**.

## graph processing related survey work
1. Graph computing systems and partitioning techniques: A survey[[pdf](https://scispace.com/pdf/graph-computing-systems-and-partitioning-techniques-a-survey-3p9cvw18.pdf)]
3. A survey of distributed graph algorithms on massive graphs[[pdf](https://arxiv.org/pdf/2404.06037)]
4. The ubiquity of large graphs and surprising challenges of graph processing: extended survey[[pdf]](https://vldb.org/pvldb/vol11/p420-sahu.pdf)
5. A survey on concurrent processing of graph analytical queries: Systems and algorithms[[pdf]](https://ieeexplore.ieee.org/document/10508807)
6. Graph processing on gpus: A survey[[pdf]](https://www.dcs.warwick.ac.uk/~liganghe/papers/ACM-Computing-Surveys-2017.pdf)
7. A survey on graph processing accelerators: Challenges and opportunities[[pdf]](https://arxiv.org/abs/1902.10130)
8. Hardware acceleration for knowledge graph processing: Challenges & recent developments[[pdf]](https://arxiv.org/abs/2408.12173)
9. Practice of streaming processing of dynamic graphs: Concepts, models, and systems[[pdf]](https://arxiv.org/abs/1912.12740)
10. Revisiting the design of in-memory dynamic graph storage[[pdf]](https://arxiv.org/abs/2502.10959)
11. BYO: A unified framework for benchmarking large-scale graph containers[[pdf]](https://vldb.org/pvldb/vol17/p2307-wheatman.pdf)[[code]](https://github.com/wheatman/BYO)
12. A survey on dynamic graph processing on GPUs: concepts, terminologies and systems[[pdf]](https://link.springer.com/article/10.1007/s11704-023-2656-1)
13. Towards sufficient GPU-accelerated dynamic graph management: Survey and experiment[[pdf]](https://www.vldb.org/pvldb/vol18/p599-lin.pdf)
14. BIFROST: A future graph database runtime[[pdf]](https://ieeexplore.ieee.org/document/10597713/)
15. Demystifying graph databases: Analysis and taxonomy of data organization, system designs, and graph queries[[pdf]](https://arxiv.org/abs/1910.09017)
16. Representation learning for dynamic graphs: a survey[[pdf]](https://arxiv.org/abs/1905.11485)
17. Foundations and modeling of dynamic networks using dynamic graph neural networks: A survey[[pdf]](https://ieeexplore.ieee.org/document/9439502)
18. A comprehensive survey of dynamic graph neural networks: Models, frameworks, benchmarks, experiments and challenges[[pdf]](https://arxiv.org/abs/2405.00476)

## dynamic graph storage work
**CSR-liked**
1. 2015-ICDE LLAMA: Efficient Graph Analytics Using Large Multiversioned Arrays[[pdf]](https://ieeexplore.ieee.org/document/7113298)[[code]](https://github.com/goatdb/llama)
2. 2017-VLDB Accelerating Dynamic Graph Analytics on GPUs[[pdf]](https://arxiv.org/abs/1709.05061)[[code]](https://github.com/desert0616/gpma_demo)
3. 2018-HPEC Packed Compressed Sparse Row: A Dynamic Graph Representation[[pdf]](https://ieeexplore.ieee.org/abstract/document/8547566)[[code]](https://github.com/wheatman/Packed-Compressed-Sparse-Row)
4. 2019-GRADES Fast Concurrent Reads and Updates with PMAs[[pdf]](https://files.core.ac.uk/download/pdf/301638222.pdf)[[code]](https://github.com/cwida/rma_concurrent)
5. 2019-ISCA GraphSSD: Graph Semantics Aware SSD[[pdf]](https://dl.acm.org/doi/10.1145/3307650.3322275)
6. 2020-OPODIS CSR++: A Fast, Scalable, Update-Friendly Graph Data Structure[[pdf]](https://drops.dagstuhl.de/storage/00lipics/lipics-vol184-opodis2020/LIPIcs.OPODIS.2020.17/LIPIcs.OPODIS.2020.17.pdf)
7. 2021-BigData SSTGraph Streaming Sparse Graphs using Efficient Dynamic Sets[[pdf]](https://ieeexplore.ieee.org/document/9671836)
8. 2021-A Parallel Packed Memory Array to Store Dynamic Graphs[[pdf]](https://people.csail.mit.edu/hjxu/papers/ppcsr-alenex.pdf)[[code]](https://github.com/wheatman/PPCSR_)
10. 2021-VLDB Teseo and the Analysis of Structural Dynamic Graphs[[pdf]](https://vldb.org/pvldb/vol14/p1053-leo.pdf)[[code]](https://github.com/cwida/teseo)
11. 2022-CGrid VCSR: Mutable CSR Graph Format Using Vertex-Centric Packed Memory Array[[pdf]](https://ieeexplore.ieee.org/document/9826086)[[code]](https://github.com/DIR-LAB/VCSR)
12. 2023-TKDE An Efficient Data Sturcture for Dynamic Graph on GPUs[[pdf]](https://dl.acm.org/doi/10.1109/TKDE.2023.3235941)
13. 2023-SC MBFGraph: An SSD-Based Analytics System for Evolving Graphs[[pdf]](https://dl.acm.org/doi/10.1145/3581784.3607070)
14. 2024-EuroSys LSGraph: A Locality-centric High-performance Streaming Graph Engine[[pdf]](https://dl.acm.org/doi/10.1145/3627703.3650076)[[code]](https://github.com/ldeng-ustc/bubble_rel/tree/master/LSGraph)
15. 2024-PPoPP CPMA: An Efficient Batch-Parallel Compressed Set Without Pointers[[pdf]](https://arxiv.org/abs/2305.05055)
16. 2024-SC DGAP: Efficient Dynamic Graph Analysis on Persistent Memory[[pdf]](https://arxiv.org/abs/2403.02665)[[code]](https://github.com/DIR-LAB/DGAP)
17. 2025-APPT GASgraph: A GPU-accelerated Streaming Graph Processing System based on SubHPMAs[[pdf]](https://dl.acm.org/doi/10.1007/978-981-95-1021-4_21)
18. 2025-ISPA DCSR: A Dual-Layer Graph Storage Structure for Hybrid Transactional and Analytical Processing[[pdf]](https://www.computer.org/csdl/proceedings-article/ispa/2025/668400a625/2c0NRI7bSQU)
19. 2025-TS Scalable and High-Performance Large-Scale Dynamic Graph Storage and Processing System[[pdf]](https://dl.acm.org/doi/10.1145/3715332)
20. 2025-SIGMOD LSMGraph: A High-Performance Dynamic Graph Storage System with Multi-Level CSR[[pdf]](https://arxiv.org/abs/2411.06392)
21. 2025-SC Bubble: Towards Scalable Evolving Graph Processing via Mini-Batch Sorting[[pdf]](https://dl.acm.org/doi/10.1145/3712285.3759897)[[code]](https://github.com/ldeng-ustc/bubble_rel) 

**AJ-liked**
1. 2012-HPEC STINGER: High Performance Data Structure for Streaming Graphs[[pdf]](https://ieeexplore.ieee.org/document/6408680)[[code]](https://github.com/stingergraph/stinger)
2. 2016-HPEC cuSTINGER: Supporting Dynamic Graph Algorithms for GPUs[[pdf]](https://ieeexplore.ieee.org/document/7761622)
3. 2018-HPEC Hornet: An Efficient Data Structure for Dynamic Sparse Graphs and Matrices on GPUs[[pdf]](https://ieeexplore.ieee.org/document/8547541)[[code]](https://github.com/hornet-gt/hornet)
4. 2018-SC faimGraph: High Performance Management of Fully-Dynamic Graphs Under Tight Memory Constraints on the GPU[[pdf]](https://ieeexplore.ieee.org/document/8665802)[[code]](https://github.com/GPUPeople/faimGraph)
6. 2019-PLDI Low-Latency Graph Streaming using Compressed Purely-Functional Trees[[pdf]](https://arxiv.org/abs/1904.08380)[[code]](https://github.com/ldhulipala/aspen)
7. 2020-IPDPS Dynamic Graphs on the GPU[[pdf]](https://ieeexplore.ieee.org/document/9139818/)
8. 2020-VLDB LiveGraph: A Transactional Graph Storage System with Purely Sequential Adjacency List Scans[[pdf]](https://dl.acm.org/doi/10.14778/3384345.3384351)[[code]](https://github.com/thu-pacman/LiveGraph)
9. 2020-FAST GraphOne: A Data Store for Real-time Analytics on Evolving Graphs[[pdf]](https://www.usenix.org/conference/fast19/presentation/kumar)[[code]](https://github.com/the-data-lab/GraphOne)
10. 2021-SIGMOD Terrace A Hierarchical Graph Container for Skewed Dynamic Graphs[[pdf]](https://dl.acm.org/doi/10.1145/3448016.3457313)[[code]](https://github.com/PASSIONLab/terrace)
11. 2021-SIGMOD RisGraph: A Real-Time Streaming System for Evolving Graphs to Support Sub-millisecond Per-update Analysis at Millions Ops/s[[pdf]](https://dl.acm.org/doi/10.1145/3448016.3457263)
12. 2022-MICRO XPGraph: XPline-Friendly Persistent Memory Graph Stores for Large-Scale Evolving Graphs[[pdf]](https://dl.acm.org/doi/pdf/10.1109/MICRO56248.2022.00091)[[code]](https://github.com/ISCS-ZJU/XPGraph)
13. 2022-VLDB Sortledton: a Universal, Transactional Graph Data Structure[[pdf]](https://www.vldb.org/pvldb/vol15/p1173-fuchs.pdf)[[code]](https://gitlab.db.in.tum.de/per.fuchs/sortledton/)
14. 2024-ISPA DAUSK: A Transactional Graph Structure for Skewed Dynamic Graph Storage[[pdf]](https://ieeexplore.ieee.org/document/10885300)
15. 2024-TDB TgStore: An Efficient Storage System for Large Time-Evolving Graphs[[pdf]](https://ieeexplore.ieee.org/document/10436166)
16. 2024-VLDB GastCoCo: Graph Storage and Coroutine-Based Prefetch Co-Design for Dynamic Graph Processing[[pdf]](https://dl.acm.org/doi/10.14778/3704965.3704986)[[code]](https://github.com/GorgeouszzZ/GastCoCo)
17. 2024-VLDB Sprue: A Fast yet Space-saving Structure for Dynamic Graph Storage[[pdf]](https://dl.acm.org/doi/10.1145/3639282)[[code]](https://github.com/Stardust-SJF/Spruce)
18. 2025-HPCC TripleGraph: A High-Throughput Data Structure for Dynamic Graph Supporting Diverse Workloads[[pdf]](https://www.computer.org/csdl/proceedings-article/hpcc/2025/687400a552/2bggojnPUQg)
19. 2025-VLDB BACH: Bridging Adjacency List and CSR Format using LSM-Trees for HGTAP Workloads[[pdf]](https://www.vldb.org/pvldb/vol18/p1509-miao.pdf)[[code]](https://github.com/2600254/BACH)
20. 2025-VLDB RapidStore: An Efficient Dynamic Graph Storage System for Concurrent Queries[[pdf]](https://dl.acm.org/doi/10.14778/3748191.3748217)

**Hash-liked**
1. 2019-PDPS GraphThinker: A High Performance Data Structure for Dynamic Graph Processing[[pdf]](https://ieeexplore.ieee.org/document/8821003/)[[code]](https://github.com/Wole308/graphtinker)
2. 2021-ICDE DuCuckoo: Dynamic Hash Tables on GPUs[[pdf]](https://ieeexplore.ieee.org/document/9458727/)[[code]](https://github.com/zhuqiweigit/DyCuckoo)
3. 2022-SEA A Fast Data Structure for Dynamic Graphs Based on Hash-Indexed Adjacency Blocks[[pdf]](https://drops.dagstuhl.de/storage/00lipics/lipics-vol233-sea2022/LIPIcs.SEA.2022.11/LIPIcs.SEA.2022.11.pdf)[[code]](https://github.com/hu-macsy/dhb)
4. 2023-ICDE Wind-Bell index: Towards Ultra-Fast Edge Query for Graph Databases[[pdf]](https://ieeexplore.ieee.org/document/10184541)
5. 2025-CDE CuckooGraph: A Scalable and Space-Time Efficient Data Structure for Large-Scale Dynamic Graphs[[pdf]](https://ieeexplore.ieee.org/document/11112841)[[code]](https://github.com/pkufzc/CuckooGraph)

**Graph databases**
1. 2013 ATC TAO: Facebook's Distributed Data Store for the Social Graph[[pdf]](https://www.usenix.org/system/files/conference/atc13/atc13-bronson.pdf)
2. 2015-TOS ImmortalGraph: A System for Storage and Analysis of Temporal Graphs[[pdf]](https://dl.acm.org/doi/10.1145/2700302)
3. 2016-SIGMOD Reducing the Storage Overhead of Main-Memory OLTP Databases with Hybrid Indexes[[pdf]](https://dl.acm.org/doi/10.1145/2882903.2915222)
4. 2016-VLDB Weaver: A High-Performance, Transactional Graph Database Based on Refinable Timestamps[[pdf]](https://www.vldb.org/pvldb/vol9/p852-dubey.pdf)
5. 2019-SIGMOD Nanosecond Indexing of Graph Data With Hash Maps and VLists[[pdf]](https://dl.acm.org/doi/10.1145/3299869.3314044)
6. 2019-SoCC Grasper: A High Performance Distributed System for OLAP on Property Graphs[[pdf]](https://dl.acm.org/doi/abs/10.1145/3357223.3362715)
7. 2019-SIGMOD X-Engine: An Optimized Storage Engine for Large-Scale E-commerce Transaction Processing[[pdf]](https://dl.acm.org/doi/10.1145/3299869.3314041)
8. 2020-SIGMOD A1: Distributed In-Memory Graph Database[[pdf]](https://dl.acm.org/doi/10.1145/3318464.3386135)
9. 2021-SIGMOD PG-Keys: Keys for Property Graphs[[pdf]](https://dl.acm.org/doi/10.1145/3448016.3457561)
10. 2021-VLDB A model and query language for temporal graph databases[[pdf]](https://dl.acm.org/doi/abs/10.1007/s00778-021-00675-4)
11. 2021-FAST Evolution of Development Priorities in Key-value Stores Serving Large-scale Applications the RocksDB Experience[[pdf]](https://www.usenix.org/system/files/fast21-dong.pdf)
12. 2022-VLDB G-Tran A High-Performance Distributed Graph Database with a Decentralized Architecture[[pdf]](https://dl.acm.org/doi/abs/10.14778/3551793.3551813)
13. 2022-VLDB ByteGraph: A High-Pefromance Distributed Graph Database on ByteDance[[pdf]](https://dl.acm.org/doi/10.14778/3554821.3554824)
15. 2022-VLDB Banyan a scoped dataflow engine for Graph Query Service[[pdf]](https://dl.acm.org/doi/abs/10.14778/3547305.3547311)
16. 2022-CIDR GRainDB: A Relational-core Graph-Relational DBMS[[pdf]](https://vldb.org/cidrdb/papers/2022/p57-jin.pdf)
17. 2022-SOCC GHive: Accelerating Analytical Query Processing in Apache Hive via CPU-GPU Heterogeneous Computing[[pdf]](https://dl.acm.org/doi/abs/10.1145/3542929.3563503)
18. 2022-ICDE Clock-G: A temporal graph management system with space-efficient storage technique[[pdf]](https://ieeexplore.ieee.org/document/9835183/)
19. 2023 Vineyard: Optimizing Data Sharing in Data-Intensive Analytics[[pdf]](https://dl.acm.org/doi/abs/10.1145/3589780)
20. 2023-TKED T-SQL A Lightweight Implementation to Enable Built-in Temporal Support in MVCC-Based RDBMSs[[pdf]](https://ieeexplore.ieee.org/document/9435995)
21. 2024-SIGMOD BG3: A Cost Effective and I/O Efficient Graph Database in ByteDance[[pdf]](https://dl.acm.org/doi/10.1145/3626246.3653373)
22. 2024-VLDB Galaxybase: A High Performance Native Distributed Graph Database for HTAP[[pdf]](https://dl.acm.org/doi/10.14778/3685800.3685814)
23. 2024-VLDB Enhancing Data Lakes with GrapAr: Efficient Graph Data Management with a Specialized Storage Scheme[[pdf]](https://arxiv.org/abs/2312.09577)
24. 2024-VLDB Mammoths Are Slow: The Overlooked Transactions of Graph Data[[pdf]](https://dl.acm.org/doi/10.14778/3636218.3636241)
25. 2024-VLDB AeonG: An Efficient Built-in Temporal Support in Graph Databases[[pdf]](https://dl.acm.org/doi/abs/10.14778/3648160.3648187)
26. 2024-BigData Building a High-Performance Graph Storage on Top of Tree-Structured Key-Value Stores[[pdf]](https://ieeexplore.ieee.org/document/10372995)
27. 2024-VLDB KGFabric: A Scalable Knowledge Graph Warehouse for Enterprise Data Interconnection[[pdf]](https://dl.acm.org/doi/10.14778/3685800.3685810)
28. 2025-SIGMOD A Modular Graph-Native Query Optimization Framework[[pdf]](https://dl.acm.org/doi/10.1145/3722212.3724425)

## dynamic graph analytics work
**Incremental Computation**
1. 2013-TPDS Maiter: An Asynchronous Graph Processing Framework for Delta-based Accumulative Iterative Computation[[pdf]](https://ieeexplore.ieee.org/document/6600686)[[code]](https://github.com/zhangyf-neu/maiter)
2. 2016-Euro-Par GraphIn: An Online High Performance Incremental Graph Processing Framework[[pdf]](https://link.springer.com/chapter/10.1007/978-3-319-43659-3_24)
3. 2017-ASPLOS KickStarter: Fast and Accurate Computations on Streaming Graphs via Trimmed Approximations[[pdf]](https://dl.acm.org/doi/10.1145/3093337.3037748)[[code]](https://github.com/pdclab/graphbolt)
4. 2017-ICS EvoGraph: On-the-fly Efficient Mining of Evoving Graphs on GPU[[pdf]](https://dl.acm.org/doi/10.1007/978-3-319-58667-0_6)
5. 2019-EuroSys GraphBolt: Dependency-Driven Synchronous Processing of Streaming Graphs[[pdf]](https://dl.acm.org/doi/10.1145/3302424.3303974)[[code]](https://github.com/pdclab/graphbolt)
6. 2021-SIGMOD Incrementalizing Graph Algorithms[[pdf]](https://basics.sjtu.edu.cn/~qyin/papers/inc-1.pdf)
7. 2021-USENIX TEGRA: Efficient Ad-Hoc Analytics on Evolving Graphs[[pdf]](https://www.usenix.org/conference/nsdi21/presentation/iyer)
8. 2021-ATC Controlling Memory Footprint of Stateful Streaming Graph Processing[[pdf]](https://www.usenix.org/conference/atc21/presentation/vaziri)
9. 2021-EuroSys DZlG: Sparsity-Aware Incremental Processing of Streaming Graphs[[pdf]](https://dl.acm.org/doi/10.1145/3447786.3456230)
10. 2021-EuroSys Tripoline: Generalized Incremental Graph Processing via Graph Triangle lnequality[[pdf]](https://dl.acm.org/doi/10.1145/3447786.3456226)
11. 2021-MICRO JetStream: Graph Analytics on Streaming Data with Event-Driven Hardware Accelerator[[pdf]](https://dl.acm.org/doi/10.1145/3466752.3480126)
12. 2022-VLDB Automating Incremental Graph Processing with Flexible Memoization[[pdf]](https://vldb.org/pvldb/vol14/p1613-gong.pdf)
13. 2022-SC Graphfly: Efficient Asynchronous Streaming Graphs Processing via Dependency-flow[[pdf]](https://ieeexplore.ieee.org/document/10046059)[[code]](https://github.com/GFLY-PAPER/GraphFly)
14. 2023-DAC ACGraph: Accelerating Streaming Graph Processing via Dependence Hierarchy[[pdf]](https://ieeexplore.ieee.org/document/10247904/)
15. 2023-ICDE Layph Making Change Propagation Constraint in Incremental Graph Processing by Layering Graph[[pdf]](https://arxiv.org/abs/2304.07458)
16. 2023-ASPLOs CommonGraph: Graph Analytics on Evolving Data[[pdf]](https://dl.acm.org/doi/10.1145/3575693.3575713)
17. 2024-SoCC IncBoost: Scaling Incremental Graph Processing for Edge Deletions and Weight Updates[[pdf]](https://dl.acm.org/doi/10.1145/3698038.3698524)
18. 2024-VLDB Enabling Window-Based Monotonic Graph Analytics with Reusable Transitional Results for Pattern-Consistent Queries[[pdf]](https://dl.acm.org/doi/10.14778/3681954.3681979)
19. 2025 Analysis of Stable Vertex Values: Fast Query Evaluation Over An Evolving Graph[[pdf]](https://arxiv.org/abs/2502.10579)
20. 2025-VLDB Efficient Graph Data Access for Out-of-Memory GPU Streaming Graph Processing[[pdf]](https://www.vldb.org/pvldb/vol18/p3854-wang.pdf)[[code]](https://github.com/Yongze-zzz/C-GpuStreamGraph)

**dynamic graph processing without incremental computation**
1. 2014-EuroSys Towards Large-Scale Graph Stream Processing Platform2014-EuroSys Chronos: A Graph Engine for Temporal Graph Analysis[[pdf]](https://pacman.cs.tsinghua.edu.cn/papers_cwg/eurosys2014.pdf)
2. 2016-Toc Synergistic Analysis of Evolving Graphs[[pdf]](https://dl.acm.org/doi/10.1145/2992784)
3. 2016-SIGMOD Tornado: A System For Real-Time lterative Analysis Over Evolving Data2016-GRADEs Time-Evolving Graph Processing at Scale[[pdf]](https://dl.acm.org/doi/10.1145/2882903.2882950)
4. 2016-ATC Version Traveler: Fast and Memory-Efficient Version Switching in Graph Processing systems[[pdf]](https://dl.acm.org/doi/10.5555/3026959.3027007)
5. 2022-ICDE TeGraph: A Novel General-Purpose Temporal Graph Computing Engine[[pdf]](https://ieeexplore.ieee.org/document/9835422)
6. 2023-EuroSys TEA: A General-Purpose Temporal Graph Random Walk Engine[[pdf]](https://dl.acm.org/doi/10.1145/3552326.3567491)
7. 2023-ICDE AFaVS: Accurate Yet Fast Version Switching for Graph Processing Systems[[pdf]](https://ieeexplore.ieee.org/document/10184537)
8. 2023-TKDE EGraph: Efficient Concurrent GPU-Based Dynamic Graph Processing[[pdf]](https://dl.acm.org/doi/10.1109/TKDE.2022.3171588)
9. 2023-SIGMOD GeaFlow: A Graph Extended and Accelerated Dataflow System[[pdf]](https://dl.acm.org/doi/10.1145/3589771)
10. 2024-TPDS TeGraph+: Scalable Temporal Graph Processing Enabling Flexible Edge Modifications[[pdf]](https://ieeexplore.ieee.org/document/10508970/)
11. 2025-TACO CGCGraph: Efficient CPU-GPU Co-execution for Concurrent Dynamic Graph Processing[[pdf]](https://dl.acm.org/doi/10.1145/3744904)
12. 2025-ASPLOS TempGraph: An Efficient Chain-driven Temporal Graph Computing Framework on the GPU[[pdf]](https://dl.acm.org/doi/10.1145/3676642.3736116)

**dyanmic graph processing on FPGA, AISC, etc**
1. 2021-FPGA GraSU: A Fast Graph Update Library for FPGA-based Dynamic Graph Processing[[pdf]](https://dl.acm.org/doi/10.1145/3431920.3439288)
2. 2024-MICRO MEGA: A Memory-Efficient GNN Accelerator Exploiting Degree-Aware Mixed-Precision Quantization[[pdf]](https://arxiv.org/abs/2311.09775)

## dynamic graph pattern work
1. 2024-VLDB Everest: GPU-Accelerated System For Mining Temporal Motifs[[pdf]](https://www.vldb.org/pvldb/vol17/p162-yuan.pdf)
2. 2025-ICDETeMatch: A Fast Temporal Subgraph Matching Framework with Temporal-Aware Subgraph Matching Algorithms[[pdf]](https://ieeexplore.ieee.org/document/11113163)
3. 2025-TACO Cheetah: Accelerating Dynamic Graph Mining with Grouping Updates[[pdf]](https://dl.acm.org/doi/full/10.1145/3736173)

## dynamic graph learning work
**dynamic GNN design**
1. 2020-AAAl EvolveGCN: Evolving Graph Convolutional Networks for Dynamic Graphs[[pdf]](https://arxiv.org/abs/1902.10191)
2. 2021-SIGMOD APAN: Asynchronous Propagation Attention Network for Real-time Temporal Graph Embedding[[pdf]](https://arxiv.org/abs/2011.11545)
3. 2022-TKDE Learning Dynamics and Heterogeneity of Spatial-Temporal Graph Data for Traffic Forecasting[[pdf]](https://ieeexplore.ieee.org/document/9346058)
4. 2022-IJCAI DyGRAlN: An Incremental Learning Framework for Dynamic Graphs[[pdf]](https://www.ijcai.org/proceedings/2022/0438.pdf)
5. 2022-KDD ROLAND: Graph Learning Framework for Dynamic Graphs[[pdf]](https://arxiv.org/abs/2208.07239)[[code]](https://github.com/snap-stanford/roland)
6. 2023-SPEED: Streaming Partition and Parallel Acceleration for Temporal Interaction Graph Embedding[[pdf]](https://arxiv.org/abs/2308.14129)[[code]](https://github.com/chenxi1228/SPEED)
7. 2023-TACO RACE: An Efficient Redundancy-aware Accelerator for Dynamic Graph Neural Network[[pdf]](https://dl.acm.org/doi/10.1145/3617685)
8. 2023-ICLR Do We Really Need Complicated Model Architectures for Temporal Networks?[[pdf]](https://arxiv.org/abs/2302.11636)
9. 2024-ASPLOS TGLITE: A Lightweight Programming Framework for Continuous-Time Temporal Graph Neural Networks[[pdf]](https://charithmendis.com/assets/pdf/asplos24-tglite.pdf)[[code]](https://github.com/ADAPT-uiuc/tglite)
10. 2024-ICDE Learning Time-aware Graph Structures for Spatially Correlated Time Series Forecasting[[pdf]](https://arxiv.org/abs/2312.16403)
11. 2024-ICDE CPDG:A Constrastive Pre-Training Method for Dynamic Graph Neural Networks[[pdf]](https://arxiv.org/abs/2307.02813)[[code]](https://github.com/YuanchenBei/CPDG)
12. 2024-ICDE TP-GNN: Continuous Dynamic Graph Neural Network for Graph Classification[[pdf]](https://ieeexplore.ieee.org/document/10598033)
13. 2024-ICLR FreeDyG: Frequency Enhanced Continuous-Time Dynamic Graph Model for Link Prediction[[pdf]](https://openreview.net/forum?id=82Mc5ilInM)[[code]](https://github.com/Tianxzzz/FreeDyG)

**dynamic GNN training**
1. 2021-SC Efficient Scaling of Dynamic Graph Neural Networks[[pdf]](https://arxiv.org/abs/2109.07893)
2. 2022-CIMK PlatoGL: Effective and Scalable Deep Graph Learning System for Graph-enhanced Real-Time Recommendation[[pdf]](https://dl.acm.org/doi/10.1145/3511808.3557084)
3. 2022-LLSWC Bottleneck Analysis of Dynamic Graph Neural Network Inference on CPU and GPU[[pdf]](https://arxiv.org/abs/2210.03900)
4. 2023-VLDB NeutronStream: A Dynamic GNN Training Framework with Sliding Window for Graph Streams[[pdf]](https://www.vldb.org/pvldb/vol17/p455-chen.pdf)
5. 2023-VLDB Decoupled Graph Neural Networks for Large Dynamic Graphs[[pdf]](https://www.vldb.org/pvldb/vol16/p2239-zheng.pdf)
6. 2023-PiPAD: Pipelined and Parallel Dynamic GNN Training on GPUs[[pdf]](https://dl.acm.org/doi/10.1145/3572848.3577487)
7. 2024-VLDB D3-GNN:Dynamic Distributed Dataflow for Streaming Graph Neural Networks[[pdf]](https://dl.acm.org/doi/10.14778/3681954.3681961)
8. 2024-VLDB DynaHB: A Communication-Avoiding Asynchronous Distributed Framework with Hybrid Batches for Dynamic GNN Training[[pdf]](https://dl.acm.org/doi/abs/10.14778/3681954.3682008)
9. 2024-SIGMOD DGC: Training Dynamic Graphs with Spatio-Temporal Non-Uniformity using Graph Partitioning by Chunks[[pdf]](https://arxiv.org/abs/2309.03523)
10. 2024-CDE TimeSGN Scalable and Effective Temporal Graph Neural Netowork[[pdf] ](https://ieeexplore.ieee.org/document/10597745)
11. 2024-ICDE PlatoD2GL: An Efficient Dynamic Deep Graph Learning System for Graph Neural Networks Training on Billion-Scale Graphs[[pdf]](https://ieeexplore.ieee.org/document/10597951)
12. 2024-HPCA Enabling Large Dynamic Neural Network Training with Learning-based Memory Management[[pdf]](https://ieeexplore.ieee.org/document/10476398)

**dynamic GNN explaination** (The more detailed relatedwork can be seen in [awesome-graph-explainability-papers](https://github.com/flyingdoog/awesome-graph-explainability-papers) )
1. 2021-ICDM GCN-SE Attention as Explainability for Node Classification in Dynamic Graphs[[pdf]](https://ieeexplore.ieee.org/iel7/9678506/9678989/09679020.pdf)
2. 2022-IJCAI Explaining Dynamic Graph Neural Networks via Relevance Back-propagation[[pdf]](https://arxiv.org/abs/2207.11175)
3. 2023-CLR Explaining Temporal Graph Models Through an Explorer-Navigator Framework[[pdf]](https://openreview.net/forum?id=BR_ZhvcYbGJ)
4. 2023-CIKM Explainable Spatio-Temporal Graph Neural Networks[[pdf]](https://dl.acm.org/doi/10.1145/3583780.3614871)
5. 2024-KDD Self-Explainable Temporal Graph Networks based on Graph Information Bottleneck[[pdf]](https://dl.acm.org/doi/10.1145/3637528.3671962)
6. 2024-ICLR Causality-Inspired Spatial-Temporal Explanations for Dynamic Graph Neural Networks[[pdf]](https://proceedings.iclr.cc/paper_files/paper/2024/file/6e2a1a8a037f9a06004fe651054e8938-Paper-Conference.pdf)
7. 2025-KDD DyExplainer: Explainable Dynamic Graph Neural Networks[[pdf]](https://dl.acm.org/doi/10.1145/3729173)
8. 2025-SIGMOD Online Detection of Anomalies in Temporal Knowledge Graphs with Interpretability[[pdf]](https://arxiv.org/abs/2408.00872)

**dynamic grapn anomaly detection**
1. 2023-IJCAl SAD: Semi-Supervised Anomaly Detection on Dynamic Graphs[[pdf]](https://dl.acm.org/doi/10.24963/ijcai.2023/256)
2. 2024-ICDE Graph Anomaly Detection at Group Level: A Topology Pattern Enhanced Unsupervised Approach[[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10597723)

## Graph Datasets
1. SNAP (Stanford Network Analysis Project)
   - Features: Widely used, well-formatted, high-quality datasets suitable for graph algorithm benchmarks.
   - URL: https://snap.stanford.edu/data
   - Types: Social networks, road networks, Web graphs, collaboration networks, temporal graphs
   - Representative datasets: Facebook, Twitter, RoadNet, Web-Google, YouTube, Email-Enron
2. KONECT (The Koblenz Network Collection)
   - URL: https://networks.skewed.de/
   - Features: One of the largest graph collections (700+ datasets), including timestamped graphs
   - Types: Social, transportation, biological networks, bipartite graphs, weighted graphs
3. LAW / WebGraph (Large Web Graph)
   - URL: https://law.di.unimi.it/datasets.php
   - Features: Large-scale Web graphs such as uk-2002, eu-2015, and it-2004
   - Use cases: Large-scale PageRank, BFS, graph compression research
4. NetworkRepository
   - URL: https://networkrepository.com/
   - Features: Interactive online visualization and dataset downloads
   - Types: Real-world graphs, random graphs, synthetic graphs, dynamic graphs
5. SuiteSparse Matrix Collection
   - URL: https://sparse.tamu.edu/
   - Features: CSR/COO sparse matrices widely used in graph processing
   - Representative data: Road networks, graph Laplacians, random sparse matrices
   - Advantages: Commonly used in graph algorithm experiments such as BFS, SpMV, and GNNs
6. Open Graph Benchmark (OGB)
   - URL: https://ogb.stanford.edu/
   - Use cases: GNN benchmarks (node classification, link prediction, graph classification)
   - Representative datasets: ogbn-products, ogbn-arxiv, ogbl-collab
7. GraphChallenge / MIT Challenge
   - URL: https://graphchallenge.mit.edu/data
   - Features: Large-scale graph benchmarks suitable for GPU and distributed graph-processing performance evaluation
   - Representative datasets: Brain connectome, Web data, deep learning graphs
8. LDBC (Linked Data Benchmark Council)
   - Features: Authoritative benchmark suite for graph databases and graph analytics; provides scalable, semantically rich datasets and standardized workloads.
   - Use cases: OLTP/OLAP workloads, graph databases, distributed graph processing, analytical benchmarks
   - Dataset entry points:
     - LDBC Social Network Benchmark (SNB): https://github.com/ldbc/ldbc_snb_data
     - LDBC SNB Data Generator: https://github.com/ldbc/ldbc_snb_datagen
     - LDBC Graphalytics Benchmark: https://github.com/ldbc/ldbc_graphalytics
     - LDBC FinBench (Financial Graph Benchmark): https://github.com/ldbc/ldbc_finbench
9. Large-Scale Internet Graphs (Common Crawl Web Graph)
   - Features: Ultra-large Web-scale graphs (billions–tens of billions of edges), suitable for large-scale graph processing and system scalability evaluation.
   - Use cases: Web graph analytics, large-scale BFS/PageRank, distributed graph systems, GPU-scale benchmarking
   - URL: https://commoncrawl.org


