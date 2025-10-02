---
layout: default
---

# Overview of the project

Reinforcement learning (RL), both classical algorithms and their deep variants, critically rely on the fact that the underlying system is assumed stationary, i.e., how the environment responds to the agent's actions does not vary with time. Unfortunately, many real-world problems fail to exhibit such stationary property. Therefore, to bring out the full potential of RL in complex application domains, existing methods must be extended to cope with non-stationarity in a principled way.

RELEvaNT investigates **new models and methods** for efficient deep RL in non-stationary environments and the potential applications on several "human-centered" domains. In particular, RELEvaNT investigates:

* Model-based RL in which the learned model _captures a low-dimensional factorized representation of the world_. We investigate the extent to which such low-dimensional representations enable the agent to robustly cope with changes in the dynamics of the world.

* _Meta-learning approaches to model-based RL_, in order to render the process of learning the low-dimensional models mentioned above more data-efficient. In particular, we build on existing frameworks for model-agnostic meta-learning to construct pre-trained "prototypical" representations that can then be adjusted, at interaction time, using a small number of samples, thus enabling the agent to adjust to changes in the environment.

The outcomes of the project will be evaluated in several real-world non-stationary domains, exploiting the application of RL in robot control and human-robot interaction.

# Research team

Research in RELEvaNT is held by a dynamic team that includes both senior and junior researchers. Several MSc students have also been advised in the context of the project.

### Senior researchers
* [Francisco S. Melo](https://gaips.inesc-id.pt/~fmelo/) (Principal Researcher, Full Professor, IST)
* [José Alberto Sardinha](https://www-di.inf.puc-rio.br/~sardinha/) (Associate Professor, PUC-Rio)
* [Manuel Lopes](https://web.tecnico.ulisboa.pt/manuel.lopes/) (Associate Professor, IST)

### Junior researchers 
* Diogo Carvalho (PhD student at IST)
* Pedro Pinto Santos (PhD student at IST)
* Jacopo Silvestrin (PhD student at IST)
* [Bernardo Esteves](https://bernardoesteves.com/) (PhD student at IST)

### Former members
* António Soares
* Fábio Vital (currently a PhD student at IST)
* Francisco Martins (former MSc student)
* Gonçalo Querido (former MSc student)
* José Rocha (currently a PhD student at IST)
* Margarida Serralheiro (currently a PhD student at IST)
* [Miguel Vasco](https://miguelvasco.com/) (currently a post-doc at KTH)
* Rustam Zayanov (former MSc student)

# Publications

### Edited volumes

F. Melo, F. Fang. (2022) _Autonomous Agents and Multiagent Systems: Best and Visionary Papers, AAMAS 2022_, Lecture Notes in Computer Science 13441, Springer ([link](https://link.springer.com/book/10.1007/978-3-031-20179-0)).

### International journals

P. P. Santos, D. Carvalho, A. Sardinha, F. Melo. (2024) The impact of data distribution on Q-learning with function approximation. Machine Learning, to appear ([pdf](/pubs/santos24ml.pdf)).

M. Vasco, H. Yin, F. Melo, A. Paiva. (2022b). Leveraging hierarchy in multimodal generative models for effective cross-modality inference. _Neural Networks_, 146:238-255 ([pdf](/pubs/vasco22nn.pdf)).

### International conferences

D. Carvalho, F. Melo, P. Santos. (2023) Theoretical remarks on feudal hierarchies and reinforcement learning. In _Proc. 26th Eur. Conf. Artificial Intelligence_, pp. 351-356. **Outstanding Paper Award** ([pdf](/pubs/carvalho23ecai.pdf)).

P. Poklukar, M. Vasco, H. Yin, F. Melo, A. Paiva, D. Kragic (2022). Geometric multimodal contrastive representation learning. In _Proc. 39th Int. Conf. Machine Learning_, pp. 17782-17800 ([pdf](/pubs/poklukar22icml.pdf)). 

G. Querido, A. Sardinha, F. Melo. (2023) Learning to perceive in deep model-free reinforcement learning. In _Proc. 22nd Int. Conf. Autonomous Agents and Multiagent Systems_, pp. 2595-2597 ([pdf](/pubs/querido23aamas.pdf)).

J. Ribeiro, C. Martinho, A. Sardinha, F. Melo. (2023) Making friends in the dark: Ad hoc teamwork under partial observability. In _Proc. 26th Eur. Conf. Artificial Intelligence_, pp. 1954-1961 ([pdf](/pubs/ribeiro23ecai.pdf)).

P. P. Santos, D. Carvalho, M. Vasco, A. Sardinha, P. A. Santos, A. Paiva, F. Melo. (2024)
Centralized training with hybrid execution in multi-agent reinforcement learning. In _Proc. 23rd Int. Conf. Autonomous Agents and Multiagent Systems, pp. 2453-2455 ([pdf](/pubs/santos24aamas.pdf)).

M. Vasco, H. Yin, F. Melo, A. Paiva. (2022) How to sense the world: Leveraging hierarchy in multimodal perception for robust reinforcement learning agents. In _Proc. 21st Int. Conf. Autonomous Agents and Multiagent Systems_, pp. 1301-1309 ([pdf](/pubs/vasco22aamas.pdf)). 

F. Vital, M. Vasco, A. Sardinha, F. Melo. (2022) Perceive, represent, generate: Translating multimodal information to robotic motion trajectories. In _Proc. 2022 IEEE/RSJ Int. Conf. Intelligent Robots and Systems_, pp. 5855-5860 ([pdf](/pubs/vital22iros.pdf)). 

R. Zayanov, F. Melo, M. Lopes. (2024) Interactively teaching an inverse reinforcement learner with limited feedback. In _Proc. 16th Int. Conf. Agents and Artificial Intelligence_, 15-24 ([pdf](/pubs/zayanov24icaart.pdf)).

### National conferences

B. Esteves, M. Vasco, F. Melo. (2023) Pre-training with augmentations for efficient transfer in model-based reinforcement learning. In _Proc. 22nd EPIA Conf. Artificial Intelligence_, pp. 133-145 ([pdf](/pubs/esteves23epia.pdf)).

A. Neves, A. Sardinha. (2022) Learning to cooperate with completely unknown teammates. In _Proc. 21st EPIA Conf. Artificial Intelligence_, pp. 739-750 ([pdf](/pubs/neves22epia.pdf)).

### MSc theses

S. Carvalho. (2022) _Using autonomous vehicles to improve traffic conditions_. MSc thesis, Instituto Superior Técnico, Univ. Lisboa.

B. Esteves. (2022) _Efficient transfer in model-based reinforcement learning_. MSc thesis, Instituto Superior Técnico, Univ. Lisboa.

A. Fernandes. (2023) _Leveraging deep unsupervised models towards learning robust multimodal representations_. MSc thesis, Instituto Superior Técnico, Univ. Lisboa.

E. Paiva. (2023) _Using deep model-based RL in ad hoc teamwork with partial observability_. MSc thesis, Instituto Superior Técnico, Univ. Lisboa.

G. Querido. (2022) _Learning to perceive in deep model-free reinforcement learning_. MSc thesis, Instituto Superior Técnico, Univ. Lisboa.

R. Zayanov. (2022) _Interactively teaching an inverse reinforcement learner with limited feedback_. MSc thesis, Instituto Superior Técnico, Univ. Lisboa. 

### Datasets and software

M. Vasco, H. Yin, Francisco S. Melo, A. Paiva. (2022) [Multimodal Handwritten Digits (MHD) dataset](https://github.com/miguelsvasco/multimodal-handwritten-digits)
