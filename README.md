# Agent4EDA Papers

AI agents for Electronic Design Automation: a categorized collection of research papers, source links, and download records.

面向电子设计自动化的 AI Agent 论文库，覆盖 2024–2026 年的主要工作。

整理日期：**2026-10-07**。共 **65 篇论文条目**，其中 **58 篇全文 PDF**，另有 **7 篇待补齐**。

## 使用方法

- 在下方分类目录中点击 **PDF** 阅读全文。
- 点击 **来源** 查看 arXiv、会议或作者页面。
- 使用 GitHub 的 **Code → Download ZIP** 下载整套文件；解压后打开 [本地可搜索目录](打开论文目录.html)。
- [CSV 清单](论文清单.csv) 包含标题、发表信息、下载状态、页数和 SHA256；[JSON 清单](papers.json) 便于程序处理。

## 收录范围

包括直接调用 EDA 工具、利用反馈迭代、多 Agent 协作的系统，也收录与其密切相关的强化学习、检索、自动搜索、数据和评测工作。它们的自动化程度和实验条件不同，不能仅依据名称中的 Agent 或各自报告的性能数字直接横向排名。

全文优先采用 arXiv 或作者公开版本，可能与最终出版版本不同。发表信息来自整理时的会议、出版或作者记录；未核实的信息已单独标注。论文版权及适用许可归原作者和出版方，本仓库不为论文另行授予许可。

## 分类概览

| 方向 | 条目 | 已下载 PDF |
|---|---:|---:|
| [RTL 生成与优化](01_RTL_Generation_Optimization) | 10 | 10 |
| [验证与调试](02_Verification_Debug) | 14 | 13 |
| [综合与物理设计](03_Synthesis_Physical_Design) | 6 | 5 |
| [工具编排与 EDA 工具研发](04_EDA_Tools_Infrastructure) | 5 | 4 |
| [SoC、Chiplet 与端到端设计](05_SoC_Chiplet_End_to_End) | 6 | 5 |
| [高层次综合 HLS](06_HLS) | 5 | 4 |
| [模拟、RF 与版图](07_Analog_RF_Layout) | 12 | 10 |
| [PCB 设计](08_PCB) | 2 | 2 |
| [基准与数据](09_Benchmarks_Data) | 4 | 4 |
| [综述](10_Surveys) | 1 | 1 |

## 论文目录

### RTL 生成与优化

