# MARL Resources Collection
This is a collection of Multi-Agent Reinforcement Learning (MARL) Resources. The purpose of this repository is to give beginners a better understanding of MARL and accelerate the learning process. Note that some of the resources are written in Chinese and only important papers that have a lot of citations were listed. 

I will continually update this repository and I welcome suggestions. (missing important papers, missing important resources, invalid links, etc.) This is only a first draft so far and I'll add more resources in the next few months.

**Update (2026):** Added recent open-source environments/benchmarks (JaxMARL, SMACv2, Melting Pot 2.0, Gigastep, POGEMA, ...), a new [MARL Libraries / Frameworks](#marl-libraries--frameworks) section, a new [LLM-based Multi-Agent Systems](#llm-based-multi-agent-systems) section, and a [Recent Surveys (2022–2026)](#recent-surveys-20222026) list.

This repository is not for commercial purposes.

My email: chenhao915@mails.ucas.ac.cn


## Overview
* [Courses](https://github.com/TimeBreaker/MARL-resources-collection#courses)
* [Important Conferences](https://github.com/TimeBreaker/MARL-resources-collection#important-conferences)
* [Reviews](https://github.com/TimeBreaker/MARL-resources-collection#reviews)
* [Books](https://github.com/TimeBreaker/MARL-resources-collection#books)
* [Open Source Environments](https://github.com/TimeBreaker/MARL-resources-collection#open-source-environments)
* [MARL Libraries / Frameworks](https://github.com/TimeBreaker/MARL-resources-collection#marl-libraries--frameworks)
* [LLM-based Multi-Agent Systems](https://github.com/TimeBreaker/MARL-resources-collection#llm-based-multi-agent-systems)
* [Research Groups](https://github.com/TimeBreaker/MARL-resources-collection#research-groups)
* [Companies](https://github.com/TimeBreaker/MARL-resources-collection#companies)
* [Paper List](https://github.com/TimeBreaker/MARL-resources-collection#paper-list)
* [Talks](https://github.com/TimeBreaker/MARL-resources-collection#talks)
* [Useful Resources](https://github.com/TimeBreaker/MARL-resources-collection#useful-links)
* [TODO](https://github.com/TimeBreaker/MARL-resources-collection#todo)


## Courses
* [RLChina](https://rlchina.org/)
* [UCL Multi-agent AI](https://www.bilibili.com/video/BV1fz4y1S72S)
* [SJTU Multi-Agent Reinforcement Learning Tutorial](http://wnzhang.net/tutorials/marl2018/index.html)
* [SJTU Reinforcement Learning](https://hrl.boyuai.com/slides/)


## Important Conferences
* AAMAS, AAAI, IJCAI, ICLR, ICML, NIPS
* Sorted by difficulty (roughly)


## Reviews
### Recent Reviews (Since 2019)
* [A Survey and Critique of Multiagent Deep Reinforcement Learning](https://arxiv.org/pdf/1810.05587v3)
* [An Overview of Multi-Agent Reinforcement Learning from Game Theoretical Perspective](https://arxiv.org/abs/2011.00583v2)
* [Multi-Agent Reinforcement Learning: A Selective Overview of Theories and Algorithms](https://arxiv.org/abs/1911.10635v1)
* [A Review of Cooperative Multi-Agent Deep Reinforcement Learning](https://arxiv.org/abs/1908.03963)
* [Dealing with Non-Stationarity in Multi-Agent Deep Reinforcement Learning](https://arxiv.org/abs/1906.04737)
* [A Survey of Learning in Multiagent Environments: Dealing with Non-Stationarity](https://arxiv.org/abs/1707.09183v1)
* [Deep Reinforcement Learning for Multi-Agent Systems: A Review of Challenges, Solutions and Applications](https://arxiv.org/pdf/1812.11794.pdf)
* [A Survey on Transfer Learning for Multiagent Reinforcement Learning Systems](https://www.researchgate.net/publication/330752409_A_Survey_on_Transfer_Learning_for_Multiagent_Reinforcement_Learning_Systems)

### Recent Surveys (2022–2026)
* [Multi-agent Reinforcement Learning: A Comprehensive Survey](https://arxiv.org/abs/2312.10256)
* [A Survey of Progress on Cooperative Multi-Agent Reinforcement Learning in Open Environments](https://arxiv.org/abs/2312.01058)
* [A Survey of Multi-Agent Deep Reinforcement Learning with Communication](https://arxiv.org/abs/2203.08975)   (AAMAS 2024)
* [A Comprehensive Survey on Multi-Agent Cooperative Decision-Making: Scenarios, Approaches, Challenges and Perspectives](https://arxiv.org/abs/2503.13415)
* [A Survey of Safe Reinforcement Learning and Constrained MDPs: Single-Agent and Multi-Agent Safety](https://arxiv.org/abs/2505.17342)
* [Multi-Agent Reinforcement Learning for Autonomous Driving: A Survey](https://arxiv.org/abs/2408.09675)
* [Multi-Agent Reinforcement Learning in Intelligent Transportation Systems: A Comprehensive Survey](https://arxiv.org/abs/2508.20315)
* [A Survey on Large Language Model based Multi-Agent Systems: Recent Advances and New Frontiers in Application](https://arxiv.org/abs/2412.17481)
* [Multi-Agent Collaboration Mechanisms: A Survey of LLMs](https://arxiv.org/abs/2501.06322)

### Other Reviews (Before 2019)
* [If multi-agent learning is the answer, what is the question?](https://ai.stanford.edu/people/shoham/www%20papers/LearningInMAS.pdf)
* [Multiagent learning is not the answer. It is the question](https://core.ac.uk/download/pdf/82595758.pdf)
* [Is multiagent deep reinforcement learning the answer or the question? A brief survey](https://arxiv.org/abs/1810.05587v1)   Note that [A Survey and Critique of Multiagent Deep Reinforcement Learning](https://arxiv.org/pdf/1810.05587v3) is an updated version of this paper with the same authors.
* [Evolutionary Dynamics of Multi-Agent Learning: A Survey](https://www.researchgate.net/publication/280919379_Evolutionary_Dynamics_of_Multi-Agent_Learning_A_Survey)
* (Worth reading although they're not recent reviews.)


## Books
* [Multiagent systems: Algorithmic, game-theoretic, and logical foundations](http://www.masfoundations.org/download.html)
* [Multi‐Agent Machine Learning A Reinforcement Approach](https://www.engineerrefe.com/multi-agent-machine-learning/)


## Open Source Environments
* StarCraft Micromanagement Environment
   * [pymarl](https://github.com/oxwhirl/pymarl) is the original environment mentioned in the paper [The StarCraft Multi-Agent Challenge](https://arxiv.org/abs/1902.04043). Note that pymarl is based on [SMAC](https://github.com/oxwhirl/smac).
   * [MARL-Algorithms](https://github.com/starry-sky6688/MARL-Algorithms) is a simplified implementation of [pymarl](https://github.com/oxwhirl/pymarl)
   * [EPyMARL](https://github.com/uoe-agents/epymarl) is a extended python MARL framework with more environments (Level Based Foraging, Multi-Robot Warehouse, Multi-Agent Particle Environment) and more algorithms. [Paper](https://link.zhihu.com/?target=https%3A//arxiv.org/abs/2006.07869)
   * [pymarl2](https://github.com/hijkzzz/pymarl2) added code-level tricks to the original pymarl. [Paper](https://arxiv.org/abs/2102.03479)
* [Multi-Agent Particle Environment](https://github.com/openai/multiagent-particle-envs)  [PyTorch Implementation](https://github.com/shariqiqbal2810/maddpg-pytorch)
* [Neural MMO: A Massively Multiagent Game Environment for Training and Evaluating Intelligent Agents](https://github.com/openai/neural-mmo)
* [OpenSpiel: A Framework for Reinforcement Learning in Games](https://github.com/deepmind/open_spiel)
* [Hanabi-learning-environment](https://github.com/deepmind/hanabi-learning-environment)
* [RoboCup 2D Half Field Offense](https://github.com/LARG/HFO)
* [Pommerman](https://www.pommerman.com/)
* [Multi-agent-emergence-environments](https://github.com/openai/multi-agent-emergence-environments)
* [Google Research Football](https://github.com/google-research/football)
* [MAgent](https://github.com/PettingZoo-Team/MAgent) Note that [the original project](https://github.com/geek-ai/MAgent) is no longer maintained.
* [DI-engine](https://github.com/opendilab/DI-engine)
* [MARLlib](https://github.com/Replicable-MARL/MARLlib) is a MARL Extension for RLlib
* [Multiagent Mujoco](https://github.com/schroederdewitt/multiagent_mujoco)
* [PettingZoo](https://github.com/Farama-Foundation/PettingZoo)  [website](https://www.pettingzoo.ml/)
* [Safe Policy Optimization (SafePO)](https://github.com/PKU-MARL/Safe-Policy-Optimization)
* (I personally recommend the first two environments for beginners, especially EPyMARL.)

### Newer Environments / Benchmarks (2022–2026)
* [SMACv2](https://github.com/oxwhirl/smacv2) — an improved, procedurally-generated version of the StarCraft Multi-Agent Challenge. [Paper](https://arxiv.org/abs/2212.07489)
* [JaxMARL](https://github.com/flairox/jaxmarl) — a large collection of GPU-accelerated MARL environments (including SMAX, an SMAC re-implementation) and baseline algorithms in JAX; extremely fast. [Paper](https://arxiv.org/abs/2311.10090)
* [Melting Pot 2.0](https://github.com/google-deepmind/meltingpot) — DeepMind's suite for evaluating generalization to novel social situations (cooperation, competition, deception). [Paper](https://arxiv.org/abs/2211.13746)
* [Overcooked-AI](https://github.com/HumanCompatibleAI/overcooked_ai) — a benchmark for human-AI coordination; the de-facto standard for zero-shot coordination research. [Paper](https://arxiv.org/abs/1910.05789)
* [Gigastep](https://github.com/mlech26l/gigastep) — one billion steps per second multi-agent RL; large-scale aerial/ground combat scenarios. [Paper](https://openreview.net/forum?id=UgPAaEugH3)
* [POGEMA](https://github.com/Cognitive-AI-Systems/pogema) — a fast benchmark platform for cooperative multi-agent pathfinding (MAPF). [Paper](https://arxiv.org/abs/2407.14931)
* [MOMAland](https://github.com/Farama-Foundation/momaland) — Farama's benchmarks for multi-objective multi-agent RL. [Paper](https://arxiv.org/abs/2407.16312)
* [MARBLER](https://github.com/GT-STAR-Lab/MARBLER) — standardized evaluation of multi-robot RL algorithms on the Robotarium. [Paper](https://arxiv.org/abs/2307.03891)
* [MABIM / ReplenishmentEnv](https://github.com/VictorYXL/ReplenishmentEnv) — a versatile MARL benchmark for inventory management. [Paper](https://arxiv.org/abs/2306.07542)


## MARL Libraries / Frameworks
Training libraries and algorithm frameworks (as opposed to task environments).
* [MARLlib](https://github.com/Replicable-MARL/MARLlib) — a Ray/RLlib-based library unifying many MARL algorithms across a wide range of environments through a standardized interface. [Paper](https://arxiv.org/abs/2210.13708)
* [BenchMARL](https://github.com/facebookresearch/BenchMARL) — a TorchRL-backed benchmarking library for reproducible, standardized comparison of MARL algorithms, tasks and models. [Paper](https://arxiv.org/abs/2312.01472)
* [EPyMARL](https://github.com/uoe-agents/epymarl) — Extended PyMARL adding more algorithms (IPPO, MAA2C, etc.) and environments.
* [pymarlzooplus](https://github.com/AILabDsUnipi/pymarlzooplus) — a further-extended PyMARL/EPyMARL benchmarking suite for complex fully-cooperative tasks. [Paper](https://arxiv.org/abs/2502.04773)
* [Mava](https://github.com/instadeepai/Mava) — InstaDeep's research-friendly JAX framework for scalable MARL.
* [JaxMARL](https://github.com/flairox/jaxmarl) — bundles both JAX environments and baseline MARL algorithms.
* [TorchRL](https://github.com/pytorch/rl) — PyTorch-native RL library with first-class multi-agent support (MAPPO, IPPO, QMIX, MADDPG); the backend of BenchMARL.


## LLM-based Multi-Agent Systems
The intersection of Large Language Models and multi-agent systems has become a very active area. A few widely-used open-source frameworks:
* [CAMEL](https://github.com/camel-ai/camel) — communicative agents / role-playing for LLM societies. [Paper](https://arxiv.org/abs/2303.17760)
* [AutoGen](https://github.com/microsoft/autogen) — Microsoft's framework for building multi-agent LLM applications via conversation. [Paper](https://arxiv.org/abs/2308.08155)
* [MetaGPT](https://github.com/geekan/MetaGPT) — a multi-agent framework encoding SOPs for collaborative software teams. [Paper](https://arxiv.org/abs/2308.00352)
* [ChatDev](https://github.com/OpenBMB/ChatDev) — communicative agents that collaborate to develop software. [Paper](https://arxiv.org/abs/2307.07924)
* [AgentVerse](https://github.com/OpenBMB/AgentVerse) — a framework for multi-agent collaboration and emergent behavior. [Paper](https://arxiv.org/abs/2308.10848)
* [Generative Agents](https://github.com/joonspk-research/generative_agents) — interactive simulacra of human behavior. [Paper](https://arxiv.org/abs/2304.03442)
* See also the **LLM-based Multi-Agent** section in [Multi-Agent-Reinforcement-Learning-papers](https://github.com/TimeBreaker/Multi-Agent-Reinforcement-Learning-papers#llm-based-multi-agent).


## Research Groups
Organization|Reaearcher|Lab homepage (if any)
--|:--:|--:
Oxford|[Shimon Whiteson](https://www.cs.ox.ac.uk/people/shimon.whiteson/), [Jakob N. Foerster](https://www.jakobfoerster.com/)|[link](http://whirl.cs.ox.ac.uk/ ) 
University College London (UCL)|[Jun Wang](http://www0.cs.ucl.ac.uk/staff/Jun.Wang/)|
Tsinghua University (THU)|[Chongjie Zhang](http://people.iiis.tsinghua.edu.cn/~zhang/)|[link](http://group.iiis.tsinghua.edu.cn/~milab/index.html)
Tsinghua University (THU)|[Yi Wu](http://jxwuyi.weebly.com/)|
Peking University (PKU)|[Zongqing Lu](https://z0ngqing.github.io/)|
HUAWEI|[Hangyu Mao](https://maohangyu.github.io/)|
Nanjing University (NJU)|[Yang Yu](http://www.lamda.nju.edu.cn/yuy/)|
Facebook|[Yuandong Tian](http://yuandong-tian.com/)|
Tianjin University (TJU)|[Jianye Hao](http://faculty.tju.edu.cn/156102/zh_CN/index/24194/list/index.htm)|[link](http://www.icdai.org/)
University of Illinois at Urbana-Champaign (UIUC)|[Kaiqing Zhang](https://kzhang66.github.io/index.html)|
Peking University (PKU)|[Yaodong Yang](https://www.yangyaodong.com)|[Link](https://github.com/PKU-MARL)
Nanyang Technological University (NTU)|[Bo An](https://personal.ntu.edu.sg/boan/index.html)|
Shanghai Jiao Tong University (SJTU)|[Weinan Zhang](http://wnzhang.net/)|[link](http://apex.sjtu.edu.cn/)
University of Chinese Academy of Sciences (UCAS)|[Haifeng Zhang](https://pkuzhf.github.io/)|[link](http://marl.ia.ac.cn/index.html)
University of Edinburgh|[Stefano V. Albrecht](https://www.turing.ac.uk/people/researchers/stefano-albrecht)|[link](https://agents.inf.ed.ac.uk/) [GitHub](https://github.com/uoe-agents)
University College London (UCL)|UCL Deciding, Acting, and Reasoning with Knowledge (DARK) Lab |[Link](https://dark.cs.ucl.ac.uk/)
University of Maryland|[Furong Huang](http://furong-huang.com/)|[Link](http://furong-huang.com/)


## Companies
* [DeepMind](https://deepmind.com/)
* [OpenAI](https://openai.com/)
* [Facebook](https://ai.facebook.com/)
* [Tencent](https://ai.tencent.com/ailab/zh/index)
* [NetEase](https://fuxi.163.com/#/home)
* [Huawei](https://www.noahlab.com.hk/#/home)
* [Parametrix.ai](https://chaocanshu.cn/)
* [Inspir.ai](http://www.inspirai.com/)


## Paper Lists
* https://github.com/TimeBreaker/Multi-Agent-Reinforcement-Learning-papers
* https://github.com/TimeBreaker/MARL-papers-with-code
* https://github.com/TimeBreaker/Adversarial-Reinforcement-Learning-Papers
* https://github.com/LantaoYu/MARL-Papers


## Talks
### In English
* https://www.youtube.com/watch?v=W_9kcQmaWjo
* https://www.youtube.com/watch?v=TMTT2z8lifA
* https://www.youtube.com/watch?v=Yd6HNZnqjis
* https://www.youtube.com/watch?v=ufFue5_gR4c

### In Chinese
* https://www.techbeat.net/talk-info?id=501
* https://www.bilibili.com/video/av457780236/
* https://space.bilibili.com/551888585/channel/detail?cid=167587
* https://www.bilibili.com/video/BV1ig4y1v7xU
* https://www.bilibili.com/video/BV18z411q7Kc
* https://www.bilibili.com/video/BV1k5411V7ue


## Useful Resources
### In English
* https://dblp.uni-trier.de/
* https://paperswithcode.com/
* https://www.connectedpapers.com
* https://deeplearn.org
* https://spinningup.openai.com/
* https://github.com/openai/spinningup
* https://github.com/Jinjiarui/hrl-papers

### In Chinese
* http://www.neurondance.com/
* https://www.zhihu.com/question/376068768
* https://www.zhihu.com/question/323584412
* https://zhuanlan.zhihu.com/p/372558232
* https://space.bilibili.com/4801051?spm_id_from=333.788.b_765f7570696e666f.2
* https://www.zhihu.com/people/tian-yuan-dong
* https://www.zhihu.com/people/eyounx
* https://www.zhihu.com/people/wan-shang-zhu-ce-de
* Wechat public account: AIORHHC; RLCN
* https://www.bilibili.com/video/av925922430/
* https://www.bilibili.com/video/av626777400/
* https://github.com/NeuronDance/DeepRL


## TODO
* The Research Groups part needs to be completed
* The Companies part needs to be completed
* The Useful Resources part needs to be perfected


## Citation

If you find this repository useful, please cite our repo:
```
@misc{chen2021collection,
  author={Chen, Hao},
  title={A Collection of Multi-Agent Reinforcement Learning Resources},
  year={2021}
  publisher = {GitHub},
  journal = {GitHub Repository},
  howpublished = {\url{https://github.com/TimeBreaker/MARL-resources-collection}}
}
```
