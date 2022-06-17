# MARL Resources Collection
This is a collection of Multi-Agent Reinforcement Learning (MARL) Resources. The purpose of this repository is to give beginners a better understanding of MARL and accelerate the learning process. Note that some of the resources are written in Chinese and only important papers that have a lot of citations were listed. 

I will continually update this repository and I welcome suggestions. (missing important papers, missing important resources, invalid links, etc.) This is only a first draft so far and I'll add more resources in the next few months.

This repository is not for commercial purposes.

My email: chenhao2019@ia.ac.cn

## Overview
* [Courses](https://github.com/TimeBreaker/MARL-resources-collection#courses)
* [Important Conferences](https://github.com/TimeBreaker/MARL-resources-collection#important-conferences)
* [Reviews](https://github.com/TimeBreaker/MARL-resources-collection#reviews)
* [Books](https://github.com/TimeBreaker/MARL-resources-collection#books)
* [Open Source Environments](https://github.com/TimeBreaker/MARL-resources-collection#open-source-environments)
* [Research Groups](https://github.com/TimeBreaker/MARL-resources-collection#research-groups)
* [Companies](https://github.com/TimeBreaker/MARL-resources-collection#companies)
* [Paper List](https://github.com/TimeBreaker/MARL-resources-collection#paper-list)
* [Talks](https://github.com/TimeBreaker/MARL-resources-collection#talks)
* [Useful Resources](https://github.com/TimeBreaker/MARL-resources-collection#useful-links)
* [TODO](https://github.com/TimeBreaker/MARL-resources-collection#todo)

## Courses
* [RLChina 2020](https://rlchina.org/)
* [UCL Multi-agent AI](https://www.bilibili.com/video/BV1fz4y1S72S)
* [SJTU Multi-Agent Reinforcement Learning Tutorial](http://wnzhang.net/tutorials/marl2018/index.html)

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
   * [pymarl](https://github.com/oxwhirl/pymarl) This is the original environment mentioned in the paper [The StarCraft Multi-Agent Challenge](https://arxiv.org/abs/1902.04043). Note that pymarl is based on [SMAC](https://github.com/oxwhirl/smac).
   * [link](https://github.com/starry-sky6688/StarCraft) This is a simplified implementation of [pymarl](https://github.com/oxwhirl/pymarl)
* [Multi-Agent Particle Environment](https://github.com/openai/multiagent-particle-envs)
* [Neural MMO: A Massively Multiagent Game Environment for Training and Evaluating Intelligent Agents](https://github.com/openai/neural-mmo)
* [OpenSpiel: A Framework for Reinforcement Learning in Games](https://github.com/deepmind/open_spiel)
* [Hanabi-learning-environment](https://github.com/deepmind/hanabi-learning-environment)
* [RoboCup 2D Half Field Offense](https://github.com/LARG/HFO)
* [Pommerman](https://www.pommerman.com/)
* [Multi-agent-emergence-environments](https://github.com/openai/multi-agent-emergence-environments)
* [Google Research Football](https://github.com/google-research/football)
* [MAgent](https://github.com/PettingZoo-Team/MAgent) Note that [the original project](https://github.com/geek-ai/MAgent) is no longer maintained.
* [DI-engine](https://github.com/opendilab/DI-engine)
* (I personally recommend the first two environments for beginners.)

## Research Groups
Organization|Reaearcher|Lab homepage (if any)
--|:--:|--:
Oxford|[Shimon Whiteson](https://www.cs.ox.ac.uk/people/shimon.whiteson/), [Jakob N. Foerster](https://www.jakobfoerster.com/)|[link](http://whirl.cs.ox.ac.uk/ ) 
UCL|[Jun Wang](http://www0.cs.ucl.ac.uk/staff/Jun.Wang/)|
THU|[Chongjie Zhang](http://people.iiis.tsinghua.edu.cn/~zhang/)|[link](http://group.iiis.tsinghua.edu.cn/~milab/index.html)
THU|[Yi Wu](http://jxwuyi.weebly.com/)|
PKU|[Zongqing Lu](https://z0ngqing.github.io/)|
HUAWEI|[Hangyu Mao](https://maohangyu.github.io/)|
NJU|[Yang Yu](http://www.lamda.nju.edu.cn/yuy/)|
Facebook|[Yuandong Tian](http://yuandong-tian.com/)|
TJU|[Jianye Hao](http://faculty.tju.edu.cn/156102/zh_CN/index/24194/list/index.htm)|[link](http://www.icdai.org/)
UIUC|[Kaiqing Zhang](https://kzhang66.github.io/index.html)|
PKU|[Yaodong Yang](https://www.yangyaodong.com)|
NTU|[Bo An](https://personal.ntu.edu.sg/boan/index.html)|
SJTU|[Weinan Zhang](http://wnzhang.net/)|[link](http://apex.sjtu.edu.cn/)
UCAS|[Haifeng Zhang](https://pkuzhf.github.io/)|[link](http://marl.ia.ac.cn/index.html)

(This collection is stil incomplete.)

## Companies
* [DeepMind](https://deepmind.com/)
* [OpenAI](https://openai.com/)
* [Facebook](https://ai.facebook.com/)
* [Tencent](https://ai.tencent.com/ailab/zh/index)
* [NetEase](https://fuxi.163.com/#/home)
* [Huawei](https://www.noahlab.com.hk/#/home)
* [Parametrix.ai](https://chaocanshu.cn/)
* [Inspir.ai](http://www.inspirai.com/)

(This collection is stil incomplete.)

## Paper List
* https://github.com/TimeBreaker/Multi-Agent-Reinforcement-Learning-papers
* https://github.com/TimeBreaker/MARL-papers-with-code
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
* [RLChina 2021](http://rlchina.org/topic/9)

## TODO
* The Research Groups part needs to be completed
* The Companies part needs to be completed
* The Useful Resources part needs to be perfected


