# A Survey on Large Language Model-Based Game Agents

<div align="center">

![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-green)
[![Visits](https://hits.sh/github.com/git-disl/awesome-LLM-game-agent-papers.svg?style=flat-square&label=visits)](https://hits.sh/github.com/git-disl/awesome-LLM-game-agent-papers/)
![Stars](https://img.shields.io/github/stars/git-disl/awesome-LLM-game-agent-papers?style=flat-square)
![Forks](https://img.shields.io/github/forks/git-disl/awesome-LLM-game-agent-papers?style=flat-square)
<a href='https://arxiv.org/pdf/2404.02039'><img src='https://img.shields.io/badge/arXiv-2404.02039-b31b1b.svg'></a>

</div>

🔥 **Must-read papers for LLM-based Game agents.**

💫 **We continuously update the GitHub list on a weekly basis.** (last update: 2025/09/13)

📝 **If you discover any papers that are suitable but not yet included, please open an issue or submit a pull request.**

📘 **Our survey paper is a living survey. The third version is scheduled for release in one month.**

**Paper update history:**  
- Version 1: 02 Apr 2024 
- Version 2: 30 Mar 2025  

## Content

- [A Survey on Large Language Model-Based Game Agents](#a-survey-on-large-language-model-based-game-agents)
  - [Content](#content)
    - [Adventure Games](#adventure-games)
      - [Text Adventure Games](#text-adventure-games)
      - [Video Adventure Games](#video-adventure-games)
    - [Crafting \& Exploration Games](#crafting--exploration-games)
      - [MineCraft](#minecraft)
      - [Crafter](#crafter)
    - [Simulation Games](#simulation-games)
      - [Human/social Simulation](#humansocial-simulation)
      - [Embodied Simulation](#embodied-simulation)
      - [Other Simulation](#other-simulation)
    - [Competition Games](#competition-games)
    - [Cooperation Games](#cooperation-games)
    - [Communication (Conversational) Games](#communication-conversational-games)
    - [Action Games](#action-games)
    - [Dialogue \& Story \& Game Generation](#dialogue--story--game-generation)
    - [Benchmark](#benchmark)
  - [Citation](#citation)
  - [Contact](#contact)


### Adventure Games

#### Text Adventure Games
- [2019/09] **Interactive Fiction Games: A Colossal Adventure** *AAAI 2020* [[paper](https://ojs.aaai.org/index.php/AAAI/article/view/6297)] [[code]](https://github.com/Microsoft/jericho)
- [2020/10] **ALFWorld: Aligning Text and Embodied Environments for Interactive Learning** *ICLR 2021* [[paper](https://arxiv.org/pdf/2010.03768.pdf)][[code](https://github.com/alfworld/alfworld)]
- [2022/03] **ScienceWorld: Is your Agent Smarter than a 5th Grader?** *EMNLP 2022* [[paper](https://arxiv.org/abs/2203.07540.pdf)] [[code](https://github.com/allenai/ScienceWorld)]
- [2022/10] **ReAct: Synergizing Reasoning and Acting in Language Models** *ICLR 2023* [[paper](https://arxiv.org/abs/2210.03629)] [[code](https://github.com/ysymyth/ReAct)]
- [2023/03] **Reflexion: Language Agents with Verbal Reinforcement Learning** *NeurIPS 2023* [[paper](https://proceedings.neurips.cc/paper_files/paper/2023/hash/1b44b878bb782e6954cd888628510e90-Abstract-Conference.html)] [[code](https://github.com/noahshinn/reflexion)]
- [2023/04] **Can Large Language Models Play Text Games Well? Current State-of-the-Art and Open Questions** *arXiv* [[paper](https://arxiv.org/pdf/2304.02868.pdf)]
- [2023/05] **SwiftSage: A Generative Agent with Fast and Slow Thinking for Complex Interactive Tasks** *NeurIPS 2023* [[paper](https://proceedings.neurips.cc/paper_files/paper/2023/hash/4b0eea69deea512c9e2c469187643dc2-Abstract-Conference.html)] [[code](https://github.com/yuchenlin/SwiftSage)]
- [2023/10] **FireAct: Toward Language Agent Fine-tuning** *arXiv* [[paper](https://arxiv.org/pdf/2310.05915)][[code](https://github.com/anchen1011/FireAct)]
- [2023/10] **Language Agent Tree Search Unifies Reasoning Acting and Planning in Language Models** *ICML 2024* [[paper](https://arxiv.org/pdf/2310.04406)][[code](https://github.com/lapisrocks/LanguageAgentTreeSearch)]
- [2023/11] **ADaPT: As-Needed Decomposition and Planning with Language Models** *arXiv* [[paper](https://arxiv.org/abs/2311.05772)][[code](https://github.com/archiki/ADaPT)]
- [2024/02] **Soft Self-Consistency Improves Language Model Agents** *arXiv* [[paper](https://arxiv.org/abs/2402.13212.pdf)][[code](https://github.com/HanNight/soft_self_consistency)]
- [2024/02] **Empowering Large Language Model Agents through Action Learning** *arXiv* [[paper]](https://arxiv.org/abs/2402.15809)[[code](https://github.com/zhao-ht/LearnAct)]
- [2024/03] **KnowAgent: Knowledge-Augmented Planning for LLM-Based Agents** *arXiv* [[paper](https://arxiv.org/abs/2403.03101.pdf)][[code](https://github.com/zjunlp/KnowAgent)]
- [2024/03] **Language Guided Exploration for RL Agents in Text Environments** *arXiv* [[paper](https://arxiv.org/abs/2403.03141.pdf)][[code](https://github.com/hitzkrieg/drrn-scienceworld-clone)]
- [2024/03] **Trial and Error: Exploration-Based Trajectory Optimization for LLM Agents** *ACL 2024* [[paper](https://arxiv.org/pdf/2403.02502)][[code](https://github.com/Yifan-Song793/ETO)]
- [2024/04] **Learning From Failure: Integrating Negative Examples When Fine-tuning Large Language Models as Agent** *arXiv*[[paper](https://arxiv.org/pdf/2402.11651)][[code](https://github.com/Reason-Wang/NAT)]
- [2024/04] **ReAct Meets ActRe: When Language Agents Enjoy Training Data Autonomy** [[paper](https://arxiv.org/pdf/2403.14589)]
- [2024/05] **Agent Planning with World Knowledge Model** *arXiv* [[paper](https://arxiv.org/pdf/2405.14205)][[code](https://github.com/zjunlp/WKM)]
- [2024/05] **THREAD: Thinking Deeper with Recursive Spawning** *arXiv* [[paper](https://arxiv.org/pdf/2405.17402)]
- [2024/06] **Watch Every Step! LLM Agent Learning via Iterative Step-Level Process Refinement** *arXiv* [[paper](https://arxiv.org/pdf/2406.11176)][[code](https://github.com/WeiminXiong/IPR)]
- [2024/06] **STARLING: Self-supervised Training of Text-based Reinforcement Learning Agent with Large Language Models** *arXiv* [[paper](https://arxiv.org/pdf/2406.05872)][[code](https://github.com/IBM/starling-agent)]
- [2024/07] **AppWorld: A Controllable World of Apps and People for Benchmarking Interactive Coding Agents** *ACL 2024* [[paper](https://arxiv.org/abs/2407.18901)][[code](https://github.com/stonybrooknlp/appworld)]
- [2024/07] **Arigraph: Learning knowledge graph world models with episodic memory for llm agents** *arXiv* [[paper](https://arxiv.org/abs/2407.04363)]
- [2024/12] **Fine-tuning large vision-language models as decision-making agents via reinforcement learning** *NeurIPS 2024* [[paper](https://proceedings.neurips.cc/paper_files/paper/2024/file/c848b7d3adc08fcd0bf1df3101ba6728-Paper-Conference.pdf)[[code](https://github.com/RL4VLM/RL4VLM)]
- [2025/02] **TextGames: Learning to Self-Play Text-Based Puzzle Games via Language Model Reasoning.** *arXiv* [[paper](https://arxiv.org/pdf/2502.18431)]


#### Video Adventure Games

- [2023/09] **Motif: Intrinsic Motivation from Artificial Intelligence Feedback** *ICLR 2024* [[paper](https://arxiv.org/abs/2310.00166.pdf)] [[code]](https://github.com/facebookresearch/motif)
- [2024/03] **Cradle: Empowering Foundation Agents Towards General Computer Control** *arXiv* [[paper](https://arxiv.org/abs/2403.03186.pdf)][[code](https://github.com/BAAI-Agents/Cradle)]
- [2024/03] **Playing NetHack with LLMs: Potential & Limitations as Zero-Shot Agents** *arXiv* [[paper](https://arxiv.org/pdf/2403.00690.pdf)] [[code](https://github.com/CommanderCero/NetPlay)]

### Crafting \& Exploration Games

#### MineCraft

- [2023/02] **Describe, Explain, Plan and Select: Interactive Planning with Large Language Models Enables Open-World Multi-Task Agents** *NeurIPS 2023* [[paper]](https://arxiv.org/abs/2302.01560.pdf)[[code](https://github.com/CraftJarvis/MC-Planner)]
- [2023/03] **Plan4MC: Skill Reinforcement Learning and Planning for Open-World Minecraft Tasks** *FMDM@NeurIPS2023* [[paper]](https://arxiv.org/abs/2303.16563.pdf)[[code](https://github.com/PKU-RL/Plan4MC)]
- [2023/05] **Ghost in the Minecraft: Generally Capable Agents for Open-World Environments via Large Language Models with Text-based Knowledge and Memory** *arXiv* [[paper]](https://arxiv.org/abs/2305.17144.pdf)
- [2023/05] **VOYAGER: An Open-Ended Embodied Agent with Large Language Models** *FMDM@NeurIPS2023* [[paper]](https://arxiv.org/abs/2305.16291.pdf)[[code](https://github.com/MineDojo/Voyager)]
- [2023/10] **LLaMA Rider: Spurring Large Language Models to Explore the Open World** *arXiv* [[paper](https://arxiv.org/abs/2310.08922.pdf)][[code](https://github.com/PKU-RL/LLaMA-Rider)]
- [2023/10] **Steve-Eye: Equipping LLM-based Embodied Agents with Visual Perception in Open Worlds** *ICLR 2024* [[paper]](https://openreview.net/forum?id=NltzxpG0nz)
- [2023/11] **JARVIS-1: Open-world Multi-task Agents with Memory-Augmented Multimodal Language Models** *arXiv* [[paper]](https://arxiv.org/abs/2311.05997.pdf)[[code](https://github.com/CraftJarvis/JARVIS-1)]
- [2023/11] **See and Think: Embodied Agent in Virtual Environment** *arXiv* [[paper](https://arxiv.org/abs/2311.15209.pdf)][[code](https://github.com/rese1f/STEVE)]
- [2023/12] **MP5: A Multi-modal Open-ended Embodied System in Minecraft via Active Perception** *CVPR 2024* [[paper](https://arxiv.org/pdf/2312.07472.pdf)][[code](https://github.com/IranQin/MP5)]
- [2023/12] **Auto MC-Reward: Automated Dense Reward Design with Large Language Models for Minecraft** *arXiv* [[paper]](https://arxiv.org/abs/2312.09238.pdf)
- [2023/12] **Creative Agents: Empowering Agents with Imagination for Creative Tasks** *arXiv* [[paper]](https://arxiv.org/abs/2312.02519.pdf)[[code](https://github.com/PKU-RL/Creative-Agents)]
- [2024/02] **RL-GPT: Integrating Reinforcement Learning and Code-as-policy** *arXiv* [[paper]](https://arxiv.org/abs/2402.19299.pdf)
- [2024/03] **MineDreamer: Learning to Follow Instructions via Chain-of-Imagination for Simulated-World Control** *arXiv* [[paper](https://arxiv.org/abs/2403.12037.pdf)][[code](https://github.com/Zhoues/MineDreamer)]
- [2024/07] **Odyssey: Empowering Agents with Open-World Skills.** *arXiv* [[paper](https://arxiv.org/abs/2407.15325)][[code](https://github.com/zju-vipa/Odyssey)]


#### Crafter

- [2023/02] **Guiding Pretraining in Reinforcement Learning with Large Language Models** *ICML 2023* [[paper](https://arxiv.org/abs/2302.06692)]
- [2023/05] **SPRING: Studying Papers and Reasoning to play Games** *NeurIPS 2023* [[paper](https://proceedings.neurips.cc/paper_files/paper/2023/hash/46c2a9a6f2b2be68682013eb1173c801-Abstract-Conference.html)]
- [2023/06] **OMNI: Open-endedness via Models of human Notions of Interestingness** *arXiv* [[paper](https://arxiv.org/abs/2306.01711.pdf)][[code](https://github.com/jennyzzt/omni)]
- [2023/09] **AdaRefiner: Refining Decisions of Language Models with Adaptive Feedback** *arXiv* [[paper](https://arxiv.org/pdf/2309.17176.pdf)]
- [2024/03] **EnvGen: Generating and Adapting Environments via LLMs for Training Embodied Agents** *arXiv* [[paper](https://arxiv.org/abs/2403.12014.pdf)]
- [2024/04] **AgentKit: Flow Engineering with Graphs, not Coding** *arXiv* [[paper](https://arxiv.org/pdf/2404.11483)][[code](https://github.com/holmeswww/AgentKit)]
- [2024/04] **World Models with Hints of Large Language Models for Goal Achieving** *arXiv* [[paper](https://arxiv.org/pdf/2406.07381)]
- [2024/07] **Enhancing Agent Learning through World Dynamics Modeling** *arXiv* [[paper](https://arxiv.org/pdf/2407.17695)]
- [2024/10] **Mars: Situated Inductive Reasoning in an Open-World Environment** *NeurIPS 2024* [[paper](https://arxiv.org/pdf/2410.08126)]


### Simulation Games

#### Human/social Simulation

- [2023/04] **Generative Agents: Interactive Simulacra of Human Behavior** *UIST 2023* [[paper](https://dl.acm.org/doi/pdf/10.1145/3586183.3606763)][[code](https://github.com/joonspk-research/generative_agents)]
- [2023/07] **S3: Social-network Simulation System with Large Language Model-Empowered Agents** *arXiv* [[paper](https://arxiv.org/pdf/2307.14984)]
- [2023/08] **AgentSims: An Open-Source Sandbox for Large Language Model Evaluation** *arXiv* [[paper](https://arxiv.org/abs/2308.04026.pdf)]
- [2023/10] **Humanoid Agents: Platform for Simulating Human-like Generative Agents** *arXiv* [[paper]](https://arxiv.org/abs/2310.05418.pdf)
- [2023/10] **Lyfe Agents: Generative agents for low-cost real-time social interactions** *arXiv* [[paper](https://arxiv.org/abs/2310.02172.pdf)]
- [2023/10] **SOTOPIA: Interactive Evaluation for Social Intelligence in Language Agents** *arXiv* [[paper](https://arxiv.org/abs/2310.11667.pdf)][[code](https://github.com/sotopia-lab/sotopia)]
- [2024/03] **SOTOPIA-$\pi$: Interactive Learning of Socially Intelligent Language Agents** *arXiv* [[paper](https://arxiv.org/pdf/2403.08715.pdf)][[code](https://github.com/sotopia-lab/sotopia-pi)]
- [2024/05] **Agent hospital: A simulacrum of hospital with evolvable medical agents**  *arXiv* [[paper](https://arxiv.org/abs/2405.02957)]
- [2024/06] **Artificial Leviathan: Exploring Social Evolution of LLM Agents Through the Lens of Hobbesian Social Contract Theory** *arXiv* [[paper](https://arxiv.org/abs/2406.14373)]
- [2024/10] **Project Sid: Many-agent simulations toward AI civilization** [[paper](https://arxiv.org/abs/2411.00114) [website](https://altera.al/)]
- [2024/11] **Oasis: Open agents social interaction simulations on one million agents** *arXiv* [[paper](https://arxiv.org/pdf/2411.11581?)]
- [2025/07] **LLM Economist: Large Population Models and Mechanism Design in Multi-Agent Generative Simulacra** *arXiv* [[paper](https://arxiv.org/abs/2507.15815)] [[code](https://github.com/sethkarten/LLM-Economist)]


[//]: # (- [2024/10] **GenSim: A General Social Simulation Platform with Large Language Model based Agents** *arXiv* [[paper]&#40;https://arxiv.org/abs/2410.04360&#41;][[code]&#40;https://github.com/TangJiakai/GenSim&#41;])


#### Embodied Simulation
- [2022/01] **Language Models as Zero-ShoSSocial-network Simulation Planners: Extracting Actionable Knowledge for Embodied Agents** *ICML 2022* [[paper](https://proceedings.mlr.press/v162/huang22a.html)][[code](https://github.com/huangwl18/language-planner)]
- [2022/12] **LLM-Planner: Few-Shot Grounded Planning for Embodied Agents with Large Language Models** *ICCV 2023* [[paper](https://openaccess.thecvf.com/content/ICCV2023/html/Song_LLM-Planner_Few-Shot_Grounded_Planning_for_Embodied_Agents_with_Large_Language_ICCV_2023_paper.html)]
- [2023/05] **Language Models Meet World Models: Embodied Experiences Enhance Language Models** *NeurIPS 2023* [[paper](https://arxiv.org/abs/2305.10626.pdf)][[code](https://github.com/szxiangjn/world-model-for-language-model)]
- [2023/10] **Octopus: Embodied Vision-Language Programmer from Environmental Feedback** *arXiv* [[paper](https://arxiv.org/abs/2310.08588.pdf)] [[code](https://github.com/dongyh20/Octopus)]
- [2024/01] **True Knowledge Comes from Practice: Aligning LLMs with Embodied Environments via Reinforcement Learning** *arXiv*[[paper]](https://arxiv.org/pdf/2401.14151.pdf)[[code](https://github.com/WeihaoTan/TWOSOME)]

#### Other Simulation

- [2024/01] **CivRealm: A Learning and Reasoning Odyssey in Civilization for Decision-Making Agents** *ICLR 2024* [[paper](https://arxiv.org/abs/2401.10568.pdf)][[code](https://github.com/bigai-ai/civrealm)]

### Competition Games

- [2022/10] **Emergent World Representations: Exploring a Sequence Model Trained on a Synthetic Task** *ICLR 2023* [[paper](https://arxiv.org/pdf/2210.13382.pdf)]
- [2023/06] **ChessGPT: Bridging Policy Learning and Language Modeling** *NeurIPS 2023* [[paper](https://proceedings.neurips.cc/paper_files/paper/2023/hash/16b14e3f288f076e0ca73bdad6405f77-Abstract-Datasets_and_Benchmarks.html)][[code](https://github.com/waterhorse1/ChessGPT)]
- [2023/08] **Are ChatGPT and GPT-4 Good Poker Players?--A Pre-Flop Analysis** *arXiv* [[paper](https://arxiv.org/abs/2308.12466)]
- [2023/09] **Suspicion-Agent: Playing Imperfect Information Games with Theory of Mind Aware GPT-4** *COLM 2024* [[paper](https://arxiv.org/abs/2309.17277.pdf)]
- [2023/12] **Large Language Models Play StarCraft II: Benchmarks and A Chain of Summarization Approach** *arXiv* [[paper](https://arxiv.org/abs/2312.11865.pdf)][[code](https://github.com/histmeisah/Large-Language-Models-play-StarCraftII/tree/main)]
- [2024/01] **PokerGPT: An End-to-End Lightweight Solver for Multi-Player Texas Hold'em via Large Language Model** *arXiv* [[paper](https://arxiv.org/abs/2401.06781)]
- [2024/01] **SwarmBrain: Embodied agent for real-time strategy game StarCraft II via large language models** *arXiv* [[paper](https://arxiv.org/abs/2401.17749.pdf)]
- [2024/02] **PokéLLMon: A Human-Parity Agent for Pokémon Battles with Large Language Models** *TOIT 2025* [[paper](https://arxiv.org/abs/2402.01118.pdf)][[code](https://github.com/git-disl/PokeLLMon)]
- [2024/02] **Agent-Pro: Learning to Evolve via Policy-Level Reflection and Optimization** *arXiv* [[paper](https://arxiv.org/abs/2402.17574.pdf)][[code](https://github.com/zwq2018/Agent-Pro)]
- [2024/03] **Embodied LLM Agents Learn to Cooperate in Organized Teams** *arXiv* [[paper](https://arxiv.org/pdf/2403.12482)]
- [2024/08] **Evaluating and Enhancing LLMs Agent based on Theory of Mind in Guandan: A Multi-Player Cooperative Game under Imperfect Information** *arXiv* [[paper](https://arxiv.org/pdf/2408.02559)]
- [2024/10] **PokéChamp: An Expert-level Minimax Language Agent** *ICML 2025* [[paper](https://arxiv.org/abs/2503.04094)] [[code](https://github.com/sethkarten/PokeChamp)]
- [2025/01] **POKERBENCH: Training Large Language Models to become Professional Poker Players** *arXiv* [[paper](https://arxiv.org/pdf/2501.08328)]
- [2025/04] **The PokeAgent Challenge: Competitive and Long Context Learning at Scale** *NeurIPS Competition Track 2025* [[paper](https://sethkarten.ai/data/NeurIPS_2025_PokeAgent_Challenge.pdf)] [[website](https://pokeagent.github.io/)]


### Cooperation Games

- [2023/07] **Building Cooperative Embodied Agents Modularly with Large Language Models** *ICLR 2024* [[paper](https://arxiv.org/abs/2307.02485.pdf)][[code](https://github.com/UMass-Foundation-Model/Co-LLM-Agents/)]
- [2023/09] **MindAgent: Emergent Gaming Interaction** *arXiv* [[paper]](http://https://arxiv.org/abs/2309.09971)
- [2023/10] **Evaluating Multi-agent Coordination Abilities in Large Language Models** *arXiv* [[paper]](https://arxiv.org/abs/2310.03903.pdf)
- [2023/10] **Theory of Mind for Multi-Agent Collaboration via Large Language Models** *arXiv* [[paper]](https://arxiv.org/pdf/2310.10701)][[code](https://github.com/romanlee6/multi_LLM_comm)]
- [2023/12] **LLM-Powered Hierarchical Language Agent for Real-time Human-AI Coordination** *arXiv* [[paper]](https://arxiv.org/abs/2312.15224.pdf)
- [2024/02] **S-Agents: Self-organizing Agents in Open-ended Environments** *arXiv*  [[paper](https://arxiv.org/abs/2402.04578)]
- [2024/03] **ProAgent: Building Proactive Cooperative Agents with Large Language Models** *AAAI 2024* [[paper](https://ojs.aaai.org/index.php/AAAI/article/view/29710)]
- [2024/03] **Can LLM-Augmented Autonomous Agents Cooperate?, An Evaluation of Their Cooperative Capabilities through Melting Pot** *arXiv* [[paper](https://arxiv.org/abs/2403.11381.pdf)]
- [2024/03] **Hierarchical Auto-Organizing System for Open-Ended Multi-Agent Navigation** *arXiv*[[paper](https://arxiv.org/abs/2403.08282.pdf)]
- [2024/05] **Towards Efficient LLM Grounding for Embodied Multi-Agent Collaboration** *arXiv*[[paper](https://arxiv.org/pdf/2405.14314)][[code](https://arxiv.org/pdf/2405.14314)]
- [2024/12] **TeamCraft: A Benchmark for Multi-Modal Multi-Agent Systems in Minecraft** *arXiv*[[paper](https://arxiv.org/pdf/2412.05255)][[code](https://teamcraft-bench.github.io/)]

[//]: # (- [2025/03] **Predicting Multi-Agent Specialization via Task Parallelizability** *arXiv*[[paper]&#40;https://arxiv.org/pdf/2503.15703&#41;])


### Communication (Conversational) Games

- [2022/12] **Human-Level Play in the Game of Diplomacy by Combining Language Models with Strategic Reasoning** *Science* [[paper](https://www.science.org/doi/pdf/10.1126/science.ade9097?casa_token=AB3PXQnKr8YAAAAA:pJO8TUkmbEUH77IhRcn-4r9PpxQc0jRgKokE3ElhmFvAhyTdjjS8aHOgJ_ViH_BnJwMDtTqdMmJgug)]
- [2023/08] **GameEval: Evaluating LLMs on Conversational Games** *arXiv* [[paper]](https://arxiv.org/abs/2308.10032.pdf)[[code](https://github.com/jordddan/GameEval)]
- [2023/09] **Exploring Large Language Models for Communication Games: An Empirical Study on Werewolf** *arXiv* [[paper](https://arxiv.org/abs/2309.04658.pdf)]
- [2023/10] **Language Agents with Reinforcement Learning for Strategic Play in the Werewolf Game** *arXiv* [[paper](https://arxiv.org/abs/2310.18940.pdf)]
- [2023/10] **Avalon's Game of Thoughts: Battle Against Deception through Recursive Contemplation** *arXiv* [[paper](https://arxiv.org/abs/2310.01320)]
- [2023/10] **AvalonBench: Evaluating LLMs Playing the Game of Avalon** *FMDM@NeurIPS2023* [[paper](https://openreview.net/pdf?id=ltUrSryS0K)][[code](https://github.com/jonathanmli/Avalon-LLM)]
- [2023/10] **LLM-Based Agent Society Investigation: Collaboration and Confrontation in Avalon Gameplay** *arXiv* [[paper](https://arxiv.org/abs/2310.14985)]
- [2023/10] **Leveraging Word Guessing Games to Assess the Intelligence of Large Language Models** *arXiv* [[paper](https://arxiv.org/abs/2310.20499.pdf)][[code](https://github.com/Skytliang/SpyGame)]
- [2023/11] **War and Peace (WarAgent): Large Language Model-based Multi-Agent Simulation of World Wars** *arXiv* [[paper](https://arxiv.org/abs/2311.17227.pdf)][[code](https://github.com/agiresearch/WarAgent)]
- [2023/11] **clembench: Systematic Evaluation of Chat-Optimized Language Models as Conversational Agents** *EMNLP 2023* [[paper](https://aclanthology.org/2023.emnlp-main.689.pdf)]
- [2023/12] **Can Large Language Models Serve as Rational Players in Game Theory? A Systematic Analysis** *AAAI 2024* [[paper](https://arxiv.org/abs/2312.05488)]
- [2023/12] **Cooperation on the Fly: Exploring Language Agents for Ad Hoc Teamwork in the Avalon Game** *arXiv* [[paper]](https://arxiv.org/abs/2312.17515.pdf)
- [2023/12] **Deciphering Digital Detectives: Understanding LLM Behaviors and Capabilities in Multi-Agent Mystery Games** [[paper]](https://arxiv.org/pdf/2312.00746.pdf)
- [2024/02] **Enhance Reasoning for Large Language Models in the Game Werewolf** *arXiv* [[paper](https://arxiv.org/abs/2402.02330.pdf)]
- [2024/02] **What if LLMs Have Different World Views: Simulating Alien Civilizations with LLM-based Agents** *arXiv* [[paper](https://arxiv.org/abs/2402.13184.pdf)]
- [2024/02] **Can Large Language Model Agents Simulate Human Trust Behaviors?** *arXiv* [[paper](https://arxiv.org/pdf/2402.04559)]
- [2024/02] **Large Language Models Fall Short: Understanding Complex Relationships in Detective Narratives** *arXiv* [[paper](https://www.arxiv.org/pdf/2402.11051)]
- [2024/04] **Self-playing Adversarial Language Game Enhances LLM Reasoning** [[paper](https://arxiv.org/pdf/2404.10642)][[code](https://arxiv.org/pdf/2404.10642)]
- [2024/06] **PLAYER: Enhancing LLM-based Multi-Agent Communication and Interaction in Murder Mystery Games** *arXiv*[[paper](https://arxiv.org/pdf/2404.17662)]
- [2024/07] **AMONGAGENTS: Evaluating Large Language Models in the Interactive Text-Based Social Deduction Game** *arXiv* [[paper](https://arxiv.org/pdf/2408.02559)]


### Action Games

- [2023/02] **Grounding Large Language Models in Interactive Environments with Online Reinforcement Learning** *ICML 2023* [[paper](https://arxiv.org/abs/2302.02662.pdf)][[code](https://github.com/flowersteam/Grounding_LLMs_with_online_RL)]
- [2024/03] **Cradle: Empowering Foundation Agents Towards General Computer Control** *arXiv* [[paper](https://arxiv.org/abs/2403.03186.pdf)][[code](https://github.com/BAAI-Agents/Cradle)]
- [2024/03] **Will GPT-4 Run DOOM?** *arXiv* [[paper](https://arxiv.org/abs/2403.05468.pdf)][[code](https://github.com/adewynter/Doom)]
- [2024/03] **Evaluate LLMs in Real Time with Street Fighter III** *GitHub* [[code](https://github.com/OpenGenerativeAI/llm-colosseum)]
- [2024/07] **Baba Is AI: Break the Rules to Beat the Benchmark** *ICML 2024* [[paper](https://arxiv.org/pdf/2407.13729)]
- [2024/08] **Atari-GPT: Investigating the Capabilities of Multimodal Large Language Models as Low-Level Policies for Atari Games** *arXiv* [[paper](https://arxiv.org/pdf/2408.15950)]
- [2024/09] **Can VLMs Play Action Role-Playing Games? Take Black Myth Wukong as a Study Case** *arXiv* [[paper](https://arxiv.org/abs/2409.12889)] [[code](https://varp-agent.github.io/)]
- [2024/08] **AMONGAGENTS: Evaluating Large Language Models in the Interactive Text-Based Social Deduction Game** *arXiv* [[paper](https://arxiv.org/pdf/2408.15950)]
- [2024/10] **Unbounded: A Generative Infinite Game of Character Life Simulation** *arXiv* [[paper](https://arxiv.org/abs/2410.18975)]

### Dialogue & Story & Game Generation

- [2023/10] **Language as reality: a co-creative storytelling game experience in 1001 nights using generative AI.** *AAAI 2023* [[paper](https://ojs.aaai.org/index.php/AIIDE/article/view/27539)][[demo on Steam](https://store.steampowered.com/app/2542850/1001_Nights/)]
- [2024/07] **What if Red Can Talk? Dynamic Dialogue Generation Using Large Language Models.** *arXiv* [[paper](https://arxiv.org/pdf/2407.20382)]

### Benchmark
- [2025/05] **lmgame-Bench: How Good are LLMs at Playing Games?."** *arXiv* [[paper](https://arxiv.org/pdf/2505.15146)][[code](https://github.com/lmgame-org/GamingAgent/tree/main/lmgame-bench)]


## Citation
If you find this repository useful, please cite our paper. We will periodically check for new papers citing the survey and update this list—and the survey itself—when relevant.
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