| 编号 | 论文 | 发表信息 | 全文与来源 |
|---:|---|---|---|
| 005 | **MAGE** — MAGE: A Multi-Agent Engine for Automated RTL Code Generation | DAC 2025 | [PDF · 7 页](01_RTL_Generation_Optimization/005_MAGE_2412.07822.pdf) · [arXiv](https://arxiv.org/abs/2412.07822) |
| 006 | **VerilogCoder** — VerilogCoder: Autonomous Verilog Coding Agents with Graph-based Planning and Abstract Syntax Tree (AST)-based Waveform Tracing Tool | AAAI 2025 | [PDF · 8 页](01_RTL_Generation_Optimization/006_VerilogCoder_2408.08927.pdf) · [arXiv](https://arxiv.org/abs/2408.08927) |
| 010 | **Dr_RTL** — Dr. RTL: Autonomous Agentic RTL Optimization through Tool-Grounded Self-Improvement | arXiv 2026 | [PDF · 9 页](01_RTL_Generation_Optimization/010_Dr_RTL_2604.14989.pdf) · [arXiv](https://arxiv.org/abs/2604.14989) |
| 015 | **ChipSeek** — ChipSeek: Optimizing Verilog Generation via EDA-Integrated Reinforcement Learning | ACL 2026 | [PDF · 22 页](01_RTL_Generation_Optimization/015_ChipSeek_2026.pdf) · [来源](https://aclanthology.org/2026.acl-long.1154/) |
| 016 | **CODMAS** — CODMAS: A Dialectic Multi-Agent Collaborative Framework for Structured RTL Optimization | EACL 2026 Industry | [PDF · 12 页](01_RTL_Generation_Optimization/016_CODMAS_2603.17204.pdf) · [arXiv](https://arxiv.org/abs/2603.17204) |
| 017 | **VFlow** — VFlow: Discovering Optimal Agentic Workflows for Verilog Generation | ASP-DAC 2026 | [PDF · 7 页](01_RTL_Generation_Optimization/017_VFlow_2504.03723.pdf) · [arXiv](https://arxiv.org/abs/2504.03723) |
| 018 | **REvolution** — REvolution: An Evolutionary Framework for RTL Generation driven by Large Language Models | ASP-DAC 2026 | [PDF · 7 页](01_RTL_Generation_Optimization/018_REvolution_2510.21407.pdf) · [arXiv](https://arxiv.org/abs/2510.21407) |
| 019 | **ReChisel** — ReChisel: Effective Automatic Chisel Code Generation by LLM with Reflection | DAC 2025 | [PDF · 7 页](01_RTL_Generation_Optimization/019_ReChisel_2505.19734.pdf) · [arXiv](https://arxiv.org/abs/2505.19734) |
| 020 | **VeriOpt** — VeriOpt: PPA-Aware High-Quality Verilog Generation via Multi-Role LLMs | ICCAD 2025 | [PDF · 9 页](01_RTL_Generation_Optimization/020_VeriOpt_2507.14776.pdf) · [arXiv](https://arxiv.org/abs/2507.14776) |
| 063 | **ChipMATE** — ChipMATE: Multi-Agent Training via Reinforcement Learning for Enhanced RTL Generation | arXiv 2026 | [PDF · 15 页](01_RTL_Generation_Optimization/063_ChipMATE_2605.12857.pdf) · [arXiv](https://arxiv.org/abs/2605.12857) |

### 验证与调试

| 编号 | 论文 | 发表信息 | 全文与来源 |
|---:|---|---|---|
| 001 | **LLM4Cov** — LLM4Cov: Execution-Aware Agentic Learning for High-coverage Testbench Generation | ICML 2026 | [PDF · 16 页](02_Verification_Debug/001_LLM4Cov_2602.16953.pdf) · [arXiv](https://arxiv.org/abs/2602.16953) |
| 002 | **PRO-V-R1** — PRO-V-R1: Reasoning Enhanced Programming Agent for RTL Verification | DAC 2026 | [PDF · 7 页](02_Verification_Debug/002_PRO-V-R1_2506.12200.pdf) · [arXiv](https://arxiv.org/abs/2506.12200) |
| 013 | **Back_to_the_Future** — Back to the Future: Rethinking EDA Infrastructure for Agentic Systems in Chip Design Verification | arXiv 2026 | [PDF · 7 页](02_Verification_Debug/013_Back_to_the_Future_2610.06790.pdf) · [arXiv](https://arxiv.org/abs/2610.06790) |
| 021 | **RTLFixer** — RTLFixer: Automatically Fixing RTL Syntax Errors with Large Language Models | DAC 2024 | [PDF · 7 页](02_Verification_Debug/021_RTLFixer_2311.16543.pdf) · [arXiv](https://arxiv.org/abs/2311.16543) |
| 022 | **MEIC** — MEIC: Re-thinking RTL Debug Automation using LLMs | ICCAD 2024 | [PDF · 11 页](02_Verification_Debug/022_MEIC_2405.06840.pdf) · [arXiv](https://arxiv.org/abs/2405.06840) |
| 023 | **ChatSVA** — ChatSVA: Bridging SVA Generation for Hardware Verification via Task-Specific LLMs | DAC 2026 | [PDF · 7 页](02_Verification_Debug/023_ChatSVA_2604.02811.pdf) · [arXiv](https://arxiv.org/abs/2604.02811) |
| 024 | **ChatTest** — ChatTest: Coverage-Enhanced Testbench Generation for Agile Hardware Verification with LLMs | DATE 2026 | [PDF · 9 页](02_Verification_Debug/024_ChatTest_2512.05371.pdf) · [arXiv](https://arxiv.org/abs/2512.05371) |
| 025 | **UVMarvel** — UVMarvel: an Automated LLM-aided UVM Machine for Subsystem-level RTL Verification | DAC 2026 | [PDF · 8 页](02_Verification_Debug/025_UVMarvel_2605.04704.pdf) · [arXiv](https://arxiv.org/abs/2605.04704) |
| 026 | **ChipModeler** — ChipModeler: LLM-Aided Reference Model Design for Agile Hardware Verification | DAC 2026 | 待补齐 · [来源](https://63dac.conference-program.com/presentation/?id=RESEARCH2319&sess=sess166) |
| 027 | **UVLLM** — UVLLM: An Automated Universal RTL Verification Framework using LLMs | DAC 2025 | [PDF · 8 页](02_Verification_Debug/027_UVLLM_2411.16238.pdf) · [arXiv](https://arxiv.org/abs/2411.16238) |
| 028 | **AssertLLM** — AssertLLM: Generating Hardware Verification Assertions from Design Specifications via Multi-LLMs | ASP-DAC 2025 | [PDF · 8 页](02_Verification_Debug/028_AssertLLM_2025.pdf) · [来源](https://zhiyaoxie.com/files/ASPDAC25_AssertLLM.pdf) |
| 029 | **AssertionForge** — AssertionForge: Enhancing Formal Verification Assertion Generation with Structured Representation of Specifications and RTL | ICLAD 2025 | [PDF · 16 页](02_Verification_Debug/029_AssertionForge_2503.19174.pdf) · [arXiv](https://arxiv.org/abs/2503.19174) |
| 030 | **FVDebug** — FVDebug: An LLM-Driven Debugging Assistant for Automated Root Cause Analysis of Formal Verification Failures | arXiv 2025 | [PDF · 28 页](02_Verification_Debug/030_FVDebug_2510.15906.pdf) · [arXiv](https://arxiv.org/abs/2510.15906) |
| 031 | **SV_LLM** — SV-LLM: An Agentic Approach for SoC Security Verification using Large Language Models | arXiv 2025 | [PDF · 21 页](02_Verification_Debug/031_SV_LLM_2506.20415.pdf) · [arXiv](https://arxiv.org/abs/2506.20415) |

### 综合与物理设计

| 编号 | 论文 | 发表信息 | 全文与来源 |
|---:|---|---|---|
| 003 | **drcAgent** — drcAgent: A Design Rule Aware LLM Agent for DRC Auto-Fix with Adversarial Reinforcement Learning | DAC 2026 | 待补齐 · [来源](https://63dac.conference-program.com/presentation/?id=RESEARCH2145&sess=sess166) |
| 011 | **AgenticPD** — AgenticPD: A Stage-Aware Agentic Framework for Physical Design QoR Optimization | arXiv 2026 | [PDF · 7 页](03_Synthesis_Physical_Design/011_AgenticPD_2607.04758.pdf) · [arXiv](https://arxiv.org/abs/2607.04758) |
| 033 | **ChatLS** — ChatLS: Multimodal Retrieval-Augmented Generation and Chain-of-Thought for Logic Synthesis Script Customization | DAC 2025 | [PDF · 7 页](03_Synthesis_Physical_Design/033_ChatLS_2025.pdf) · [来源](https://leozheng.tech/papers/C13-DAC%2725-ChatLS.pdf) |
| 034 | **ORFS_agent** — ORFS-agent: Tool-Using Agents for Chip Design Optimization | MLCAD 2025 | [PDF · 31 页](03_Synthesis_Physical_Design/034_ORFS_agent_2506.08332.pdf) · [arXiv](https://arxiv.org/abs/2506.08332) |
| 036 | **DRC_Coder** — DRC-Coder: Automated DRC Checker Code Generation Using LLM Autonomous Agent | ISPD 2025 | [PDF · 9 页](03_Synthesis_Physical_Design/036_DRC_Coder_2412.05311.pdf) · [arXiv](https://arxiv.org/abs/2412.05311) |
| 062 | **SynAct** — SynAct: A Reasoning-Acting Large Language Model Agent for Adaptive Synthesis Optimization | arXiv 2026 | [PDF · 12 页](03_Synthesis_Physical_Design/062_SynAct_2608.12751.pdf) · [arXiv](https://arxiv.org/abs/2608.12751) |

### 工具编排与 EDA 工具研发

| 编号 | 论文 | 发表信息 | 全文与来源 |
|---:|---|---|---|
| 009 | **AutoEDA** — AutoEDA: Enabling EDA Flow Automation through Microservice-Based LLM Agents | TODAES 2026 | [PDF · 8 页](04_EDA_Tools_Infrastructure/009_AutoEDA_2508.01012.pdf) · [arXiv](https://arxiv.org/abs/2508.01012) |
| 032 | **EDAid** — Divergent Thoughts toward One Goal: LLM-based Multi-Agent Collaboration System for Electronic Design Automation | NAACL 2025 | [PDF · 12 页](04_EDA_Tools_Infrastructure/032_EDAid_2502.10857.pdf) · [arXiv](https://arxiv.org/abs/2502.10857) |
| 035 | **OpenROAD_Agent** — OpenROAD Agent: An Intelligent Self-Correcting Script Generator for OpenROAD | ICLAD 2025 | 待补齐 · [来源](https://doi.org/10.1109/ICLAD65226.2025.00039) |
| 037 | **Self_Evolved_ABC** — Autonomous Evolution of EDA Tools: Multi-Agent Self-Evolved ABC | DAC 2026 | [PDF · 7 页](04_EDA_Tools_Infrastructure/037_Self_Evolved_ABC_2604.15082.pdf) · [arXiv](https://arxiv.org/abs/2604.15082) |
| 038 | **AuDoPEDA** — Automated QoR improvement in OpenROAD with coding agents | arXiv 2026 | [PDF · 8 页](04_EDA_Tools_Infrastructure/038_AuDoPEDA_2601.06268.pdf) · [arXiv](https://arxiv.org/abs/2601.06268) |

### SoC、Chiplet 与端到端设计

| 编号 | 论文 | 发表信息 | 全文与来源 |
|---:|---|---|---|
| 039 | **MAHL** — MAHL: Multi-Agent LLM-Guided Hierarchical Chiplet Design with Adaptive Debugging | ICCAD 2025 | [PDF · 9 页](05_SoC_Chiplet_End_to_End/039_MAHL_2508.14053.pdf) · [arXiv](https://arxiv.org/abs/2508.14053) |
| 040 | **GenSoC** — GenSoC: A Multi-Agent-Assisted SoC Generation Methodology Leveraging Open-Source Hardware | ISLPED 2025 | 待补齐 · [来源](https://doi.org/10.1109/ISLPED65674.2025.11261756) |
| 041 | **ASIC_Agent** — ASIC-Agent: An Autonomous Multi-Agent System for ASIC Design with Benchmark Evaluation | ICLAD 2025 | [PDF · 31 页](05_SoC_Chiplet_End_to_End/041_ASIC_Agent_2508.15940.pdf) · [arXiv](https://arxiv.org/abs/2508.15940) |
| 042 | **Spec2RTL_Agent** — Spec2RTL-Agent: Automated Hardware Code Generation from Complex Specifications Using LLM Agent Systems | ICLAD 2025 | [PDF · 7 页](05_SoC_Chiplet_End_to_End/042_Spec2RTL_Agent_2506.13905.pdf) · [arXiv](https://arxiv.org/abs/2506.13905) |
| 064 | **Design_Conductor** — Design Conductor: An agent autonomously builds a 1.5 GHz Linux-capable RISC-V CPU | arXiv 2026 | [PDF · 13 页](05_SoC_Chiplet_End_to_End/064_Design_Conductor_2603.08716.pdf) · [arXiv](https://arxiv.org/abs/2603.08716) |
| 065 | **Design_Conductor_2** — Design Conductor 2.0: An agent builds a TurboQuant inference accelerator in 80 hours | arXiv 2026 | [PDF · 12 页](05_SoC_Chiplet_End_to_End/065_Design_Conductor_2_2605.05170.pdf) · [arXiv](https://arxiv.org/abs/2605.05170) |

### 高层次综合 HLS

| 编号 | 论文 | 发表信息 | 全文与来源 |
|---:|---|---|---|
| 043 | **ChatHLS** — ChatHLS: Towards Systematic Design Automation and Optimization for High-Level Synthesis | ACL 2026 | [PDF · 20 页](06_HLS/043_ChatHLS_2026.pdf) · [来源](https://aclanthology.org/2026.acl-long.962.pdf) |
| 044 | **ParetoPilot** — ParetoPilot: Global Optimization Reasoning on HLS Design Space Exploration with LLMs | DAC 2026 | 待补齐 · [来源](https://63dac.conference-program.com/presentation/?id=RESEARCH865&sess=sess168) |
| 045 | **HLSPilot** — HLSPilot: LLM-based High-Level Synthesis | ICCAD 2024 | [PDF · 9 页](06_HLS/045_HLSPilot_2408.06810.pdf) · [arXiv](https://arxiv.org/abs/2408.06810) |
| 046 | **AgRefactor** — AgRefactor: Self-Evolving Agentic Workflow for HLS Compatibility and Performance | arXiv 2026 | [PDF · 9 页](06_HLS/046_AgRefactor_2606.30949.pdf) · [arXiv](https://arxiv.org/abs/2606.30949) |
| 047 | **ContractHIL_HLS** — ContractHIL-HLS: Contract-Aligned Multi-Agent Workflow with Hardware-in-the-Loop Feedback for HLS Design | arXiv 2026 | [PDF · 6 页](06_HLS/047_ContractHIL_HLS_2607.25283.pdf) · [arXiv](https://arxiv.org/abs/2607.25283) |

### 模拟、RF 与版图

| 编号 | 论文 | 发表信息 | 全文与来源 |
|---:|---|---|---|
| 004 | **Code_Not_Canvas** — Code, Not Canvas: Multi-Agent Layout Generation Beyond Vision Models | ASP-DAC 2026 | 待补齐 · [来源](https://research.nvidia.com/labs/electronic-design-automation/publication/yang2026aspdac/) |
| 007 | **AnalogCoder** — AnalogCoder: Analog Circuit Design via Training-Free Code Generation | AAAI 2025 | [PDF · 28 页](07_Analog_RF_Layout/007_AnalogCoder_2405.14918.pdf) · [arXiv](https://arxiv.org/abs/2405.14918) |
| 008 | **AnaFlow** — AnaFlow: Agentic LLM-based Workflow for Reasoning-Driven Explainable and Sample-Efficient Analog Circuit Sizing | ICCAD 2025 (Invited) | [PDF · 7 页](07_Analog_RF_Layout/008_AnaFlow_2511.03697.pdf) · [arXiv](https://arxiv.org/abs/2511.03697) |
| 048 | **Atelier** — Atelier: An Automated Analog Circuit Design Framework via Multiple Large Language Model-Based Agents | TCAD (accepted 2025) | 待补齐 · [来源](https://doi.org/10.1109/TCAD.2025.3573228) |
| 049 | **LayoutCopilot** — LayoutCopilot: An LLM-powered Multi-agent Collaborative Framework for Interactive Analog Layout Design | TCAD 2025 | [PDF · 14 页](07_Analog_RF_Layout/049_LayoutCopilot_2406.18873.pdf) · [arXiv](https://arxiv.org/abs/2406.18873) |
| 050 | **ADO_LLM** — ADO-LLM: Analog Design Bayesian Optimization with In-Context Learning of Large Language Models | ICCAD 2024 | [PDF · 9 页](07_Analog_RF_Layout/050_ADO_LLM_2406.18770.pdf) · [arXiv](https://arxiv.org/abs/2406.18770) |
| 051 | **LEDRO** — LEDRO: LLM-Enhanced Design Space Reduction and Optimization for Analog Circuits | ICLAD 2025 | [PDF · 8 页](07_Analog_RF_Layout/051_LEDRO_2411.12930.pdf) · [arXiv](https://arxiv.org/abs/2411.12930) |
| 052 | **MenTeR** — MenTeR: A fully-automated Multi-agenT workflow for end-to-end RF/Analog Circuits Netlist Design | ICLAD 2025 | [PDF · 9 页](07_Analog_RF_Layout/052_MenTeR_2505.22990.pdf) · [arXiv](https://arxiv.org/abs/2505.22990) |
| 053 | **AnalogXpert** — AnalogXpert: Automating Analog Topology Synthesis by Incorporating Circuit Design Expertise into Large Language Models | ISEDA 2025 | [PDF · 6 页](07_Analog_RF_Layout/053_AnalogXpert_2412.19824.pdf) · [arXiv](https://arxiv.org/abs/2412.19824) |
| 054 | **TopoSizing** — TopoSizing: An LLM-aided Framework of Topology-based Understanding and Sizing for AMS Circuits | arXiv 2025; journal status not verified | [PDF · 14 页](07_Analog_RF_Layout/054_TopoSizing_2509.14169.pdf) · [arXiv](https://arxiv.org/abs/2509.14169) |
| 055 | **AmpAgent** — AmpAgent: An LLM-based Multi-Agent System for Multi-stage Amplifier Schematic Design from Literature for Process and Performance Porting | arXiv 2024 | [PDF · 7 页](07_Analog_RF_Layout/055_AmpAgent_2409.14739.pdf) · [arXiv](https://arxiv.org/abs/2409.14739) |
| 056 | **AnalogCoder_Pro** — AnalogCoder-Pro: Unifying Analog Circuit Generation and Optimization via Multi-modal LLMs | TCAD 2026 | [PDF · 13 页](07_Analog_RF_Layout/056_AnalogCoder_Pro_2508.02518.pdf) · [arXiv](https://arxiv.org/abs/2508.02518) |

### PCB 设计

| 编号 | 论文 | 发表信息 | 全文与来源 |
|---:|---|---|---|
| 057 | **PCBAgent** — PCBAgent: An Agent-based Framework for High-Density Printed Circuit Board Placement | ASP-DAC 2025 | [PDF · 7 页](08_PCB/057_PCBAgent_2025.pdf) · [来源](https://www.cse.cuhk.edu.hk/~byu/papers/C247-ASPDAC2025-PCBAgent.pdf) |
| 058 | **ModuPlace** — ModuPlace: LLM-Assisted Modular PCB Placement via Preference-Optimized Constraint Graph Generation | DAC 2026 | [PDF · 7 页](08_PCB/058_ModuPlace_2026.pdf) · [来源](https://yhhan.com/PDFs/ModuPlace_paper.pdf) |

### 基准与数据

| 编号 | 论文 | 发表信息 | 全文与来源 |
|---:|---|---|---|
| 012 | **RTL_to_GDS_Benchmark** — Can AI Agents Really Complete RTL-to-GDS? Lessons from Benchmarking Tool-Interactive EDA Workflows | arXiv 2026 | [PDF · 7 页](09_Benchmarks_Data/012_RTL_to_GDS_Benchmark_2607.17528.pdf) · [arXiv](https://arxiv.org/abs/2607.17528) |
| 059 | **RTL_BenchMT** — RTL-BenchMT: Dynamic Maintenance of RTL Generation Benchmark Through Agent-Assisted Analysis and Revision | DAC 2026 | [PDF · 7 页](09_Benchmarks_Data/059_RTL_BenchMT_2605.15537.pdf) · [arXiv](https://arxiv.org/abs/2605.15537) |
| 060 | **HLSFactory_Agent** — HLSFactory-Agent: Large-Scale Agentic HLS Dataset Construction from Academic and Open-Source Projects | ISCA 2026 OSCAR Workshop | [PDF · 2 页](09_Benchmarks_Data/060_HLSFactory_Agent_2609.09519.pdf) · [arXiv](https://arxiv.org/abs/2609.09519) |
| 061 | **Agentic_HLS_Eval** — Benchmarking Agentic HLS Design Tasks With HLS-Eval | ISCA 2026 Architecture 2.0 Workshop | [PDF · 4 页](09_Benchmarks_Data/061_Agentic_HLS_Eval_2609.09526.pdf) · [arXiv](https://arxiv.org/abs/2609.09526) |

### 综述

| 编号 | 论文 | 发表信息 | 全文与来源 |
|---:|---|---|---|
| 014 | **Agentic_EDA_Handoff_Survey** — Agentic Electronic Design Automation: A Handoff Perspective | arXiv 2026 | [PDF · 46 页](10_Surveys/014_Agentic_EDA_Handoff_Survey_2606.19795.pdf) · [arXiv](https://arxiv.org/abs/2606.19795) |

## 待补齐全文

以下论文未能获取可直接下载的公开全文；保留了相应记录和来源链接。

- **drcAgent**：[drcAgent: A Design Rule Aware LLM Agent for DRC Auto-Fix with Adversarial Reinforcement Learning](https://63dac.conference-program.com/presentation/?id=RESEARCH2145&sess=sess166)
- **Code_Not_Canvas**：[Code, Not Canvas: Multi-Agent Layout Generation Beyond Vision Models](https://research.nvidia.com/labs/electronic-design-automation/publication/yang2026aspdac/)
- **ChipModeler**：[ChipModeler: LLM-Aided Reference Model Design for Agile Hardware Verification](https://63dac.conference-program.com/presentation/?id=RESEARCH2319&sess=sess166)
- **OpenROAD_Agent**：[OpenROAD Agent: An Intelligent Self-Correcting Script Generator for OpenROAD](https://doi.org/10.1109/ICLAD65226.2025.00039)
- **GenSoC**：[GenSoC: A Multi-Agent-Assisted SoC Generation Methodology Leveraging Open-Source Hardware](https://doi.org/10.1109/ISLPED65674.2025.11261756)
- **ParetoPilot**：[ParetoPilot: Global Optimization Reasoning on HLS Design Space Exploration with LLMs](https://63dac.conference-program.com/presentation/?id=RESEARCH865&sess=sess168)
- **Atelier**：[Atelier: An Automated Analog Circuit Design Framework via Multiple Large Language Model-Based Agents](https://doi.org/10.1109/TCAD.2025.3573228)

详见 [待补齐清单](待补齐全文.txt)。

## 文件验证

下载文件已检查 PDF 文件结构、可读页树与标题对应关系，记录了 SHA256 校验值。未将登录页面、错误响应或标题不符的文件保存为论文。全文保留原始内容。

## 更新

新增或补齐论文时，请同步更新 `papers.json`、CSV 清单及目录，避免同一论文的不同版本重复计数。
