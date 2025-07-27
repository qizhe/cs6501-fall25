---
layout: default
title: Schedule
nav_order: 2
---

### Overview

| Date | Topic | Readings |
|---|---|---|
| Wed 08/27 | Introduction: datacenter infra |  |
| Mon 09/01 | How to profile your system |  |

---

### Network core

| Date | Topic | Readings |
|---|---|---|
| Wed 09/03 | Datacenter topology | [Fat‑Tree](https://dl.acm.org/doi/10.1145/1402946.1402967); [Jupiter Rising](https://dl.acm.org/doi/10.1145/2785956.2787508) |
|  |  | *Optional:* [Facebook’s Data Center Fabric](https://conferences.sigcomm.org/sigcomm/2015/pdf/papers/p123.pdf); [VL2](https://web.eecs.umich.edu/~mosharaf/Readings/VL2.pdf); [Jellyfish](https://www.usenix.org/system/files/conference/nsdi12/nsdi12-final82.pdf) |
| Mon 09/08 | Congestion control I: Rate control | [DCQCN](https://dl.acm.org/doi/10.1145/2785956.2787484); [HPCC](https://dl.acm.org/doi/10.1145/3341302.3342085) |
|  |  | *Optional:* [DCTCP](https://dl.acm.org/doi/10.1145/1851275.1851192); [TIMELY](https://dl.acm.org/doi/10.1145/2829988.2787510) |
| Wed 09/10 | Congestion control II: Admission control | [Homa](https://dl.acm.org/doi/10.1145/3230543.3230564); [dcPIM](https://dl.acm.org/doi/10.1145/3544216.3544235) |
|  |  | *Optional:* [NDP](https://dl.acm.org/doi/10.1145/3098822.3098825); [FastPass](https://dl.acm.org/doi/10.1145/2740070.2626309); [pHost](https://dl.acm.org/doi/10.1145/2716281.2836086) |
| Mon 09/15 | Load balancing | [Hedera](https://dl.acm.org/doi/10.5555/1855711.1855730); [CONGA](https://dl.acm.org/doi/10.1145/2619239.2626316) |
|  |  | *Optional:* [HULA](https://dl.acm.org/doi/10.1145/2890955.2890968); [PLB](https://dl.acm.org/doi/10.1145/3544216.3544226); [Conweave](https://dl.acm.org/doi/10.1145/3603269.3604849) |
| Wed 09/17 | Networking infra for ML | [HPN](https://dl.acm.org/doi/10.1145/3651890.3672265); [Distributed AI at Meta](https://cs.stanford.edu/~keithw/sigcomm2024/sigcomm24-final246-acmpaginated.pdf) |
| Mon 09/22 | Network communication for ML | [TCCL](https://dl.acm.org/doi/10.1145/3620666.3651362); [CRUX](https://cs.stanford.edu/~keithw/sigcomm2024/sigcomm24-final380-acmpaginated.pdf) |
|  |  | *Optional:* [TACCL](https://www.usenix.org/system/files/nsdi23-shah.pdf); [TE‑CCL](https://dl.acm.org/doi/10.1145/3651890.3672249) |
| Wed 09/24 | Optical networking | [Jupiter Evolving](https://dl.acm.org/doi/10.1145/3544216.3544265); [SIRIUS](https://www.microsoft.com/en-us/research/wp-content/uploads/2020/07/sirius-sigcomm20.pdf) |
|  |  | *Optional:* [Lightwave Fabrics](https://dl.acm.org/doi/10.1145/3603269.3604836); [Rotornet](https://dl.acm.org/doi/10.1145/3098822.3098838); [ProjecToR](https://dl.acm.org/doi/10.1145/2934872.2934911) |

---

### Host HW

| Date | Topic | Readings |
|---|---|---|
| Mon 09/29 | Interconnect I: PCIe | [Understanding PCIe Perf](https://dl.acm.org/doi/10.1145/3230543.3230560); [Routable PCIe](https://www.usenix.org/conference/nsdi24/presentation/hou) |
|  |  | *Optional:* [Low‑latency compatible PCIe](https://dl.acm.org/doi/10.1145/3555050.3569128) |
| Wed 10/01 | Interconnect II: CXL | [POND](https://dl.acm.org/doi/abs/10.1145/3575693.3578835); [CXL](https://dl.acm.org/doi/abs/10.1145/3613424.3614256) |
|  |  | *Optional:* [TPP](https://dl.acm.org/doi/abs/10.1145/3582016.3582063); [CXL‑virtual](https://www.usenix.org/system/files/osdi24-zhong-yuhong.pdf) |
| Mon 10/06 | Silicon Photonics | [sip‑ML](https://dl.acm.org/doi/pdf/10.1145/3452296.3472900); [Lightning](https://people.csail.mit.edu/ghobadi/papers/lightning_sigcomm_2023.pdf) |
|  |  | *Optional:* [Server‑scale SP connectivity](https://dl.acm.org/doi/pdf/10.1145/3696348.3696856) |
| Wed 10/08 | Host Network I | [Understanding the Host Network](https://www.cs.cornell.edu/~ragarwal/pubs/understanding-the-host-network.pdf); [Manageable Host](https://sigops.org/s/conferences/hotos/2023/papers/kong.pdf) |
|  |  | *Optional:* [Hostping](https://www.usenix.org/conference/nsdi23/presentation/liu-kefei); [HostCC](https://dl.acm.org/doi/10.1145/3603269.3604878) |
| Mon 10/13 | No class | — |
| Wed 10/15 | Host Network II | [GH](https://dl.acm.org/doi/abs/10.1145/3673038.3673110); [AMD Exascale](https://computermachines.org/joe/publications/pdfs/isca2024_exascale.pdf) |
| Mon 10/20 | FPGA-based computing/networking | [Faery](https://www.usenix.org/system/files/osdi22-zeng.pdf); [ACCL+](https://www.usenix.org/system/files/osdi24-he.pdf) |
|  |  | *Optional:* [OS abstraction](https://www.usenix.org/system/files/osdi20-korolija.pdf); [DUA](https://www.usenix.org/conference/nsdi19/presentation/shu) |
| Wed 10/22 | Memory | [Siloz](https://dl.acm.org/doi/10.1145/3600006.3613143); [STFM](https://ieeexplore.ieee.org/abstract/document/4408252) |
|  |  | *Optional:* [ROWPRESS](https://dl.acm.org/doi/abs/10.1145/3579371.3589063); [ATLAS](https://ieeexplore.ieee.org/abstract/document/5416658) |

---

### OS layer

| Date | Topic | Readings |
|---|---|---|
| Mon 10/27 | Software network stacks | [Understanding Overheads](https://www.cs.cornell.edu/~ragarwal/pubs/network-stack.pdf); [NetChannel](https://dl.acm.org/doi/10.1145/3544216.3544230) |
|  |  | *Optional:* [Shenango](https://dl.acm.org/doi/10.5555/3323234.3323265); [eRPC](https://www.usenix.org/system/files/nsdi19-kalia.pdf) |
| Wed 10/29 | Hardware network stacks | [ZeroNIC](https://www.usenix.org/system/files/osdi24-skiadopoulos.pdf); [FlexTOE](https://www.usenix.org/system/files/nsdi22-paper-shashidhara.pdf) |
|  |  | *Optional:* [Tonic](https://www.cs.princeton.edu/~jrex/papers/tonic.pdf); [BlueField](https://arxiv.org/abs/2402.03041) |
| Mon 11/03 | Storage stacks | [XRP](https://www.usenix.org/conference/osdi22/presentation/zhong); [blk‑switch](https://www.usenix.org/conference/osdi21/presentation/hwang) |
|  |  | *Optional:* [FlashShare](https://www.usenix.org/conference/osdi18/presentation/zhang) |
| Wed 11/05 | Remote storage stacks | [i10](https://www.usenix.org/system/files/nsdi20-paper-hwang.pdf); [nvme‑tcp](https://www.usenix.org/conference/nsdi25/presentation/kang) |
| Mon 11/10 | CPU scheduling | [ZygOS](https://dl.acm.org/doi/10.1145/3132747.3132780); [Caladan](https://dl.acm.org/doi/10.5555/3488766.3488782) |
|  |  | *Optional:* [Arachne](https://www.usenix.org/conference/osdi18/presentation/qin); [Syrup](https://dl.acm.org/doi/10.1145/3477132.3483548) |
| Wed 11/12 | Memory management | [Colloid](https://dl.acm.org/doi/10.1145/3694715.3695968); [TMO](https://dl.acm.org/doi/10.1145/3503222.3507731) |
|  |  | *Optional:* [MEMTIS](https://dl.acm.org/doi/abs/10.1145/3600006.3613167) |
| Mon 11/17 | I/O Memory protection | [F&S](https://www.cs.cornell.edu/~ragarwal/pubs/fands.pdf); [Scalable IOMMU](https://www.usenix.org/conference/atc15/technical-session/presentation/peleg) |
|  |  | *Optional:* [vIOMMU](https://www.usenix.org/legacy/events/atc11/tech/final_files/Amit.pdf); [V‑PROBE](https://www.usenix.org/system/files/atc23-wang-yaohui.pdf) |
| Wed 11/19 | I/O Virtualization | [PicNIC](https://dl.acm.org/doi/10.1145/3341302.3342093); [FreeFlow](https://www.usenix.org/conference/nsdi19/presentation/kim) |
|  |  | *Optional:* [FVM](https://www.usenix.org/system/files/osdi20-kwon.pdf) |

---

### ML Sys

| Date | Topic | Readings |
|---|---|---|
| Mon 11/24 | System for inference | [vLLM](https://arxiv.org/pdf/2309.06180); [Orca](https://www.usenix.org/conference/osdi22/presentation/yu) |
|  |  | *Optional:* [Parrot](https://www.usenix.org/system/files/osdi24-lin-chaofan.pdf); [AQUA](https://dl.acm.org/doi/pdf/10.1145/3676641.3715983) |
| Wed 11/26 | No class | — |
| Wed 12/01 | System for training | [NCCL](https://arxiv.org/pdf/2507.04786); [DeepSeek‑v3](https://arxiv.org/pdf/2505.09343) |

---

### Project presentations

| Date | Topic | Readings |
|---|---|---|
| Mon 12/03 | Student project presentations (TBD) | — |
| Wed 12/08 | Student project presentations (TBD) | — |

