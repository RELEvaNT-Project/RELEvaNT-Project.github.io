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

U. Endriss, F. Melo, K. Bach, A. Bugarin-Diz, J. Alonso-Moral, S. Barro, and F. Heintz, eds. _ECAI 2024 - 27th European Conference on Artificial Intelligence_. IOS Press, 2024 ([link](https://ebooks.iospress.nl/volume/ecai-2024-27th-european-conference-on-artificial-intelligence-1924-october-2024-santiago-de-compostela-spain-including-pais-2024)).

F. Melo, F. Fang. (2022) _Autonomous Agents and Multiagent Systems: Best and Visionary Papers, AAMAS 2022_, Lecture Notes in Computer Science 13441, Springer ([link](https://link.springer.com/book/10.1007/978-3-031-20179-0)).

### International journals

D. Carvalho, P. Santos, F. Melo. Multi-Bellman operator for convergence of Q-learning with linear function approximation. _Trans. Machine Learning Research_, vol. 2025, 2025. ([pdf](/pubs/carvalho25tmlr.pdf))

D. Carvalho, P. Santos, F. Melo. Reinforcement learning in convergently non-stationary environments: Feudal hierarchies and learned representations. _Artificial Intelligence_,  vol. 347, p. 104382, 2025. ([pdf](/pubs/carvalho26aij.pdf))

H. Fonseca, C. de Melo, K. Terada, J. Gratch, A. Paiva, F. Santos. Evolution of indirect reciprocity under emotion expression. _Nature Scientific Reports_, vol. 15, p. 9151, 2025. ([pdf](/pubs/fonseca25nsr.pdf))

P. Santos, F. Melo, A. Sardinha, D. Carvalho. Understanding the impact of data distribution on Q-learning with function approximation. _Machine Learning_, vol. 113, pp. 6141-6163, 2024. ([pdf](/pubs/santos24mlj.pdf))

P. Santos, D. Carvalho, M. Vasco, A. Sardinha, P. Santos, A. Paiva, F. Melo. Centralized training with hybrid execution in multi-agent reinforcement learning via predictive observation imputation. _Artificial Intelligence_, vol. 348, p. 104404, 2025. ([pdf](/pubs/santos25aij.pdf))

M. Vasco, H. Yin, F. Melo, A. Paiva. Leveraging hierarchy in multimodal generative models for effective cross-modality inference. _Neural Networks_, vol. 146, pp. 238-255, 2022. ([pdf](/pubs/vasco22nn.pdf))

### International conferences

D. Carvalho, F. Melo, P. Santos. Theoretical remarks on feudal hierarchies and reinforcement learning. In _Proc. 26th Eur. Conf. Artificial Intelligence_, pp. 351-356, 2023. ([pdf](/pubs/carvalho23ecai.pdf))

B. Esteves, M. Vasco, F. Melo. NeuralSolver: Learning algorithms for consistent and efficient extrapolation across general tasks. In _Advances in Neural Information Proc. Systems_ 37, 2024. ([pdf](/pubs/esteves24neurips.pdf))

P. Poklukar, M. Vasco, H. Yin, F. Melo, A. Paiva, D. Kragic. Geometric multi-modal contrastive representation learning. In _Proc. 39th Int. Conf. Machine Learning_, pp. 17782-17800, 2022. ([pdf](/pubs/poklukar22icml.pdf))

G. Querido, A. Sardinha, F. Melo. Learning to perceive in deep model-free reinforcement learning. In _Proc. 22nd Int. Conf. Autonomous Agents and Multiagent Systems_, pp. 2595-2597, 2023. ([pdf](/pubs/querido23aamas.pdf))

J. Ribeiro, C. Martinho, A. Sardinha, F. Melo. Making friends in the dark: Ad hoc teamwork under partial observability. In _Proc. 26th Eur. Conf. Artificial Intelligence_, pp. 1954-1961, 2023. ([pdf](/pubs/ribeiro23ecai.pdf))

P. Santos, D. Carvalho, M. Vasco, A. Sardinha, P. Santos, A. Paiva, F. Melo. Centralized training with hybrid execution in multi-agent reinforcement learning. In _Proc. 23rd Int. Conf. Autonomous Agents and Multiagent Systems_, pp. 2453-2455, 2024. ([pdf](/pubs/santos24aamas.pdf))

M. Vasco, H. Yin, F. Melo, A. Paiva. "How to sense the world": Leveraging hierarchy in multimodal perception for robust reinforcement learning agents. In _Proc. 21st Int. Conf. Autonomous Agents and Multiagent Systems_, pp. 1301-1309, 2022. ([pdf](/pubs/vasco22aamas.pdf))

F. Vital, M. Vasco, A. Sardinha, F. Melo. Perceive, represent, generate: Translating multimodal information to robotic motion trajectories”. In _Proc. 2022 IEEE/RSJ Int. Conf. Intelligent Robots and Systems_, pp. 5855-5860, 2022. ([pdf](/pubs/vital22iros.pdf))

G. Varela, A. Sardinha, F. Melo. Distributed value decomposition networks with networked agents. In _Proc. 24th Int. Conf. Autonomous Agents and Multiagent Systems_, pp. 2774-2776, 2025. ([pdf](/pubs/varela25aamas-b.pdf))

G. Varela, A. Sardinha, F. Melo. Networked agents in the dark: Team value learning under partial observability. In _Proc. 24th Int. Conf. Autonomous Agents and Multiagent Systems_, pp. 2087-2095, 2025. ([pdf](/pubs/varela25aamas-a.pdf))

F. Vital, A. Sardinha, F. Melo. Implicit repair with reinforcement learning in emergent communication. In _Proc. 24th Int. Conf. Autonomous Agents and Multiagent Systems_, pp. 2115-2124, 2025. ([pdf](/pubs/vital25aamas.pdf))

R. Zayanov, F. Melo, M. Lopes. Interactively teaching an inverse reinforcement learner with limited feedback. In _Proc. 16th Int. Conf. Agents and Artificial Intelligence_, pp. 15-24, 2024. ([pdf](/pubs/zayanov24icaart.pdf))

### National conferences

B. Esteves, M. Vasco, F. Melo. Pre-training with augmentations for efficient transfer in model-based reinforcement learning”. In: _Proc. 22nd EPIA Conf. Artificial Intelligence_, pp. 133–145, 2023. ([pdf](/pubs/esteves23epia.pdf))

A. Neves, A. Sardinha. Learning to cooperate with completely unknown teammates. In: _Proc. 21st EPIA Conf. Artificial Intelligence_, pp. 739-750, 2022. ([pdf](/pubs/neves22epia.pdf))

J. Silvestrin, J., Melo, F., and Lopes, M. “A comparative study of continual backpropagation”.
In: Proc. 23rd EPIA Conf. Artificial Intelligence. 2024, pp. 324–334. ([pdf](/pubs/silvestrin24epia.pdf))

### PhD theses

J. Ribeiro. _Ad Hoc Teamwork in Realistic Environments_. PhD thesis, Instituto Superior Técnico, Univ. Lisboa, 2025.

M. Vasco. _Multimodal Representation Learning for Agent Perception and Action_. PhD thesis, Instituto Superior Técnico, Univ. Lisboa, 2023.

### MSc theses

S. Carvalho. _Using autonomous vehicles to improve traffic conditions_. MSc thesis, Instituto Superior Técnico, Univ. Lisboa, 2022.

B. Esteves. _Efficient transfer in model-based reinforcement learning_. MSc thesis, Instituto Superior Técnico, Univ. Lisboa, 2022.

A. Fernandes. _Leveraging deep unsupervised models towards learning robust multimodal representations_. MSc thesis, Instituto Superior Técnico, Univ. Lisboa, 2023.

G. Jardim. _Using feudal hierarchies for non-stationary reinforcement learning_. MSc thesis, Instituto Superior Técnico, Univ. Lisboa, 2024.

E. Paiva. _Using deep model-based RL in ad hoc teamwork with partial observability_. MSc thesis, Instituto Superior Técnico, Univ. Lisboa, 2023.

G. Querido. _Learning to perceive in deep model-free reinforcement learning_. MSc thesis, Instituto Superior Técnico, Univ. Lisboa, 2022.

G. Salvador. _Discounting strategies for planning in hazardous environments_. MSc thesis, Instituto Superior Técnico, Univ. Lisboa, 2024.

R. Zayanov. _Interactively teaching an inverse reinforcement learner with limited feedback_. MSc thesis, Instituto Superior Técnico, Univ. Lisboa, 2022. 

### Datasets and software

M. Vasco, H. Yin, Francisco S. Melo, A. Paiva. (2022) [Multimodal Handwritten Digits (MHD) dataset](https://github.com/miguelsvasco/multimodal-handwritten-digits)
