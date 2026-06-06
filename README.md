# A Survey on Large Language Model-Based Game Agents (ACM CSUR)

<div align="center">

![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-green)
[![Visits](https://hits.sh/github.com/git-disl/awesome-LLM-game-agent-papers.svg?style=flat-square&label=visits)](https://hits.sh/github.com/git-disl/awesome-LLM-game-agent-papers/)
![Stars](https://img.shields.io/github/stars/git-disl/awesome-LLM-game-agent-papers?style=flat-square)
![Forks](https://img.shields.io/github/forks/git-disl/awesome-LLM-game-agent-papers?style=flat-square)
<a href='https://arxiv.org/pdf/2404.02039'><img src='https://img.shields.io/badge/arXiv-2404.02039-b31b1b.svg'></a>

</div>

🔥 **Must-read papers for LLM-based Game agents.**

📘 **Our survey has been accepted by ACM Computing Surveys (CSUR). We are preparing the camera ready. Feel free to reach out if you find missing reference.**

💫 **We continuously update the GitHub list on a weekly basis.**

📝 **If you discover any papers that are suitable but not yet included, please open an issue or submit a pull request.**

## Browse by Genre

- [`#minecraft` (60)](#minecraft)
- [`#text-adventure` (124)](#text-adventure)
- [`#communication` (45)](#communication)
- [`#competition` (48)](#competition)
- [`#cooperation` (15)](#cooperation)
- [`#sim-social` (53)](#sim-social)
- [`#sim-embodied` (17)](#sim-embodied)
- [`#sim-other` (1)](#sim-other)
- [`#crafter` (14)](#crafter)
- [`#action` (29)](#action)
- [`#video-adventure` (3)](#video-adventure)
- [`#benchmark` (7)](#benchmark)
- [`#other` (20)](#other)

## Browse by Mechanism

- [`#planning` (144)](#planning)
- [`#memory` (41)](#memory)
- [`#multi-agent` (73)](#multi-agent)
- [`#world-model` (18)](#world-model)
- [`#tool-use` (19)](#tool-use)
- [`#training` (155)](#training)
- [`#self-improvement` (33)](#self-improvement)
- [`#prompting` (28)](#prompting)
- [`#role-play` (9)](#role-play)
- [`#vlm` (37)](#vlm)
- [`#generation` (11)](#generation)

---

# By Genre

## minecraft

- [2026/05] **GROW: Aligning GRPO with State-Action Modeling for Open-World VLM Agents** *arXiv* [[paper](https://arxiv.org/abs/2605.20246)] `#minecraft` `#training` `#vlm`
- [2026/05] **Ratchet: A Minimal Hygiene Recipe for Self-Evolving LLM Agents** *arXiv* [[paper](https://arxiv.org/abs/2605.22148)] `#minecraft` `#self-improvement`
- [2026/04] **Experience Transfer for Multimodal LLM Agents in Minecraft Game** *arXiv* [[paper](https://arxiv.org/abs/2604.05533)] `#minecraft`
- [2026/04] **Gated Coordination for Efficient Multi-Agent Collaboration in Minecraft Game** *arXiv* [[paper](https://arxiv.org/abs/2604.18975)] `#minecraft` `#memory` `#multi-agent` `#vlm`
- [2026/03] **BLOCK: An Open-Source Bi-Stage MLLM Character-to-Skin Pipeline for Minecraft** *arXiv* [[paper](https://arxiv.org/abs/2603.03964)] `#minecraft` `#vlm`
- [2026/02] **Requesting Expert Reasoning: Augmenting LLM Agents with Learned Collaborative Intervention** *arXiv* [[paper](https://arxiv.org/abs/2602.22546)] `#minecraft`
- [2026/01] **MineNPC-Task: Task Suite for Memory-Aware Minecraft Agents** *arXiv* [[paper](https://arxiv.org/abs/2601.05215)] `#minecraft`
- [2025/12] **Synergizing Code Coverage and Gameplay Intent: Coverage-Aware Game Playtesting with LLM-Guided Reinforcement Learning** *arXiv* [[paper](https://arxiv.org/abs/2512.12706)] `#minecraft` `#training`
- [2025/11] **Knowledge Graph-enhanced Large Language Model for Incremental Game PlayTesting** *IEICE Transactions on Information and Systems 2025* [[paper](https://arxiv.org/abs/2511.02534)] `#minecraft` `#memory`
- [2025/09] **PillagerBench: Benchmarking LLM-Based Agents in Competitive Minecraft Team Environments** *2025 IEEE Conference on Games (CoG) 2025* [[paper](https://arxiv.org/abs/2509.06235)] `#minecraft` `#multi-agent` `#self-improvement`
- [2025/09] **Experience-based Knowledge Correction for Robust Planning in Minecraft** *ICLR 2026 Poster* [[paper](https://openreview.net/forum?id=N22lDHYrXe)] `#minecraft` `#planning`
- [2025/08] **CausalMACE: Causality Empowered Multi-Agents in Minecraft Cooperative Tasks** *Findings of EMNLP 2025* [[paper](https://arxiv.org/abs/2508.18797)] `#minecraft` `#planning` `#multi-agent`
- [2025/08] **Vistawise: Building Cost-effective Agent with Cross-modal Knowledge Graph for Minecraft** *EMNLP 2025* [[paper](https://arxiv.org/abs/2508.18722)] `#minecraft` `#memory` `#tool-use`
- [2025/07] **VoyagerVision: Investigating the Role of Multi-modal Information for Open-ended Learning Systems** *arXiv* [[paper](https://arxiv.org/abs/2507.00079)] `#minecraft` `#vlm`
- [2025/07] **Referential ambiguity and clarification requests: comparing human and LLM behaviour** *Proceedings of the Eighth Workshop on Computational Models of Reference, Anaphora and Coreference 2025* [[paper](https://arxiv.org/abs/2507.10445)] `#minecraft`
- [2025/06] **Optimus-3: Towards Generalist Multimodal Minecraft Agents with Scalable Task Experts** *arXiv* [[paper](https://arxiv.org/pdf/2506.10357)][[code](https://github.com/JiuTian-VL/Optimus-3)] `#minecraft` `#planning`
- [2025/06] **Matrix-Game: Interactive World Foundation Model** *arXiv* [[paper](https://arxiv.org/abs/2506.18701)][[code](https://github.com/SkyworkAI/Matrix-Game)] `#minecraft`
- [2025/06] **GuessBench: Sensemaking Multimodal Creativity in the Wild** *arXiv* [[paper](https://arxiv.org/abs/2506.00814)] `#minecraft` `#training` `#vlm`
- [2025/05] **Don’t Just Follow MLLM Plans: Robust and Efficient Planning for Open-World Agents** *arXiv* [[paper](https://arxiv.org/abs/2505.24157)] `#minecraft` `#planning` `#vlm`
- [2025/05] **Knowledge Retrieval in LLM Gaming: A Shift from Entity-Centric to Goal-Oriented Graphs** *Knowledge-Based Systems 2025* [[paper](https://arxiv.org/abs/2505.18607)] `#minecraft` `#planning` `#memory`
- [2025/05] **BeliefNest: A Joint Action Simulator for Embodied Agents with Theory of Mind** *arXiv* [[paper](https://arxiv.org/abs/2505.12321)] `#minecraft`
- [2025/05] **MindForge: Empowering Embodied Agents with Theory of Mind for Lifelong Cultural Learning** *NeurIPS 2025 poster* [[paper](https://openreview.net/forum?id=u7jtLj46i9)] `#minecraft` `#training`
- [2025/05] **WALL-E: World Alignment by NeuroSymbolic Learning improves World Model-based LLM Agents** *NeurIPS 2025 poster* [[paper](https://openreview.net/forum?id=DorAT49sxj)] `#minecraft` `#planning` `#world-model` `#prompting`
- [2025/04] **Collaborating Action by Action: A Multi-agent LLM Framework for Embodied Reasoning** *arXiv* [[paper](https://arxiv.org/abs/2504.17950)][[code](https://github.com/mindcraft-bots/mindcraft)] `#minecraft` `#multi-agent` `#training`
- [2025/04] **WALL-E 2.0: World Alignment by NeuroSymbolic Learning Improves World Model-based LLM Agents** *arXiv* [[paper](https://arxiv.org/abs/2504.15785)][[code](https://github.com/elated-sawyer/WALL-E)] `#minecraft` `#planning` `#world-model` `#prompting`
- [2025/03] **Uncertainty in Action: Confidence Elicitation in Embodied Agents** *arXiv* [[paper](https://arxiv.org/abs/2503.10628)] `#minecraft`
- [2025/03] **Parallelized Planning-Acting for Efficient LLM-based Multi-Agent Systems** *arXiv* [[paper](https://arxiv.org/abs/2503.03505)] `#minecraft` `#planning` `#multi-agent` `#tool-use`
- [2025/03] **NeSyC: A Neuro-symbolic Continual Learner For Complex Embodied Tasks In Open Domains** *ICLR 2025 Poster* [[paper](https://arxiv.org/abs/2503.00870)] `#minecraft`
- [2025/03] **Word2Minecraft: Generating 3D Game Levels through Large Language Models** *arXiv* [[paper](https://arxiv.org/abs/2503.16536)][[code](https://github.com/JMZ-kk/Word2Minecraft/tree/word2mc_v0)] `#minecraft` `#generation`
- [2025/03] **Plancraft: an evaluation dataset for planning with LLM agents** *COLM 2025* [[paper](https://openreview.net/forum?id=nSV8Depcpx)] `#minecraft` `#planning` `#memory` `#tool-use`
- [2025/02] **GATE: Graph-based Adaptive Tool Evolution Across Diverse Tasks** *arXiv* [[paper](https://arxiv.org/abs/2502.14848)][[code](https://github.com/ayanami2003/GATE)] `#minecraft`
- [2025/02] **Optimus-2: Multimodal World Model for Open-World Minecraft Agents** *CVPR 2025* [[paper](https://arxiv.org/pdf/2502.19902)][[code](https://github.com/JiuTian-VL/Optimus-2)] `#minecraft` `#planning` `#world-model` `#vlm`
- [2025/01] **LARM: Large Auto-Regressive Model for Long-Horizon Embodied Intelligence** *ICML 2025 poster* [[paper](https://openreview.net/forum?id=zcx7jqUZg5)] `#minecraft` `#training`
- [2024/12] **TeamCraft: A Benchmark for Multi-Modal Multi-Agent Systems in Minecraft** *arXiv* [[paper](https://arxiv.org/abs/2412.05255)][[code](https://github.com/teamcraft-bench/teamcraft)] `#minecraft` `#multi-agent` `#training` `#vlm`
- [2024/11] **MrSteve: Instruction-Following Agents with What-Where-When Memory** *ICLR 2025* [[paper](https://arxiv.org/abs/2411.06736)][[code](https://github.com/frechele/MrSteve)] `#minecraft` `#memory`
- [2024/10] **WALL-E: World Alignment by Rule Learning Improves World Model-based LLM Agents** *arXiv* [[paper](https://arxiv.org/abs/2410.07484)][[code](https://github.com/elated-sawyer/WALL-E)] `#minecraft` `#planning` `#world-model`
- [2024/10] **ADAM: An Embodied Causal Agent in Open-World Environments** *ICLR 2025* [[paper](https://arxiv.org/abs/2410.22194)][[code](https://github.com/OpenCausaLab/ADAM)] `#minecraft` `#planning`
- [2024/09] **MrSteve: Instruction-Following Agents in Minecraft with What-Where-When Memory** *ICLR 2025 Poster* [[paper](https://openreview.net/forum?id=CjXaMI2kUH)] `#minecraft` `#memory`
- [2024/08] **Optimus-1: Hybrid Multimodal Memory Empowered Agents Excel in Long-horizon Tasks** *NeurIPS 2024* [[paper](https://arxiv.org/abs/2408.03615)][[code](https://github.com/JiuTian-VL/Optimus-1)] `#minecraft` `#planning` `#memory` `#prompting`
- [2024/07] **Odyssey: Empowering Agents with Open-World Skills.** *IJCAI 2024* [[paper](https://arxiv.org/abs/2407.15325)][[code](https://github.com/zju-vipa/Odyssey)] `#minecraft` `#planning` `#tool-use`
- [2024/07] **OmniJARVIS: Omni-Modal Open-World Agents in Minecraft** *NeurIPS 2024* [[paper](https://arxiv.org/abs/2407.00114)][[code](https://github.com/CraftJarvis/OmniJARVIS)] `#minecraft` `#training` `#vlm`
- [2024/06] **VillagerAgent: A Graph-Based Multi-Agent Framework for Coordinating Complex Task Dependencies in Minecraft** *Findings of ACL 2024* [[paper](https://arxiv.org/abs/2406.05720)][[code](https://github.com/cnsdqd-dyb/VillagerAgent)] `#minecraft` `#planning` `#multi-agent`
- [2024/03] **MineDreamer: Learning to Follow Instructions via Chain-of-Imagination for Simulated-World Control** *arXiv* [[paper](https://arxiv.org/abs/2403.12037.pdf)][[code](https://github.com/Zhoues/MineDreamer)] `#minecraft`
- [2024/03] **MineLand: Simulating Large-Scale Multi-Agent Interactions with Limited Multimodal Senses and Physical Needs** *arXiv* [[paper](https://arxiv.org/abs/2403.19267)][[code](https://github.com/cocacola-lab/MineLand)] `#minecraft` `#multi-agent` `#vlm`
- [2024/03] **Hierarchical Auto-Organizing System for Open-Ended Multi-Agent Navigation (HAS)** *ICLR 2024 Workshop* [[paper](https://arxiv.org/abs/2403.08282)] `#minecraft` `#planning` `#multi-agent` `#vlm`
- [2024/02] **RL-GPT: Integrating Reinforcement Learning and Code-as-policy** *NeurIPS 2024 oral* [[paper](https://arxiv.org/abs/2402.19299.pdf)] `#minecraft` `#planning` `#tool-use` `#training`
- [2024/01] **ReGAL: Refactoring Programs to Discover Generalizable Abstractions** *ICML 2024* [[paper](https://arxiv.org/abs/2401.16467)][[code](https://github.com/esteng/regal_program_learning)] `#minecraft`
- [2023/12] **MP5: A Multi-modal Open-ended Embodied System in Minecraft via Active Perception** *CVPR 2024* [[paper](https://arxiv.org/pdf/2312.07472.pdf)][[code](https://github.com/IranQin/MP5)] `#minecraft` `#planning` `#vlm`
- [2023/12] **Auto MC-Reward: Automated Dense Reward Design with Large Language Models for Minecraft** *CVPR 2023* [[paper](https://arxiv.org/abs/2312.09238.pdf)] `#minecraft` `#training`
- [2023/12] **Creative Agents: Empowering Agents with Imagination for Creative Tasks** *UAI 2023* [[paper](https://arxiv.org/abs/2312.02519.pdf)][[code](https://github.com/PKU-RL/Creative-Agents)] `#minecraft` `#planning`
- [2023/11] **JARVIS-1: Open-world Multi-task Agents with Memory-Augmented Multimodal Language Models** *TPAMI 2023* [[paper](https://arxiv.org/abs/2311.05997.pdf)][[code](https://github.com/CraftJarvis/JARVIS-1)] `#minecraft` `#planning` `#memory`
- [2023/11] **See and Think: Embodied Agent in Virtual Environment** *ECCV 2023* [[paper](https://arxiv.org/abs/2311.15209.pdf)][[code](https://github.com/rese1f/STEVE)] `#minecraft` `#memory`
- [2023/10] **LLaMA Rider: Spurring Large Language Models to Explore the Open World** *NAACL 2023* [[paper](https://arxiv.org/abs/2310.08922.pdf)][[code](https://github.com/PKU-RL/LLaMA-Rider)] `#minecraft` `#planning` `#training`
- [2023/10] **MCU: A Task-centric Framework for Open-ended Agent Evaluation in Minecraft** *ICML 2023* [[paper](https://arxiv.org/abs/2310.08367)][[code](https://github.com/CraftJarvis/MCU)] `#minecraft`
- [2023/10] **Steve-Eye: Equipping LLM-based Embodied Agents with Visual Perception in Open Worlds** *ICLR 2024* [[paper](https://openreview.net/forum?id=NltzxpG0nz)] `#minecraft` `#vlm`
- [2023/05] **Ghost in the Minecraft: Generally Capable Agents for Open-World Environments via Large Language Models with Text-based Knowledge and Memory** *arXiv* [[paper](https://arxiv.org/abs/2305.17144.pdf)] `#minecraft` `#training`
- [2023/05] **VOYAGER: An Open-Ended Embodied Agent with Large Language Models** *FMDM@NeurIPS2023* [[paper](https://arxiv.org/abs/2305.16291.pdf)][[code](https://github.com/MineDojo/Voyager)] `#minecraft` `#tool-use` `#training`
- [2023/03] **Plan4MC: Skill Reinforcement Learning and Planning for Open-World Minecraft Tasks** *FMDM@NeurIPS2023* [[paper](https://arxiv.org/abs/2303.16563.pdf)][[code](https://github.com/PKU-RL/Plan4MC)] `#minecraft` `#planning` `#training`
- [2023/02] **Describe, Explain, Plan and Select: Interactive Planning with Large Language Models Enables Open-World Multi-Task Agents** *NeurIPS 2023* [[paper](https://arxiv.org/abs/2302.01560.pdf)][[code](https://github.com/CraftJarvis/MC-Planner)] `#minecraft` `#planning` `#prompting`
- [2022/07] **Craft an Iron Sword: Dynamically Generating Interactive Game Characters by Prompting Large Language Models Tuned on Code** *Wordplay@ACL 2022* [[paper](https://aclanthology.org/2022.wordplay-1.3.pdf)] `#minecraft`

## text-adventure

- [2026/05] **T$^2$PO: Uncertainty-Guided Exploration Control for Stable Multi-Turn Agentic Reinforcement Learning** *arXiv* [[paper](https://arxiv.org/abs/2605.02178)][[code](https://github.com/WillDreamer/T2PO)] `#text-adventure` `#training`
- [2026/05] **PRISM: Perception Reasoning Interleaved for Sequential Decision Making** *arXiv* [[paper](https://arxiv.org/abs/2605.05407)] `#text-adventure` `#vlm`
- [2026/05] **From History to State: Constant-Context Skill Learning for LLM Agents** *arXiv* [[paper](https://arxiv.org/abs/2605.05413)] `#text-adventure` `#planning` `#training`
- [2026/05] **StraTA: Incentivizing Agentic Reinforcement Learning with Strategic Trajectory Abstraction** *arXiv* [[paper](https://arxiv.org/abs/2605.06642)] `#text-adventure` `#training`
- [2026/05] **AEM: Adaptive Entropy Modulation for Multi-Turn Agentic Reinforcement Learning** *arXiv* [[paper](https://arxiv.org/abs/2605.00425)] `#text-adventure` `#training`
- [2026/05] **Belief Memory: Agent Memory Under Partial Observability** *arXiv* [[paper](https://arxiv.org/abs/2605.05583)] `#text-adventure` `#memory`
- [2026/05] **SkillLens: Adaptive Multi-Granularity Skill Reuse for Cost-Efficient LLM Agents** *arXiv* [[paper](https://arxiv.org/abs/2605.08386)] `#text-adventure`
- [2026/05] **Evolving-RL: End-to-End Optimization of Experience-Driven Self-Evolving Capability within Agents** *arXiv* [[paper](https://arxiv.org/abs/2605.10663)] `#text-adventure` `#training` `#self-improvement`
- [2026/05] **Skill1: Unified Evolution of Skill-Augmented Agents via Reinforcement Learning** *arXiv* [[paper](https://arxiv.org/abs/2605.06130)] `#text-adventure` `#tool-use` `#training`
- [2026/05] **SkillMaster: Toward Autonomous Skill Mastery in LLM Agents** *arXiv* [[paper](https://arxiv.org/abs/2605.08693)] `#text-adventure` `#training`
- [2026/05] **PriorZero: Bridging Language Priors and World Models for Decision Making** *arXiv* [[paper](https://arxiv.org/abs/2605.12289)][[code](https://github.com/opendilab/LightZero)] `#text-adventure` `#planning` `#world-model` `#training`
- [2026/05] **Skills on the Fly: Test-Time Adaptive Skill Synthesis for LLM Agents** *arXiv* [[paper](https://arxiv.org/abs/2605.16986)] `#text-adventure` `#memory` `#tool-use`
- [2026/05] **What and When to Distill: Selective Hindsight Distillation for Multi-Turn Agents** *arXiv* [[paper](https://arxiv.org/abs/2605.19447)] `#text-adventure` `#training`
- [2026/05] **APEX: Autonomous Policy Exploration for Self-Evolving LLM Agents** *arXiv* [[paper](https://arxiv.org/abs/2605.21240)] `#text-adventure` `#planning` `#self-improvement`
- [2026/05] **SkillGraph: Skill-Augmented Reinforcement Learning for Agents via Evolving Skill Graphs** *arXiv* [[paper](https://arxiv.org/abs/2605.12039)] `#text-adventure` `#memory` `#tool-use` `#training`
- [2026/05] **Dynamic Skill Lifecycle Management for Agentic Reinforcement Learning** *arXiv* [[paper](https://arxiv.org/abs/2605.10923)] `#text-adventure` `#training`
- [2026/05] **Selective Rollout: Mid-Trajectory Termination for Multi-Sample Agent RL** *arXiv* [[paper](https://arxiv.org/abs/2605.05802)][[code](https://github.com/zhiyuanZhai20/selective-rollout)] `#text-adventure` `#training`
- [2026/05] **R2V Agent: Teaching SLMs When to Ask for Help** *arXiv* [[paper](https://arxiv.org/abs/2605.16604)] `#text-adventure` `#training`
- [2026/05] **SkillOps: Managing LLM Agent Skill Libraries as Self-Maintaining Software Ecosystems** *arXiv* [[paper](https://arxiv.org/abs/2605.13716)] `#text-adventure` `#planning` `#memory` `#tool-use`
- [2026/04] **Aligning Progress and Feasibility: A Neuro-Symbolic Dual Memory Framework for Long-Horizon LLM Agents** *arXiv* [[paper](https://arxiv.org/abs/2604.02734)] `#text-adventure` `#planning` `#memory`
- [2026/04] **Hierarchical Reinforcement Learning with Augmented Step-Level Transitions for LLM Agents** *arXiv* [[paper](https://arxiv.org/abs/2604.05808)][[code](https://github.com/TonyStark042/STEP-HRL)] `#text-adventure` `#training`
- [2026/04] **DORA Explorer: Improving the Exploration Ability of LLMs Without Training** *arXiv* [[paper](https://arxiv.org/abs/2604.17244)] `#text-adventure` `#planning` `#prompting`
- [2026/04] **From Actions to Understanding: Conformal Interpretability of Temporal Concepts in LLM Agents** *arXiv* [[paper](https://arxiv.org/abs/2604.19775)] `#text-adventure` `#planning`
- [2026/04] **Complete Cyclic Subtask Graphs for Tool-Using LLM Agents: Flexibility, Cost, and Bottlenecks in Multi-Agent Workflows** *arXiv* [[paper](https://arxiv.org/abs/2604.22820)] `#text-adventure` `#planning` `#memory` `#multi-agent`
- [2026/04] **ReDAct: Uncertainty-Aware Deferral for LLM Agents** *arXiv* [[paper](https://arxiv.org/abs/2604.07036)] `#text-adventure`
- [2026/04] **GraSP: Graph-Structured Skill Compositions for LLM Agents** *arXiv* [[paper](https://arxiv.org/abs/2604.17870)] `#text-adventure` `#planning` `#memory` `#self-improvement`
- [2026/04] **DPEPO: Diverse Parallel Exploration Policy Optimization for LLM-based Agents** *arXiv* [[paper](https://arxiv.org/abs/2604.24320)][[code](https://github.com/LePanda026/Code-for-DPEPO)] `#text-adventure` `#training`
- [2026/03] **Hindsight Credit Assignment for Long-Horizon LLM Agents** *arXiv* [[paper](https://arxiv.org/abs/2603.08754)] `#text-adventure` `#training`
- [2026/03] **How Clued up are LLMs? Evaluating Multi-Step Deductive Reasoning in a Text-Based Game Environment** *arXiv* [[paper](https://arxiv.org/abs/2603.17169)] `#text-adventure` `#multi-agent` `#training`
- [2026/03] **RPMS: Enhancing LLM-Based Embodied Planning through Rule-Augmented Memory Synergy** *arXiv* [[paper](https://arxiv.org/abs/2603.17831)] `#text-adventure` `#planning` `#memory`
- [2026/03] **RetroAgent: From Solving to Evolving via Retrospective Dual Intrinsic Feedback** *arXiv* [[paper](https://arxiv.org/abs/2603.08561)] `#text-adventure` `#memory` `#training` `#self-improvement`
- [2026/03] **Reward Prediction with Factorized World States** *arXiv* [[paper](https://arxiv.org/abs/2603.09400)] `#text-adventure` `#planning` `#prompting`
- [2026/02] **MemSkill: Learning and Evolving Memory Skills for Self-Evolving Agents** *arXiv* [[paper](https://arxiv.org/abs/2602.02474)] `#text-adventure` `#self-improvement`
- [2026/02] **Active Epistemic Control for Query-Efficient Verified Planning** *arXiv* [[paper](https://arxiv.org/abs/2602.03974)] `#text-adventure` `#planning`
- [2026/02] **Think Fast and Slow: Step-Level Cognitive Depth Adaptation for LLM Agents** *arXiv* [[paper](https://arxiv.org/abs/2602.12662)] `#text-adventure` `#planning` `#training`
- [2026/02] **TAPE: Tool-Guided Adaptive Planning and Constrained Execution in Language Model Agents** *arXiv* [[paper](https://arxiv.org/abs/2602.19633)] `#text-adventure` `#planning`
- [2026/02] **CWM: Contrastive World Models for Action Feasibility Learning in Embodied Agent Pipelines** *arXiv* [[paper](https://arxiv.org/abs/2602.22452)] `#text-adventure` `#planning` `#world-model` `#training`
- [2026/02] **Reinforcement World Model Learning for LLM-based Agents** *arXiv* [[paper](https://arxiv.org/abs/2602.05842)] `#text-adventure` `#world-model`
- [2026/02] **SELAUR: Self Evolving LLM Agent via Uncertainty-aware Rewards** *arXiv* [[paper](https://arxiv.org/abs/2602.21158)] `#text-adventure` `#training`
- [2026/02] **SkillRL: Evolving Agents via Recursive Skill-Augmented Reinforcement Learning** *arXiv* [[paper](https://arxiv.org/abs/2602.08234)][[code](https://github.com/aiming-lab/SkillRL)] `#text-adventure` `#memory` `#tool-use` `#training`
- [2026/01] **Learning How to Remember: A Meta-Cognitive Management Method for Structured and Transferable Agent Memory** *arXiv* [[paper](https://arxiv.org/abs/2601.07470)] `#text-adventure`
- [2026/01] **Beyond Entangled Planning: Task-Decoupled Planning for Long-Horizon Agents** *arXiv* [[paper](https://arxiv.org/abs/2601.07577)] `#text-adventure` `#planning` `#prompting`
- [2026/01] **Paying Less Generalization Tax: A Cross-Domain Generalization Study of RL Training for LLM Agents** *arXiv* [[paper](https://arxiv.org/abs/2601.18217)] `#text-adventure` `#planning` `#training`
- [2026/01] **Just-In-Time Reinforcement Learning: Continual Learning in LLM Agents Without Gradient Updates** *arXiv* [[paper](https://arxiv.org/abs/2601.18510)][[code](https://github.com/liushiliushi/JitRL)] `#text-adventure` `#training`
- [2025/12] **Learning Hierarchical Procedural Memory for LLM Agents through Bayesian Selection and Contrastive Refinement** *Proceedings of the 25th International Conference on Autonomous Agents and Multiagent Systems 2025* [[paper](https://arxiv.org/abs/2512.18950)] `#text-adventure` `#memory`
- [2025/12] **GenEnv: Difficulty-Aligned Co-Evolution Between LLM Agents and Environment Simulators** *arXiv* [[paper](https://arxiv.org/abs/2512.19682)] `#text-adventure`
- [2025/11] **SkillGen: Learning Domain Skills for In-Context Sequential Decision Making** *arXiv* [[paper](https://arxiv.org/abs/2511.14670)] `#text-adventure` `#prompting`
- [2025/10] **Fine-tuning with RAG for Improving LLM Learning of New Skills** *arXiv* [[paper](https://arxiv.org/abs/2510.01375)] `#text-adventure` `#planning` `#memory` `#training`
- [2025/10] **GenQuest: An LLM-based Text Adventure Game for Language Learners** *arXiv* [[paper](https://arxiv.org/abs/2510.04498)] `#text-adventure` `#vlm` `#generation`
- [2025/10] **Constrained Natural Language Action Planning for Resilient Embodied Systems** *arXiv* [[paper](https://arxiv.org/abs/2510.06357)] `#text-adventure` `#planning` `#prompting`
- [2025/10] **The Cognitive Bandwidth Bottleneck: Shifting Long-Horizon Agent from Planning with Actions to Planning with Schemas** *arXiv* [[paper](https://arxiv.org/abs/2510.07091)] `#text-adventure` `#planning`
- [2025/10] **Graph-Enhanced Policy Optimization in LLM Agent Training** *arXiv* [[paper](https://arxiv.org/abs/2510.26270)] `#text-adventure` `#planning` `#training`
- [2025/10] **SALT: Step-level Advantage Assignment for Long-horizon Agents via Trajectory Graph** *arXiv* [[paper](https://arxiv.org/abs/2510.20022)] `#text-adventure` `#training`
- [2025/09] **World Model Implanting for Test-time Adaptation of Embodied Agents** *ICML 2025 poster* [[paper](https://arxiv.org/abs/2509.03956)] `#text-adventure` `#memory` `#world-model` `#prompting`
- [2025/09] **Meta-Policy Reflexion: Reusable Reflective Memory and Rule Admissibility for Resource-Efficient LLM Agent** *arXiv* [[paper](https://arxiv.org/abs/2509.03990)] `#text-adventure` `#planning` `#multi-agent` `#self-improvement`
- [2025/09] **Code Driven Planning with Domain-Adaptive Critic** *arXiv* [[paper](https://arxiv.org/abs/2509.19077)] `#text-adventure` `#planning` `#self-improvement`
- [2025/09] **Harnessing Uncertainty: Entropy-Modulated Policy Gradients for Long-Horizon LLM Agents** *arXiv* [[paper](https://arxiv.org/abs/2509.09265)] `#text-adventure` `#training`
- [2025/09] **Reflect before Act: Proactive Error Correction in Language Models** *arXiv* [[paper](https://arxiv.org/abs/2509.18607)] `#text-adventure`
- [2025/09] **Reward Is Enough: LLMs Are In-Context Reinforcement Learners** *ICLR 2026 Poster* [[paper](https://openreview.net/forum?id=keCXNHOe4W)] `#text-adventure` `#training` `#self-improvement`
- [2025/09] **Natural Language PDDL (NL-PDDL) for Open-world Goal-oriented Commonsense Regression Planning in Embodied AI** *ICLR 2026 Poster* [[paper](https://openreview.net/forum?id=kWCNhRdcDI)] `#text-adventure` `#planning` `#vlm`
- [2025/09] **Test-Time Mixture of World Models for Embodied Agents in Dynamic Environments** *ICLR 2026 Poster* [[paper](https://openreview.net/forum?id=LQD1MrnbxH)] `#text-adventure` `#prompting`
- [2025/09] **Spinning Straw into Gold: Relabeling LLM Agent Trajectories in Hindsight for Successful Demonstrations** *ICLR 2026 Poster* [[paper](https://openreview.net/forum?id=QNfmqMSR7r)] `#text-adventure` `#training`
- [2025/09] **Dual-Scale World Memory for LLM Agents towards Hard-Exploration Problems** *ICLR 2026 Poster* [[paper](https://openreview.net/forum?id=bH5uHIVtTe)] `#text-adventure`
- [2025/09] **Code Driven Planning with Domain-Adaptive Selector** *ICLR 2026 Poster* [[paper](https://openreview.net/forum?id=yDbJHQlrbf)] `#text-adventure` `#planning`
- [2025/09] **Exploratory Memory-Augmented LLM Agent via Hybrid On- and Off-Policy Optimization** *ICLR 2026 Poster* [[paper](https://openreview.net/forum?id=UOzxviKVFO)] `#text-adventure` `#memory` `#training`
- [2025/09] **DreamPhase: Offline Imagination and Uncertainty-Guided Planning for Large-Language-Model Agents** *ICLR 2026 Poster* [[paper](https://openreview.net/forum?id=81PJ2KPnmK)] `#text-adventure` `#planning` `#world-model`
- [2025/09] **Learn the Ropes, Then Trust the Wins: Self-imitation with Progressive Exploration for Agentic Reinforcement Learning** *ICLR 2026 Poster* [[paper](https://openreview.net/forum?id=Kssko33Ekq)] `#text-adventure` `#tool-use` `#training`
- [2025/08] **Enhancing Vision-Language Model Training with Reinforcement Learning in Synthetic Worlds for Real-World Success** *Proceedings of the 25th International Conference on Autonomous Agents and Multiagent Systems 2025* [[paper](https://arxiv.org/abs/2508.04280)] `#text-adventure` `#planning` `#training` `#vlm`
- [2025/07] **CoEx -- Co-evolving World-model and Exploration** *EMNLP 2025* [[paper](https://arxiv.org/abs/2507.22281)] `#text-adventure` `#planning` `#world-model`
- [2025/06] **Enhancing Decision-Making of Large Language Models via Actor-Critic** *ICML 2025 poster* [[paper](https://arxiv.org/abs/2506.06376)] `#text-adventure` `#training`
- [2025/06] **Improving LLM Agent Planning with In-Context Learning via Atomic Fact Augmentation and Lookahead Search** *arXiv* [[paper](https://arxiv.org/abs/2506.09171)] `#text-adventure` `#planning` `#world-model` `#training`
- [2025/06] **StoryBench: A Dynamic Benchmark for Evaluating Long-Term Memory with Multi Turns** *arXiv* [[paper](https://arxiv.org/abs/2506.13356)] `#text-adventure` `#memory`
- [2025/06] **OmniReflect: Discovering Transferable Constitutions for LLM agents via Neuro-Symbolic Reflections** *arXiv* [[paper](https://arxiv.org/abs/2506.17449)] `#text-adventure` `#planning` `#training` `#self-improvement`
- [2025/06] **KnowMap: Efficient Knowledge-Driven Task Adaptation for LLMs** *arXiv* [[paper](https://arxiv.org/abs/2506.19527)] `#text-adventure` `#training`
- [2025/05] **STORY2GAME: Generating (Almost) Everything in an Interactive Fiction Game** *arXiv* [[paper](https://arxiv.org/abs/2505.03547)] `#text-adventure` `#generation`
- [2025/05] **LLM-BABYBENCH: Understanding and Evaluating Grounded Planning and Reasoning in LLMs** *arXiv* [[paper](https://arxiv.org/abs/2505.12135)][[code](https://github.com/choukrani/llm-babybench}{\text{GitHub}}$)] `#text-adventure` `#planning`
- [2025/05] **Divide and Conquer: Grounding LLMs as Efficient Decision-Making Agents via Offline Hierarchical Reinforcement Learning** *ICML 2025 poster* [[paper](https://arxiv.org/abs/2505.19761)] `#text-adventure` `#planning` `#training`
- [2025/05] **Retrospex: Language Agent Meets Offline Reinforcement Learning Critic** *EMNLP 2025* [[paper](https://arxiv.org/abs/2505.11807)] `#text-adventure` `#training`
- [2025/05] **Agent-Environment Alignment via Automated Interface Generation** *arXiv* [[paper](https://arxiv.org/abs/2505.21055)][[code](https://github.com/THUNLP-MT/ALIGN)] `#text-adventure` `#tool-use`
- [2025/05] **Divide, Optimize, Merge: Fine-Grained LLM Agent Optimization at Scale** *arXiv* [[paper](https://arxiv.org/abs/2505.03973)] `#text-adventure`
- [2025/05] **Self-Generated In-Context Examples Improve LLM Agents for Sequential Decision-Making Tasks** *NeurIPS 2025 poster* [[paper](https://arxiv.org/abs/2505.00234)] `#text-adventure`
- [2025/05] **Learning to Play Like Humans: A Framework for LLM Adaptation in Interactive Fiction Games** *ACL 2025* [[paper](https://arxiv.org/abs/2505.12439)] `#text-adventure`
- [2025/05] **Training LLM-Based Agents with Synthetic Self-Reflected Trajectories and Partial Masking** *arXiv* [[paper](https://arxiv.org/abs/2505.20023)] `#text-adventure` `#prompting`
- [2025/05] **SPA-RL: Reinforcing LLM Agents via Stepwise Progress Attribution** *arXiv* [[paper](https://arxiv.org/abs/2505.20732)][[code](https://github.com/WangHanLinHenry/SPA-RL-Agent)] `#text-adventure` `#training`
- [2025/05] **ActiveVOO: Value of Observation Guided Active Knowledge Acquisition for Open-World Embodied Lifted Regression Planning** *NeurIPS 2025 poster* [[paper](https://openreview.net/forum?id=cZVYswQQMt)] `#text-adventure` `#planning` `#prompting` `#vlm`
- [2025/05] **SEEA-R1: Tree-Structured Reinforcement Fine-Tuning for Self-Evolving Embodied Agents** *NeurIPS 2025 poster* [[paper](https://openreview.net/forum?id=dAwKePZvcN)] `#text-adventure` `#planning` `#training` `#self-improvement`
- [2025/04] **TALES: Text Adventure Learning Environment Suite** *arXiv* [[paper](https://arxiv.org/abs/2504.14128)] `#text-adventure`
- [2025/04] **Monte Carlo Planning with Large Language Model for Text-Based Game Agents** *ICLR 2025 Poster* [[paper](https://arxiv.org/abs/2504.16855)] `#text-adventure` `#planning` `#training`
- [2025/04] **Group-in-Group Policy Optimization for LLM Agent Training** *NeurIPS 2025 poster* [[paper](https://openreview.net/forum?id=QXEhBMNrCW)] `#text-adventure` `#training`
- [2025/03] **Haunted House: A text-based game for comparing the flexibility of mental models in humans and LLMs** *arXiv* [[paper](https://arxiv.org/abs/2503.16437)] `#text-adventure`
- [2025/03] **GFlowVLM: Enhancing Multi-step Reasoning in Vision-Language Models with Generative Flow Networks** *CVPR 2025* [[paper](https://arxiv.org/abs/2503.06514)] `#text-adventure` `#planning` `#training` `#vlm`
- [2025/02] **TextGames: Learning to Self-Play Text-Based Puzzle Games via Language Model Reasoning.** *arXiv* [[paper](https://arxiv.org/pdf/2502.18431)] `#text-adventure` `#self-improvement`
- [2025/02] **Process Reward Models for LLM Agents: Practical Framework and Directions** *arXiv* [[paper](https://arxiv.org/abs/2502.10325)][[code](https://github.com/sanjibanc/agent_prm)] `#text-adventure` `#training`
- [2024/12] **Fine-tuning large vision-language models as decision-making agents via reinforcement learning** *NeurIPS 2024* [[paper](https://proceedings.neurips.cc/paper_files/paper/2024/file/c848b7d3adc08fcd0bf1df3101ba6728-Paper-Conference.pdf)][[code](https://github.com/RL4VLM/RL4VLM)] `#text-adventure` `#training` `#vlm`
- [2024/09] **Discriminator-Guided Embodied Planning for LLM Agent** *ICLR 2025 Poster* [[paper](https://openreview.net/forum?id=TjP1d8PP8l)] `#text-adventure` `#planning`
- [2024/09] **Better than Your Teacher: LLM Agents that learn from Privileged AI Feedback** *ICLR 2025 Poster* [[paper](https://openreview.net/forum?id=st7XqFgbAH)] `#text-adventure` `#planning` `#training` `#self-improvement`
- [2024/07] **AppWorld: A Controllable World of Apps and People for Benchmarking Interactive Coding Agents** *ACL 2024* [[paper](https://arxiv.org/abs/2407.18901)][[code](https://github.com/stonybrooknlp/appworld)] `#text-adventure` `#tool-use`
- [2024/07] **Arigraph: Learning knowledge graph world models with episodic memory for llm agents** *IJCAI 2024* [[paper](https://arxiv.org/abs/2407.04363)] `#text-adventure` `#planning` `#memory`
- [2024/06] **Watch Every Step! LLM Agent Learning via Iterative Step-Level Process Refinement** *EMNLP 2024* [[paper](https://arxiv.org/pdf/2406.11176)][[code](https://github.com/WeiminXiong/IPR)] `#text-adventure` `#self-improvement`
- [2024/06] **STARLING: Self-supervised Training of Text-based Reinforcement Learning Agent with Large Language Models** *ACL 2024* [[paper](https://arxiv.org/pdf/2406.05872)][[code](https://github.com/IBM/starling-agent)] `#text-adventure` `#training`
- [2024/05] **Agent Planning with World Knowledge Model** *NeurIPS 2024* [[paper](https://arxiv.org/pdf/2405.14205)][[code](https://github.com/zjunlp/WKM)] `#text-adventure` `#planning` `#memory` `#world-model`
- [2024/05] **THREAD: Thinking Deeper with Recursive Spawning** *NAACL 2024* [[paper](https://arxiv.org/pdf/2405.17402)] `#text-adventure` `#prompting`
- [2024/05] **Policy Improvement using Language Feedback Models** *NeurIPS 2024 poster* [[paper](https://openreview.net/forum?id=FVgCwcwpJw)] `#text-adventure` `#training`
- [2024/05] **AutoManual: Constructing Instruction Manuals by LLM Agents via Interactive Environmental Learning** *NeurIPS 2024 poster* [[paper](https://openreview.net/forum?id=Pwl9n4zlf5)][[code](https://github.com/minghchen/automanual)] `#text-adventure` `#planning`
- [2024/04] **Learning From Failure: Integrating Negative Examples When Fine-tuning Large Language Models as Agent** *arXiv* [[paper](https://arxiv.org/pdf/2402.11651)][[code](https://github.com/Reason-Wang/NAT)] `#text-adventure` `#tool-use` `#training`
- [2024/04] **ReAct Meets ActRe: When Language Agents Enjoy Training Data Autonomy** *arXiv* [[paper](https://arxiv.org/pdf/2403.14589)] `#text-adventure` `#planning` `#training` `#self-improvement`
- [2024/03] **KnowAgent: Knowledge-Augmented Planning for LLM-Based Agents** *NAACL 2024* [[paper](https://arxiv.org/abs/2403.03101.pdf)][[code](https://github.com/zjunlp/KnowAgent)] `#text-adventure` `#planning`
- [2024/03] **Language Guided Exploration for RL Agents in Text Environments** *NAACL 2024* [[paper](https://arxiv.org/abs/2403.03141.pdf)][[code](https://github.com/hitzkrieg/drrn-scienceworld-clone)] `#text-adventure` `#training`
- [2024/03] **Trial and Error: Exploration-Based Trajectory Optimization for LLM Agents** *ACL 2024* [[paper](https://arxiv.org/pdf/2403.02502)][[code](https://github.com/Yifan-Song793/ETO)] `#text-adventure` `#training` `#self-improvement`
- [2024/03] **O3D: Offline Data-driven Discovery and Distillation for Sequential Decision-Making with Large Language Models** *COLM* [[paper](https://openreview.net/forum?id=bkY8zEDdH9)] `#text-adventure` `#training`
- [2024/03] **ReAct Meets ActRe: Autonomous Annotation of Agent Trajectories for Contrastive Self-Training** *COLM* [[paper](https://openreview.net/forum?id=0VLBwQGWpA)] `#text-adventure` `#planning` `#training` `#self-improvement`
- [2024/03] **StateFlow: Enhancing LLM Task-Solving through State-Driven Workflows** *COLM* [[paper](https://openreview.net/forum?id=3nTbuygoop)] `#text-adventure` `#planning` `#self-improvement`
- [2024/02] **Soft Self-Consistency Improves Language Model Agents** *arXiv* [[paper](https://arxiv.org/abs/2402.13212.pdf)][[code](https://github.com/HanNight/soft_self_consistency)] `#text-adventure` `#self-improvement`
- [2024/02] **Empowering Large Language Model Agents through Action Learning** *COLM* [[paper](https://arxiv.org/abs/2402.15809)][[code](https://github.com/zhao-ht/LearnAct)] `#text-adventure` `#planning` `#self-improvement`
- [2023/11] **ADaPT: As-Needed Decomposition and Planning with Language Models** *NAACL 2023* [[paper](https://arxiv.org/abs/2311.05772)][[code](https://github.com/archiki/ADaPT)] `#text-adventure` `#planning`
- [2023/10] **FireAct: Toward Language Agent Fine-tuning** *arXiv* [[paper](https://arxiv.org/pdf/2310.05915)][[code](https://github.com/anchen1011/FireAct)] `#text-adventure` `#training`
- [2023/10] **Language Agent Tree Search Unifies Reasoning Acting and Planning in Language Models** *ICML 2024* [[paper](https://arxiv.org/pdf/2310.04406)][[code](https://github.com/lapisrocks/LanguageAgentTreeSearch)] `#text-adventure` `#planning` `#training`
- [2023/05] **SwiftSage: A Generative Agent with Fast and Slow Thinking for Complex Interactive Tasks** *NeurIPS 2023* [[paper](https://proceedings.neurips.cc/paper_files/paper/2023/hash/4b0eea69deea512c9e2c469187643dc2-Abstract-Conference.html)][[code](https://github.com/yuchenlin/SwiftSage)] `#text-adventure` `#planning`
- [2023/04] **Can Large Language Models Play Text Games Well? Current State-of-the-Art and Open Questions** *arXiv* [[paper](https://arxiv.org/pdf/2304.02868.pdf)] `#text-adventure` `#world-model`
- [2023/03] **Reflexion: Language Agents with Verbal Reinforcement Learning** *NeurIPS 2023* [[paper](https://proceedings.neurips.cc/paper_files/paper/2023/hash/1b44b878bb782e6954cd888628510e90-Abstract-Conference.html)][[code](https://github.com/noahshinn/reflexion)] `#text-adventure` `#training` `#self-improvement`
- [2022/10] **ReAct: Synergizing Reasoning and Acting in Language Models** *ICLR 2023* [[paper](https://arxiv.org/abs/2210.03629)][[code](https://github.com/ysymyth/ReAct)] `#text-adventure` `#planning` `#training`
- [2022/03] **ScienceWorld: Is your Agent Smarter than a 5th Grader?** *EMNLP 2022* [[paper](https://arxiv.org/abs/2203.07540.pdf)][[code](https://github.com/allenai/ScienceWorld)] `#text-adventure`
- [2020/10] **ALFWorld: Aligning Text and Embodied Environments for Interactive Learning** *ICLR 2021* [[paper](https://arxiv.org/pdf/2010.03768.pdf)][[code](https://github.com/alfworld/alfworld)] `#text-adventure` `#planning`
- [2019/09] **Interactive Fiction Games: A Colossal Adventure** *AAAI 2020* [[paper](https://ojs.aaai.org/index.php/AAAI/article/view/6297)][[code](https://github.com/Microsoft/jericho)] `#text-adventure`

## communication

- [2026/05] **Evaluating Large Language Models in a Complex Hidden Role Game** *arXiv* [[paper](https://arxiv.org/abs/2605.22826)] `#communication` `#planning`
- [2026/05] **QUACK: Questioning, Understanding, and Auditing Communicated Knowledge in Multimodal Social Deduction Agents** *arXiv* [[paper](https://arxiv.org/abs/2605.27068)][[code](https://github.com/AAAAA-Academia-Attractions/QUACK)] `#communication`
- [2026/04] **Trust, Lies, and Long Memories: Emergent Social Dynamics and Reputation in Multi-Round Avalon with LLM Agents** *arXiv* [[paper](https://arxiv.org/abs/2604.20582)] `#communication`
- [2026/03] **Enhancing Consistency of Werewolf AI through Dialogue Summarization and Persona Information** *arXiv* [[paper](https://arxiv.org/abs/2603.07111)] `#communication` `#role-play`
- [2026/03] **Deception and Communication in Autonomous Multi-Agent Systems: An Experimental Study with Among Us** *Proceedings of the 25th International Conference on Autonomous Agents and Multiagent Systems 2026* [[paper](https://arxiv.org/abs/2603.26635)] `#communication` `#multi-agent`
- [2026/01] **Hidden in Plain Text: Measuring LLM Deception Quality Against Human Baselines Using Social Deduction Games** *International Conference on Agents 2027* [[paper](https://arxiv.org/abs/2601.13709)] `#communication` `#multi-agent`
- [2026/01] **Multicultural Spyfall: Assessing LLMs through Dynamic Multilingual Social Deduction Game** *arXiv* [[paper](https://arxiv.org/abs/2601.09017)] `#communication`
- [2025/12] **WOLF: Werewolf-based Observations for LLM Deception and Falsehoods** *arXiv* [[paper](https://arxiv.org/abs/2512.09187)] `#communication` `#multi-agent`
- [2025/12] **Measuring Fine-Grained Negotiation Tactics of Humans and LLMs in Diplomacy** *arXiv* [[paper](https://arxiv.org/abs/2512.18292)] `#communication` `#training`
- [2025/11] **CSP4SDG: Constraint and Information-Theory Based Role Identification in Social Deduction Games with LLM-Enhanced Inference** *AAAI 2025* [[paper](https://arxiv.org/abs/2511.06175)] `#communication`
- [2025/11] **Multi-agent Undercover Gaming: Hallucination Removal via Counterfactual Test for Multimodal Reasoning** *arXiv* [[paper](https://arxiv.org/abs/2511.11182)][[code](https://github.com/YongLD/MUG.git)] `#communication` `#multi-agent`
- [2025/10] **Beyond Survival: Evaluating LLMs in Social Deduction Games with Human-Aligned Strategies** *arXiv* [[paper](https://arxiv.org/abs/2510.11389)] `#communication` `#multi-agent` `#self-improvement`
- [2025/08] **Democratizing Diplomacy: A Harness for Evaluating Any Large Language Model on Full-Press Diplomacy** *AAAI 2025* [[paper](https://arxiv.org/abs/2508.07485)] `#communication` `#training`
- [2025/08] **What to Ask Next? Probing the Imaginative Reasoning of LLMs with TurtleSoup Puzzles** *AAAI 2025* [[paper](https://arxiv.org/abs/2508.10358)] `#communication`
- [2025/08] **Ethical Considerations of Large Language Models in Game Playing** *arXiv* [[paper](https://arxiv.org/abs/2508.16065)] `#communication`
- [2025/07] **CoMet: Metaphor-Driven Covert Communication for Multi-Agent Language Games** *ACL 2025* [[paper](https://www.arxiv.org/abs/2505.18218)][[code](https://github.com/Yeswolo/CoMet)] `#communication` `#multi-agent`
- [2025/07] **Strategy Adaptation in Large Language Model Werewolf Agents** *arXiv* [[paper](https://arxiv.org/abs/2507.12732)] `#communication` `#prompting`
- [2025/06] **WereWolf-Plus: An Update of Werewolf Game setting Based on DSGBench** *arXiv* [[paper](https://arxiv.org/abs/2506.12841)][[code](https://github.com/MinstrelsyXia/WereWolfPlus)] `#communication` `#multi-agent`
- [2025/06] **DipLLM: Fine-Tuning LLM for Strategic Decision-making in Diplomacy** *ICML 2025 poster* [[paper](https://arxiv.org/abs/2506.09655)] `#communication` `#training`
- [2025/05] **Planning without Search: Refining Frontier LLMs with Offline Goal-Conditioned RL** *NeurIPS 2025 poster* [[paper](https://openreview.net/forum?id=kuoD6G0Suq)] `#communication` `#planning` `#tool-use` `#training`
- [2025/01] **DVM: Towards Controllable LLM Agents in Social Deduction Games** *IEEE International Conference on Acoustics, Speech, and Signal Processing 2025* [[paper](https://arxiv.org/abs/2501.06695)] `#communication` `#training`
- [2024/12] **Richelieu: Self-Evolving LLM-Based Agents for AI Diplomacy** *NeurIPS 2024* [[paper](https://openreview.net/pdf?id=7Jb4NJS8Yk)][[code](https://sites.google.com/view/richelieu-diplomacy)] `#communication` `#self-improvement`
- [2024/09] **Strategist: Self-improvement of LLM Decision Making via Bi-Level Tree Search** *ICLR 2025 Poster* [[paper](https://openreview.net/forum?id=gfI9v7AbFg)] `#communication` `#planning` `#multi-agent` `#training`
- [2024/06] **PLAYER: Enhancing LLM-based Multi-Agent Communication and Interaction in Murder Mystery Games** *arXiv* [[paper](https://arxiv.org/pdf/2404.17662)] `#communication` `#multi-agent`
- [2024/05] **Learning to Discuss Strategically: A Case Study on One Night Ultimate Werewolf** *NeurIPS 2024 poster* [[paper](https://openreview.net/forum?id=1f82rnwCbl)] `#communication` `#training`
- [2024/05] **Richelieu: Self-Evolving LLM-Based Agents for AI Diplomacy** *NeurIPS 2024 poster* [[paper](https://openreview.net/forum?id=7Jb4NJS8Yk)] `#communication` `#planning` `#multi-agent` `#self-improvement`
- [2024/04] **Self-playing Adversarial Language Game Enhances LLM Reasoning** *NeurIPS 2024* [[paper](https://arxiv.org/pdf/2404.10642)][[code](https://arxiv.org/pdf/2404.10642)] `#communication` `#training` `#self-improvement`
- [2024/03] **Helmsman of the Masses? Evaluate the Opinion Leadership of Large Language Models in the Werewolf Game** *COLM* [[paper](https://openreview.net/forum?id=xMt9kCv5YR)] `#communication` `#multi-agent`
- [2024/02] **Enhance Reasoning for Large Language Models in the Game Werewolf** *arXiv* [[paper](https://arxiv.org/abs/2402.02330.pdf)] `#communication` `#training`
- [2024/02] **What if LLMs Have Different World Views: Simulating Alien Civilizations with LLM-based Agents** *arXiv* [[paper](https://arxiv.org/abs/2402.13184.pdf)] `#communication`
- [2024/02] **Can Large Language Model Agents Simulate Human Trust Behaviors?** *NeurIPS 2024* [[paper](https://arxiv.org/pdf/2402.04559)] `#communication`
- [2024/02] **Large Language Models Fall Short: Understanding Complex Relationships in Detective Narratives** *ACL 2024* [[paper](https://www.arxiv.org/pdf/2402.11051)] `#communication`
- [2023/12] **Can Large Language Models Serve as Rational Players in Game Theory? A Systematic Analysis** *AAAI 2024* [[paper](https://arxiv.org/abs/2312.05488)] `#communication`
- [2023/12] **Cooperation on the Fly: Exploring Language Agents for Ad Hoc Teamwork in the Avalon Game** *arXiv* [[paper](https://arxiv.org/abs/2312.17515.pdf)] `#communication` `#multi-agent`
- [2023/12] **Deciphering Digital Detectives: Understanding LLM Behaviors and Capabilities in Multi-Agent Mystery Games** *ACL 2023* [[paper](https://arxiv.org/pdf/2312.00746.pdf)] `#communication` `#multi-agent` `#prompting`
- [2023/11] **War and Peace (WarAgent): Large Language Model-based Multi-Agent Simulation of World Wars** *arXiv* [[paper](https://arxiv.org/abs/2311.17227.pdf)][[code](https://github.com/agiresearch/WarAgent)] `#communication` `#multi-agent`
- [2023/11] **clembench: Systematic Evaluation of Chat-Optimized Language Models as Conversational Agents** *EMNLP 2023* [[paper](https://aclanthology.org/2023.emnlp-main.689.pdf)] `#communication`
- [2023/10] **Language Agents with Reinforcement Learning for Strategic Play in the Werewolf Game** *ICML 2023* [[paper](https://arxiv.org/abs/2310.18940.pdf)] `#communication` `#training`
- [2023/10] **Avalon's Game of Thoughts: Battle Against Deception through Recursive Contemplation** *arXiv* [[paper](https://arxiv.org/abs/2310.01320)] `#communication` `#training`
- [2023/10] **LLM-Based Agent Society Investigation: Collaboration and Confrontation in Avalon Gameplay** *EMNLP 2023* [[paper](https://arxiv.org/abs/2310.14985)] `#communication` `#multi-agent`
- [2023/10] **Leveraging Word Guessing Games to Assess the Intelligence of Large Language Models** *arXiv* [[paper](https://arxiv.org/abs/2310.20499.pdf)][[code](https://github.com/Skytliang/SpyGame)] `#communication` `#multi-agent`
- [2023/10] **AvalonBench: Evaluating LLMs Playing the Game of Avalon** *FMDM@NeurIPS2023* [[paper](https://openreview.net/pdf?id=ltUrSryS0K)][[code](https://github.com/jonathanmli/Avalon-LLM)] `#communication`
- [2023/09] **Exploring Large Language Models for Communication Games: An Empirical Study on Werewolf** *arXiv* [[paper](https://arxiv.org/abs/2309.04658.pdf)] `#communication` `#memory`
- [2023/08] **GameEval: Evaluating LLMs on Conversational Games** *arXiv* [[paper](https://arxiv.org/abs/2308.10032.pdf)][[code](https://github.com/jordddan/GameEval)] `#communication`
- [2022/12] **Human-Level Play in the Game of Diplomacy by Combining Language Models with Strategic Reasoning** *Science* [[paper](https://www.science.org/doi/pdf/10.1126/science.ade9097?casa_token=AB3PXQnKr8YAAAAA:pJO8TUkmbEUH77IhRcn-4r9PpxQc0jRgKokE3ElhmFvAhyTdjjS8aHOgJ_ViH_BnJwMDtTqdMmJgug)] `#communication`

## competition

- [2026/05] **GAMBIT: A Three-Mode Benchmark for Adversarial Robustness in Multi-Agent LLM Collectives** *arXiv* [[paper](https://arxiv.org/abs/2605.09027)] `#competition` `#multi-agent` `#prompting`
- [2026/05] **Watermarking Game-Playing Agents in Perfect-Information Extensive-Form Games** *arXiv* [[paper](https://arxiv.org/abs/2605.14283)] `#competition`
- [2026/05] **Generalization or Memorization? Brittleness Testing for Chess-Trained Language Models** *arXiv* [[paper](https://arxiv.org/abs/2605.17565)] `#competition` `#training`
- [2026/04] **Readable Minds: Emergent Theory-of-Mind-Like Behavior in LLM Poker Agents** *arXiv* [[paper](https://arxiv.org/abs/2604.04157)] `#competition`
- [2026/04] **MARL-GPT: Foundation Model for Multi-Agent Reinforcement Learning** *Proceedings of the 25th International Conference on Autonomous Agents and Multiagent Systems 2026* [[paper](https://arxiv.org/abs/2604.05943)] `#competition` `#multi-agent` `#training`
- [2026/03] **Grounded Chess Reasoning in Language Models via Master Distillation** *arXiv* [[paper](https://arxiv.org/abs/2603.20510)] `#competition` `#planning` `#training`
- [2026/03] **GTO Wizard Benchmark** *arXiv* [[paper](https://arxiv.org/abs/2603.23660)] `#competition` `#planning` `#multi-agent` `#prompting`
- [2026/03] **Self-Evolving Multi-Agent Framework for Efficient Decision Making in Real-Time Strategy Scenarios** *arXiv* [[paper](https://arxiv.org/abs/2603.23875)] `#competition` `#planning` `#memory` `#multi-agent`
- [2026/02] **World Models for Policy Refinement in StarCraft II** *arXiv* [[paper](https://arxiv.org/abs/2602.14857)] `#competition` `#world-model` `#prompting`
- [2026/02] **VAM: Verbalized Action Masking for Controllable Exploration in RL Post-Training -- A Chess Case Study** *arXiv* [[paper](https://arxiv.org/abs/2602.16833)] `#competition` `#training`
- [2025/12] **LLM CHESS: Benchmarking Reasoning and Instruction-Following in LLMs through Chess** *arXiv* [[paper](https://arxiv.org/abs/2512.01992)] `#competition`
- [2025/12] **Beyond Accuracy: A Geometric Stability Analysis of Large Language Models in Chess Evaluation** *arXiv* [[paper](https://arxiv.org/abs/2512.15033)] `#competition`
- [2025/10] **Memory-Augmented State Machine Prompting: A Novel LLM Agent Framework for Real-Time Strategy Games** *arXiv* [[paper](https://arxiv.org/abs/2510.18395)] `#competition` `#memory`
- [2025/10] **ChessQA: Evaluating Large Language Models for Chess Understanding** *arXiv* [[paper](https://arxiv.org/abs/2510.23948)] `#competition`
- [2025/10] **Out-of-distribution Tests Reveal Compositionality in Chess Transformers** *arXiv* [[paper](https://arxiv.org/abs/2510.20783)] `#competition` `#planning`
- [2025/09] **HLSMAC: A New StarCraft Multi-Agent Challenge for High-Level Strategic Decision-Making** *arXiv* [[paper](https://arxiv.org/abs/2509.12927)] `#competition` `#multi-agent` `#training`
- [2025/09] **Speculative Actions: A Lossless Framework for Faster AI Agents** *ICLR 2026 Oral* [[paper](https://openreview.net/forum?id=P0GOk5wslg)] `#competition` `#tool-use`
- [2025/09] **SPIRAL: Self-Play on Zero-Sum Games Incentivizes Reasoning via Multi-Agent Multi-Turn Reinforcement Learning** *ICLR 2026 Poster* [[paper](https://openreview.net/forum?id=7Yayy5fNLg)] `#competition` `#planning` `#multi-agent` `#training`
- [2025/08] **Tracking World States with Language Models: State-Based Evaluation Using Chess** *arXiv* [[paper](https://arxiv.org/abs/2508.19851)] `#competition`
- [2025/08] **SC2Arena and StarEvolve: Benchmark and Self-Improvement Framework for LLMs in Complex Decision-Making Tasks** *arXiv* [[paper](https://arxiv.org/abs/2508.10428)] `#competition` `#planning` `#training` `#self-improvement`
- [2025/07] **Learning to Imitate with Less: Efficient Individual Behavior Modeling in Chess** *arXiv* [[paper](https://arxiv.org/abs/2507.21488)] `#competition`
- [2025/05] **Enfoque Odychess: Un método dialéctico, constructivista y adaptativo para la enseñanza del ajedrez con inteligencias artificiales generativas** *arXiv* [[paper](https://arxiv.org/abs/2505.06652)] `#competition` `#training`
- [2025/05] **Can Large Language Models Master Complex Card Games?** *NeurIPS 2025 poster* [[paper](https://openreview.net/forum?id=cmN8Wbvanr)][[code](https://github.com/THUDM/LLM4CardGame)] `#competition` `#training`
- [2025/04] **Explore the Reasoning Capability of LLMs in the Chess Testbed** *NAACL 2025* [[paper](https://arxiv.org/abs/2411.06655)] `#competition`
- [2025/04] **ZeroSumEval: Scaling LLM Evaluation with Inter-Model Competition** *arXiv* [[paper](https://arxiv.org/abs/2504.12562)][[code](https://github.com/facebookresearch/ZeroSumEval)] `#competition` `#planning`
- [2025/04] **LLM-PySC2: Starcraft II learning environment for Large Language Models** *NeurIPS 2025 poster* [[paper](https://openreview.net/forum?id=Xr73jEYG29)] `#competition` `#planning` `#multi-agent` `#vlm`
- [2025/04] **The PokeAgent Challenge: Competitive and Long Context Learning at Scale** *NeurIPS Competition Track 2025* [[paper](https://sethkarten.ai/data/NeurIPS_2025_PokeAgent_Challenge.pdf)] `#competition`
- [2025/03] **Society of Mind Meets Real-Time Strategy: A Hierarchical Multi-Agent Framework for Strategic Reasoning** *COLM 2025* [[paper](https://arxiv.org/abs/2508.06042)] `#competition` `#multi-agent` `#training`
- [2025/02] **Hierarchical Expert Prompt for Large-Language-Model: An Approach Defeat Elite AI in TextStarCraft II for the First Time** *arXiv* [[paper](https://arxiv.org/abs/2502.11122)][[code](https://github.com/luchang1113/HEP-LLM-play-StarCraftII)] `#competition`
- [2025/02] **Implicit Search via Discrete Diffusion: A Study on Chess** *ICLR 2025 Poster* [[paper](https://arxiv.org/abs/2502.19805)][[code](https://github.com/HKUNLP/DiffuSearch}{https://github.com/HKUNLP/DiffuSearch})] `#competition` `#planning`
- [2025/01] **POKERBENCH: Training Large Language Models to become Professional Poker Players** *AAAI 2025* [[paper](https://arxiv.org/pdf/2501.08328)] `#competition` `#planning` `#training`
- [2025/01] **Complete Chess Games Enable LLM Become A Chess Master** *NAACL 2025* [[paper](https://arxiv.org/abs/2501.17186)] `#competition` `#training`
- [2025/01] **Mastering Board Games by External and Internal Planning with Language Models** *ICML 2025 spotlightposter* [[paper](https://openreview.net/forum?id=KKwBo3u3IW)] `#competition` `#planning`
- [2025/01] **Language Models as Implicit Tree Search** *ICML 2025 poster* [[paper](https://openreview.net/forum?id=bEqMmGu6qg)] `#competition` `#planning` `#training`
- [2024/10] **PokéChamp: An Expert-level Minimax Language Agent** *ICML 2025* [[paper](https://arxiv.org/abs/2503.04094)][[code](https://github.com/sethkarten/PokeChamp)] `#competition` `#planning`
- [2024/08] **Evaluating and Enhancing LLMs Agent based on Theory of Mind in Guandan: A Multi-Player Cooperative Game under Imperfect Information** *2024 IEEE/WIC International Conference on Web Intelligence and Intelligent Agent Technology (WI-IAT) 2024* [[paper](https://arxiv.org/pdf/2408.02559)] `#competition` `#planning` `#multi-agent` `#training`
- [2024/05] **Measuring Progress in Dictionary Learning for Language Model Interpretability with Board Game Models** *NeurIPS 2024 poster* [[paper](https://openreview.net/forum?id=SCEdoGghcw)] `#competition`
- [2024/05] **Reflective Multi-Agent Collaboration based on Large Language Models** *NeurIPS 2024 poster* [[paper](https://openreview.net/forum?id=wWiAR5mqXq)] `#competition` `#planning` `#multi-agent` `#training`
- [2024/03] **Embodied LLM Agents Learn to Cooperate in Organized Teams** *IEEE Transactions on Computational Social Systems 2024* [[paper](https://arxiv.org/pdf/2403.12482)] `#competition` `#planning` `#multi-agent`
- [2024/02] **PokéLLMon: A Human-Parity Agent for Pokémon Battles with Large Language Models** *TOIT 2025* [[paper](https://arxiv.org/abs/2402.01118.pdf)][[code](https://github.com/git-disl/PokeLLMon)] `#competition` `#training`
- [2024/02] **Agent-Pro: Learning to Evolve via Policy-Level Reflection and Optimization** *ACL 2024* [[paper](https://arxiv.org/abs/2402.17574.pdf)][[code](https://github.com/zwq2018/Agent-Pro)] `#competition` `#training`
- [2024/01] **PokerGPT: An End-to-End Lightweight Solver for Multi-Player Texas Hold'em via Large Language Model** *arXiv* [[paper](https://arxiv.org/abs/2401.06781)] `#competition` `#training`
- [2024/01] **SwarmBrain: Embodied agent for real-time strategy game StarCraft II via large language models** *arXiv* [[paper](https://arxiv.org/abs/2401.17749.pdf)] `#competition` `#training`
- [2023/12] **Large Language Models Play StarCraft II: Benchmarks and A Chain of Summarization Approach** *NeurIPS 2024 poster* [[paper](https://arxiv.org/abs/2312.11865.pdf)][[code](https://github.com/histmeisah/Large-Language-Models-play-StarCraftII/tree/main)] `#competition` `#planning`
- [2023/09] **Suspicion-Agent: Playing Imperfect Information Games with Theory of Mind Aware GPT-4** *COLM 2024* [[paper](https://arxiv.org/abs/2309.17277.pdf)] `#competition` `#planning` `#memory` `#prompting`
- [2023/08] **Are ChatGPT and GPT-4 Good Poker Players?--A Pre-Flop Analysis** *arXiv* [[paper](https://arxiv.org/abs/2308.12466)] `#competition`
- [2023/06] **ChessGPT: Bridging Policy Learning and Language Modeling** *NeurIPS 2023* [[paper](https://proceedings.neurips.cc/paper_files/paper/2023/hash/16b14e3f288f076e0ca73bdad6405f77-Abstract-Datasets_and_Benchmarks.html)][[code](https://github.com/waterhorse1/ChessGPT)] `#competition`
- [2022/10] **Emergent World Representations: Exploring a Sequence Model Trained on a Synthetic Task** *ICLR 2023* [[paper](https://arxiv.org/pdf/2210.13382.pdf)] `#competition`

## cooperation

- [2026/04] **Don't Make the LLM Read the Graph: Make the Graph Think** *arXiv* [[paper](https://arxiv.org/abs/2604.23057)] `#cooperation` `#multi-agent`
- [2026/03] **On the Strengths and Weaknesses of Data for Open-set Embodied Assistance** *arXiv* [[paper](https://arxiv.org/abs/2603.04819)] `#cooperation` `#training`
- [2025/12] **ReCollab: Retrieval-Augmented LLMs for Cooperative Ad-hoc Teammate Modeling** *arXiv* [[paper](https://arxiv.org/abs/2512.22129)] `#cooperation` `#memory`
- [2025/10] **LLM-Hanabi: Evaluating Multi-Agent Gameplays with Theory-of-Mind and Rationale Inference in Imperfect Information Collaboration Game** *arXiv* [[paper](https://arxiv.org/abs/2510.04980)] `#cooperation` `#multi-agent`
- [2025/08] **CausalPlan: Empowering Efficient LLM Multi-Agent Collaboration Through Causality-Driven Planning** *arXiv* [[paper](https://arxiv.org/abs/2508.13721)] `#cooperation` `#planning` `#multi-agent` `#training`
- [2025/06] **PSALM-V: Automating Symbolic Planning in Interactive Visual Environments with Large Language Models** *arXiv* [[paper](https://arxiv.org/abs/2506.20097)] `#cooperation` `#planning` `#multi-agent`
- [2024/05] **Towards Efficient LLM Grounding for Embodied Multi-Agent Collaboration** *ACL 2024* [[paper](https://arxiv.org/pdf/2405.14314)][[code](https://arxiv.org/pdf/2405.14314)] `#cooperation` `#planning` `#multi-agent` `#training`
- [2024/03] **Can LLM-Augmented Autonomous Agents Cooperate?, An Evaluation of Their Cooperative Capabilities through Melting Pot** *IEEE Transactions on Artificial Intelligence 2024* [[paper](https://arxiv.org/abs/2403.11381.pdf)] `#cooperation` `#multi-agent`
- [2024/03] **ProAgent: Building Proactive Cooperative Agents with Large Language Models** *AAAI 2024* [[paper](https://ojs.aaai.org/index.php/AAAI/article/view/29710)] `#cooperation`
- [2024/02] **S-Agents: Self-organizing Agents in Open-ended Environments** *arXiv* [[paper](https://arxiv.org/abs/2402.04578)] `#cooperation`
- [2023/12] **LLM-Powered Hierarchical Language Agent for Real-time Human-AI Coordination** *AAMAS 2023* [[paper](https://arxiv.org/abs/2312.15224.pdf)] `#cooperation`
- [2023/10] **Evaluating Multi-agent Coordination Abilities in Large Language Models** *NAACL 2023* [[paper](https://arxiv.org/abs/2310.03903.pdf)] `#cooperation` `#planning` `#multi-agent` `#prompting`
- [2023/10] **Theory of Mind for Multi-Agent Collaboration via Large Language Models** *EMNLP 2023* [[paper](https://arxiv.org/pdf/2310.10701)][[code](https://github.com/romanlee6/multi_LLM_comm)] `#cooperation` `#planning` `#multi-agent` `#training`
- [2023/09] **MindAgent: Emergent Gaming Interaction** *NAACL 2023* [[paper](http://https://arxiv.org/abs/2309.09971)] `#cooperation` `#planning` `#multi-agent` `#prompting`
- [2023/07] **Building Cooperative Embodied Agents Modularly with Large Language Models** *ICLR 2024* [[paper](https://arxiv.org/abs/2307.02485.pdf)][[code](https://github.com/UMass-Foundation-Model/Co-LLM-Agents/)] `#cooperation` `#planning` `#multi-agent` `#training`

## sim-social

- [2026/05] **GASim: A Graph-Accelerated Hybrid Framework for Social Simulation** *arXiv* [[paper](https://arxiv.org/abs/2605.07692)][[code](https://github.com/Jasmine0201/GASim)] `#sim-social` `#memory` `#multi-agent`
- [2026/05] **ScioMind: Cognitively Grounded Multi-Agent Social Simulation with Anchoring-Based Belief Dynamics and Dynamic Profiles** *arXiv* [[paper](https://arxiv.org/abs/2605.13725)] `#sim-social` `#memory` `#multi-agent`
- [2026/05] **ALSO: Adversarial Online Strategy Optimization for Social Agents** *arXiv* [[paper](https://arxiv.org/abs/2605.15768)] `#sim-social` `#multi-agent` `#training`
- [2026/05] **PAVE: A Cognitive Architecture for Legitimate Violation in Generative Agent Societies** *arXiv* [[paper](https://arxiv.org/abs/2605.19351)] `#sim-social` `#role-play`
- [2026/04] **LLM-Agent-based Social Simulation for Attitude Diffusion** *arXiv* [[paper](https://arxiv.org/abs/2604.03898)] `#sim-social` `#memory`
- [2026/04] **Restoring Heterogeneity in LLM-based Social Simulation: An Audience Segmentation Approach** *arXiv* [[paper](https://arxiv.org/abs/2604.06663)] `#sim-social` `#role-play`
- [2026/04] **SLALOM: Simulation Lifecycle Analysis via Longitudinal Observation Metrics for Social Simulation** *arXiv* [[paper](https://arxiv.org/abs/2604.11466)] `#sim-social`
- [2026/04] **RPA-Check: A Multi-Stage Automated Framework for Evaluating Dynamic LLM-based Role-Playing Agents** *arXiv* [[paper](https://arxiv.org/abs/2604.11655)] `#sim-social` `#planning`
- [2026/04] **Superminds Test: Actively Evaluating Collective Intelligence of Agent Society via Probing Agents** *arXiv* [[paper](https://arxiv.org/abs/2604.22452)] `#sim-social`
- [2026/04] **Auditing Support Strategies in LLMs through Grounded Multi-Turn Social Simulation** *arXiv* [[paper](https://arxiv.org/abs/2604.17079)] `#sim-social`
- [2026/03] **PolicySim: An LLM-Based Agent Social Simulation Sandbox for Proactive Policy Optimization** *WWW 2026* [[paper](https://arxiv.org/abs/2603.19649)] `#sim-social` `#training`
- [2026/03] **Belief-Driven Multi-Agent Collaboration via Approximate Perfect Bayesian Equilibrium for Social Simulation** *WWW 2026* [[paper](https://arxiv.org/abs/2603.24973)][[code](https://github.com/WUT-IDEA/BEACOF)] `#sim-social` `#multi-agent`
- [2026/02] **AIvilization v0: Toward Large-Scale Artificial Social Simulation with a Unified Agent Architecture and Adaptive Agent Profiles** *arXiv* [[paper](https://arxiv.org/abs/2602.10429)] `#sim-social` `#planning`
- [2026/02] **Exploring Silicon-Based Societies: An Early Study of the Moltbook Agent Community** *arXiv* [[paper](https://arxiv.org/abs/2602.02613)] `#sim-social`
- [2026/02] **Does Socialization Emerge in AI Agent Society? A Case Study of Moltbook** *Proceedings of the ACM Conference on AI and Agentic Systems 2026* [[paper](https://arxiv.org/abs/2602.14299)] `#sim-social`
- [2026/02] **The Devil Behind Moltbook: Anthropic Safety is Always Vanishing in Self-Evolving AI Societies** *arXiv* [[paper](https://arxiv.org/abs/2602.09877)] `#sim-social` `#multi-agent` `#self-improvement`
- [2026/01] **When Agents See Humans as the Outgroup: Belief-Dependent Bias in LLM-Powered Agents** *arXiv* [[paper](https://arxiv.org/abs/2601.00240)] `#sim-social` `#multi-agent`
- [2026/01] **MARO: Learning Stronger Reasoning from Social Interaction** *arXiv* [[paper](https://arxiv.org/abs/2601.12323)] `#sim-social` `#multi-agent`
- [2026/01] **HumanLLM: Towards Personalized Understanding and Simulation of Human Nature** *arXiv* [[paper](https://arxiv.org/abs/2601.15793)] `#sim-social` `#training`
- [2025/12] **EZYer: A simulacrum of high school with generative agent** *arXiv* [[paper](https://arxiv.org/abs/2512.02561)] `#sim-social` `#memory`
- [2025/12] **Agent-Kernel: A MicroKernel Multi-Agent System Framework for Adaptive Social Simulation Powered by LLMs** *arXiv* [[paper](https://arxiv.org/abs/2512.01610)] `#sim-social` `#multi-agent`
- [2025/10] **Multimodal Safety Evaluation in Generative Agent Social Simulations** *arXiv* [[paper](https://arxiv.org/abs/2510.07709)] `#sim-social` `#planning` `#vlm`
- [2025/10] **Alita-G: Self-Evolving Generative Agent for Agent Generation** *arXiv* [[paper](https://arxiv.org/abs/2510.23601)] `#sim-social` `#memory` `#self-improvement`
- [2025/10] **Doing Things with Words: Rethinking Theory of Mind Simulation in Large Language Models** *Computational Linguistics 2025* [[paper](https://arxiv.org/abs/2510.13395)] `#sim-social`
- [2025/10] **Social Simulations with Large Language Model Risk Utopian Illusion** *arXiv* [[paper](https://arxiv.org/abs/2510.21180)] `#sim-social` `#multi-agent`
- [2025/10] **Emergent Coordinated Behaviors in Networked LLM Agents: Modeling the Strategic Dynamics of Information Operations** *WWW 2025* [[paper](https://arxiv.org/abs/2510.25003)] `#sim-social`
- [2025/09] **Implicit Behavioral Alignment of Language Agents in High-Stakes Crowd Simulations** *EMNLP 2025* [[paper](https://arxiv.org/abs/2509.16457)] `#sim-social` `#role-play`
- [2025/09] **The Emergence of Altruism in Large-Language-Model Agents Society** *arXiv* [[paper](https://arxiv.org/abs/2509.22537)] `#sim-social`
- [2025/07] **LLM Economist: Large Population Models and Mechanism Design in Multi-Agent Generative Simulacra** *arXiv* [[paper](https://arxiv.org/abs/2507.15815)][[code](https://github.com/sethkarten/LLM-Economist)] `#sim-social` `#multi-agent` `#training` `#role-play`
- [2025/07] **Too Human to Model:The Uncanny Valley of LLMs in Social Simulation -- When Generative Language Agents Misalign with Modelling Principles** *arXiv* [[paper](https://arxiv.org/abs/2507.06310)] `#sim-social`
- [2025/07] **Validating Generative Agent-Based Models of Social Norm Enforcement: From Replication to Novel Predictions** *Annual Meeting of the Cognitive Science Society 2025* [[paper](https://arxiv.org/abs/2507.22049)] `#sim-social` `#role-play`
- [2025/06] **Empowering Economic Simulation for Massively Multiplayer Online Games through Generative Agent-Based Modeling** *KDD 2025* [[paper](https://arxiv.org/abs/2506.04699)] `#sim-social` `#training`
- [2025/06] **IndoorWorld: Integrating Physical Task Solving and Social Simulation in A Heterogeneous Multi-Agent Environment** *EMNLP 2025* [[paper](https://arxiv.org/abs/2506.12331)] `#sim-social` `#multi-agent`
- [2025/06] **AgentGroupChat-V2: Divide-and-Conquer Is What LLM-Based Multi-Agent System Need** *arXiv* [[paper](https://arxiv.org/abs/2506.15451)][[code](https://github.com/MikeGu721/AgentGroupChat-V2)] `#sim-social` `#planning` `#multi-agent`
- [2025/06] **Infected Smallville: How Disease Threat Shapes Sociality in LLM Agents** *arXiv* [[paper](https://arxiv.org/abs/2506.13783)] `#sim-social`
- [2025/05] **EcoLANG: Efficient and Effective Agent Communication Language Induction for Social Simulation** *EMNLP 2025* [[paper](https://arxiv.org/abs/2505.06904)] `#sim-social` `#role-play`
- [2025/04] **SOTOPIA-S4: a user-friendly system for flexible, customizable, and large-scale social simulation** *NAACL 2025* [[paper](https://arxiv.org/abs/2504.16122)] `#sim-social` `#planning`
- [2025/04] **BookWorld: From Novels to Interactive Agent Societies for Creative Story Generation** *arXiv* [[paper](https://arxiv.org/abs/2504.14538)] `#sim-social` `#multi-agent` `#generation`
- [2025/04] **MF-LLM: Simulating Population Decision Dynamics via a Mean-Field Large Language Model Framework** *NeurIPS 2025 poster* [[paper](https://openreview.net/forum?id=m0q8NfGWnv)] `#sim-social` `#planning` `#training`
- [2025/03] **The Impact of Big Five Personality Traits on AI Agent Decision-Making in Public Spaces: A Social Simulation Study** *arXiv* [[paper](https://arxiv.org/abs/2503.15497)] `#sim-social`
- [2025/02] **Investigating and Extending Homans' Social Exchange Theory with Large Language Model based Agents** *ACL 2025* [[paper](https://arxiv.org/abs/2502.12450)][[code](https://github.com/Paitesanshi/SET)] `#sim-social`
- [2025/01] **Simulating Human-like Daily Activities with Desire-driven Autonomy** *ICLR 2025* [[paper](https://arxiv.org/abs/2412.06435)][[code](https://github.com/zfw1226/D2A)] `#sim-social`
- [2025/01] **Are Human Interactions Replicable by Generative Agents? A Case Study on Pronoun Usage in Hierarchical Interactions** *arXiv* [[paper](https://arxiv.org/abs/2501.15283)] `#sim-social`
- [2024/10] **Project Sid: Many-agent simulations toward AI civilization** *arXiv* [[paper](https://arxiv.org/abs/2411.00114)] `#sim-social`
- [2024/06] **Artificial Leviathan: Exploring Social Evolution of LLM Agents Through the Lens of Hobbesian Social Contract Theory** *arXiv* [[paper](https://arxiv.org/abs/2406.14373)] `#sim-social` `#multi-agent`
- [2024/05] **Agent hospital: A simulacrum of hospital with evolvable medical agents** *arXiv* [[paper](https://arxiv.org/abs/2405.02957)] `#sim-social` `#planning`
- [2024/03] **SOTOPIA-$\pi$: Interactive Learning of Socially Intelligent Language Agents** *ACL 2024* [[paper](https://arxiv.org/pdf/2403.08715.pdf)][[code](https://github.com/sotopia-lab/sotopia-pi)] `#sim-social` `#training`
- [2023/10] **Humanoid Agents: Platform for Simulating Human-like Generative Agents** *EMNLP 2023* [[paper](https://arxiv.org/abs/2310.05418.pdf)] `#sim-social`
- [2023/10] **Lyfe Agents: Generative agents for low-cost real-time social interactions** *arXiv* [[paper](https://arxiv.org/abs/2310.02172.pdf)] `#sim-social` `#memory` `#multi-agent` `#self-improvement`
- [2023/10] **SOTOPIA: Interactive Evaluation for Social Intelligence in Language Agents** *ICLR 2023* [[paper](https://arxiv.org/abs/2310.11667.pdf)][[code](https://github.com/sotopia-lab/sotopia)] `#sim-social` `#role-play`
- [2023/08] **AgentSims: An Open-Source Sandbox for Large Language Model Evaluation** *arXiv* [[paper](https://arxiv.org/abs/2308.04026.pdf)][[code](https://github.com/py499372727/AgentSims)] `#sim-social` `#planning` `#tool-use`
- [2023/07] **S3: Social-network Simulation System with Large Language Model-Empowered Agents** *arXiv* [[paper](https://arxiv.org/pdf/2307.14984)] `#sim-social` `#prompting`
- [2023/04] **Generative Agents: Interactive Simulacra of Human Behavior** *UIST 2023* [[paper](https://dl.acm.org/doi/pdf/10.1145/3586183.3606763)][[code](https://github.com/joonspk-research/generative_agents)] `#sim-social`

## sim-embodied

- [2026/05] **Agent-BRACE: Decoupling Beliefs from Actions in Long-Horizon Tasks via Verbalized State Uncertainty** *arXiv* [[paper](https://arxiv.org/abs/2605.11436)] `#sim-embodied` `#training`
- [2026/05] **Probing Embodied LLMs: When Higher Observation Fidelity Hurts Problem Solving** *arXiv* [[paper](https://arxiv.org/abs/2605.20072)] `#sim-embodied`
- [2026/02] **To Move or Not to Move: Constraint-based Planning Enables Zero-Shot Generalization for Interactive Navigation** *arXiv* [[paper](https://arxiv.org/abs/2602.20055)] `#sim-embodied` `#planning` `#prompting` `#vlm`
- [2025/12] **Emergence: Overcoming Privileged Information Bias in Asymmetric Embodied Agents via Active Querying** *arXiv* [[paper](https://arxiv.org/abs/2512.15776)] `#sim-embodied`
- [2025/12] **ESearch-R1: Learning Cost-Aware MLLM Agents for Interactive Embodied Search via Reinforcement Learning** *arXiv* [[paper](https://arxiv.org/abs/2512.18571)] `#sim-embodied` `#planning` `#memory` `#training`
- [2025/12] **HELP: Hierarchical Embodied Language Planner for Household Tasks** *arXiv* [[paper](https://arxiv.org/abs/2512.21723)] `#sim-embodied` `#planning`
- [2025/11] **DR. WELL: Dynamic Reasoning and Learning with Symbolic World Model for Embodied LLM-Based Multi-Agent Collaboration** *arXiv* [[paper](https://arxiv.org/abs/2511.04646)] `#sim-embodied` `#planning` `#multi-agent` `#world-model`
- [2025/11] **MADRA: Multi-Agent Debate for Risk-Aware Embodied Planning** *arXiv* [[paper](https://arxiv.org/abs/2511.21460)] `#sim-embodied` `#planning` `#multi-agent` `#prompting`
- [2025/09] **ReCAPA: Hierarchical Predictive Correction to Mitigate Cascading Failures** *ICLR 2026 Poster* [[paper](https://openreview.net/forum?id=WC6MJ5r5Bj)] `#sim-embodied` `#planning`
- [2024/09] **Can We Trust Embodied Agents? Exploring Backdoor Attacks against Embodied LLM-Based Decision-Making Systems** *ICLR 2025 Poster* [[paper](https://openreview.net/forum?id=S1Bv3068Xt)] `#sim-embodied` `#training`
- [2024/09] **BadRobot: Jailbreaking Embodied LLM Agents in the Physical World** *ICLR 2025 Poster* [[paper](https://openreview.net/forum?id=ei3qCntB66)] `#sim-embodied` `#planning` `#vlm`
- [2024/09] **GameGen-X: Interactive Open-world Game Video Generation** *ICLR 2025 Poster* [[paper](https://openreview.net/forum?id=8VG8tpPZhe)][[code](https://github.com/GameGen-X/GameGen-X)] `#sim-embodied` `#vlm`
- [2024/01] **True Knowledge Comes from Practice: Aligning LLMs with Embodied Environments via Reinforcement Learning** *arXiv* [[paper](https://arxiv.org/pdf/2401.14151.pdf)][[code](https://github.com/WeihaoTan/TWOSOME)] `#sim-embodied` `#training`
- [2023/10] **Octopus: Embodied Vision-Language Programmer from Environmental Feedback** *ECCV 2023* [[paper](https://arxiv.org/abs/2310.08588.pdf)][[code](https://github.com/dongyh20/Octopus)] `#sim-embodied` `#planning` `#training` `#vlm`
- [2023/05] **Language Models Meet World Models: Embodied Experiences Enhance Language Models** *NeurIPS 2023* [[paper](https://arxiv.org/abs/2305.10626.pdf)][[code](https://github.com/szxiangjn/world-model-for-language-model)] `#sim-embodied` `#planning` `#world-model`
- [2022/12] **LLM-Planner: Few-Shot Grounded Planning for Embodied Agents with Large Language Models** *ICCV 2023* [[paper](https://openaccess.thecvf.com/content/ICCV2023/html/Song_LLM-Planner_Few-Shot_Grounded_Planning_for_Embodied_Agents_with_Large_Language_ICCV_2023_paper.html)] `#sim-embodied` `#planning` `#prompting`
- [2022/01] **Language Models as Zero-ShoSSocial-network Simulation Planners: Extracting Actionable Knowledge for Embodied Agents** *ICML 2022* [[paper](https://proceedings.mlr.press/v162/huang22a.html)][[code](https://github.com/huangwl18/language-planner)] `#sim-embodied`

## sim-other

- [2024/01] **CivRealm: A Learning and Reasoning Odyssey in Civilization for Decision-Making Agents** *ICLR 2024* [[paper](https://arxiv.org/abs/2401.10568.pdf)][[code](https://github.com/bigai-ai/civrealm)] `#sim-other`

## crafter

- [2025/09] **Goal-Guided Efficient Exploration via Large Language Model in Reinforcement Learning** *arXiv* [[paper](https://arxiv.org/abs/2509.22008)] `#crafter` `#planning` `#training`
- [2025/08] **HERAKLES: Hierarchical Skill Compilation for Open-ended LLM Agents** *arXiv* [[paper](https://arxiv.org/abs/2508.14751)] `#crafter` `#planning` `#training`
- [2025/06] **Automated Skill Discovery for Language Agents through Exploration and Iterative Feedback** *arXiv* [[paper](https://arxiv.org/abs/2506.04287)] `#crafter` `#self-improvement`
- [2025/02] **LLM-Powered Decentralized Generative Agents with Adaptive Hierarchical Knowledge Graph for Cooperative Planning** *arXiv* [[paper](https://arxiv.org/abs/2502.05453)] `#crafter` `#planning` `#memory` `#multi-agent`
- [2024/10] **Mars: Situated Inductive Reasoning in an Open-World Environment** *NeurIPS 2024* [[paper](https://arxiv.org/pdf/2410.08126)] `#crafter`
- [2024/07] **Enhancing Agent Learning through World Dynamics Modeling** *EMNLP 2024* [[paper](https://arxiv.org/pdf/2407.17695)] `#crafter`
- [2024/04] **AgentKit: Flow Engineering with Graphs, not Coding** *arXiv* [[paper](https://arxiv.org/pdf/2404.11483)][[code](https://github.com/holmeswww/AgentKit)] `#crafter` `#planning`
- [2024/04] **World Models with Hints of Large Language Models for Goal Achieving** *NAACL 2024* [[paper](https://arxiv.org/pdf/2406.07381)] `#crafter` `#training` `#vlm`
- [2024/03] **EnvGen: Generating and Adapting Environments via LLMs for Training Embodied Agents** *COLM* [[paper](https://arxiv.org/abs/2403.12014.pdf)] `#crafter` `#training`
- [2024/03] **AgentKit: Structured LLM Reasoning with Dynamic Graphs** *COLM* [[paper](https://openreview.net/forum?id=PKfAq8N4fK)] `#crafter` `#planning`
- [2023/09] **AdaRefiner: Refining Decisions of Language Models with Adaptive Feedback** *NAACL 2023* [[paper](https://arxiv.org/pdf/2309.17176.pdf)] `#crafter` `#training`
- [2023/06] **OMNI: Open-endedness via Models of human Notions of Interestingness** *arXiv* [[paper](https://arxiv.org/abs/2306.01711.pdf)][[code](https://github.com/jennyzzt/omni)] `#crafter`
- [2023/05] **SPRING: Studying Papers and Reasoning to play Games** *NeurIPS 2023* [[paper](https://proceedings.neurips.cc/paper_files/paper/2023/hash/46c2a9a6f2b2be68682013eb1173c801-Abstract-Conference.html)] `#crafter`
- [2023/02] **Guiding Pretraining in Reinforcement Learning with Large Language Models** *ICML 2023* [[paper](https://arxiv.org/abs/2302.06692)] `#crafter` `#training`

## action

- [2026/05] **Odysseus: Scaling VLMs to 100+ Turn Decision-Making in Games via Reinforcement Learning** *arXiv* [[paper](https://arxiv.org/abs/2605.00347)] `#action` `#training` `#vlm`
- [2026/05] **ANO: A Principled Approach to Robust Policy Optimization** *arXiv* [[paper](https://arxiv.org/abs/2605.02320)] `#action` `#training`
- [2026/05] **Brain alignment of reasoning and action representations from vision-language and action models during naturalistic gameplay** *arXiv* [[paper](https://arxiv.org/abs/2605.19352)] `#action` `#planning` `#training` `#vlm`
- [2026/04] **Playing DOOM with 1.3M Parameters: Specialized Small Models vs Large Language Models for Real-Time Game Control** *arXiv* [[paper](https://arxiv.org/abs/2604.07385)] `#action`
- [2026/04] **PokeGym: A Visually-Driven Long-Horizon Benchmark for Vision-Language Models** *arXiv* [[paper](https://arxiv.org/abs/2604.08340)] `#action` `#planning` `#vlm`
- [2026/04] **GRAIL: Autonomous Concept Grounding for Neuro-Symbolic Reinforcement Learning** *arXiv* [[paper](https://arxiv.org/abs/2604.16871)] `#action` `#training`
- [2026/03] **Understanding the Challenges in Iterative Generative Optimization with LLMs** *arXiv* [[paper](https://arxiv.org/abs/2603.23994)] `#action`
- [2026/03] **See, Symbolize, Act: Grounding VLMs with Spatial Representations for Better Gameplay** *arXiv* [[paper](https://arxiv.org/abs/2603.11601)] `#action` `#vlm`
- [2026/02] **Implicit Strategic Optimization: Rethinking Long-Horizon Decision-Making in Adversarial Poker Environments** *arXiv* [[paper](https://arxiv.org/abs/2602.08041)] `#action` `#training`
- [2025/12] **Robust Agents in Open-Ended Worlds** *arXiv* [[paper](https://arxiv.org/abs/2512.08139)] `#action` `#multi-agent` `#training` `#generation`
- [2025/09] **Exploration with Foundation Models: Capabilities, Limitations, and Hybrid Approaches** *arXiv* [[paper](https://arxiv.org/abs/2509.19924)] `#action` `#training` `#vlm`
- [2025/08] **A Multi-Agent Pokemon Tournament for Evaluating Strategic Reasoning of Large Language Models** *arXiv* [[paper](https://arxiv.org/abs/2508.01623)] `#action` `#multi-agent`
- [2025/08] **Learning Game-Playing Agents with Generative Code Optimization** *arXiv* [[paper](https://arxiv.org/abs/2508.19506)] `#action` `#training` `#self-improvement`
- [2025/05] **Frog Soup: Zero-Shot, In-Context, and Sample-Efficient Frogger Agents** *arXiv* [[paper](https://arxiv.org/abs/2505.03947)][[code](https://github.com/AlienKevin/frogger)] `#action` `#training`
- [2025/05] **Multiple Weaks Win Single Strong: Large Language Models Ensemble Weak Reinforcement Learning Agents into a Supreme One** *arXiv* [[paper](https://arxiv.org/abs/2505.15306)] `#action` `#training`
- [2025/05] **Prompted Policy Search: Reinforcement Learning through Linguistic and Numerical Reasoning in LLMs** *NeurIPS 2025 poster* [[paper](https://openreview.net/forum?id=95plu1Mo20)] `#action` `#training`
- [2025/05] **LLM-Explorer: A Plug-in Reinforcement Learning Policy Exploration Enhancement Driven by Large Language Models** *NeurIPS 2025 spotlight* [[paper](https://openreview.net/forum?id=VA5P0rUZPx)][[code](https://github.com/tsinghua-fib-lab/LLM-Explorer)] `#action` `#training`
- [2025/05] **PoE-World: Compositional World Modeling with Products of Programmatic Experts** *NeurIPS 2025 spotlight* [[paper](https://openreview.net/forum?id=obwRcksFZw)] `#action` `#planning` `#world-model`
- [2025/04] **Better Decisions through the Right Causal World Model** *arXiv* [[paper](https://arxiv.org/abs/2504.07257)] `#action` `#planning` `#world-model` `#training`
- [2025/01] **LMAct: A Benchmark for In-Context Imitation Learning with Long Multimodal Demonstrations** *ICML 2025 poster* [[paper](https://openreview.net/forum?id=8aChcUzAhI)] `#action` `#planning` `#training`
- [2024/10] **Unbounded: A Generative Infinite Game of Character Life Simulation** *ICLR 2024* [[paper](https://arxiv.org/abs/2410.18975)] `#action`
- [2024/09] **Can VLMs Play Action Role-Playing Games? Take Black Myth Wukong as a Study Case** *arXiv* [[paper](https://arxiv.org/abs/2409.12889)][[code](https://varp-agent.github.io/)] `#action` `#planning` `#training`
- [2024/09] **MaestroMotif: Skill Design from Artificial Intelligence Feedback** *ICLR 2025 Oral* [[paper](https://openreview.net/forum?id=or8mMhmyRV)] `#action` `#training`
- [2024/09] **BALROG: Benchmarking Agentic LLM and VLM Reasoning On Games** *ICLR 2025 Poster* [[paper](https://openreview.net/forum?id=fp6t3F669F)] `#action` `#planning` `#training` `#vlm`
- [2024/08] **Atari-GPT: Investigating the Capabilities of Multimodal Large Language Models as Low-Level Policies for Atari Games** *arXiv* [[paper](https://arxiv.org/pdf/2408.15950)] `#action` `#planning` `#training`
- [2024/07] **Baba Is AI: Break the Rules to Beat the Benchmark** *ICML 2024* [[paper](https://arxiv.org/pdf/2407.13729)] `#action` `#vlm`
- [2024/03] **Will GPT-4 Run DOOM?** *IEEE Transactions on Games 2024* [[paper](https://arxiv.org/abs/2403.05468.pdf)][[code](https://github.com/adewynter/Doom)] `#action` `#planning` `#training`
- [2024/03] **Evaluate LLMs in Real Time with Street Fighter III** *GitHub* [[paper](https://github.com/OpenGenerativeAI/llm-colosseum)][[code](https://github.com/OpenGenerativeAI/llm-colosseum)] `#action`
- [2023/02] **Grounding Large Language Models in Interactive Environments with Online Reinforcement Learning** *ICML 2023* [[paper](https://arxiv.org/abs/2302.02662.pdf)][[code](https://github.com/flowersteam/Grounding_LLMs_with_online_RL)] `#action` `#training`

## video-adventure

- [2024/03] **Cradle: Empowering Foundation Agents Towards General Computer Control** *ICML 2024* [[paper](https://arxiv.org/abs/2403.03186.pdf)][[code](https://github.com/BAAI-Agents/Cradle)] `#video-adventure` `#planning`
- [2024/03] **Playing NetHack with LLMs: Potential & Limitations as Zero-Shot Agents** *2024 IEEE Conference on Games (CoG) 2024* [[paper](https://arxiv.org/pdf/2403.00690.pdf)][[code](https://github.com/CommanderCero/NetPlay)] `#video-adventure` `#planning` `#prompting`
- [2023/09] **Motif: Intrinsic Motivation from Artificial Intelligence Feedback** *ICLR 2024* [[paper](https://arxiv.org/abs/2310.00166.pdf)][[code](https://github.com/facebookresearch/motif)] `#video-adventure` `#training`

## benchmark

- [2026/01] **NitroGen: An Open Foundation Model for Generalist Gaming Agents** *arXiv* [[paper](https://arxiv.org/abs/2601.02427)] `#benchmark` `#training`
- [2025/10] **Think Globally, Group Locally: Evaluating LLMs Using Multi-Lingual Word Grouping Games** *EMNLP 2025* [[paper](https://arxiv.org/abs/2510.14030)] `#benchmark`
- [2025/07] **GAMEBoT: Transparent Assessment of LLM Reasoning in Games** *ACL 2025 Main* [[paper](https://aclanthology.org/2025.acl-long.378/)][[code](https://github.com/Visual-AI/GAMEBoT)] `#benchmark` `#planning` `#prompting`
- [2025/06] **Orak: A Foundational Benchmark for Training and Evaluating LLM Agents on Diverse Video Games** *arXiv* [[paper](https://arxiv.org/pdf/2506.03610)][[code](https://github.com/krafton-ai/Orak)] `#benchmark` `#training`
- [2025/06] **UnrealZoo: Enriching Photo-realistic Virtual Worlds for Embodied AI** *ICCV 2025* [[paper](https://arxiv.org/abs/2412.20977)][[code](https://github.com/UnrealZoo/unrealzoo-gym)] `#benchmark` `#multi-agent` `#training`
- [2025/05] **lmgame-Bench: How Good are LLMs at Playing Games?."** *ICLR 2026 Poster* [[paper](https://arxiv.org/pdf/2505.15146)][[code](https://github.com/lmgame-org/GamingAgent/tree/main/lmgame-bench)] `#benchmark` `#planning` `#training`
- [2025/05] **Is Your LLM Really Mastering the Concept? A Multi-Agent Benchmark** *arXiv* [[paper](https://arxiv.org/pdf/2505.17512)][[code](https://ck-arena.site/)] `#benchmark` `#multi-agent`

## other

- [2026/04] **GameWorld: Towards Standardized and Verifiable Evaluation of Multimodal Game Agents** *arXiv* [[paper](https://arxiv.org/abs/2604.07429)] `#planning` `#vlm`
- [2026/04] **Nemobot Games: Crafting Strategic AI Gaming Agents for Interactive Learning with Large Language Models** *arXiv* [[paper](https://arxiv.org/abs/2604.21896)] `#tool-use` `#training` `#self-improvement`
- [2026/04] **From World-Gen to Quest-Line: A Dependency-Driven Prompt Pipeline for Coherent RPG Generation** *arXiv* [[paper](https://arxiv.org/abs/2604.25482)] `#planning` `#generation`
- [2026/03] **Sensi: Learn One Thing at a Time -- Curriculum-Based Test-Time Learning for LLM Game Agents** *arXiv* [[paper](https://arxiv.org/abs/2603.17683)]
- [2026/02] **VLM-Guided Experience Replay** *arXiv* [[paper](https://arxiv.org/abs/2602.01915)] `#planning` `#training` `#vlm`
- [2026/01] **SNAP: A Plan-Driven Framework for Controllable Interactive Narrative Generation** *arXiv* [[paper](https://arxiv.org/abs/2601.11529)] `#planning` `#generation`
- [2025/10] **ROBOPSY PL[AI]: Using Role-Play to Investigate how LLMs Present Collective Memory** *arXiv* [[paper](https://arxiv.org/abs/2510.09874)] `#role-play`
- [2025/08] **All Stories Are One Story: Emotional Arc Guided Procedural Game Level Generation** *arXiv* [[paper](https://arxiv.org/abs/2508.02132)] `#generation`
- [2025/08] **CHBench: A Cognitive Hierarchy Benchmark for Evaluating Strategic Reasoning Capability of LLMs** *arXiv* [[paper](https://arxiv.org/abs/2508.11944)] `#memory`
- [2025/06] **The Decrypto Benchmark for Multi-Agent Reasoning and Theory of Mind** *arXiv* [[paper](https://arxiv.org/abs/2506.20664)] `#multi-agent` `#training`
- [2025/04] **PAYADOR: A Minimalist Approach to Grounding Language Models on Structured Data for Interactive Storytelling and Role-playing Games** *arXiv* [[paper](https://arxiv.org/abs/2504.07304)]
- [2025/04] **Enhancing Player Enjoyment with a Two-Tier DRL and LLM-Based Agent System for Fighting Games** *arXiv* [[paper](https://arxiv.org/abs/2504.07425)] `#training`
- [2025/03] **Playing games with Large language models: Randomness and strategy** *arXiv* [[paper](https://arxiv.org/abs/2503.02582)] `#multi-agent`
- [2025/03] **Collaborative Storytelling and LLM: A Linguistic Analysis of Automatically-Generated Role-Playing Game Sessions** *arXiv* [[paper](https://arxiv.org/abs/2503.20623)]
- [2025/03] **Cultivating Game Sense for Yourself: Making VLMs Gaming Experts** *arXiv* [[paper](https://arxiv.org/abs/2503.21263)] `#vlm`
- [2025/02] **RPGBENCH: Evaluating Large Language Models as Role-Playing Game Engines** *arXiv* [[paper](https://arxiv.org/abs/2502.00595)]
- [2025/02] **Hybrid Voting-Based Task Assignment in Role-Playing Games** *arXiv* [[paper](https://arxiv.org/abs/2502.18690)] `#planning`
- [2024/09] **Agents' Room:  Narrative Generation through Multi-step Collaboration** *ICLR 2025 Poster* [[paper](https://openreview.net/forum?id=HfWcFs7XLR)] `#generation`
- [2024/07] **What if Red Can Talk? Dynamic Dialogue Generation Using Large Language Models.** *arXiv* [[paper](https://arxiv.org/pdf/2407.20382)] `#generation`
- [2023/10] **Language as reality: a co-creative storytelling game experience in 1001 nights using generative AI.** *AAAI 2023* [[paper](https://ojs.aaai.org/index.php/AIIDE/article/view/27539)] `#generation`


---

# By Mechanism

*The same papers as above, re-grouped by agent design. A paper with multiple Mechanism tags appears in each relevant section.*

## planning

- [2026/05] **From History to State: Constant-Context Skill Learning for LLM Agents** *arXiv* [[paper](https://arxiv.org/abs/2605.05413)] `#text-adventure` `#planning` `#training`
- [2026/05] **PriorZero: Bridging Language Priors and World Models for Decision Making** *arXiv* [[paper](https://arxiv.org/abs/2605.12289)][[code](https://github.com/opendilab/LightZero)] `#text-adventure` `#planning` `#world-model` `#training`
- [2026/05] **Brain alignment of reasoning and action representations from vision-language and action models during naturalistic gameplay** *arXiv* [[paper](https://arxiv.org/abs/2605.19352)] `#action` `#planning` `#training` `#vlm`
- [2026/05] **APEX: Autonomous Policy Exploration for Self-Evolving LLM Agents** *arXiv* [[paper](https://arxiv.org/abs/2605.21240)] `#text-adventure` `#planning` `#self-improvement`
- [2026/05] **Evaluating Large Language Models in a Complex Hidden Role Game** *arXiv* [[paper](https://arxiv.org/abs/2605.22826)] `#communication` `#planning`
- [2026/05] **SkillOps: Managing LLM Agent Skill Libraries as Self-Maintaining Software Ecosystems** *arXiv* [[paper](https://arxiv.org/abs/2605.13716)] `#text-adventure` `#planning` `#memory` `#tool-use`
- [2026/04] **Aligning Progress and Feasibility: A Neuro-Symbolic Dual Memory Framework for Long-Horizon LLM Agents** *arXiv* [[paper](https://arxiv.org/abs/2604.02734)] `#text-adventure` `#planning` `#memory`
- [2026/04] **GameWorld: Towards Standardized and Verifiable Evaluation of Multimodal Game Agents** *arXiv* [[paper](https://arxiv.org/abs/2604.07429)] `#planning` `#vlm`
- [2026/04] **PokeGym: A Visually-Driven Long-Horizon Benchmark for Vision-Language Models** *arXiv* [[paper](https://arxiv.org/abs/2604.08340)] `#action` `#planning` `#vlm`
- [2026/04] **RPA-Check: A Multi-Stage Automated Framework for Evaluating Dynamic LLM-based Role-Playing Agents** *arXiv* [[paper](https://arxiv.org/abs/2604.11655)] `#sim-social` `#planning`
- [2026/04] **DORA Explorer: Improving the Exploration Ability of LLMs Without Training** *arXiv* [[paper](https://arxiv.org/abs/2604.17244)] `#text-adventure` `#planning` `#prompting`
- [2026/04] **From Actions to Understanding: Conformal Interpretability of Temporal Concepts in LLM Agents** *arXiv* [[paper](https://arxiv.org/abs/2604.19775)] `#text-adventure` `#planning`
- [2026/04] **Complete Cyclic Subtask Graphs for Tool-Using LLM Agents: Flexibility, Cost, and Bottlenecks in Multi-Agent Workflows** *arXiv* [[paper](https://arxiv.org/abs/2604.22820)] `#text-adventure` `#planning` `#memory` `#multi-agent`
- [2026/04] **From World-Gen to Quest-Line: A Dependency-Driven Prompt Pipeline for Coherent RPG Generation** *arXiv* [[paper](https://arxiv.org/abs/2604.25482)] `#planning` `#generation`
- [2026/04] **GraSP: Graph-Structured Skill Compositions for LLM Agents** *arXiv* [[paper](https://arxiv.org/abs/2604.17870)] `#text-adventure` `#planning` `#memory` `#self-improvement`
- [2026/03] **RPMS: Enhancing LLM-Based Embodied Planning through Rule-Augmented Memory Synergy** *arXiv* [[paper](https://arxiv.org/abs/2603.17831)] `#text-adventure` `#planning` `#memory`
- [2026/03] **Grounded Chess Reasoning in Language Models via Master Distillation** *arXiv* [[paper](https://arxiv.org/abs/2603.20510)] `#competition` `#planning` `#training`
- [2026/03] **GTO Wizard Benchmark** *arXiv* [[paper](https://arxiv.org/abs/2603.23660)] `#competition` `#planning` `#multi-agent` `#prompting`
- [2026/03] **Reward Prediction with Factorized World States** *arXiv* [[paper](https://arxiv.org/abs/2603.09400)] `#text-adventure` `#planning` `#prompting`
- [2026/03] **Self-Evolving Multi-Agent Framework for Efficient Decision Making in Real-Time Strategy Scenarios** *arXiv* [[paper](https://arxiv.org/abs/2603.23875)] `#competition` `#planning` `#memory` `#multi-agent`
- [2026/02] **VLM-Guided Experience Replay** *arXiv* [[paper](https://arxiv.org/abs/2602.01915)] `#planning` `#training` `#vlm`
- [2026/02] **Active Epistemic Control for Query-Efficient Verified Planning** *arXiv* [[paper](https://arxiv.org/abs/2602.03974)] `#text-adventure` `#planning`
- [2026/02] **AIvilization v0: Toward Large-Scale Artificial Social Simulation with a Unified Agent Architecture and Adaptive Agent Profiles** *arXiv* [[paper](https://arxiv.org/abs/2602.10429)] `#sim-social` `#planning`
- [2026/02] **Think Fast and Slow: Step-Level Cognitive Depth Adaptation for LLM Agents** *arXiv* [[paper](https://arxiv.org/abs/2602.12662)] `#text-adventure` `#planning` `#training`
- [2026/02] **TAPE: Tool-Guided Adaptive Planning and Constrained Execution in Language Model Agents** *arXiv* [[paper](https://arxiv.org/abs/2602.19633)] `#text-adventure` `#planning`
- [2026/02] **To Move or Not to Move: Constraint-based Planning Enables Zero-Shot Generalization for Interactive Navigation** *arXiv* [[paper](https://arxiv.org/abs/2602.20055)] `#sim-embodied` `#planning` `#prompting` `#vlm`
- [2026/02] **CWM: Contrastive World Models for Action Feasibility Learning in Embodied Agent Pipelines** *arXiv* [[paper](https://arxiv.org/abs/2602.22452)] `#text-adventure` `#planning` `#world-model` `#training`
- [2026/01] **Beyond Entangled Planning: Task-Decoupled Planning for Long-Horizon Agents** *arXiv* [[paper](https://arxiv.org/abs/2601.07577)] `#text-adventure` `#planning` `#prompting`
- [2026/01] **SNAP: A Plan-Driven Framework for Controllable Interactive Narrative Generation** *arXiv* [[paper](https://arxiv.org/abs/2601.11529)] `#planning` `#generation`
- [2026/01] **Paying Less Generalization Tax: A Cross-Domain Generalization Study of RL Training for LLM Agents** *arXiv* [[paper](https://arxiv.org/abs/2601.18217)] `#text-adventure` `#planning` `#training`
- [2025/12] **ESearch-R1: Learning Cost-Aware MLLM Agents for Interactive Embodied Search via Reinforcement Learning** *arXiv* [[paper](https://arxiv.org/abs/2512.18571)] `#sim-embodied` `#planning` `#memory` `#training`
- [2025/12] **HELP: Hierarchical Embodied Language Planner for Household Tasks** *arXiv* [[paper](https://arxiv.org/abs/2512.21723)] `#sim-embodied` `#planning`
- [2025/11] **DR. WELL: Dynamic Reasoning and Learning with Symbolic World Model for Embodied LLM-Based Multi-Agent Collaboration** *arXiv* [[paper](https://arxiv.org/abs/2511.04646)] `#sim-embodied` `#planning` `#multi-agent` `#world-model`
- [2025/11] **MADRA: Multi-Agent Debate for Risk-Aware Embodied Planning** *arXiv* [[paper](https://arxiv.org/abs/2511.21460)] `#sim-embodied` `#planning` `#multi-agent` `#prompting`
- [2025/10] **Fine-tuning with RAG for Improving LLM Learning of New Skills** *arXiv* [[paper](https://arxiv.org/abs/2510.01375)] `#text-adventure` `#planning` `#memory` `#training`
- [2025/10] **Constrained Natural Language Action Planning for Resilient Embodied Systems** *arXiv* [[paper](https://arxiv.org/abs/2510.06357)] `#text-adventure` `#planning` `#prompting`
- [2025/10] **The Cognitive Bandwidth Bottleneck: Shifting Long-Horizon Agent from Planning with Actions to Planning with Schemas** *arXiv* [[paper](https://arxiv.org/abs/2510.07091)] `#text-adventure` `#planning`
- [2025/10] **Multimodal Safety Evaluation in Generative Agent Social Simulations** *arXiv* [[paper](https://arxiv.org/abs/2510.07709)] `#sim-social` `#planning` `#vlm`
- [2025/10] **Graph-Enhanced Policy Optimization in LLM Agent Training** *arXiv* [[paper](https://arxiv.org/abs/2510.26270)] `#text-adventure` `#planning` `#training`
- [2025/10] **Out-of-distribution Tests Reveal Compositionality in Chess Transformers** *arXiv* [[paper](https://arxiv.org/abs/2510.20783)] `#competition` `#planning`
- [2025/09] **Meta-Policy Reflexion: Reusable Reflective Memory and Rule Admissibility for Resource-Efficient LLM Agent** *arXiv* [[paper](https://arxiv.org/abs/2509.03990)] `#text-adventure` `#planning` `#multi-agent` `#self-improvement`
- [2025/09] **Code Driven Planning with Domain-Adaptive Critic** *arXiv* [[paper](https://arxiv.org/abs/2509.19077)] `#text-adventure` `#planning` `#self-improvement`
- [2025/09] **Goal-Guided Efficient Exploration via Large Language Model in Reinforcement Learning** *arXiv* [[paper](https://arxiv.org/abs/2509.22008)] `#crafter` `#planning` `#training`
- [2025/09] **Natural Language PDDL (NL-PDDL) for Open-world Goal-oriented Commonsense Regression Planning in Embodied AI** *ICLR 2026 Poster* [[paper](https://openreview.net/forum?id=kWCNhRdcDI)] `#text-adventure` `#planning` `#vlm`
- [2025/09] **Experience-based Knowledge Correction for Robust Planning in Minecraft** *ICLR 2026 Poster* [[paper](https://openreview.net/forum?id=N22lDHYrXe)] `#minecraft` `#planning`
- [2025/09] **SPIRAL: Self-Play on Zero-Sum Games Incentivizes Reasoning via Multi-Agent Multi-Turn Reinforcement Learning** *ICLR 2026 Poster* [[paper](https://openreview.net/forum?id=7Yayy5fNLg)] `#competition` `#planning` `#multi-agent` `#training`
- [2025/09] **Code Driven Planning with Domain-Adaptive Selector** *ICLR 2026 Poster* [[paper](https://openreview.net/forum?id=yDbJHQlrbf)] `#text-adventure` `#planning`
- [2025/09] **ReCAPA: Hierarchical Predictive Correction to Mitigate Cascading Failures** *ICLR 2026 Poster* [[paper](https://openreview.net/forum?id=WC6MJ5r5Bj)] `#sim-embodied` `#planning`
- [2025/09] **DreamPhase: Offline Imagination and Uncertainty-Guided Planning for Large-Language-Model Agents** *ICLR 2026 Poster* [[paper](https://openreview.net/forum?id=81PJ2KPnmK)] `#text-adventure` `#planning` `#world-model`
- [2025/08] **CausalMACE: Causality Empowered Multi-Agents in Minecraft Cooperative Tasks** *Findings of EMNLP 2025* [[paper](https://arxiv.org/abs/2508.18797)] `#minecraft` `#planning` `#multi-agent`
- [2025/08] **Enhancing Vision-Language Model Training with Reinforcement Learning in Synthetic Worlds for Real-World Success** *Proceedings of the 25th International Conference on Autonomous Agents and Multiagent Systems 2025* [[paper](https://arxiv.org/abs/2508.04280)] `#text-adventure` `#planning` `#training` `#vlm`
- [2025/08] **CausalPlan: Empowering Efficient LLM Multi-Agent Collaboration Through Causality-Driven Planning** *arXiv* [[paper](https://arxiv.org/abs/2508.13721)] `#cooperation` `#planning` `#multi-agent` `#training`
- [2025/08] **SC2Arena and StarEvolve: Benchmark and Self-Improvement Framework for LLMs in Complex Decision-Making Tasks** *arXiv* [[paper](https://arxiv.org/abs/2508.10428)] `#competition` `#planning` `#training` `#self-improvement`
- [2025/08] **HERAKLES: Hierarchical Skill Compilation for Open-ended LLM Agents** *arXiv* [[paper](https://arxiv.org/abs/2508.14751)] `#crafter` `#planning` `#training`
- [2025/07] **GAMEBoT: Transparent Assessment of LLM Reasoning in Games** *ACL 2025 Main* [[paper](https://aclanthology.org/2025.acl-long.378/)][[code](https://github.com/Visual-AI/GAMEBoT)] `#benchmark` `#planning` `#prompting`
- [2025/07] **CoEx -- Co-evolving World-model and Exploration** *EMNLP 2025* [[paper](https://arxiv.org/abs/2507.22281)] `#text-adventure` `#planning` `#world-model`
- [2025/06] **Optimus-3: Towards Generalist Multimodal Minecraft Agents with Scalable Task Experts** *arXiv* [[paper](https://arxiv.org/pdf/2506.10357)][[code](https://github.com/JiuTian-VL/Optimus-3)] `#minecraft` `#planning`
- [2025/06] **Improving LLM Agent Planning with In-Context Learning via Atomic Fact Augmentation and Lookahead Search** *arXiv* [[paper](https://arxiv.org/abs/2506.09171)] `#text-adventure` `#planning` `#world-model` `#training`
- [2025/06] **OmniReflect: Discovering Transferable Constitutions for LLM agents via Neuro-Symbolic Reflections** *arXiv* [[paper](https://arxiv.org/abs/2506.17449)] `#text-adventure` `#planning` `#training` `#self-improvement`
- [2025/06] **AgentGroupChat-V2: Divide-and-Conquer Is What LLM-Based Multi-Agent System Need** *arXiv* [[paper](https://arxiv.org/abs/2506.15451)][[code](https://github.com/MikeGu721/AgentGroupChat-V2)] `#sim-social` `#planning` `#multi-agent`
- [2025/06] **PSALM-V: Automating Symbolic Planning in Interactive Visual Environments with Large Language Models** *arXiv* [[paper](https://arxiv.org/abs/2506.20097)] `#cooperation` `#planning` `#multi-agent`
- [2025/05] **Don’t Just Follow MLLM Plans: Robust and Efficient Planning for Open-World Agents** *arXiv* [[paper](https://arxiv.org/abs/2505.24157)] `#minecraft` `#planning` `#vlm`
- [2025/05] **Knowledge Retrieval in LLM Gaming: A Shift from Entity-Centric to Goal-Oriented Graphs** *Knowledge-Based Systems 2025* [[paper](https://arxiv.org/abs/2505.18607)] `#minecraft` `#planning` `#memory`
- [2025/05] **lmgame-Bench: How Good are LLMs at Playing Games?."** *ICLR 2026 Poster* [[paper](https://arxiv.org/pdf/2505.15146)][[code](https://github.com/lmgame-org/GamingAgent/tree/main/lmgame-bench)] `#benchmark` `#planning` `#training`
- [2025/05] **LLM-BABYBENCH: Understanding and Evaluating Grounded Planning and Reasoning in LLMs** *arXiv* [[paper](https://arxiv.org/abs/2505.12135)][[code](https://github.com/choukrani/llm-babybench}{\text{GitHub}}$)] `#text-adventure` `#planning`
- [2025/05] **Divide and Conquer: Grounding LLMs as Efficient Decision-Making Agents via Offline Hierarchical Reinforcement Learning** *ICML 2025 poster* [[paper](https://arxiv.org/abs/2505.19761)] `#text-adventure` `#planning` `#training`
- [2025/05] **ActiveVOO: Value of Observation Guided Active Knowledge Acquisition for Open-World Embodied Lifted Regression Planning** *NeurIPS 2025 poster* [[paper](https://openreview.net/forum?id=cZVYswQQMt)] `#text-adventure` `#planning` `#prompting` `#vlm`
- [2025/05] **Planning without Search: Refining Frontier LLMs with Offline Goal-Conditioned RL** *NeurIPS 2025 poster* [[paper](https://openreview.net/forum?id=kuoD6G0Suq)] `#communication` `#planning` `#tool-use` `#training`
- [2025/05] **SEEA-R1: Tree-Structured Reinforcement Fine-Tuning for Self-Evolving Embodied Agents** *NeurIPS 2025 poster* [[paper](https://openreview.net/forum?id=dAwKePZvcN)] `#text-adventure` `#planning` `#training` `#self-improvement`
- [2025/05] **PoE-World: Compositional World Modeling with Products of Programmatic Experts** *NeurIPS 2025 spotlight* [[paper](https://openreview.net/forum?id=obwRcksFZw)] `#action` `#planning` `#world-model`
- [2025/05] **WALL-E: World Alignment by NeuroSymbolic Learning improves World Model-based LLM Agents** *NeurIPS 2025 poster* [[paper](https://openreview.net/forum?id=DorAT49sxj)] `#minecraft` `#planning` `#world-model` `#prompting`
- [2025/04] **WALL-E 2.0: World Alignment by NeuroSymbolic Learning Improves World Model-based LLM Agents** *arXiv* [[paper](https://arxiv.org/abs/2504.15785)][[code](https://github.com/elated-sawyer/WALL-E)] `#minecraft` `#planning` `#world-model` `#prompting`
- [2025/04] **Better Decisions through the Right Causal World Model** *arXiv* [[paper](https://arxiv.org/abs/2504.07257)] `#action` `#planning` `#world-model` `#training`
- [2025/04] **ZeroSumEval: Scaling LLM Evaluation with Inter-Model Competition** *arXiv* [[paper](https://arxiv.org/abs/2504.12562)][[code](https://github.com/facebookresearch/ZeroSumEval)] `#competition` `#planning`
- [2025/04] **SOTOPIA-S4: a user-friendly system for flexible, customizable, and large-scale social simulation** *NAACL 2025* [[paper](https://arxiv.org/abs/2504.16122)] `#sim-social` `#planning`
- [2025/04] **Monte Carlo Planning with Large Language Model for Text-Based Game Agents** *ICLR 2025 Poster* [[paper](https://arxiv.org/abs/2504.16855)] `#text-adventure` `#planning` `#training`
- [2025/04] **LLM-PySC2: Starcraft II learning environment for Large Language Models** *NeurIPS 2025 poster* [[paper](https://openreview.net/forum?id=Xr73jEYG29)] `#competition` `#planning` `#multi-agent` `#vlm`
- [2025/04] **MF-LLM: Simulating Population Decision Dynamics via a Mean-Field Large Language Model Framework** *NeurIPS 2025 poster* [[paper](https://openreview.net/forum?id=m0q8NfGWnv)] `#sim-social` `#planning` `#training`
- [2025/03] **Parallelized Planning-Acting for Efficient LLM-based Multi-Agent Systems** *arXiv* [[paper](https://arxiv.org/abs/2503.03505)] `#minecraft` `#planning` `#multi-agent` `#tool-use`
- [2025/03] **GFlowVLM: Enhancing Multi-step Reasoning in Vision-Language Models with Generative Flow Networks** *CVPR 2025* [[paper](https://arxiv.org/abs/2503.06514)] `#text-adventure` `#planning` `#training` `#vlm`
- [2025/03] **Plancraft: an evaluation dataset for planning with LLM agents** *COLM 2025* [[paper](https://openreview.net/forum?id=nSV8Depcpx)] `#minecraft` `#planning` `#memory` `#tool-use`
- [2025/02] **Optimus-2: Multimodal World Model for Open-World Minecraft Agents** *CVPR 2025* [[paper](https://arxiv.org/pdf/2502.19902)][[code](https://github.com/JiuTian-VL/Optimus-2)] `#minecraft` `#planning` `#world-model` `#vlm`
- [2025/02] **LLM-Powered Decentralized Generative Agents with Adaptive Hierarchical Knowledge Graph for Cooperative Planning** *arXiv* [[paper](https://arxiv.org/abs/2502.05453)] `#crafter` `#planning` `#memory` `#multi-agent`
- [2025/02] **Hybrid Voting-Based Task Assignment in Role-Playing Games** *arXiv* [[paper](https://arxiv.org/abs/2502.18690)] `#planning`
- [2025/02] **Implicit Search via Discrete Diffusion: A Study on Chess** *ICLR 2025 Poster* [[paper](https://arxiv.org/abs/2502.19805)][[code](https://github.com/HKUNLP/DiffuSearch}{https://github.com/HKUNLP/DiffuSearch})] `#competition` `#planning`
- [2025/01] **POKERBENCH: Training Large Language Models to become Professional Poker Players** *AAAI 2025* [[paper](https://arxiv.org/pdf/2501.08328)] `#competition` `#planning` `#training`
- [2025/01] **Mastering Board Games by External and Internal Planning with Language Models** *ICML 2025 spotlightposter* [[paper](https://openreview.net/forum?id=KKwBo3u3IW)] `#competition` `#planning`
- [2025/01] **LMAct: A Benchmark for In-Context Imitation Learning with Long Multimodal Demonstrations** *ICML 2025 poster* [[paper](https://openreview.net/forum?id=8aChcUzAhI)] `#action` `#planning` `#training`
- [2025/01] **Language Models as Implicit Tree Search** *ICML 2025 poster* [[paper](https://openreview.net/forum?id=bEqMmGu6qg)] `#competition` `#planning` `#training`
- [2024/10] **WALL-E: World Alignment by Rule Learning Improves World Model-based LLM Agents** *arXiv* [[paper](https://arxiv.org/abs/2410.07484)][[code](https://github.com/elated-sawyer/WALL-E)] `#minecraft` `#planning` `#world-model`
- [2024/10] **ADAM: An Embodied Causal Agent in Open-World Environments** *ICLR 2025* [[paper](https://arxiv.org/abs/2410.22194)][[code](https://github.com/OpenCausaLab/ADAM)] `#minecraft` `#planning`
- [2024/10] **PokéChamp: An Expert-level Minimax Language Agent** *ICML 2025* [[paper](https://arxiv.org/abs/2503.04094)][[code](https://github.com/sethkarten/PokeChamp)] `#competition` `#planning`
- [2024/09] **Can VLMs Play Action Role-Playing Games? Take Black Myth Wukong as a Study Case** *arXiv* [[paper](https://arxiv.org/abs/2409.12889)][[code](https://varp-agent.github.io/)] `#action` `#planning` `#training`
- [2024/09] **Strategist: Self-improvement of LLM Decision Making via Bi-Level Tree Search** *ICLR 2025 Poster* [[paper](https://openreview.net/forum?id=gfI9v7AbFg)] `#communication` `#planning` `#multi-agent` `#training`
- [2024/09] **Discriminator-Guided Embodied Planning for LLM Agent** *ICLR 2025 Poster* [[paper](https://openreview.net/forum?id=TjP1d8PP8l)] `#text-adventure` `#planning`
- [2024/09] **Better than Your Teacher: LLM Agents that learn from Privileged AI Feedback** *ICLR 2025 Poster* [[paper](https://openreview.net/forum?id=st7XqFgbAH)] `#text-adventure` `#planning` `#training` `#self-improvement`
- [2024/09] **BadRobot: Jailbreaking Embodied LLM Agents in the Physical World** *ICLR 2025 Poster* [[paper](https://openreview.net/forum?id=ei3qCntB66)] `#sim-embodied` `#planning` `#vlm`
- [2024/09] **BALROG: Benchmarking Agentic LLM and VLM Reasoning On Games** *ICLR 2025 Poster* [[paper](https://openreview.net/forum?id=fp6t3F669F)] `#action` `#planning` `#training` `#vlm`
- [2024/08] **Optimus-1: Hybrid Multimodal Memory Empowered Agents Excel in Long-horizon Tasks** *NeurIPS 2024* [[paper](https://arxiv.org/abs/2408.03615)][[code](https://github.com/JiuTian-VL/Optimus-1)] `#minecraft` `#planning` `#memory` `#prompting`
- [2024/08] **Evaluating and Enhancing LLMs Agent based on Theory of Mind in Guandan: A Multi-Player Cooperative Game under Imperfect Information** *2024 IEEE/WIC International Conference on Web Intelligence and Intelligent Agent Technology (WI-IAT) 2024* [[paper](https://arxiv.org/pdf/2408.02559)] `#competition` `#planning` `#multi-agent` `#training`
- [2024/08] **Atari-GPT: Investigating the Capabilities of Multimodal Large Language Models as Low-Level Policies for Atari Games** *arXiv* [[paper](https://arxiv.org/pdf/2408.15950)] `#action` `#planning` `#training`
- [2024/07] **Arigraph: Learning knowledge graph world models with episodic memory for llm agents** *IJCAI 2024* [[paper](https://arxiv.org/abs/2407.04363)] `#text-adventure` `#planning` `#memory`
- [2024/07] **Odyssey: Empowering Agents with Open-World Skills.** *IJCAI 2024* [[paper](https://arxiv.org/abs/2407.15325)][[code](https://github.com/zju-vipa/Odyssey)] `#minecraft` `#planning` `#tool-use`
- [2024/06] **VillagerAgent: A Graph-Based Multi-Agent Framework for Coordinating Complex Task Dependencies in Minecraft** *Findings of ACL 2024* [[paper](https://arxiv.org/abs/2406.05720)][[code](https://github.com/cnsdqd-dyb/VillagerAgent)] `#minecraft` `#planning` `#multi-agent`
- [2024/05] **Agent Planning with World Knowledge Model** *NeurIPS 2024* [[paper](https://arxiv.org/pdf/2405.14205)][[code](https://github.com/zjunlp/WKM)] `#text-adventure` `#planning` `#memory` `#world-model`
- [2024/05] **Agent hospital: A simulacrum of hospital with evolvable medical agents** *arXiv* [[paper](https://arxiv.org/abs/2405.02957)] `#sim-social` `#planning`
- [2024/05] **Towards Efficient LLM Grounding for Embodied Multi-Agent Collaboration** *ACL 2024* [[paper](https://arxiv.org/pdf/2405.14314)][[code](https://arxiv.org/pdf/2405.14314)] `#cooperation` `#planning` `#multi-agent` `#training`
- [2024/05] **Reflective Multi-Agent Collaboration based on Large Language Models** *NeurIPS 2024 poster* [[paper](https://openreview.net/forum?id=wWiAR5mqXq)] `#competition` `#planning` `#multi-agent` `#training`
- [2024/05] **AutoManual: Constructing Instruction Manuals by LLM Agents via Interactive Environmental Learning** *NeurIPS 2024 poster* [[paper](https://openreview.net/forum?id=Pwl9n4zlf5)][[code](https://github.com/minghchen/automanual)] `#text-adventure` `#planning`
- [2024/05] **Richelieu: Self-Evolving LLM-Based Agents for AI Diplomacy** *NeurIPS 2024 poster* [[paper](https://openreview.net/forum?id=7Jb4NJS8Yk)] `#communication` `#planning` `#multi-agent` `#self-improvement`
- [2024/04] **ReAct Meets ActRe: When Language Agents Enjoy Training Data Autonomy** *arXiv* [[paper](https://arxiv.org/pdf/2403.14589)] `#text-adventure` `#planning` `#training` `#self-improvement`
- [2024/04] **AgentKit: Flow Engineering with Graphs, not Coding** *arXiv* [[paper](https://arxiv.org/pdf/2404.11483)][[code](https://github.com/holmeswww/AgentKit)] `#crafter` `#planning`
- [2024/03] **KnowAgent: Knowledge-Augmented Planning for LLM-Based Agents** *NAACL 2024* [[paper](https://arxiv.org/abs/2403.03101.pdf)][[code](https://github.com/zjunlp/KnowAgent)] `#text-adventure` `#planning`
- [2024/03] **Cradle: Empowering Foundation Agents Towards General Computer Control** *ICML 2024* [[paper](https://arxiv.org/abs/2403.03186.pdf)][[code](https://github.com/BAAI-Agents/Cradle)] `#video-adventure` `#planning`
- [2024/03] **Playing NetHack with LLMs: Potential & Limitations as Zero-Shot Agents** *2024 IEEE Conference on Games (CoG) 2024* [[paper](https://arxiv.org/pdf/2403.00690.pdf)][[code](https://github.com/CommanderCero/NetPlay)] `#video-adventure` `#planning` `#prompting`
- [2024/03] **Hierarchical Auto-Organizing System for Open-Ended Multi-Agent Navigation (HAS)** *ICLR 2024 Workshop* [[paper](https://arxiv.org/abs/2403.08282)] `#minecraft` `#planning` `#multi-agent` `#vlm`
- [2024/03] **Embodied LLM Agents Learn to Cooperate in Organized Teams** *IEEE Transactions on Computational Social Systems 2024* [[paper](https://arxiv.org/pdf/2403.12482)] `#competition` `#planning` `#multi-agent`
- [2024/03] **Will GPT-4 Run DOOM?** *IEEE Transactions on Games 2024* [[paper](https://arxiv.org/abs/2403.05468.pdf)][[code](https://github.com/adewynter/Doom)] `#action` `#planning` `#training`
- [2024/03] **ReAct Meets ActRe: Autonomous Annotation of Agent Trajectories for Contrastive Self-Training** *COLM* [[paper](https://openreview.net/forum?id=0VLBwQGWpA)] `#text-adventure` `#planning` `#training` `#self-improvement`
- [2024/03] **StateFlow: Enhancing LLM Task-Solving through State-Driven Workflows** *COLM* [[paper](https://openreview.net/forum?id=3nTbuygoop)] `#text-adventure` `#planning` `#self-improvement`
- [2024/03] **AgentKit: Structured LLM Reasoning with Dynamic Graphs** *COLM* [[paper](https://openreview.net/forum?id=PKfAq8N4fK)] `#crafter` `#planning`
- [2024/02] **Empowering Large Language Model Agents through Action Learning** *COLM* [[paper](https://arxiv.org/abs/2402.15809)][[code](https://github.com/zhao-ht/LearnAct)] `#text-adventure` `#planning` `#self-improvement`
- [2024/02] **RL-GPT: Integrating Reinforcement Learning and Code-as-policy** *NeurIPS 2024 oral* [[paper](https://arxiv.org/abs/2402.19299.pdf)] `#minecraft` `#planning` `#tool-use` `#training`
- [2023/12] **MP5: A Multi-modal Open-ended Embodied System in Minecraft via Active Perception** *CVPR 2024* [[paper](https://arxiv.org/pdf/2312.07472.pdf)][[code](https://github.com/IranQin/MP5)] `#minecraft` `#planning` `#vlm`
- [2023/12] **Creative Agents: Empowering Agents with Imagination for Creative Tasks** *UAI 2023* [[paper](https://arxiv.org/abs/2312.02519.pdf)][[code](https://github.com/PKU-RL/Creative-Agents)] `#minecraft` `#planning`
- [2023/12] **Large Language Models Play StarCraft II: Benchmarks and A Chain of Summarization Approach** *NeurIPS 2024 poster* [[paper](https://arxiv.org/abs/2312.11865.pdf)][[code](https://github.com/histmeisah/Large-Language-Models-play-StarCraftII/tree/main)] `#competition` `#planning`
- [2023/11] **ADaPT: As-Needed Decomposition and Planning with Language Models** *NAACL 2023* [[paper](https://arxiv.org/abs/2311.05772)][[code](https://github.com/archiki/ADaPT)] `#text-adventure` `#planning`
- [2023/11] **JARVIS-1: Open-world Multi-task Agents with Memory-Augmented Multimodal Language Models** *TPAMI 2023* [[paper](https://arxiv.org/abs/2311.05997.pdf)][[code](https://github.com/CraftJarvis/JARVIS-1)] `#minecraft` `#planning` `#memory`
- [2023/10] **Language Agent Tree Search Unifies Reasoning Acting and Planning in Language Models** *ICML 2024* [[paper](https://arxiv.org/pdf/2310.04406)][[code](https://github.com/lapisrocks/LanguageAgentTreeSearch)] `#text-adventure` `#planning` `#training`
- [2023/10] **LLaMA Rider: Spurring Large Language Models to Explore the Open World** *NAACL 2023* [[paper](https://arxiv.org/abs/2310.08922.pdf)][[code](https://github.com/PKU-RL/LLaMA-Rider)] `#minecraft` `#planning` `#training`
- [2023/10] **Octopus: Embodied Vision-Language Programmer from Environmental Feedback** *ECCV 2023* [[paper](https://arxiv.org/abs/2310.08588.pdf)][[code](https://github.com/dongyh20/Octopus)] `#sim-embodied` `#planning` `#training` `#vlm`
- [2023/10] **Evaluating Multi-agent Coordination Abilities in Large Language Models** *NAACL 2023* [[paper](https://arxiv.org/abs/2310.03903.pdf)] `#cooperation` `#planning` `#multi-agent` `#prompting`
- [2023/10] **Theory of Mind for Multi-Agent Collaboration via Large Language Models** *EMNLP 2023* [[paper](https://arxiv.org/pdf/2310.10701)][[code](https://github.com/romanlee6/multi_LLM_comm)] `#cooperation` `#planning` `#multi-agent` `#training`
- [2023/09] **Suspicion-Agent: Playing Imperfect Information Games with Theory of Mind Aware GPT-4** *COLM 2024* [[paper](https://arxiv.org/abs/2309.17277.pdf)] `#competition` `#planning` `#memory` `#prompting`
- [2023/09] **MindAgent: Emergent Gaming Interaction** *NAACL 2023* [[paper](http://https://arxiv.org/abs/2309.09971)] `#cooperation` `#planning` `#multi-agent` `#prompting`
- [2023/08] **AgentSims: An Open-Source Sandbox for Large Language Model Evaluation** *arXiv* [[paper](https://arxiv.org/abs/2308.04026.pdf)][[code](https://github.com/py499372727/AgentSims)] `#sim-social` `#planning` `#tool-use`
- [2023/07] **Building Cooperative Embodied Agents Modularly with Large Language Models** *ICLR 2024* [[paper](https://arxiv.org/abs/2307.02485.pdf)][[code](https://github.com/UMass-Foundation-Model/Co-LLM-Agents/)] `#cooperation` `#planning` `#multi-agent` `#training`
- [2023/05] **Language Models Meet World Models: Embodied Experiences Enhance Language Models** *NeurIPS 2023* [[paper](https://arxiv.org/abs/2305.10626.pdf)][[code](https://github.com/szxiangjn/world-model-for-language-model)] `#sim-embodied` `#planning` `#world-model`
- [2023/05] **SwiftSage: A Generative Agent with Fast and Slow Thinking for Complex Interactive Tasks** *NeurIPS 2023* [[paper](https://proceedings.neurips.cc/paper_files/paper/2023/hash/4b0eea69deea512c9e2c469187643dc2-Abstract-Conference.html)][[code](https://github.com/yuchenlin/SwiftSage)] `#text-adventure` `#planning`
- [2023/03] **Plan4MC: Skill Reinforcement Learning and Planning for Open-World Minecraft Tasks** *FMDM@NeurIPS2023* [[paper](https://arxiv.org/abs/2303.16563.pdf)][[code](https://github.com/PKU-RL/Plan4MC)] `#minecraft` `#planning` `#training`
- [2023/02] **Describe, Explain, Plan and Select: Interactive Planning with Large Language Models Enables Open-World Multi-Task Agents** *NeurIPS 2023* [[paper](https://arxiv.org/abs/2302.01560.pdf)][[code](https://github.com/CraftJarvis/MC-Planner)] `#minecraft` `#planning` `#prompting`
- [2022/12] **LLM-Planner: Few-Shot Grounded Planning for Embodied Agents with Large Language Models** *ICCV 2023* [[paper](https://openaccess.thecvf.com/content/ICCV2023/html/Song_LLM-Planner_Few-Shot_Grounded_Planning_for_Embodied_Agents_with_Large_Language_ICCV_2023_paper.html)] `#sim-embodied` `#planning` `#prompting`
- [2022/10] **ReAct: Synergizing Reasoning and Acting in Language Models** *ICLR 2023* [[paper](https://arxiv.org/abs/2210.03629)][[code](https://github.com/ysymyth/ReAct)] `#text-adventure` `#planning` `#training`
- [2020/10] **ALFWorld: Aligning Text and Embodied Environments for Interactive Learning** *ICLR 2021* [[paper](https://arxiv.org/pdf/2010.03768.pdf)][[code](https://github.com/alfworld/alfworld)] `#text-adventure` `#planning`

## memory

- [2026/05] **Belief Memory: Agent Memory Under Partial Observability** *arXiv* [[paper](https://arxiv.org/abs/2605.05583)] `#text-adventure` `#memory`
- [2026/05] **GASim: A Graph-Accelerated Hybrid Framework for Social Simulation** *arXiv* [[paper](https://arxiv.org/abs/2605.07692)][[code](https://github.com/Jasmine0201/GASim)] `#sim-social` `#memory` `#multi-agent`
- [2026/05] **ScioMind: Cognitively Grounded Multi-Agent Social Simulation with Anchoring-Based Belief Dynamics and Dynamic Profiles** *arXiv* [[paper](https://arxiv.org/abs/2605.13725)] `#sim-social` `#memory` `#multi-agent`
- [2026/05] **Skills on the Fly: Test-Time Adaptive Skill Synthesis for LLM Agents** *arXiv* [[paper](https://arxiv.org/abs/2605.16986)] `#text-adventure` `#memory` `#tool-use`
- [2026/05] **SkillGraph: Skill-Augmented Reinforcement Learning for Agents via Evolving Skill Graphs** *arXiv* [[paper](https://arxiv.org/abs/2605.12039)] `#text-adventure` `#memory` `#tool-use` `#training`
- [2026/05] **SkillOps: Managing LLM Agent Skill Libraries as Self-Maintaining Software Ecosystems** *arXiv* [[paper](https://arxiv.org/abs/2605.13716)] `#text-adventure` `#planning` `#memory` `#tool-use`
- [2026/04] **Aligning Progress and Feasibility: A Neuro-Symbolic Dual Memory Framework for Long-Horizon LLM Agents** *arXiv* [[paper](https://arxiv.org/abs/2604.02734)] `#text-adventure` `#planning` `#memory`
- [2026/04] **LLM-Agent-based Social Simulation for Attitude Diffusion** *arXiv* [[paper](https://arxiv.org/abs/2604.03898)] `#sim-social` `#memory`
- [2026/04] **Complete Cyclic Subtask Graphs for Tool-Using LLM Agents: Flexibility, Cost, and Bottlenecks in Multi-Agent Workflows** *arXiv* [[paper](https://arxiv.org/abs/2604.22820)] `#text-adventure` `#planning` `#memory` `#multi-agent`
- [2026/04] **GraSP: Graph-Structured Skill Compositions for LLM Agents** *arXiv* [[paper](https://arxiv.org/abs/2604.17870)] `#text-adventure` `#planning` `#memory` `#self-improvement`
- [2026/04] **Gated Coordination for Efficient Multi-Agent Collaboration in Minecraft Game** *arXiv* [[paper](https://arxiv.org/abs/2604.18975)] `#minecraft` `#memory` `#multi-agent` `#vlm`
- [2026/03] **RPMS: Enhancing LLM-Based Embodied Planning through Rule-Augmented Memory Synergy** *arXiv* [[paper](https://arxiv.org/abs/2603.17831)] `#text-adventure` `#planning` `#memory`
- [2026/03] **RetroAgent: From Solving to Evolving via Retrospective Dual Intrinsic Feedback** *arXiv* [[paper](https://arxiv.org/abs/2603.08561)] `#text-adventure` `#memory` `#training` `#self-improvement`
- [2026/03] **Self-Evolving Multi-Agent Framework for Efficient Decision Making in Real-Time Strategy Scenarios** *arXiv* [[paper](https://arxiv.org/abs/2603.23875)] `#competition` `#planning` `#memory` `#multi-agent`
- [2026/02] **SkillRL: Evolving Agents via Recursive Skill-Augmented Reinforcement Learning** *arXiv* [[paper](https://arxiv.org/abs/2602.08234)][[code](https://github.com/aiming-lab/SkillRL)] `#text-adventure` `#memory` `#tool-use` `#training`
- [2025/12] **EZYer: A simulacrum of high school with generative agent** *arXiv* [[paper](https://arxiv.org/abs/2512.02561)] `#sim-social` `#memory`
- [2025/12] **ESearch-R1: Learning Cost-Aware MLLM Agents for Interactive Embodied Search via Reinforcement Learning** *arXiv* [[paper](https://arxiv.org/abs/2512.18571)] `#sim-embodied` `#planning` `#memory` `#training`
- [2025/12] **Learning Hierarchical Procedural Memory for LLM Agents through Bayesian Selection and Contrastive Refinement** *Proceedings of the 25th International Conference on Autonomous Agents and Multiagent Systems 2025* [[paper](https://arxiv.org/abs/2512.18950)] `#text-adventure` `#memory`
- [2025/12] **ReCollab: Retrieval-Augmented LLMs for Cooperative Ad-hoc Teammate Modeling** *arXiv* [[paper](https://arxiv.org/abs/2512.22129)] `#cooperation` `#memory`
- [2025/11] **Knowledge Graph-enhanced Large Language Model for Incremental Game PlayTesting** *IEICE Transactions on Information and Systems 2025* [[paper](https://arxiv.org/abs/2511.02534)] `#minecraft` `#memory`
- [2025/10] **Fine-tuning with RAG for Improving LLM Learning of New Skills** *arXiv* [[paper](https://arxiv.org/abs/2510.01375)] `#text-adventure` `#planning` `#memory` `#training`
- [2025/10] **Memory-Augmented State Machine Prompting: A Novel LLM Agent Framework for Real-Time Strategy Games** *arXiv* [[paper](https://arxiv.org/abs/2510.18395)] `#competition` `#memory`
- [2025/10] **Alita-G: Self-Evolving Generative Agent for Agent Generation** *arXiv* [[paper](https://arxiv.org/abs/2510.23601)] `#sim-social` `#memory` `#self-improvement`
- [2025/09] **World Model Implanting for Test-time Adaptation of Embodied Agents** *ICML 2025 poster* [[paper](https://arxiv.org/abs/2509.03956)] `#text-adventure` `#memory` `#world-model` `#prompting`
- [2025/09] **Exploratory Memory-Augmented LLM Agent via Hybrid On- and Off-Policy Optimization** *ICLR 2026 Poster* [[paper](https://openreview.net/forum?id=UOzxviKVFO)] `#text-adventure` `#memory` `#training`
- [2025/08] **Vistawise: Building Cost-effective Agent with Cross-modal Knowledge Graph for Minecraft** *EMNLP 2025* [[paper](https://arxiv.org/abs/2508.18722)] `#minecraft` `#memory` `#tool-use`
- [2025/08] **CHBench: A Cognitive Hierarchy Benchmark for Evaluating Strategic Reasoning Capability of LLMs** *arXiv* [[paper](https://arxiv.org/abs/2508.11944)] `#memory`
- [2025/06] **StoryBench: A Dynamic Benchmark for Evaluating Long-Term Memory with Multi Turns** *arXiv* [[paper](https://arxiv.org/abs/2506.13356)] `#text-adventure` `#memory`
- [2025/05] **Knowledge Retrieval in LLM Gaming: A Shift from Entity-Centric to Goal-Oriented Graphs** *Knowledge-Based Systems 2025* [[paper](https://arxiv.org/abs/2505.18607)] `#minecraft` `#planning` `#memory`
- [2025/03] **Plancraft: an evaluation dataset for planning with LLM agents** *COLM 2025* [[paper](https://openreview.net/forum?id=nSV8Depcpx)] `#minecraft` `#planning` `#memory` `#tool-use`
- [2025/02] **LLM-Powered Decentralized Generative Agents with Adaptive Hierarchical Knowledge Graph for Cooperative Planning** *arXiv* [[paper](https://arxiv.org/abs/2502.05453)] `#crafter` `#planning` `#memory` `#multi-agent`
- [2024/11] **MrSteve: Instruction-Following Agents with What-Where-When Memory** *ICLR 2025* [[paper](https://arxiv.org/abs/2411.06736)][[code](https://github.com/frechele/MrSteve)] `#minecraft` `#memory`
- [2024/09] **MrSteve: Instruction-Following Agents in Minecraft with What-Where-When Memory** *ICLR 2025 Poster* [[paper](https://openreview.net/forum?id=CjXaMI2kUH)] `#minecraft` `#memory`
- [2024/08] **Optimus-1: Hybrid Multimodal Memory Empowered Agents Excel in Long-horizon Tasks** *NeurIPS 2024* [[paper](https://arxiv.org/abs/2408.03615)][[code](https://github.com/JiuTian-VL/Optimus-1)] `#minecraft` `#planning` `#memory` `#prompting`
- [2024/07] **Arigraph: Learning knowledge graph world models with episodic memory for llm agents** *IJCAI 2024* [[paper](https://arxiv.org/abs/2407.04363)] `#text-adventure` `#planning` `#memory`
- [2024/05] **Agent Planning with World Knowledge Model** *NeurIPS 2024* [[paper](https://arxiv.org/pdf/2405.14205)][[code](https://github.com/zjunlp/WKM)] `#text-adventure` `#planning` `#memory` `#world-model`
- [2023/11] **JARVIS-1: Open-world Multi-task Agents with Memory-Augmented Multimodal Language Models** *TPAMI 2023* [[paper](https://arxiv.org/abs/2311.05997.pdf)][[code](https://github.com/CraftJarvis/JARVIS-1)] `#minecraft` `#planning` `#memory`
- [2023/11] **See and Think: Embodied Agent in Virtual Environment** *ECCV 2023* [[paper](https://arxiv.org/abs/2311.15209.pdf)][[code](https://github.com/rese1f/STEVE)] `#minecraft` `#memory`
- [2023/10] **Lyfe Agents: Generative agents for low-cost real-time social interactions** *arXiv* [[paper](https://arxiv.org/abs/2310.02172.pdf)] `#sim-social` `#memory` `#multi-agent` `#self-improvement`
- [2023/09] **Suspicion-Agent: Playing Imperfect Information Games with Theory of Mind Aware GPT-4** *COLM 2024* [[paper](https://arxiv.org/abs/2309.17277.pdf)] `#competition` `#planning` `#memory` `#prompting`
- [2023/09] **Exploring Large Language Models for Communication Games: An Empirical Study on Werewolf** *arXiv* [[paper](https://arxiv.org/abs/2309.04658.pdf)] `#communication` `#memory`

## multi-agent

- [2026/05] **GASim: A Graph-Accelerated Hybrid Framework for Social Simulation** *arXiv* [[paper](https://arxiv.org/abs/2605.07692)][[code](https://github.com/Jasmine0201/GASim)] `#sim-social` `#memory` `#multi-agent`
- [2026/05] **ScioMind: Cognitively Grounded Multi-Agent Social Simulation with Anchoring-Based Belief Dynamics and Dynamic Profiles** *arXiv* [[paper](https://arxiv.org/abs/2605.13725)] `#sim-social` `#memory` `#multi-agent`
- [2026/05] **GAMBIT: A Three-Mode Benchmark for Adversarial Robustness in Multi-Agent LLM Collectives** *arXiv* [[paper](https://arxiv.org/abs/2605.09027)] `#competition` `#multi-agent` `#prompting`
- [2026/05] **ALSO: Adversarial Online Strategy Optimization for Social Agents** *arXiv* [[paper](https://arxiv.org/abs/2605.15768)] `#sim-social` `#multi-agent` `#training`
- [2026/04] **MARL-GPT: Foundation Model for Multi-Agent Reinforcement Learning** *Proceedings of the 25th International Conference on Autonomous Agents and Multiagent Systems 2026* [[paper](https://arxiv.org/abs/2604.05943)] `#competition` `#multi-agent` `#training`
- [2026/04] **Complete Cyclic Subtask Graphs for Tool-Using LLM Agents: Flexibility, Cost, and Bottlenecks in Multi-Agent Workflows** *arXiv* [[paper](https://arxiv.org/abs/2604.22820)] `#text-adventure` `#planning` `#memory` `#multi-agent`
- [2026/04] **Don't Make the LLM Read the Graph: Make the Graph Think** *arXiv* [[paper](https://arxiv.org/abs/2604.23057)] `#cooperation` `#multi-agent`
- [2026/04] **Gated Coordination for Efficient Multi-Agent Collaboration in Minecraft Game** *arXiv* [[paper](https://arxiv.org/abs/2604.18975)] `#minecraft` `#memory` `#multi-agent` `#vlm`
- [2026/03] **How Clued up are LLMs? Evaluating Multi-Step Deductive Reasoning in a Text-Based Game Environment** *arXiv* [[paper](https://arxiv.org/abs/2603.17169)] `#text-adventure` `#multi-agent` `#training`
- [2026/03] **GTO Wizard Benchmark** *arXiv* [[paper](https://arxiv.org/abs/2603.23660)] `#competition` `#planning` `#multi-agent` `#prompting`
- [2026/03] **Self-Evolving Multi-Agent Framework for Efficient Decision Making in Real-Time Strategy Scenarios** *arXiv* [[paper](https://arxiv.org/abs/2603.23875)] `#competition` `#planning` `#memory` `#multi-agent`
- [2026/03] **Belief-Driven Multi-Agent Collaboration via Approximate Perfect Bayesian Equilibrium for Social Simulation** *WWW 2026* [[paper](https://arxiv.org/abs/2603.24973)][[code](https://github.com/WUT-IDEA/BEACOF)] `#sim-social` `#multi-agent`
- [2026/03] **Deception and Communication in Autonomous Multi-Agent Systems: An Experimental Study with Among Us** *Proceedings of the 25th International Conference on Autonomous Agents and Multiagent Systems 2026* [[paper](https://arxiv.org/abs/2603.26635)] `#communication` `#multi-agent`
- [2026/02] **The Devil Behind Moltbook: Anthropic Safety is Always Vanishing in Self-Evolving AI Societies** *arXiv* [[paper](https://arxiv.org/abs/2602.09877)] `#sim-social` `#multi-agent` `#self-improvement`
- [2026/01] **When Agents See Humans as the Outgroup: Belief-Dependent Bias in LLM-Powered Agents** *arXiv* [[paper](https://arxiv.org/abs/2601.00240)] `#sim-social` `#multi-agent`
- [2026/01] **Hidden in Plain Text: Measuring LLM Deception Quality Against Human Baselines Using Social Deduction Games** *International Conference on Agents 2027* [[paper](https://arxiv.org/abs/2601.13709)] `#communication` `#multi-agent`
- [2026/01] **MARO: Learning Stronger Reasoning from Social Interaction** *arXiv* [[paper](https://arxiv.org/abs/2601.12323)] `#sim-social` `#multi-agent`
- [2025/12] **WOLF: Werewolf-based Observations for LLM Deception and Falsehoods** *arXiv* [[paper](https://arxiv.org/abs/2512.09187)] `#communication` `#multi-agent`
- [2025/12] **Robust Agents in Open-Ended Worlds** *arXiv* [[paper](https://arxiv.org/abs/2512.08139)] `#action` `#multi-agent` `#training` `#generation`
- [2025/12] **Agent-Kernel: A MicroKernel Multi-Agent System Framework for Adaptive Social Simulation Powered by LLMs** *arXiv* [[paper](https://arxiv.org/abs/2512.01610)] `#sim-social` `#multi-agent`
- [2025/11] **DR. WELL: Dynamic Reasoning and Learning with Symbolic World Model for Embodied LLM-Based Multi-Agent Collaboration** *arXiv* [[paper](https://arxiv.org/abs/2511.04646)] `#sim-embodied` `#planning` `#multi-agent` `#world-model`
- [2025/11] **Multi-agent Undercover Gaming: Hallucination Removal via Counterfactual Test for Multimodal Reasoning** *arXiv* [[paper](https://arxiv.org/abs/2511.11182)][[code](https://github.com/YongLD/MUG.git)] `#communication` `#multi-agent`
- [2025/11] **MADRA: Multi-Agent Debate for Risk-Aware Embodied Planning** *arXiv* [[paper](https://arxiv.org/abs/2511.21460)] `#sim-embodied` `#planning` `#multi-agent` `#prompting`
- [2025/10] **LLM-Hanabi: Evaluating Multi-Agent Gameplays with Theory-of-Mind and Rationale Inference in Imperfect Information Collaboration Game** *arXiv* [[paper](https://arxiv.org/abs/2510.04980)] `#cooperation` `#multi-agent`
- [2025/10] **Beyond Survival: Evaluating LLMs in Social Deduction Games with Human-Aligned Strategies** *arXiv* [[paper](https://arxiv.org/abs/2510.11389)] `#communication` `#multi-agent` `#self-improvement`
- [2025/10] **Social Simulations with Large Language Model Risk Utopian Illusion** *arXiv* [[paper](https://arxiv.org/abs/2510.21180)] `#sim-social` `#multi-agent`
- [2025/09] **Meta-Policy Reflexion: Reusable Reflective Memory and Rule Admissibility for Resource-Efficient LLM Agent** *arXiv* [[paper](https://arxiv.org/abs/2509.03990)] `#text-adventure` `#planning` `#multi-agent` `#self-improvement`
- [2025/09] **PillagerBench: Benchmarking LLM-Based Agents in Competitive Minecraft Team Environments** *2025 IEEE Conference on Games (CoG) 2025* [[paper](https://arxiv.org/abs/2509.06235)] `#minecraft` `#multi-agent` `#self-improvement`
- [2025/09] **HLSMAC: A New StarCraft Multi-Agent Challenge for High-Level Strategic Decision-Making** *arXiv* [[paper](https://arxiv.org/abs/2509.12927)] `#competition` `#multi-agent` `#training`
- [2025/09] **SPIRAL: Self-Play on Zero-Sum Games Incentivizes Reasoning via Multi-Agent Multi-Turn Reinforcement Learning** *ICLR 2026 Poster* [[paper](https://openreview.net/forum?id=7Yayy5fNLg)] `#competition` `#planning` `#multi-agent` `#training`
- [2025/08] **CausalMACE: Causality Empowered Multi-Agents in Minecraft Cooperative Tasks** *Findings of EMNLP 2025* [[paper](https://arxiv.org/abs/2508.18797)] `#minecraft` `#planning` `#multi-agent`
- [2025/08] **A Multi-Agent Pokemon Tournament for Evaluating Strategic Reasoning of Large Language Models** *arXiv* [[paper](https://arxiv.org/abs/2508.01623)] `#action` `#multi-agent`
- [2025/08] **CausalPlan: Empowering Efficient LLM Multi-Agent Collaboration Through Causality-Driven Planning** *arXiv* [[paper](https://arxiv.org/abs/2508.13721)] `#cooperation` `#planning` `#multi-agent` `#training`
- [2025/07] **LLM Economist: Large Population Models and Mechanism Design in Multi-Agent Generative Simulacra** *arXiv* [[paper](https://arxiv.org/abs/2507.15815)][[code](https://github.com/sethkarten/LLM-Economist)] `#sim-social` `#multi-agent` `#training` `#role-play`
- [2025/07] **CoMet: Metaphor-Driven Covert Communication for Multi-Agent Language Games** *ACL 2025* [[paper](https://www.arxiv.org/abs/2505.18218)][[code](https://github.com/Yeswolo/CoMet)] `#communication` `#multi-agent`
- [2025/06] **UnrealZoo: Enriching Photo-realistic Virtual Worlds for Embodied AI** *ICCV 2025* [[paper](https://arxiv.org/abs/2412.20977)][[code](https://github.com/UnrealZoo/unrealzoo-gym)] `#benchmark` `#multi-agent` `#training`
- [2025/06] **IndoorWorld: Integrating Physical Task Solving and Social Simulation in A Heterogeneous Multi-Agent Environment** *EMNLP 2025* [[paper](https://arxiv.org/abs/2506.12331)] `#sim-social` `#multi-agent`
- [2025/06] **WereWolf-Plus: An Update of Werewolf Game setting Based on DSGBench** *arXiv* [[paper](https://arxiv.org/abs/2506.12841)][[code](https://github.com/MinstrelsyXia/WereWolfPlus)] `#communication` `#multi-agent`
- [2025/06] **The Decrypto Benchmark for Multi-Agent Reasoning and Theory of Mind** *arXiv* [[paper](https://arxiv.org/abs/2506.20664)] `#multi-agent` `#training`
- [2025/06] **AgentGroupChat-V2: Divide-and-Conquer Is What LLM-Based Multi-Agent System Need** *arXiv* [[paper](https://arxiv.org/abs/2506.15451)][[code](https://github.com/MikeGu721/AgentGroupChat-V2)] `#sim-social` `#planning` `#multi-agent`
- [2025/06] **PSALM-V: Automating Symbolic Planning in Interactive Visual Environments with Large Language Models** *arXiv* [[paper](https://arxiv.org/abs/2506.20097)] `#cooperation` `#planning` `#multi-agent`
- [2025/05] **Is Your LLM Really Mastering the Concept? A Multi-Agent Benchmark** *arXiv* [[paper](https://arxiv.org/pdf/2505.17512)][[code](https://ck-arena.site/)] `#benchmark` `#multi-agent`
- [2025/04] **Collaborating Action by Action: A Multi-agent LLM Framework for Embodied Reasoning** *arXiv* [[paper](https://arxiv.org/abs/2504.17950)][[code](https://github.com/mindcraft-bots/mindcraft)] `#minecraft` `#multi-agent` `#training`
- [2025/04] **BookWorld: From Novels to Interactive Agent Societies for Creative Story Generation** *arXiv* [[paper](https://arxiv.org/abs/2504.14538)] `#sim-social` `#multi-agent` `#generation`
- [2025/04] **LLM-PySC2: Starcraft II learning environment for Large Language Models** *NeurIPS 2025 poster* [[paper](https://openreview.net/forum?id=Xr73jEYG29)] `#competition` `#planning` `#multi-agent` `#vlm`
- [2025/03] **Parallelized Planning-Acting for Efficient LLM-based Multi-Agent Systems** *arXiv* [[paper](https://arxiv.org/abs/2503.03505)] `#minecraft` `#planning` `#multi-agent` `#tool-use`
- [2025/03] **Playing games with Large language models: Randomness and strategy** *arXiv* [[paper](https://arxiv.org/abs/2503.02582)] `#multi-agent`
- [2025/03] **Society of Mind Meets Real-Time Strategy: A Hierarchical Multi-Agent Framework for Strategic Reasoning** *COLM 2025* [[paper](https://arxiv.org/abs/2508.06042)] `#competition` `#multi-agent` `#training`
- [2025/02] **LLM-Powered Decentralized Generative Agents with Adaptive Hierarchical Knowledge Graph for Cooperative Planning** *arXiv* [[paper](https://arxiv.org/abs/2502.05453)] `#crafter` `#planning` `#memory` `#multi-agent`
- [2024/12] **TeamCraft: A Benchmark for Multi-Modal Multi-Agent Systems in Minecraft** *arXiv* [[paper](https://arxiv.org/abs/2412.05255)][[code](https://github.com/teamcraft-bench/teamcraft)] `#minecraft` `#multi-agent` `#training` `#vlm`
- [2024/09] **Strategist: Self-improvement of LLM Decision Making via Bi-Level Tree Search** *ICLR 2025 Poster* [[paper](https://openreview.net/forum?id=gfI9v7AbFg)] `#communication` `#planning` `#multi-agent` `#training`
- [2024/08] **Evaluating and Enhancing LLMs Agent based on Theory of Mind in Guandan: A Multi-Player Cooperative Game under Imperfect Information** *2024 IEEE/WIC International Conference on Web Intelligence and Intelligent Agent Technology (WI-IAT) 2024* [[paper](https://arxiv.org/pdf/2408.02559)] `#competition` `#planning` `#multi-agent` `#training`
- [2024/06] **VillagerAgent: A Graph-Based Multi-Agent Framework for Coordinating Complex Task Dependencies in Minecraft** *Findings of ACL 2024* [[paper](https://arxiv.org/abs/2406.05720)][[code](https://github.com/cnsdqd-dyb/VillagerAgent)] `#minecraft` `#planning` `#multi-agent`
- [2024/06] **Artificial Leviathan: Exploring Social Evolution of LLM Agents Through the Lens of Hobbesian Social Contract Theory** *arXiv* [[paper](https://arxiv.org/abs/2406.14373)] `#sim-social` `#multi-agent`
- [2024/06] **PLAYER: Enhancing LLM-based Multi-Agent Communication and Interaction in Murder Mystery Games** *arXiv* [[paper](https://arxiv.org/pdf/2404.17662)] `#communication` `#multi-agent`
- [2024/05] **Towards Efficient LLM Grounding for Embodied Multi-Agent Collaboration** *ACL 2024* [[paper](https://arxiv.org/pdf/2405.14314)][[code](https://arxiv.org/pdf/2405.14314)] `#cooperation` `#planning` `#multi-agent` `#training`
- [2024/05] **Reflective Multi-Agent Collaboration based on Large Language Models** *NeurIPS 2024 poster* [[paper](https://openreview.net/forum?id=wWiAR5mqXq)] `#competition` `#planning` `#multi-agent` `#training`
- [2024/05] **Richelieu: Self-Evolving LLM-Based Agents for AI Diplomacy** *NeurIPS 2024 poster* [[paper](https://openreview.net/forum?id=7Jb4NJS8Yk)] `#communication` `#planning` `#multi-agent` `#self-improvement`
- [2024/03] **MineLand: Simulating Large-Scale Multi-Agent Interactions with Limited Multimodal Senses and Physical Needs** *arXiv* [[paper](https://arxiv.org/abs/2403.19267)][[code](https://github.com/cocacola-lab/MineLand)] `#minecraft` `#multi-agent` `#vlm`
- [2024/03] **Hierarchical Auto-Organizing System for Open-Ended Multi-Agent Navigation (HAS)** *ICLR 2024 Workshop* [[paper](https://arxiv.org/abs/2403.08282)] `#minecraft` `#planning` `#multi-agent` `#vlm`
- [2024/03] **Embodied LLM Agents Learn to Cooperate in Organized Teams** *IEEE Transactions on Computational Social Systems 2024* [[paper](https://arxiv.org/pdf/2403.12482)] `#competition` `#planning` `#multi-agent`
- [2024/03] **Can LLM-Augmented Autonomous Agents Cooperate?, An Evaluation of Their Cooperative Capabilities through Melting Pot** *IEEE Transactions on Artificial Intelligence 2024* [[paper](https://arxiv.org/abs/2403.11381.pdf)] `#cooperation` `#multi-agent`
- [2024/03] **Helmsman of the Masses? Evaluate the Opinion Leadership of Large Language Models in the Werewolf Game** *COLM* [[paper](https://openreview.net/forum?id=xMt9kCv5YR)] `#communication` `#multi-agent`
- [2023/12] **Cooperation on the Fly: Exploring Language Agents for Ad Hoc Teamwork in the Avalon Game** *arXiv* [[paper](https://arxiv.org/abs/2312.17515.pdf)] `#communication` `#multi-agent`
- [2023/12] **Deciphering Digital Detectives: Understanding LLM Behaviors and Capabilities in Multi-Agent Mystery Games** *ACL 2023* [[paper](https://arxiv.org/pdf/2312.00746.pdf)] `#communication` `#multi-agent` `#prompting`
- [2023/11] **War and Peace (WarAgent): Large Language Model-based Multi-Agent Simulation of World Wars** *arXiv* [[paper](https://arxiv.org/abs/2311.17227.pdf)][[code](https://github.com/agiresearch/WarAgent)] `#communication` `#multi-agent`
- [2023/10] **Lyfe Agents: Generative agents for low-cost real-time social interactions** *arXiv* [[paper](https://arxiv.org/abs/2310.02172.pdf)] `#sim-social` `#memory` `#multi-agent` `#self-improvement`
- [2023/10] **Evaluating Multi-agent Coordination Abilities in Large Language Models** *NAACL 2023* [[paper](https://arxiv.org/abs/2310.03903.pdf)] `#cooperation` `#planning` `#multi-agent` `#prompting`
- [2023/10] **Theory of Mind for Multi-Agent Collaboration via Large Language Models** *EMNLP 2023* [[paper](https://arxiv.org/pdf/2310.10701)][[code](https://github.com/romanlee6/multi_LLM_comm)] `#cooperation` `#planning` `#multi-agent` `#training`
- [2023/10] **LLM-Based Agent Society Investigation: Collaboration and Confrontation in Avalon Gameplay** *EMNLP 2023* [[paper](https://arxiv.org/abs/2310.14985)] `#communication` `#multi-agent`
- [2023/10] **Leveraging Word Guessing Games to Assess the Intelligence of Large Language Models** *arXiv* [[paper](https://arxiv.org/abs/2310.20499.pdf)][[code](https://github.com/Skytliang/SpyGame)] `#communication` `#multi-agent`
- [2023/09] **MindAgent: Emergent Gaming Interaction** *NAACL 2023* [[paper](http://https://arxiv.org/abs/2309.09971)] `#cooperation` `#planning` `#multi-agent` `#prompting`
- [2023/07] **Building Cooperative Embodied Agents Modularly with Large Language Models** *ICLR 2024* [[paper](https://arxiv.org/abs/2307.02485.pdf)][[code](https://github.com/UMass-Foundation-Model/Co-LLM-Agents/)] `#cooperation` `#planning` `#multi-agent` `#training`

## world-model

- [2026/05] **PriorZero: Bridging Language Priors and World Models for Decision Making** *arXiv* [[paper](https://arxiv.org/abs/2605.12289)][[code](https://github.com/opendilab/LightZero)] `#text-adventure` `#planning` `#world-model` `#training`
- [2026/02] **World Models for Policy Refinement in StarCraft II** *arXiv* [[paper](https://arxiv.org/abs/2602.14857)] `#competition` `#world-model` `#prompting`
- [2026/02] **CWM: Contrastive World Models for Action Feasibility Learning in Embodied Agent Pipelines** *arXiv* [[paper](https://arxiv.org/abs/2602.22452)] `#text-adventure` `#planning` `#world-model` `#training`
- [2026/02] **Reinforcement World Model Learning for LLM-based Agents** *arXiv* [[paper](https://arxiv.org/abs/2602.05842)] `#text-adventure` `#world-model`
- [2025/11] **DR. WELL: Dynamic Reasoning and Learning with Symbolic World Model for Embodied LLM-Based Multi-Agent Collaboration** *arXiv* [[paper](https://arxiv.org/abs/2511.04646)] `#sim-embodied` `#planning` `#multi-agent` `#world-model`
- [2025/09] **World Model Implanting for Test-time Adaptation of Embodied Agents** *ICML 2025 poster* [[paper](https://arxiv.org/abs/2509.03956)] `#text-adventure` `#memory` `#world-model` `#prompting`
- [2025/09] **DreamPhase: Offline Imagination and Uncertainty-Guided Planning for Large-Language-Model Agents** *ICLR 2026 Poster* [[paper](https://openreview.net/forum?id=81PJ2KPnmK)] `#text-adventure` `#planning` `#world-model`
- [2025/07] **CoEx -- Co-evolving World-model and Exploration** *EMNLP 2025* [[paper](https://arxiv.org/abs/2507.22281)] `#text-adventure` `#planning` `#world-model`
- [2025/06] **Improving LLM Agent Planning with In-Context Learning via Atomic Fact Augmentation and Lookahead Search** *arXiv* [[paper](https://arxiv.org/abs/2506.09171)] `#text-adventure` `#planning` `#world-model` `#training`
- [2025/05] **PoE-World: Compositional World Modeling with Products of Programmatic Experts** *NeurIPS 2025 spotlight* [[paper](https://openreview.net/forum?id=obwRcksFZw)] `#action` `#planning` `#world-model`
- [2025/05] **WALL-E: World Alignment by NeuroSymbolic Learning improves World Model-based LLM Agents** *NeurIPS 2025 poster* [[paper](https://openreview.net/forum?id=DorAT49sxj)] `#minecraft` `#planning` `#world-model` `#prompting`
- [2025/04] **WALL-E 2.0: World Alignment by NeuroSymbolic Learning Improves World Model-based LLM Agents** *arXiv* [[paper](https://arxiv.org/abs/2504.15785)][[code](https://github.com/elated-sawyer/WALL-E)] `#minecraft` `#planning` `#world-model` `#prompting`
- [2025/04] **Better Decisions through the Right Causal World Model** *arXiv* [[paper](https://arxiv.org/abs/2504.07257)] `#action` `#planning` `#world-model` `#training`
- [2025/02] **Optimus-2: Multimodal World Model for Open-World Minecraft Agents** *CVPR 2025* [[paper](https://arxiv.org/pdf/2502.19902)][[code](https://github.com/JiuTian-VL/Optimus-2)] `#minecraft` `#planning` `#world-model` `#vlm`
- [2024/10] **WALL-E: World Alignment by Rule Learning Improves World Model-based LLM Agents** *arXiv* [[paper](https://arxiv.org/abs/2410.07484)][[code](https://github.com/elated-sawyer/WALL-E)] `#minecraft` `#planning` `#world-model`
- [2024/05] **Agent Planning with World Knowledge Model** *NeurIPS 2024* [[paper](https://arxiv.org/pdf/2405.14205)][[code](https://github.com/zjunlp/WKM)] `#text-adventure` `#planning` `#memory` `#world-model`
- [2023/05] **Language Models Meet World Models: Embodied Experiences Enhance Language Models** *NeurIPS 2023* [[paper](https://arxiv.org/abs/2305.10626.pdf)][[code](https://github.com/szxiangjn/world-model-for-language-model)] `#sim-embodied` `#planning` `#world-model`
- [2023/04] **Can Large Language Models Play Text Games Well? Current State-of-the-Art and Open Questions** *arXiv* [[paper](https://arxiv.org/pdf/2304.02868.pdf)] `#text-adventure` `#world-model`

## tool-use

- [2026/05] **Skill1: Unified Evolution of Skill-Augmented Agents via Reinforcement Learning** *arXiv* [[paper](https://arxiv.org/abs/2605.06130)] `#text-adventure` `#tool-use` `#training`
- [2026/05] **Skills on the Fly: Test-Time Adaptive Skill Synthesis for LLM Agents** *arXiv* [[paper](https://arxiv.org/abs/2605.16986)] `#text-adventure` `#memory` `#tool-use`
- [2026/05] **SkillGraph: Skill-Augmented Reinforcement Learning for Agents via Evolving Skill Graphs** *arXiv* [[paper](https://arxiv.org/abs/2605.12039)] `#text-adventure` `#memory` `#tool-use` `#training`
- [2026/05] **SkillOps: Managing LLM Agent Skill Libraries as Self-Maintaining Software Ecosystems** *arXiv* [[paper](https://arxiv.org/abs/2605.13716)] `#text-adventure` `#planning` `#memory` `#tool-use`
- [2026/04] **Nemobot Games: Crafting Strategic AI Gaming Agents for Interactive Learning with Large Language Models** *arXiv* [[paper](https://arxiv.org/abs/2604.21896)] `#tool-use` `#training` `#self-improvement`
- [2026/02] **SkillRL: Evolving Agents via Recursive Skill-Augmented Reinforcement Learning** *arXiv* [[paper](https://arxiv.org/abs/2602.08234)][[code](https://github.com/aiming-lab/SkillRL)] `#text-adventure` `#memory` `#tool-use` `#training`
- [2025/09] **Speculative Actions: A Lossless Framework for Faster AI Agents** *ICLR 2026 Oral* [[paper](https://openreview.net/forum?id=P0GOk5wslg)] `#competition` `#tool-use`
- [2025/09] **Learn the Ropes, Then Trust the Wins: Self-imitation with Progressive Exploration for Agentic Reinforcement Learning** *ICLR 2026 Poster* [[paper](https://openreview.net/forum?id=Kssko33Ekq)] `#text-adventure` `#tool-use` `#training`
- [2025/08] **Vistawise: Building Cost-effective Agent with Cross-modal Knowledge Graph for Minecraft** *EMNLP 2025* [[paper](https://arxiv.org/abs/2508.18722)] `#minecraft` `#memory` `#tool-use`
- [2025/05] **Agent-Environment Alignment via Automated Interface Generation** *arXiv* [[paper](https://arxiv.org/abs/2505.21055)][[code](https://github.com/THUNLP-MT/ALIGN)] `#text-adventure` `#tool-use`
- [2025/05] **Planning without Search: Refining Frontier LLMs with Offline Goal-Conditioned RL** *NeurIPS 2025 poster* [[paper](https://openreview.net/forum?id=kuoD6G0Suq)] `#communication` `#planning` `#tool-use` `#training`
- [2025/03] **Parallelized Planning-Acting for Efficient LLM-based Multi-Agent Systems** *arXiv* [[paper](https://arxiv.org/abs/2503.03505)] `#minecraft` `#planning` `#multi-agent` `#tool-use`
- [2025/03] **Plancraft: an evaluation dataset for planning with LLM agents** *COLM 2025* [[paper](https://openreview.net/forum?id=nSV8Depcpx)] `#minecraft` `#planning` `#memory` `#tool-use`
- [2024/07] **AppWorld: A Controllable World of Apps and People for Benchmarking Interactive Coding Agents** *ACL 2024* [[paper](https://arxiv.org/abs/2407.18901)][[code](https://github.com/stonybrooknlp/appworld)] `#text-adventure` `#tool-use`
- [2024/07] **Odyssey: Empowering Agents with Open-World Skills.** *IJCAI 2024* [[paper](https://arxiv.org/abs/2407.15325)][[code](https://github.com/zju-vipa/Odyssey)] `#minecraft` `#planning` `#tool-use`
- [2024/04] **Learning From Failure: Integrating Negative Examples When Fine-tuning Large Language Models as Agent** *arXiv* [[paper](https://arxiv.org/pdf/2402.11651)][[code](https://github.com/Reason-Wang/NAT)] `#text-adventure` `#tool-use` `#training`
- [2024/02] **RL-GPT: Integrating Reinforcement Learning and Code-as-policy** *NeurIPS 2024 oral* [[paper](https://arxiv.org/abs/2402.19299.pdf)] `#minecraft` `#planning` `#tool-use` `#training`
- [2023/08] **AgentSims: An Open-Source Sandbox for Large Language Model Evaluation** *arXiv* [[paper](https://arxiv.org/abs/2308.04026.pdf)][[code](https://github.com/py499372727/AgentSims)] `#sim-social` `#planning` `#tool-use`
- [2023/05] **VOYAGER: An Open-Ended Embodied Agent with Large Language Models** *FMDM@NeurIPS2023* [[paper](https://arxiv.org/abs/2305.16291.pdf)][[code](https://github.com/MineDojo/Voyager)] `#minecraft` `#tool-use` `#training`

## training

- [2026/05] **Odysseus: Scaling VLMs to 100+ Turn Decision-Making in Games via Reinforcement Learning** *arXiv* [[paper](https://arxiv.org/abs/2605.00347)] `#action` `#training` `#vlm`
- [2026/05] **T$^2$PO: Uncertainty-Guided Exploration Control for Stable Multi-Turn Agentic Reinforcement Learning** *arXiv* [[paper](https://arxiv.org/abs/2605.02178)][[code](https://github.com/WillDreamer/T2PO)] `#text-adventure` `#training`
- [2026/05] **ANO: A Principled Approach to Robust Policy Optimization** *arXiv* [[paper](https://arxiv.org/abs/2605.02320)] `#action` `#training`
- [2026/05] **From History to State: Constant-Context Skill Learning for LLM Agents** *arXiv* [[paper](https://arxiv.org/abs/2605.05413)] `#text-adventure` `#planning` `#training`
- [2026/05] **StraTA: Incentivizing Agentic Reinforcement Learning with Strategic Trajectory Abstraction** *arXiv* [[paper](https://arxiv.org/abs/2605.06642)] `#text-adventure` `#training`
- [2026/05] **AEM: Adaptive Entropy Modulation for Multi-Turn Agentic Reinforcement Learning** *arXiv* [[paper](https://arxiv.org/abs/2605.00425)] `#text-adventure` `#training`
- [2026/05] **Evolving-RL: End-to-End Optimization of Experience-Driven Self-Evolving Capability within Agents** *arXiv* [[paper](https://arxiv.org/abs/2605.10663)] `#text-adventure` `#training` `#self-improvement`
- [2026/05] **Skill1: Unified Evolution of Skill-Augmented Agents via Reinforcement Learning** *arXiv* [[paper](https://arxiv.org/abs/2605.06130)] `#text-adventure` `#tool-use` `#training`
- [2026/05] **SkillMaster: Toward Autonomous Skill Mastery in LLM Agents** *arXiv* [[paper](https://arxiv.org/abs/2605.08693)] `#text-adventure` `#training`
- [2026/05] **Agent-BRACE: Decoupling Beliefs from Actions in Long-Horizon Tasks via Verbalized State Uncertainty** *arXiv* [[paper](https://arxiv.org/abs/2605.11436)] `#sim-embodied` `#training`
- [2026/05] **PriorZero: Bridging Language Priors and World Models for Decision Making** *arXiv* [[paper](https://arxiv.org/abs/2605.12289)][[code](https://github.com/opendilab/LightZero)] `#text-adventure` `#planning` `#world-model` `#training`
- [2026/05] **Generalization or Memorization? Brittleness Testing for Chess-Trained Language Models** *arXiv* [[paper](https://arxiv.org/abs/2605.17565)] `#competition` `#training`
- [2026/05] **ALSO: Adversarial Online Strategy Optimization for Social Agents** *arXiv* [[paper](https://arxiv.org/abs/2605.15768)] `#sim-social` `#multi-agent` `#training`
- [2026/05] **Brain alignment of reasoning and action representations from vision-language and action models during naturalistic gameplay** *arXiv* [[paper](https://arxiv.org/abs/2605.19352)] `#action` `#planning` `#training` `#vlm`
- [2026/05] **What and When to Distill: Selective Hindsight Distillation for Multi-Turn Agents** *arXiv* [[paper](https://arxiv.org/abs/2605.19447)] `#text-adventure` `#training`
- [2026/05] **GROW: Aligning GRPO with State-Action Modeling for Open-World VLM Agents** *arXiv* [[paper](https://arxiv.org/abs/2605.20246)] `#minecraft` `#training` `#vlm`
- [2026/05] **SkillGraph: Skill-Augmented Reinforcement Learning for Agents via Evolving Skill Graphs** *arXiv* [[paper](https://arxiv.org/abs/2605.12039)] `#text-adventure` `#memory` `#tool-use` `#training`
- [2026/05] **Dynamic Skill Lifecycle Management for Agentic Reinforcement Learning** *arXiv* [[paper](https://arxiv.org/abs/2605.10923)] `#text-adventure` `#training`
- [2026/05] **Selective Rollout: Mid-Trajectory Termination for Multi-Sample Agent RL** *arXiv* [[paper](https://arxiv.org/abs/2605.05802)][[code](https://github.com/zhiyuanZhai20/selective-rollout)] `#text-adventure` `#training`
- [2026/05] **R2V Agent: Teaching SLMs When to Ask for Help** *arXiv* [[paper](https://arxiv.org/abs/2605.16604)] `#text-adventure` `#training`
- [2026/04] **MARL-GPT: Foundation Model for Multi-Agent Reinforcement Learning** *Proceedings of the 25th International Conference on Autonomous Agents and Multiagent Systems 2026* [[paper](https://arxiv.org/abs/2604.05943)] `#competition` `#multi-agent` `#training`
- [2026/04] **Hierarchical Reinforcement Learning with Augmented Step-Level Transitions for LLM Agents** *arXiv* [[paper](https://arxiv.org/abs/2604.05808)][[code](https://github.com/TonyStark042/STEP-HRL)] `#text-adventure` `#training`
- [2026/04] **GRAIL: Autonomous Concept Grounding for Neuro-Symbolic Reinforcement Learning** *arXiv* [[paper](https://arxiv.org/abs/2604.16871)] `#action` `#training`
- [2026/04] **Nemobot Games: Crafting Strategic AI Gaming Agents for Interactive Learning with Large Language Models** *arXiv* [[paper](https://arxiv.org/abs/2604.21896)] `#tool-use` `#training` `#self-improvement`
- [2026/04] **DPEPO: Diverse Parallel Exploration Policy Optimization for LLM-based Agents** *arXiv* [[paper](https://arxiv.org/abs/2604.24320)][[code](https://github.com/LePanda026/Code-for-DPEPO)] `#text-adventure` `#training`
- [2026/03] **On the Strengths and Weaknesses of Data for Open-set Embodied Assistance** *arXiv* [[paper](https://arxiv.org/abs/2603.04819)] `#cooperation` `#training`
- [2026/03] **Hindsight Credit Assignment for Long-Horizon LLM Agents** *arXiv* [[paper](https://arxiv.org/abs/2603.08754)] `#text-adventure` `#training`
- [2026/03] **How Clued up are LLMs? Evaluating Multi-Step Deductive Reasoning in a Text-Based Game Environment** *arXiv* [[paper](https://arxiv.org/abs/2603.17169)] `#text-adventure` `#multi-agent` `#training`
- [2026/03] **PolicySim: An LLM-Based Agent Social Simulation Sandbox for Proactive Policy Optimization** *WWW 2026* [[paper](https://arxiv.org/abs/2603.19649)] `#sim-social` `#training`
- [2026/03] **Grounded Chess Reasoning in Language Models via Master Distillation** *arXiv* [[paper](https://arxiv.org/abs/2603.20510)] `#competition` `#planning` `#training`
- [2026/03] **RetroAgent: From Solving to Evolving via Retrospective Dual Intrinsic Feedback** *arXiv* [[paper](https://arxiv.org/abs/2603.08561)] `#text-adventure` `#memory` `#training` `#self-improvement`
- [2026/02] **VLM-Guided Experience Replay** *arXiv* [[paper](https://arxiv.org/abs/2602.01915)] `#planning` `#training` `#vlm`
- [2026/02] **Implicit Strategic Optimization: Rethinking Long-Horizon Decision-Making in Adversarial Poker Environments** *arXiv* [[paper](https://arxiv.org/abs/2602.08041)] `#action` `#training`
- [2026/02] **Think Fast and Slow: Step-Level Cognitive Depth Adaptation for LLM Agents** *arXiv* [[paper](https://arxiv.org/abs/2602.12662)] `#text-adventure` `#planning` `#training`
- [2026/02] **VAM: Verbalized Action Masking for Controllable Exploration in RL Post-Training -- A Chess Case Study** *arXiv* [[paper](https://arxiv.org/abs/2602.16833)] `#competition` `#training`
- [2026/02] **CWM: Contrastive World Models for Action Feasibility Learning in Embodied Agent Pipelines** *arXiv* [[paper](https://arxiv.org/abs/2602.22452)] `#text-adventure` `#planning` `#world-model` `#training`
- [2026/02] **SELAUR: Self Evolving LLM Agent via Uncertainty-aware Rewards** *arXiv* [[paper](https://arxiv.org/abs/2602.21158)] `#text-adventure` `#training`
- [2026/02] **SkillRL: Evolving Agents via Recursive Skill-Augmented Reinforcement Learning** *arXiv* [[paper](https://arxiv.org/abs/2602.08234)][[code](https://github.com/aiming-lab/SkillRL)] `#text-adventure` `#memory` `#tool-use` `#training`
- [2026/01] **NitroGen: An Open Foundation Model for Generalist Gaming Agents** *arXiv* [[paper](https://arxiv.org/abs/2601.02427)] `#benchmark` `#training`
- [2026/01] **Paying Less Generalization Tax: A Cross-Domain Generalization Study of RL Training for LLM Agents** *arXiv* [[paper](https://arxiv.org/abs/2601.18217)] `#text-adventure` `#planning` `#training`
- [2026/01] **Just-In-Time Reinforcement Learning: Continual Learning in LLM Agents Without Gradient Updates** *arXiv* [[paper](https://arxiv.org/abs/2601.18510)][[code](https://github.com/liushiliushi/JitRL)] `#text-adventure` `#training`
- [2026/01] **HumanLLM: Towards Personalized Understanding and Simulation of Human Nature** *arXiv* [[paper](https://arxiv.org/abs/2601.15793)] `#sim-social` `#training`
- [2025/12] **Synergizing Code Coverage and Gameplay Intent: Coverage-Aware Game Playtesting with LLM-Guided Reinforcement Learning** *arXiv* [[paper](https://arxiv.org/abs/2512.12706)] `#minecraft` `#training`
- [2025/12] **ESearch-R1: Learning Cost-Aware MLLM Agents for Interactive Embodied Search via Reinforcement Learning** *arXiv* [[paper](https://arxiv.org/abs/2512.18571)] `#sim-embodied` `#planning` `#memory` `#training`
- [2025/12] **Measuring Fine-Grained Negotiation Tactics of Humans and LLMs in Diplomacy** *arXiv* [[paper](https://arxiv.org/abs/2512.18292)] `#communication` `#training`
- [2025/12] **Robust Agents in Open-Ended Worlds** *arXiv* [[paper](https://arxiv.org/abs/2512.08139)] `#action` `#multi-agent` `#training` `#generation`
- [2025/10] **Fine-tuning with RAG for Improving LLM Learning of New Skills** *arXiv* [[paper](https://arxiv.org/abs/2510.01375)] `#text-adventure` `#planning` `#memory` `#training`
- [2025/10] **Graph-Enhanced Policy Optimization in LLM Agent Training** *arXiv* [[paper](https://arxiv.org/abs/2510.26270)] `#text-adventure` `#planning` `#training`
- [2025/10] **SALT: Step-level Advantage Assignment for Long-horizon Agents via Trajectory Graph** *arXiv* [[paper](https://arxiv.org/abs/2510.20022)] `#text-adventure` `#training`
- [2025/09] **HLSMAC: A New StarCraft Multi-Agent Challenge for High-Level Strategic Decision-Making** *arXiv* [[paper](https://arxiv.org/abs/2509.12927)] `#competition` `#multi-agent` `#training`
- [2025/09] **Exploration with Foundation Models: Capabilities, Limitations, and Hybrid Approaches** *arXiv* [[paper](https://arxiv.org/abs/2509.19924)] `#action` `#training` `#vlm`
- [2025/09] **Harnessing Uncertainty: Entropy-Modulated Policy Gradients for Long-Horizon LLM Agents** *arXiv* [[paper](https://arxiv.org/abs/2509.09265)] `#text-adventure` `#training`
- [2025/09] **Goal-Guided Efficient Exploration via Large Language Model in Reinforcement Learning** *arXiv* [[paper](https://arxiv.org/abs/2509.22008)] `#crafter` `#planning` `#training`
- [2025/09] **Reward Is Enough: LLMs Are In-Context Reinforcement Learners** *ICLR 2026 Poster* [[paper](https://openreview.net/forum?id=keCXNHOe4W)] `#text-adventure` `#training` `#self-improvement`
- [2025/09] **Spinning Straw into Gold: Relabeling LLM Agent Trajectories in Hindsight for Successful Demonstrations** *ICLR 2026 Poster* [[paper](https://openreview.net/forum?id=QNfmqMSR7r)] `#text-adventure` `#training`
- [2025/09] **SPIRAL: Self-Play on Zero-Sum Games Incentivizes Reasoning via Multi-Agent Multi-Turn Reinforcement Learning** *ICLR 2026 Poster* [[paper](https://openreview.net/forum?id=7Yayy5fNLg)] `#competition` `#planning` `#multi-agent` `#training`
- [2025/09] **Exploratory Memory-Augmented LLM Agent via Hybrid On- and Off-Policy Optimization** *ICLR 2026 Poster* [[paper](https://openreview.net/forum?id=UOzxviKVFO)] `#text-adventure` `#memory` `#training`
- [2025/09] **Learn the Ropes, Then Trust the Wins: Self-imitation with Progressive Exploration for Agentic Reinforcement Learning** *ICLR 2026 Poster* [[paper](https://openreview.net/forum?id=Kssko33Ekq)] `#text-adventure` `#tool-use` `#training`
- [2025/08] **Enhancing Vision-Language Model Training with Reinforcement Learning in Synthetic Worlds for Real-World Success** *Proceedings of the 25th International Conference on Autonomous Agents and Multiagent Systems 2025* [[paper](https://arxiv.org/abs/2508.04280)] `#text-adventure` `#planning` `#training` `#vlm`
- [2025/08] **Democratizing Diplomacy: A Harness for Evaluating Any Large Language Model on Full-Press Diplomacy** *AAAI 2025* [[paper](https://arxiv.org/abs/2508.07485)] `#communication` `#training`
- [2025/08] **CausalPlan: Empowering Efficient LLM Multi-Agent Collaboration Through Causality-Driven Planning** *arXiv* [[paper](https://arxiv.org/abs/2508.13721)] `#cooperation` `#planning` `#multi-agent` `#training`
- [2025/08] **Learning Game-Playing Agents with Generative Code Optimization** *arXiv* [[paper](https://arxiv.org/abs/2508.19506)] `#action` `#training` `#self-improvement`
- [2025/08] **SC2Arena and StarEvolve: Benchmark and Self-Improvement Framework for LLMs in Complex Decision-Making Tasks** *arXiv* [[paper](https://arxiv.org/abs/2508.10428)] `#competition` `#planning` `#training` `#self-improvement`
- [2025/08] **HERAKLES: Hierarchical Skill Compilation for Open-ended LLM Agents** *arXiv* [[paper](https://arxiv.org/abs/2508.14751)] `#crafter` `#planning` `#training`
- [2025/07] **LLM Economist: Large Population Models and Mechanism Design in Multi-Agent Generative Simulacra** *arXiv* [[paper](https://arxiv.org/abs/2507.15815)][[code](https://github.com/sethkarten/LLM-Economist)] `#sim-social` `#multi-agent` `#training` `#role-play`
- [2025/06] **Orak: A Foundational Benchmark for Training and Evaluating LLM Agents on Diverse Video Games** *arXiv* [[paper](https://arxiv.org/pdf/2506.03610)][[code](https://github.com/krafton-ai/Orak)] `#benchmark` `#training`
- [2025/06] **UnrealZoo: Enriching Photo-realistic Virtual Worlds for Embodied AI** *ICCV 2025* [[paper](https://arxiv.org/abs/2412.20977)][[code](https://github.com/UnrealZoo/unrealzoo-gym)] `#benchmark` `#multi-agent` `#training`
- [2025/06] **Empowering Economic Simulation for Massively Multiplayer Online Games through Generative Agent-Based Modeling** *KDD 2025* [[paper](https://arxiv.org/abs/2506.04699)] `#sim-social` `#training`
- [2025/06] **Enhancing Decision-Making of Large Language Models via Actor-Critic** *ICML 2025 poster* [[paper](https://arxiv.org/abs/2506.06376)] `#text-adventure` `#training`
- [2025/06] **Improving LLM Agent Planning with In-Context Learning via Atomic Fact Augmentation and Lookahead Search** *arXiv* [[paper](https://arxiv.org/abs/2506.09171)] `#text-adventure` `#planning` `#world-model` `#training`
- [2025/06] **DipLLM: Fine-Tuning LLM for Strategic Decision-making in Diplomacy** *ICML 2025 poster* [[paper](https://arxiv.org/abs/2506.09655)] `#communication` `#training`
- [2025/06] **OmniReflect: Discovering Transferable Constitutions for LLM agents via Neuro-Symbolic Reflections** *arXiv* [[paper](https://arxiv.org/abs/2506.17449)] `#text-adventure` `#planning` `#training` `#self-improvement`
- [2025/06] **The Decrypto Benchmark for Multi-Agent Reasoning and Theory of Mind** *arXiv* [[paper](https://arxiv.org/abs/2506.20664)] `#multi-agent` `#training`
- [2025/06] **GuessBench: Sensemaking Multimodal Creativity in the Wild** *arXiv* [[paper](https://arxiv.org/abs/2506.00814)] `#minecraft` `#training` `#vlm`
- [2025/06] **KnowMap: Efficient Knowledge-Driven Task Adaptation for LLMs** *arXiv* [[paper](https://arxiv.org/abs/2506.19527)] `#text-adventure` `#training`
- [2025/05] **lmgame-Bench: How Good are LLMs at Playing Games?."** *ICLR 2026 Poster* [[paper](https://arxiv.org/pdf/2505.15146)][[code](https://github.com/lmgame-org/GamingAgent/tree/main/lmgame-bench)] `#benchmark` `#planning` `#training`
- [2025/05] **Frog Soup: Zero-Shot, In-Context, and Sample-Efficient Frogger Agents** *arXiv* [[paper](https://arxiv.org/abs/2505.03947)][[code](https://github.com/AlienKevin/frogger)] `#action` `#training`
- [2025/05] **Enfoque Odychess: Un método dialéctico, constructivista y adaptativo para la enseñanza del ajedrez con inteligencias artificiales generativas** *arXiv* [[paper](https://arxiv.org/abs/2505.06652)] `#competition` `#training`
- [2025/05] **Multiple Weaks Win Single Strong: Large Language Models Ensemble Weak Reinforcement Learning Agents into a Supreme One** *arXiv* [[paper](https://arxiv.org/abs/2505.15306)] `#action` `#training`
- [2025/05] **Divide and Conquer: Grounding LLMs as Efficient Decision-Making Agents via Offline Hierarchical Reinforcement Learning** *ICML 2025 poster* [[paper](https://arxiv.org/abs/2505.19761)] `#text-adventure` `#planning` `#training`
- [2025/05] **Retrospex: Language Agent Meets Offline Reinforcement Learning Critic** *EMNLP 2025* [[paper](https://arxiv.org/abs/2505.11807)] `#text-adventure` `#training`
- [2025/05] **SPA-RL: Reinforcing LLM Agents via Stepwise Progress Attribution** *arXiv* [[paper](https://arxiv.org/abs/2505.20732)][[code](https://github.com/WangHanLinHenry/SPA-RL-Agent)] `#text-adventure` `#training`
- [2025/05] **Prompted Policy Search: Reinforcement Learning through Linguistic and Numerical Reasoning in LLMs** *NeurIPS 2025 poster* [[paper](https://openreview.net/forum?id=95plu1Mo20)] `#action` `#training`
- [2025/05] **Planning without Search: Refining Frontier LLMs with Offline Goal-Conditioned RL** *NeurIPS 2025 poster* [[paper](https://openreview.net/forum?id=kuoD6G0Suq)] `#communication` `#planning` `#tool-use` `#training`
- [2025/05] **Can Large Language Models Master Complex Card Games?** *NeurIPS 2025 poster* [[paper](https://openreview.net/forum?id=cmN8Wbvanr)][[code](https://github.com/THUDM/LLM4CardGame)] `#competition` `#training`
- [2025/05] **MindForge: Empowering Embodied Agents with Theory of Mind for Lifelong Cultural Learning** *NeurIPS 2025 poster* [[paper](https://openreview.net/forum?id=u7jtLj46i9)] `#minecraft` `#training`
- [2025/05] **SEEA-R1: Tree-Structured Reinforcement Fine-Tuning for Self-Evolving Embodied Agents** *NeurIPS 2025 poster* [[paper](https://openreview.net/forum?id=dAwKePZvcN)] `#text-adventure` `#planning` `#training` `#self-improvement`
- [2025/05] **LLM-Explorer: A Plug-in Reinforcement Learning Policy Exploration Enhancement Driven by Large Language Models** *NeurIPS 2025 spotlight* [[paper](https://openreview.net/forum?id=VA5P0rUZPx)][[code](https://github.com/tsinghua-fib-lab/LLM-Explorer)] `#action` `#training`
- [2025/04] **Collaborating Action by Action: A Multi-agent LLM Framework for Embodied Reasoning** *arXiv* [[paper](https://arxiv.org/abs/2504.17950)][[code](https://github.com/mindcraft-bots/mindcraft)] `#minecraft` `#multi-agent` `#training`
- [2025/04] **Better Decisions through the Right Causal World Model** *arXiv* [[paper](https://arxiv.org/abs/2504.07257)] `#action` `#planning` `#world-model` `#training`
- [2025/04] **Enhancing Player Enjoyment with a Two-Tier DRL and LLM-Based Agent System for Fighting Games** *arXiv* [[paper](https://arxiv.org/abs/2504.07425)] `#training`
- [2025/04] **Monte Carlo Planning with Large Language Model for Text-Based Game Agents** *ICLR 2025 Poster* [[paper](https://arxiv.org/abs/2504.16855)] `#text-adventure` `#planning` `#training`
- [2025/04] **MF-LLM: Simulating Population Decision Dynamics via a Mean-Field Large Language Model Framework** *NeurIPS 2025 poster* [[paper](https://openreview.net/forum?id=m0q8NfGWnv)] `#sim-social` `#planning` `#training`
- [2025/04] **Group-in-Group Policy Optimization for LLM Agent Training** *NeurIPS 2025 poster* [[paper](https://openreview.net/forum?id=QXEhBMNrCW)] `#text-adventure` `#training`
- [2025/03] **GFlowVLM: Enhancing Multi-step Reasoning in Vision-Language Models with Generative Flow Networks** *CVPR 2025* [[paper](https://arxiv.org/abs/2503.06514)] `#text-adventure` `#planning` `#training` `#vlm`
- [2025/03] **Society of Mind Meets Real-Time Strategy: A Hierarchical Multi-Agent Framework for Strategic Reasoning** *COLM 2025* [[paper](https://arxiv.org/abs/2508.06042)] `#competition` `#multi-agent` `#training`
- [2025/02] **Process Reward Models for LLM Agents: Practical Framework and Directions** *arXiv* [[paper](https://arxiv.org/abs/2502.10325)][[code](https://github.com/sanjibanc/agent_prm)] `#text-adventure` `#training`
- [2025/01] **POKERBENCH: Training Large Language Models to become Professional Poker Players** *AAAI 2025* [[paper](https://arxiv.org/pdf/2501.08328)] `#competition` `#planning` `#training`
- [2025/01] **DVM: Towards Controllable LLM Agents in Social Deduction Games** *IEEE International Conference on Acoustics, Speech, and Signal Processing 2025* [[paper](https://arxiv.org/abs/2501.06695)] `#communication` `#training`
- [2025/01] **Complete Chess Games Enable LLM Become A Chess Master** *NAACL 2025* [[paper](https://arxiv.org/abs/2501.17186)] `#competition` `#training`
- [2025/01] **LMAct: A Benchmark for In-Context Imitation Learning with Long Multimodal Demonstrations** *ICML 2025 poster* [[paper](https://openreview.net/forum?id=8aChcUzAhI)] `#action` `#planning` `#training`
- [2025/01] **Language Models as Implicit Tree Search** *ICML 2025 poster* [[paper](https://openreview.net/forum?id=bEqMmGu6qg)] `#competition` `#planning` `#training`
- [2025/01] **LARM: Large Auto-Regressive Model for Long-Horizon Embodied Intelligence** *ICML 2025 poster* [[paper](https://openreview.net/forum?id=zcx7jqUZg5)] `#minecraft` `#training`
- [2024/12] **TeamCraft: A Benchmark for Multi-Modal Multi-Agent Systems in Minecraft** *arXiv* [[paper](https://arxiv.org/abs/2412.05255)][[code](https://github.com/teamcraft-bench/teamcraft)] `#minecraft` `#multi-agent` `#training` `#vlm`
- [2024/12] **Fine-tuning large vision-language models as decision-making agents via reinforcement learning** *NeurIPS 2024* [[paper](https://proceedings.neurips.cc/paper_files/paper/2024/file/c848b7d3adc08fcd0bf1df3101ba6728-Paper-Conference.pdf)][[code](https://github.com/RL4VLM/RL4VLM)] `#text-adventure` `#training` `#vlm`
- [2024/09] **Can VLMs Play Action Role-Playing Games? Take Black Myth Wukong as a Study Case** *arXiv* [[paper](https://arxiv.org/abs/2409.12889)][[code](https://varp-agent.github.io/)] `#action` `#planning` `#training`
- [2024/09] **Strategist: Self-improvement of LLM Decision Making via Bi-Level Tree Search** *ICLR 2025 Poster* [[paper](https://openreview.net/forum?id=gfI9v7AbFg)] `#communication` `#planning` `#multi-agent` `#training`
- [2024/09] **MaestroMotif: Skill Design from Artificial Intelligence Feedback** *ICLR 2025 Oral* [[paper](https://openreview.net/forum?id=or8mMhmyRV)] `#action` `#training`
- [2024/09] **Can We Trust Embodied Agents? Exploring Backdoor Attacks against Embodied LLM-Based Decision-Making Systems** *ICLR 2025 Poster* [[paper](https://openreview.net/forum?id=S1Bv3068Xt)] `#sim-embodied` `#training`
- [2024/09] **Better than Your Teacher: LLM Agents that learn from Privileged AI Feedback** *ICLR 2025 Poster* [[paper](https://openreview.net/forum?id=st7XqFgbAH)] `#text-adventure` `#planning` `#training` `#self-improvement`
- [2024/09] **BALROG: Benchmarking Agentic LLM and VLM Reasoning On Games** *ICLR 2025 Poster* [[paper](https://openreview.net/forum?id=fp6t3F669F)] `#action` `#planning` `#training` `#vlm`
- [2024/08] **Evaluating and Enhancing LLMs Agent based on Theory of Mind in Guandan: A Multi-Player Cooperative Game under Imperfect Information** *2024 IEEE/WIC International Conference on Web Intelligence and Intelligent Agent Technology (WI-IAT) 2024* [[paper](https://arxiv.org/pdf/2408.02559)] `#competition` `#planning` `#multi-agent` `#training`
- [2024/08] **Atari-GPT: Investigating the Capabilities of Multimodal Large Language Models as Low-Level Policies for Atari Games** *arXiv* [[paper](https://arxiv.org/pdf/2408.15950)] `#action` `#planning` `#training`
- [2024/07] **OmniJARVIS: Omni-Modal Open-World Agents in Minecraft** *NeurIPS 2024* [[paper](https://arxiv.org/abs/2407.00114)][[code](https://github.com/CraftJarvis/OmniJARVIS)] `#minecraft` `#training` `#vlm`
- [2024/06] **STARLING: Self-supervised Training of Text-based Reinforcement Learning Agent with Large Language Models** *ACL 2024* [[paper](https://arxiv.org/pdf/2406.05872)][[code](https://github.com/IBM/starling-agent)] `#text-adventure` `#training`
- [2024/05] **Towards Efficient LLM Grounding for Embodied Multi-Agent Collaboration** *ACL 2024* [[paper](https://arxiv.org/pdf/2405.14314)][[code](https://arxiv.org/pdf/2405.14314)] `#cooperation` `#planning` `#multi-agent` `#training`
- [2024/05] **Policy Improvement using Language Feedback Models** *NeurIPS 2024 poster* [[paper](https://openreview.net/forum?id=FVgCwcwpJw)] `#text-adventure` `#training`
- [2024/05] **Learning to Discuss Strategically: A Case Study on One Night Ultimate Werewolf** *NeurIPS 2024 poster* [[paper](https://openreview.net/forum?id=1f82rnwCbl)] `#communication` `#training`
- [2024/05] **Reflective Multi-Agent Collaboration based on Large Language Models** *NeurIPS 2024 poster* [[paper](https://openreview.net/forum?id=wWiAR5mqXq)] `#competition` `#planning` `#multi-agent` `#training`
- [2024/04] **Learning From Failure: Integrating Negative Examples When Fine-tuning Large Language Models as Agent** *arXiv* [[paper](https://arxiv.org/pdf/2402.11651)][[code](https://github.com/Reason-Wang/NAT)] `#text-adventure` `#tool-use` `#training`
- [2024/04] **ReAct Meets ActRe: When Language Agents Enjoy Training Data Autonomy** *arXiv* [[paper](https://arxiv.org/pdf/2403.14589)] `#text-adventure` `#planning` `#training` `#self-improvement`
- [2024/04] **World Models with Hints of Large Language Models for Goal Achieving** *NAACL 2024* [[paper](https://arxiv.org/pdf/2406.07381)] `#crafter` `#training` `#vlm`
- [2024/04] **Self-playing Adversarial Language Game Enhances LLM Reasoning** *NeurIPS 2024* [[paper](https://arxiv.org/pdf/2404.10642)][[code](https://arxiv.org/pdf/2404.10642)] `#communication` `#training` `#self-improvement`
- [2024/03] **Language Guided Exploration for RL Agents in Text Environments** *NAACL 2024* [[paper](https://arxiv.org/abs/2403.03141.pdf)][[code](https://github.com/hitzkrieg/drrn-scienceworld-clone)] `#text-adventure` `#training`
- [2024/03] **Trial and Error: Exploration-Based Trajectory Optimization for LLM Agents** *ACL 2024* [[paper](https://arxiv.org/pdf/2403.02502)][[code](https://github.com/Yifan-Song793/ETO)] `#text-adventure` `#training` `#self-improvement`
- [2024/03] **EnvGen: Generating and Adapting Environments via LLMs for Training Embodied Agents** *COLM* [[paper](https://arxiv.org/abs/2403.12014.pdf)] `#crafter` `#training`
- [2024/03] **SOTOPIA-$\pi$: Interactive Learning of Socially Intelligent Language Agents** *ACL 2024* [[paper](https://arxiv.org/pdf/2403.08715.pdf)][[code](https://github.com/sotopia-lab/sotopia-pi)] `#sim-social` `#training`
- [2024/03] **Will GPT-4 Run DOOM?** *IEEE Transactions on Games 2024* [[paper](https://arxiv.org/abs/2403.05468.pdf)][[code](https://github.com/adewynter/Doom)] `#action` `#planning` `#training`
- [2024/03] **O3D: Offline Data-driven Discovery and Distillation for Sequential Decision-Making with Large Language Models** *COLM* [[paper](https://openreview.net/forum?id=bkY8zEDdH9)] `#text-adventure` `#training`
- [2024/03] **ReAct Meets ActRe: Autonomous Annotation of Agent Trajectories for Contrastive Self-Training** *COLM* [[paper](https://openreview.net/forum?id=0VLBwQGWpA)] `#text-adventure` `#planning` `#training` `#self-improvement`
- [2024/02] **RL-GPT: Integrating Reinforcement Learning and Code-as-policy** *NeurIPS 2024 oral* [[paper](https://arxiv.org/abs/2402.19299.pdf)] `#minecraft` `#planning` `#tool-use` `#training`
- [2024/02] **PokéLLMon: A Human-Parity Agent for Pokémon Battles with Large Language Models** *TOIT 2025* [[paper](https://arxiv.org/abs/2402.01118.pdf)][[code](https://github.com/git-disl/PokeLLMon)] `#competition` `#training`
- [2024/02] **Agent-Pro: Learning to Evolve via Policy-Level Reflection and Optimization** *ACL 2024* [[paper](https://arxiv.org/abs/2402.17574.pdf)][[code](https://github.com/zwq2018/Agent-Pro)] `#competition` `#training`
- [2024/02] **Enhance Reasoning for Large Language Models in the Game Werewolf** *arXiv* [[paper](https://arxiv.org/abs/2402.02330.pdf)] `#communication` `#training`
- [2024/01] **True Knowledge Comes from Practice: Aligning LLMs with Embodied Environments via Reinforcement Learning** *arXiv* [[paper](https://arxiv.org/pdf/2401.14151.pdf)][[code](https://github.com/WeihaoTan/TWOSOME)] `#sim-embodied` `#training`
- [2024/01] **PokerGPT: An End-to-End Lightweight Solver for Multi-Player Texas Hold'em via Large Language Model** *arXiv* [[paper](https://arxiv.org/abs/2401.06781)] `#competition` `#training`
- [2024/01] **SwarmBrain: Embodied agent for real-time strategy game StarCraft II via large language models** *arXiv* [[paper](https://arxiv.org/abs/2401.17749.pdf)] `#competition` `#training`
- [2023/12] **Auto MC-Reward: Automated Dense Reward Design with Large Language Models for Minecraft** *CVPR 2023* [[paper](https://arxiv.org/abs/2312.09238.pdf)] `#minecraft` `#training`
- [2023/10] **FireAct: Toward Language Agent Fine-tuning** *arXiv* [[paper](https://arxiv.org/pdf/2310.05915)][[code](https://github.com/anchen1011/FireAct)] `#text-adventure` `#training`
- [2023/10] **Language Agent Tree Search Unifies Reasoning Acting and Planning in Language Models** *ICML 2024* [[paper](https://arxiv.org/pdf/2310.04406)][[code](https://github.com/lapisrocks/LanguageAgentTreeSearch)] `#text-adventure` `#planning` `#training`
- [2023/10] **LLaMA Rider: Spurring Large Language Models to Explore the Open World** *NAACL 2023* [[paper](https://arxiv.org/abs/2310.08922.pdf)][[code](https://github.com/PKU-RL/LLaMA-Rider)] `#minecraft` `#planning` `#training`
- [2023/10] **Octopus: Embodied Vision-Language Programmer from Environmental Feedback** *ECCV 2023* [[paper](https://arxiv.org/abs/2310.08588.pdf)][[code](https://github.com/dongyh20/Octopus)] `#sim-embodied` `#planning` `#training` `#vlm`
- [2023/10] **Theory of Mind for Multi-Agent Collaboration via Large Language Models** *EMNLP 2023* [[paper](https://arxiv.org/pdf/2310.10701)][[code](https://github.com/romanlee6/multi_LLM_comm)] `#cooperation` `#planning` `#multi-agent` `#training`
- [2023/10] **Language Agents with Reinforcement Learning for Strategic Play in the Werewolf Game** *ICML 2023* [[paper](https://arxiv.org/abs/2310.18940.pdf)] `#communication` `#training`
- [2023/10] **Avalon's Game of Thoughts: Battle Against Deception through Recursive Contemplation** *arXiv* [[paper](https://arxiv.org/abs/2310.01320)] `#communication` `#training`
- [2023/09] **Motif: Intrinsic Motivation from Artificial Intelligence Feedback** *ICLR 2024* [[paper](https://arxiv.org/abs/2310.00166.pdf)][[code](https://github.com/facebookresearch/motif)] `#video-adventure` `#training`
- [2023/09] **AdaRefiner: Refining Decisions of Language Models with Adaptive Feedback** *NAACL 2023* [[paper](https://arxiv.org/pdf/2309.17176.pdf)] `#crafter` `#training`
- [2023/07] **Building Cooperative Embodied Agents Modularly with Large Language Models** *ICLR 2024* [[paper](https://arxiv.org/abs/2307.02485.pdf)][[code](https://github.com/UMass-Foundation-Model/Co-LLM-Agents/)] `#cooperation` `#planning` `#multi-agent` `#training`
- [2023/05] **Ghost in the Minecraft: Generally Capable Agents for Open-World Environments via Large Language Models with Text-based Knowledge and Memory** *arXiv* [[paper](https://arxiv.org/abs/2305.17144.pdf)] `#minecraft` `#training`
- [2023/05] **VOYAGER: An Open-Ended Embodied Agent with Large Language Models** *FMDM@NeurIPS2023* [[paper](https://arxiv.org/abs/2305.16291.pdf)][[code](https://github.com/MineDojo/Voyager)] `#minecraft` `#tool-use` `#training`
- [2023/03] **Plan4MC: Skill Reinforcement Learning and Planning for Open-World Minecraft Tasks** *FMDM@NeurIPS2023* [[paper](https://arxiv.org/abs/2303.16563.pdf)][[code](https://github.com/PKU-RL/Plan4MC)] `#minecraft` `#planning` `#training`
- [2023/03] **Reflexion: Language Agents with Verbal Reinforcement Learning** *NeurIPS 2023* [[paper](https://proceedings.neurips.cc/paper_files/paper/2023/hash/1b44b878bb782e6954cd888628510e90-Abstract-Conference.html)][[code](https://github.com/noahshinn/reflexion)] `#text-adventure` `#training` `#self-improvement`
- [2023/02] **Guiding Pretraining in Reinforcement Learning with Large Language Models** *ICML 2023* [[paper](https://arxiv.org/abs/2302.06692)] `#crafter` `#training`
- [2023/02] **Grounding Large Language Models in Interactive Environments with Online Reinforcement Learning** *ICML 2023* [[paper](https://arxiv.org/abs/2302.02662.pdf)][[code](https://github.com/flowersteam/Grounding_LLMs_with_online_RL)] `#action` `#training`
- [2022/10] **ReAct: Synergizing Reasoning and Acting in Language Models** *ICLR 2023* [[paper](https://arxiv.org/abs/2210.03629)][[code](https://github.com/ysymyth/ReAct)] `#text-adventure` `#planning` `#training`

## self-improvement

- [2026/05] **Evolving-RL: End-to-End Optimization of Experience-Driven Self-Evolving Capability within Agents** *arXiv* [[paper](https://arxiv.org/abs/2605.10663)] `#text-adventure` `#training` `#self-improvement`
- [2026/05] **APEX: Autonomous Policy Exploration for Self-Evolving LLM Agents** *arXiv* [[paper](https://arxiv.org/abs/2605.21240)] `#text-adventure` `#planning` `#self-improvement`
- [2026/05] **Ratchet: A Minimal Hygiene Recipe for Self-Evolving LLM Agents** *arXiv* [[paper](https://arxiv.org/abs/2605.22148)] `#minecraft` `#self-improvement`
- [2026/04] **Nemobot Games: Crafting Strategic AI Gaming Agents for Interactive Learning with Large Language Models** *arXiv* [[paper](https://arxiv.org/abs/2604.21896)] `#tool-use` `#training` `#self-improvement`
- [2026/04] **GraSP: Graph-Structured Skill Compositions for LLM Agents** *arXiv* [[paper](https://arxiv.org/abs/2604.17870)] `#text-adventure` `#planning` `#memory` `#self-improvement`
- [2026/03] **RetroAgent: From Solving to Evolving via Retrospective Dual Intrinsic Feedback** *arXiv* [[paper](https://arxiv.org/abs/2603.08561)] `#text-adventure` `#memory` `#training` `#self-improvement`
- [2026/02] **MemSkill: Learning and Evolving Memory Skills for Self-Evolving Agents** *arXiv* [[paper](https://arxiv.org/abs/2602.02474)] `#text-adventure` `#self-improvement`
- [2026/02] **The Devil Behind Moltbook: Anthropic Safety is Always Vanishing in Self-Evolving AI Societies** *arXiv* [[paper](https://arxiv.org/abs/2602.09877)] `#sim-social` `#multi-agent` `#self-improvement`
- [2025/10] **Alita-G: Self-Evolving Generative Agent for Agent Generation** *arXiv* [[paper](https://arxiv.org/abs/2510.23601)] `#sim-social` `#memory` `#self-improvement`
- [2025/10] **Beyond Survival: Evaluating LLMs in Social Deduction Games with Human-Aligned Strategies** *arXiv* [[paper](https://arxiv.org/abs/2510.11389)] `#communication` `#multi-agent` `#self-improvement`
- [2025/09] **Meta-Policy Reflexion: Reusable Reflective Memory and Rule Admissibility for Resource-Efficient LLM Agent** *arXiv* [[paper](https://arxiv.org/abs/2509.03990)] `#text-adventure` `#planning` `#multi-agent` `#self-improvement`
- [2025/09] **PillagerBench: Benchmarking LLM-Based Agents in Competitive Minecraft Team Environments** *2025 IEEE Conference on Games (CoG) 2025* [[paper](https://arxiv.org/abs/2509.06235)] `#minecraft` `#multi-agent` `#self-improvement`
- [2025/09] **Code Driven Planning with Domain-Adaptive Critic** *arXiv* [[paper](https://arxiv.org/abs/2509.19077)] `#text-adventure` `#planning` `#self-improvement`
- [2025/09] **Reward Is Enough: LLMs Are In-Context Reinforcement Learners** *ICLR 2026 Poster* [[paper](https://openreview.net/forum?id=keCXNHOe4W)] `#text-adventure` `#training` `#self-improvement`
- [2025/08] **Learning Game-Playing Agents with Generative Code Optimization** *arXiv* [[paper](https://arxiv.org/abs/2508.19506)] `#action` `#training` `#self-improvement`
- [2025/08] **SC2Arena and StarEvolve: Benchmark and Self-Improvement Framework for LLMs in Complex Decision-Making Tasks** *arXiv* [[paper](https://arxiv.org/abs/2508.10428)] `#competition` `#planning` `#training` `#self-improvement`
- [2025/06] **Automated Skill Discovery for Language Agents through Exploration and Iterative Feedback** *arXiv* [[paper](https://arxiv.org/abs/2506.04287)] `#crafter` `#self-improvement`
- [2025/06] **OmniReflect: Discovering Transferable Constitutions for LLM agents via Neuro-Symbolic Reflections** *arXiv* [[paper](https://arxiv.org/abs/2506.17449)] `#text-adventure` `#planning` `#training` `#self-improvement`
- [2025/05] **SEEA-R1: Tree-Structured Reinforcement Fine-Tuning for Self-Evolving Embodied Agents** *NeurIPS 2025 poster* [[paper](https://openreview.net/forum?id=dAwKePZvcN)] `#text-adventure` `#planning` `#training` `#self-improvement`
- [2025/02] **TextGames: Learning to Self-Play Text-Based Puzzle Games via Language Model Reasoning.** *arXiv* [[paper](https://arxiv.org/pdf/2502.18431)] `#text-adventure` `#self-improvement`
- [2024/12] **Richelieu: Self-Evolving LLM-Based Agents for AI Diplomacy** *NeurIPS 2024* [[paper](https://openreview.net/pdf?id=7Jb4NJS8Yk)][[code](https://sites.google.com/view/richelieu-diplomacy)] `#communication` `#self-improvement`
- [2024/09] **Better than Your Teacher: LLM Agents that learn from Privileged AI Feedback** *ICLR 2025 Poster* [[paper](https://openreview.net/forum?id=st7XqFgbAH)] `#text-adventure` `#planning` `#training` `#self-improvement`
- [2024/06] **Watch Every Step! LLM Agent Learning via Iterative Step-Level Process Refinement** *EMNLP 2024* [[paper](https://arxiv.org/pdf/2406.11176)][[code](https://github.com/WeiminXiong/IPR)] `#text-adventure` `#self-improvement`
- [2024/05] **Richelieu: Self-Evolving LLM-Based Agents for AI Diplomacy** *NeurIPS 2024 poster* [[paper](https://openreview.net/forum?id=7Jb4NJS8Yk)] `#communication` `#planning` `#multi-agent` `#self-improvement`
- [2024/04] **ReAct Meets ActRe: When Language Agents Enjoy Training Data Autonomy** *arXiv* [[paper](https://arxiv.org/pdf/2403.14589)] `#text-adventure` `#planning` `#training` `#self-improvement`
- [2024/04] **Self-playing Adversarial Language Game Enhances LLM Reasoning** *NeurIPS 2024* [[paper](https://arxiv.org/pdf/2404.10642)][[code](https://arxiv.org/pdf/2404.10642)] `#communication` `#training` `#self-improvement`
- [2024/03] **Trial and Error: Exploration-Based Trajectory Optimization for LLM Agents** *ACL 2024* [[paper](https://arxiv.org/pdf/2403.02502)][[code](https://github.com/Yifan-Song793/ETO)] `#text-adventure` `#training` `#self-improvement`
- [2024/03] **ReAct Meets ActRe: Autonomous Annotation of Agent Trajectories for Contrastive Self-Training** *COLM* [[paper](https://openreview.net/forum?id=0VLBwQGWpA)] `#text-adventure` `#planning` `#training` `#self-improvement`
- [2024/03] **StateFlow: Enhancing LLM Task-Solving through State-Driven Workflows** *COLM* [[paper](https://openreview.net/forum?id=3nTbuygoop)] `#text-adventure` `#planning` `#self-improvement`
- [2024/02] **Soft Self-Consistency Improves Language Model Agents** *arXiv* [[paper](https://arxiv.org/abs/2402.13212.pdf)][[code](https://github.com/HanNight/soft_self_consistency)] `#text-adventure` `#self-improvement`
- [2024/02] **Empowering Large Language Model Agents through Action Learning** *COLM* [[paper](https://arxiv.org/abs/2402.15809)][[code](https://github.com/zhao-ht/LearnAct)] `#text-adventure` `#planning` `#self-improvement`
- [2023/10] **Lyfe Agents: Generative agents for low-cost real-time social interactions** *arXiv* [[paper](https://arxiv.org/abs/2310.02172.pdf)] `#sim-social` `#memory` `#multi-agent` `#self-improvement`
- [2023/03] **Reflexion: Language Agents with Verbal Reinforcement Learning** *NeurIPS 2023* [[paper](https://proceedings.neurips.cc/paper_files/paper/2023/hash/1b44b878bb782e6954cd888628510e90-Abstract-Conference.html)][[code](https://github.com/noahshinn/reflexion)] `#text-adventure` `#training` `#self-improvement`

## prompting

- [2026/05] **GAMBIT: A Three-Mode Benchmark for Adversarial Robustness in Multi-Agent LLM Collectives** *arXiv* [[paper](https://arxiv.org/abs/2605.09027)] `#competition` `#multi-agent` `#prompting`
- [2026/04] **DORA Explorer: Improving the Exploration Ability of LLMs Without Training** *arXiv* [[paper](https://arxiv.org/abs/2604.17244)] `#text-adventure` `#planning` `#prompting`
- [2026/03] **GTO Wizard Benchmark** *arXiv* [[paper](https://arxiv.org/abs/2603.23660)] `#competition` `#planning` `#multi-agent` `#prompting`
- [2026/03] **Reward Prediction with Factorized World States** *arXiv* [[paper](https://arxiv.org/abs/2603.09400)] `#text-adventure` `#planning` `#prompting`
- [2026/02] **World Models for Policy Refinement in StarCraft II** *arXiv* [[paper](https://arxiv.org/abs/2602.14857)] `#competition` `#world-model` `#prompting`
- [2026/02] **To Move or Not to Move: Constraint-based Planning Enables Zero-Shot Generalization for Interactive Navigation** *arXiv* [[paper](https://arxiv.org/abs/2602.20055)] `#sim-embodied` `#planning` `#prompting` `#vlm`
- [2026/01] **Beyond Entangled Planning: Task-Decoupled Planning for Long-Horizon Agents** *arXiv* [[paper](https://arxiv.org/abs/2601.07577)] `#text-adventure` `#planning` `#prompting`
- [2025/11] **SkillGen: Learning Domain Skills for In-Context Sequential Decision Making** *arXiv* [[paper](https://arxiv.org/abs/2511.14670)] `#text-adventure` `#prompting`
- [2025/11] **MADRA: Multi-Agent Debate for Risk-Aware Embodied Planning** *arXiv* [[paper](https://arxiv.org/abs/2511.21460)] `#sim-embodied` `#planning` `#multi-agent` `#prompting`
- [2025/10] **Constrained Natural Language Action Planning for Resilient Embodied Systems** *arXiv* [[paper](https://arxiv.org/abs/2510.06357)] `#text-adventure` `#planning` `#prompting`
- [2025/09] **World Model Implanting for Test-time Adaptation of Embodied Agents** *ICML 2025 poster* [[paper](https://arxiv.org/abs/2509.03956)] `#text-adventure` `#memory` `#world-model` `#prompting`
- [2025/09] **Test-Time Mixture of World Models for Embodied Agents in Dynamic Environments** *ICLR 2026 Poster* [[paper](https://openreview.net/forum?id=LQD1MrnbxH)] `#text-adventure` `#prompting`
- [2025/07] **Strategy Adaptation in Large Language Model Werewolf Agents** *arXiv* [[paper](https://arxiv.org/abs/2507.12732)] `#communication` `#prompting`
- [2025/07] **GAMEBoT: Transparent Assessment of LLM Reasoning in Games** *ACL 2025 Main* [[paper](https://aclanthology.org/2025.acl-long.378/)][[code](https://github.com/Visual-AI/GAMEBoT)] `#benchmark` `#planning` `#prompting`
- [2025/05] **Training LLM-Based Agents with Synthetic Self-Reflected Trajectories and Partial Masking** *arXiv* [[paper](https://arxiv.org/abs/2505.20023)] `#text-adventure` `#prompting`
- [2025/05] **ActiveVOO: Value of Observation Guided Active Knowledge Acquisition for Open-World Embodied Lifted Regression Planning** *NeurIPS 2025 poster* [[paper](https://openreview.net/forum?id=cZVYswQQMt)] `#text-adventure` `#planning` `#prompting` `#vlm`
- [2025/05] **WALL-E: World Alignment by NeuroSymbolic Learning improves World Model-based LLM Agents** *NeurIPS 2025 poster* [[paper](https://openreview.net/forum?id=DorAT49sxj)] `#minecraft` `#planning` `#world-model` `#prompting`
- [2025/04] **WALL-E 2.0: World Alignment by NeuroSymbolic Learning Improves World Model-based LLM Agents** *arXiv* [[paper](https://arxiv.org/abs/2504.15785)][[code](https://github.com/elated-sawyer/WALL-E)] `#minecraft` `#planning` `#world-model` `#prompting`
- [2024/08] **Optimus-1: Hybrid Multimodal Memory Empowered Agents Excel in Long-horizon Tasks** *NeurIPS 2024* [[paper](https://arxiv.org/abs/2408.03615)][[code](https://github.com/JiuTian-VL/Optimus-1)] `#minecraft` `#planning` `#memory` `#prompting`
- [2024/05] **THREAD: Thinking Deeper with Recursive Spawning** *NAACL 2024* [[paper](https://arxiv.org/pdf/2405.17402)] `#text-adventure` `#prompting`
- [2024/03] **Playing NetHack with LLMs: Potential & Limitations as Zero-Shot Agents** *2024 IEEE Conference on Games (CoG) 2024* [[paper](https://arxiv.org/pdf/2403.00690.pdf)][[code](https://github.com/CommanderCero/NetPlay)] `#video-adventure` `#planning` `#prompting`
- [2023/12] **Deciphering Digital Detectives: Understanding LLM Behaviors and Capabilities in Multi-Agent Mystery Games** *ACL 2023* [[paper](https://arxiv.org/pdf/2312.00746.pdf)] `#communication` `#multi-agent` `#prompting`
- [2023/10] **Evaluating Multi-agent Coordination Abilities in Large Language Models** *NAACL 2023* [[paper](https://arxiv.org/abs/2310.03903.pdf)] `#cooperation` `#planning` `#multi-agent` `#prompting`
- [2023/09] **Suspicion-Agent: Playing Imperfect Information Games with Theory of Mind Aware GPT-4** *COLM 2024* [[paper](https://arxiv.org/abs/2309.17277.pdf)] `#competition` `#planning` `#memory` `#prompting`
- [2023/09] **MindAgent: Emergent Gaming Interaction** *NAACL 2023* [[paper](http://https://arxiv.org/abs/2309.09971)] `#cooperation` `#planning` `#multi-agent` `#prompting`
- [2023/07] **S3: Social-network Simulation System with Large Language Model-Empowered Agents** *arXiv* [[paper](https://arxiv.org/pdf/2307.14984)] `#sim-social` `#prompting`
- [2023/02] **Describe, Explain, Plan and Select: Interactive Planning with Large Language Models Enables Open-World Multi-Task Agents** *NeurIPS 2023* [[paper](https://arxiv.org/abs/2302.01560.pdf)][[code](https://github.com/CraftJarvis/MC-Planner)] `#minecraft` `#planning` `#prompting`
- [2022/12] **LLM-Planner: Few-Shot Grounded Planning for Embodied Agents with Large Language Models** *ICCV 2023* [[paper](https://openaccess.thecvf.com/content/ICCV2023/html/Song_LLM-Planner_Few-Shot_Grounded_Planning_for_Embodied_Agents_with_Large_Language_ICCV_2023_paper.html)] `#sim-embodied` `#planning` `#prompting`

## role-play

- [2026/05] **PAVE: A Cognitive Architecture for Legitimate Violation in Generative Agent Societies** *arXiv* [[paper](https://arxiv.org/abs/2605.19351)] `#sim-social` `#role-play`
- [2026/04] **Restoring Heterogeneity in LLM-based Social Simulation: An Audience Segmentation Approach** *arXiv* [[paper](https://arxiv.org/abs/2604.06663)] `#sim-social` `#role-play`
- [2026/03] **Enhancing Consistency of Werewolf AI through Dialogue Summarization and Persona Information** *arXiv* [[paper](https://arxiv.org/abs/2603.07111)] `#communication` `#role-play`
- [2025/10] **ROBOPSY PL[AI]: Using Role-Play to Investigate how LLMs Present Collective Memory** *arXiv* [[paper](https://arxiv.org/abs/2510.09874)] `#role-play`
- [2025/09] **Implicit Behavioral Alignment of Language Agents in High-Stakes Crowd Simulations** *EMNLP 2025* [[paper](https://arxiv.org/abs/2509.16457)] `#sim-social` `#role-play`
- [2025/07] **LLM Economist: Large Population Models and Mechanism Design in Multi-Agent Generative Simulacra** *arXiv* [[paper](https://arxiv.org/abs/2507.15815)][[code](https://github.com/sethkarten/LLM-Economist)] `#sim-social` `#multi-agent` `#training` `#role-play`
- [2025/07] **Validating Generative Agent-Based Models of Social Norm Enforcement: From Replication to Novel Predictions** *Annual Meeting of the Cognitive Science Society 2025* [[paper](https://arxiv.org/abs/2507.22049)] `#sim-social` `#role-play`
- [2025/05] **EcoLANG: Efficient and Effective Agent Communication Language Induction for Social Simulation** *EMNLP 2025* [[paper](https://arxiv.org/abs/2505.06904)] `#sim-social` `#role-play`
- [2023/10] **SOTOPIA: Interactive Evaluation for Social Intelligence in Language Agents** *ICLR 2023* [[paper](https://arxiv.org/abs/2310.11667.pdf)][[code](https://github.com/sotopia-lab/sotopia)] `#sim-social` `#role-play`

## vlm

- [2026/05] **Odysseus: Scaling VLMs to 100+ Turn Decision-Making in Games via Reinforcement Learning** *arXiv* [[paper](https://arxiv.org/abs/2605.00347)] `#action` `#training` `#vlm`
- [2026/05] **PRISM: Perception Reasoning Interleaved for Sequential Decision Making** *arXiv* [[paper](https://arxiv.org/abs/2605.05407)] `#text-adventure` `#vlm`
- [2026/05] **Brain alignment of reasoning and action representations from vision-language and action models during naturalistic gameplay** *arXiv* [[paper](https://arxiv.org/abs/2605.19352)] `#action` `#planning` `#training` `#vlm`
- [2026/05] **GROW: Aligning GRPO with State-Action Modeling for Open-World VLM Agents** *arXiv* [[paper](https://arxiv.org/abs/2605.20246)] `#minecraft` `#training` `#vlm`
- [2026/04] **GameWorld: Towards Standardized and Verifiable Evaluation of Multimodal Game Agents** *arXiv* [[paper](https://arxiv.org/abs/2604.07429)] `#planning` `#vlm`
- [2026/04] **PokeGym: A Visually-Driven Long-Horizon Benchmark for Vision-Language Models** *arXiv* [[paper](https://arxiv.org/abs/2604.08340)] `#action` `#planning` `#vlm`
- [2026/04] **Gated Coordination for Efficient Multi-Agent Collaboration in Minecraft Game** *arXiv* [[paper](https://arxiv.org/abs/2604.18975)] `#minecraft` `#memory` `#multi-agent` `#vlm`
- [2026/03] **BLOCK: An Open-Source Bi-Stage MLLM Character-to-Skin Pipeline for Minecraft** *arXiv* [[paper](https://arxiv.org/abs/2603.03964)] `#minecraft` `#vlm`
- [2026/03] **See, Symbolize, Act: Grounding VLMs with Spatial Representations for Better Gameplay** *arXiv* [[paper](https://arxiv.org/abs/2603.11601)] `#action` `#vlm`
- [2026/02] **VLM-Guided Experience Replay** *arXiv* [[paper](https://arxiv.org/abs/2602.01915)] `#planning` `#training` `#vlm`
- [2026/02] **To Move or Not to Move: Constraint-based Planning Enables Zero-Shot Generalization for Interactive Navigation** *arXiv* [[paper](https://arxiv.org/abs/2602.20055)] `#sim-embodied` `#planning` `#prompting` `#vlm`
- [2025/10] **GenQuest: An LLM-based Text Adventure Game for Language Learners** *arXiv* [[paper](https://arxiv.org/abs/2510.04498)] `#text-adventure` `#vlm` `#generation`
- [2025/10] **Multimodal Safety Evaluation in Generative Agent Social Simulations** *arXiv* [[paper](https://arxiv.org/abs/2510.07709)] `#sim-social` `#planning` `#vlm`
- [2025/09] **Exploration with Foundation Models: Capabilities, Limitations, and Hybrid Approaches** *arXiv* [[paper](https://arxiv.org/abs/2509.19924)] `#action` `#training` `#vlm`
- [2025/09] **Natural Language PDDL (NL-PDDL) for Open-world Goal-oriented Commonsense Regression Planning in Embodied AI** *ICLR 2026 Poster* [[paper](https://openreview.net/forum?id=kWCNhRdcDI)] `#text-adventure` `#planning` `#vlm`
- [2025/08] **Enhancing Vision-Language Model Training with Reinforcement Learning in Synthetic Worlds for Real-World Success** *Proceedings of the 25th International Conference on Autonomous Agents and Multiagent Systems 2025* [[paper](https://arxiv.org/abs/2508.04280)] `#text-adventure` `#planning` `#training` `#vlm`
- [2025/07] **VoyagerVision: Investigating the Role of Multi-modal Information for Open-ended Learning Systems** *arXiv* [[paper](https://arxiv.org/abs/2507.00079)] `#minecraft` `#vlm`
- [2025/06] **GuessBench: Sensemaking Multimodal Creativity in the Wild** *arXiv* [[paper](https://arxiv.org/abs/2506.00814)] `#minecraft` `#training` `#vlm`
- [2025/05] **Don’t Just Follow MLLM Plans: Robust and Efficient Planning for Open-World Agents** *arXiv* [[paper](https://arxiv.org/abs/2505.24157)] `#minecraft` `#planning` `#vlm`
- [2025/05] **ActiveVOO: Value of Observation Guided Active Knowledge Acquisition for Open-World Embodied Lifted Regression Planning** *NeurIPS 2025 poster* [[paper](https://openreview.net/forum?id=cZVYswQQMt)] `#text-adventure` `#planning` `#prompting` `#vlm`
- [2025/04] **LLM-PySC2: Starcraft II learning environment for Large Language Models** *NeurIPS 2025 poster* [[paper](https://openreview.net/forum?id=Xr73jEYG29)] `#competition` `#planning` `#multi-agent` `#vlm`
- [2025/03] **GFlowVLM: Enhancing Multi-step Reasoning in Vision-Language Models with Generative Flow Networks** *CVPR 2025* [[paper](https://arxiv.org/abs/2503.06514)] `#text-adventure` `#planning` `#training` `#vlm`
- [2025/03] **Cultivating Game Sense for Yourself: Making VLMs Gaming Experts** *arXiv* [[paper](https://arxiv.org/abs/2503.21263)] `#vlm`
- [2025/02] **Optimus-2: Multimodal World Model for Open-World Minecraft Agents** *CVPR 2025* [[paper](https://arxiv.org/pdf/2502.19902)][[code](https://github.com/JiuTian-VL/Optimus-2)] `#minecraft` `#planning` `#world-model` `#vlm`
- [2024/12] **TeamCraft: A Benchmark for Multi-Modal Multi-Agent Systems in Minecraft** *arXiv* [[paper](https://arxiv.org/abs/2412.05255)][[code](https://github.com/teamcraft-bench/teamcraft)] `#minecraft` `#multi-agent` `#training` `#vlm`
- [2024/12] **Fine-tuning large vision-language models as decision-making agents via reinforcement learning** *NeurIPS 2024* [[paper](https://proceedings.neurips.cc/paper_files/paper/2024/file/c848b7d3adc08fcd0bf1df3101ba6728-Paper-Conference.pdf)][[code](https://github.com/RL4VLM/RL4VLM)] `#text-adventure` `#training` `#vlm`
- [2024/09] **BadRobot: Jailbreaking Embodied LLM Agents in the Physical World** *ICLR 2025 Poster* [[paper](https://openreview.net/forum?id=ei3qCntB66)] `#sim-embodied` `#planning` `#vlm`
- [2024/09] **GameGen-X: Interactive Open-world Game Video Generation** *ICLR 2025 Poster* [[paper](https://openreview.net/forum?id=8VG8tpPZhe)][[code](https://github.com/GameGen-X/GameGen-X)] `#sim-embodied` `#vlm`
- [2024/09] **BALROG: Benchmarking Agentic LLM and VLM Reasoning On Games** *ICLR 2025 Poster* [[paper](https://openreview.net/forum?id=fp6t3F669F)] `#action` `#planning` `#training` `#vlm`
- [2024/07] **OmniJARVIS: Omni-Modal Open-World Agents in Minecraft** *NeurIPS 2024* [[paper](https://arxiv.org/abs/2407.00114)][[code](https://github.com/CraftJarvis/OmniJARVIS)] `#minecraft` `#training` `#vlm`
- [2024/07] **Baba Is AI: Break the Rules to Beat the Benchmark** *ICML 2024* [[paper](https://arxiv.org/pdf/2407.13729)] `#action` `#vlm`
- [2024/04] **World Models with Hints of Large Language Models for Goal Achieving** *NAACL 2024* [[paper](https://arxiv.org/pdf/2406.07381)] `#crafter` `#training` `#vlm`
- [2024/03] **MineLand: Simulating Large-Scale Multi-Agent Interactions with Limited Multimodal Senses and Physical Needs** *arXiv* [[paper](https://arxiv.org/abs/2403.19267)][[code](https://github.com/cocacola-lab/MineLand)] `#minecraft` `#multi-agent` `#vlm`
- [2024/03] **Hierarchical Auto-Organizing System for Open-Ended Multi-Agent Navigation (HAS)** *ICLR 2024 Workshop* [[paper](https://arxiv.org/abs/2403.08282)] `#minecraft` `#planning` `#multi-agent` `#vlm`
- [2023/12] **MP5: A Multi-modal Open-ended Embodied System in Minecraft via Active Perception** *CVPR 2024* [[paper](https://arxiv.org/pdf/2312.07472.pdf)][[code](https://github.com/IranQin/MP5)] `#minecraft` `#planning` `#vlm`
- [2023/10] **Octopus: Embodied Vision-Language Programmer from Environmental Feedback** *ECCV 2023* [[paper](https://arxiv.org/abs/2310.08588.pdf)][[code](https://github.com/dongyh20/Octopus)] `#sim-embodied` `#planning` `#training` `#vlm`
- [2023/10] **Steve-Eye: Equipping LLM-based Embodied Agents with Visual Perception in Open Worlds** *ICLR 2024* [[paper](https://openreview.net/forum?id=NltzxpG0nz)] `#minecraft` `#vlm`

## generation

- [2026/04] **From World-Gen to Quest-Line: A Dependency-Driven Prompt Pipeline for Coherent RPG Generation** *arXiv* [[paper](https://arxiv.org/abs/2604.25482)] `#planning` `#generation`
- [2026/01] **SNAP: A Plan-Driven Framework for Controllable Interactive Narrative Generation** *arXiv* [[paper](https://arxiv.org/abs/2601.11529)] `#planning` `#generation`
- [2025/12] **Robust Agents in Open-Ended Worlds** *arXiv* [[paper](https://arxiv.org/abs/2512.08139)] `#action` `#multi-agent` `#training` `#generation`
- [2025/10] **GenQuest: An LLM-based Text Adventure Game for Language Learners** *arXiv* [[paper](https://arxiv.org/abs/2510.04498)] `#text-adventure` `#vlm` `#generation`
- [2025/08] **All Stories Are One Story: Emotional Arc Guided Procedural Game Level Generation** *arXiv* [[paper](https://arxiv.org/abs/2508.02132)] `#generation`
- [2025/05] **STORY2GAME: Generating (Almost) Everything in an Interactive Fiction Game** *arXiv* [[paper](https://arxiv.org/abs/2505.03547)] `#text-adventure` `#generation`
- [2025/04] **BookWorld: From Novels to Interactive Agent Societies for Creative Story Generation** *arXiv* [[paper](https://arxiv.org/abs/2504.14538)] `#sim-social` `#multi-agent` `#generation`
- [2025/03] **Word2Minecraft: Generating 3D Game Levels through Large Language Models** *arXiv* [[paper](https://arxiv.org/abs/2503.16536)][[code](https://github.com/JMZ-kk/Word2Minecraft/tree/word2mc_v0)] `#minecraft` `#generation`
- [2024/09] **Agents' Room:  Narrative Generation through Multi-step Collaboration** *ICLR 2025 Poster* [[paper](https://openreview.net/forum?id=HfWcFs7XLR)] `#generation`
- [2024/07] **What if Red Can Talk? Dynamic Dialogue Generation Using Large Language Models.** *arXiv* [[paper](https://arxiv.org/pdf/2407.20382)] `#generation`
- [2023/10] **Language as reality: a co-creative storytelling game experience in 1001 nights using generative AI.** *AAAI 2023* [[paper](https://ojs.aaai.org/index.php/AIIDE/article/view/27539)] `#generation`


## Citation
If you find this repository useful, please cite our paper. We will periodically check for new papers citing the survey and update this list and the survey if relevant.
```
@misc{hu2024survey,
      title={A Survey on Large Language Model-Based Game Agents},
      author={Sihao Hu and Tiansheng Huang and Fatih Ilhan and Selim Tekin and Gaowen Liu and Ramana Kompella and Ling Liu},
      year={2024},
      eprint={2404.02039},
      archivePrefix={arXiv},
      primaryClass={cs.AI}
}
```
