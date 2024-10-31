# A Survey Analyzing Generalization in Deep Reinforcement Learning

Reinforcement learning research obtained significant success and attention with the utilization of deep neural networks to solve problems in high dimensional state or action spaces. While deep reinforcement learning policies are currently being deployed in many different fields from medical applications to self-driving vehicles, there are still ongoing questions the field is trying to answer on the generalization capabilities of deep reinforcement learning policies. In this paper, we will outline the fundamental reasons why deep reinforcement learning policies encounter overfitting problems that limit their robustness and generalization capabilities. Furthermore, we will formalize and unify the diverse solution approaches to increase generalization, and overcome overfitting in state-action value functions. We believe our study can provide a compact systematic unified analysis for the current advancements in deep reinforcement learning, and help to construct robust deep neural policies with improved generalization abilities. 


This repository contains the outline of the [survey](https://arxiv.org/pdf/2401.02349v2) with relevant links. See the [paper](https://arxiv.org/pdf/2401.02349v2) here for more details.



```
@article{korkmazrlsurvey24,
    title={A Survey Analyzing Generalization in Deep Reinforcement Learning},
    author={Ezgi Korkmaz},
    journal={https://arxiv.org/pdf/2401.02349v2},
    year={2024}
}
```



### 1. How to Achieve Generalization?
See the [paper](https://arxiv.org/pdf/2401.02349.pdf) for a formal definition of generalization in deep reinforcement learning.


### 2. Roots of Overestimation in Deep Reinforcement Learning

+ Issues in using function approximation for reinforcement learning, 1993.
[[Paper]](https://www.ri.cmu.edu/pub_files/pub1/thrun_sebastian_1993_1/thrun_sebastian_1993_1.pdf)
  
+ Generalization in Reinforcement Learning : Safely approximating the value function, NeurIPS 1994.
[[Paper]](https://proceedings.neurips.cc/paper_files/paper/1994/file/ef50c335cca9f340bde656363ebd02fd-Paper.pdf)
  
+ Double Q-learning, NeurIPS 2010.
[[Paper]](https://proceedings.neurips.cc/paper_files/paper/2010/file/091d584fced301b442654dd8c23b3fc9-Paper.pdf)

+ Deep reinforcement learning with double Q-learning, AAAI 2016.
[[Paper]](https://arxiv.org/pdf/1509.06461.pdf)

### 3. The Role of Exploration in Overfitting

+ Unifying count-based exploration and intrinsic motivation.
[[Paper]](https://dl.acm.org/doi/pdf/10.5555/3157096.3157262)

+ Generalization and exploration via randomized value functions, ICML 2016.
[[Paper]](https://proceedings.mlr.press/v48/osband16.pdf)

+ Deep exploration via bootstrapped DQN, NeurIPS 2016.
[[Paper]](https://papers.nips.cc/paper_files/paper/2016/file/8d8818c8e140c64c743113f563cf750f-Paper.pdf)

+ VIME: variational information maximizing exploration, ICML 2017.
[[Paper]](https://dl.acm.org/doi/pdf/10.5555/3157096.3157221)

+ Noisy networks for exploration, ICLR 2018.
[[Paper]](https://openreview.net/pdf?id=rywHCPkAW)

+ SUNRISE: A simple unified framework for ensemble learning in deep reinforcement learning, ICML 2021.
[[Paper]](https://proceedings.mlr.press/v139/lee21g/lee21g.pdf)


### 4. Regularization

#### 4.1.  Data Augmentation

+ Improving generalization in reinforcement learning with mixture regularization, NeurIPS 2020.
[[Paper]](https://proceedings.neurips.cc/paper/2020/file/5a751d6a0b6ef05cfe51b86e5d1458e6-Paper.pdf) 

+ CURL: contrastive unsupervised representations for reinforcement learning, ICML 2020.
[[Paper]](https://proceedings.mlr.press/v119/laskin20a/laskin20a.pdf)

+ Reinforcement learning with augmented data, NeurIPS 2020.
[[Paper]](https://proceedings.neurips.cc/paper/2020/file/e615c82aba461681ade82da2da38004a-Paper.pdf)

+ Improving generalization in RL with mixture regularization, NeurIPS 2020.
[[Paper]](https://proceedings.neurips.cc/paper/2020/file/5a751d6a0b6ef05cfe51b86e5d1458e6-Paper.pdf)






#### 4.2. Direct Function Regularization

+ Munchausen Reinforcement Learning, NeurIPS 2020.
[[Paper]](https://proceedings.neurips.cc/paper/2020/file/2c6a0bae0f071cbbf0bb3d5b11d90a82-Paper.pdf)

+ Network randomization: A simple technique for generalization in deep reinforcement learning, ICLR 2020.
[[Paper]](https://openreview.net/pdf?id=HJgcvJBFvB)

+ Discount factor as a regularizer in Reinforcement Learning, ICML 2020.
[[Paper]](https://proceedings.mlr.press/v119/amit20a/amit20a.pdf)

+ Contrastive behavioral similarity embeddings for generalization in reinforcement learning, ICLR 2021.
[[Paper]](https://openreview.net/pdf?id=qda7-sVg84)

+ Regularization matters in policy optimization an empirical study on continuous control, ICLR 2021.
[[Paper]](https://openreview.net/pdf?id=yr1mzrH3IC)

#### 4.3. The Adversarial Perspective for Deep Reinforcement Learning Generalization

+ Adversarial Attacks on Neural Network Policies. ICLR Workshop 2017. [[Paper]](https://openreview.net/pdf?id=ryvlRyBKl)

+ Robust Adversarial Reinforcement Learning. ICML 2017. [[Paper]](http://proceedings.mlr.press/v70/pinto17a/pinto17a.pdf)

+ Adversarial Policies: Attacking Deep Reinforcement Learning. ICLR 2020. [[Paper]](https://openreview.net/pdf?id=HJgEMpVFwB)

+ Investigating Vulnerabilities of Deep Neural Policies. UAI 2021. [[Paper]](https://proceedings.mlr.press/v161/korkmaz21a.html)

+ Deep Reinforcement Learning Policies Learn Shared Adversarial Features Across MDPs. AAAI 2022. [[Paper]](https://aaai.org/papers/07229-deep-reinforcement-learning-policies-learn-shared-adversarial-features-across-mdps/)

+ Adversarial Robust Deep Reinforcement Learning Requires Redefining Robustness. AAAI 2023. [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/26009)

+ Detecting Adversarial Directions in Deep Reinforcement Learning to Make Robust Decisions. ICML 2023. [[Paper]](https://proceedings.mlr.press/v202/korkmaz23a.html)



### 5. Meta-Reinforcement Learning and Meta Gradients

+ Discovering reinforcement learning algorithms, NeurIPS 2020.
  
+ Meta-gradient reinforcement learning with an objective discovered online, NeurIPS 2020.
  
+ Discovery of options via meta-learned subgoals, NeurIPS 2021.
  
+ Introducing symmetries to black box meta reinforcement learning, AAAI 2022.

### 6. Lifelong Reinforcement Learning

+ A meta-mdp approach to exploration for lifelong reinforcement learning, NeurIPS 2019.
  
+ Lifelong learning with a changing action set, AAAI 2020.
  
+ Lipschitz lifelong Reinforcement Learning, AAAI 2021.

### 7. Inverse Reinforcement Learning

+ Algorithms for inverse reinforcement learning, ICML 2000.
  
+ IQ-learn: Inverse soft-Q learning for imitation, NeurIPS 2021.
