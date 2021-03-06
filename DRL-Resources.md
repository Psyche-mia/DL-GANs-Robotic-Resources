# DRL-Resources
Deep Reinforcement Learning Resources

## DRL Implementations
- **RL code resources**, [[github]](https://github.com/TheMTank/RL-code-resources).
- **DRL Hands-On**, implemented using Pytorch, [[github]](https://github.com/PacktPublishing/Deep-Reinforcement-Learning-Hands-On)
- **Pytorch-RL** [[github]](https://github.com/Psyche-mia/pytorch-rl)
- **OpenAI baselines**, implemented using Tensorflow, [[github]](https://github.com/openai/baselines)
- **Stable baselines**, implemented using Tensorflow, A Fork of OpenAI baselines, [[github]](https://github.com/hill-a/stable-baselines), [[docs]](https://stable-baselines.readthedocs.io/en/master/guide/install.html)

## Task Learning papers
- **A Learning framework for high precision industrial assembly**, UC Berkely, [[paper]](https://arxiv.org/pdf/1809.08548.pdf)

## RL algorithm papers

### Meta Reinforcement Learning

- **Meta Reinforcement Learning introduction**, [[blog]](https://lilianweng.github.io/lil-log/2019/06/23/meta-reinforcement-learning.html)[[Meta-Learning: Learning to Learn Fast]](https://lilianweng.github.io/lil-log/2018/11/30/meta-learning.html)
- **Meta-RL code (Meta-RL A3C algorithm)**, [[github]](https://github.com/Psyche-mia/Meta-RL)

### Hierachical RL

- **Learning Multi-level hierachies with hindsight**, [[paper]](https://openreview.net/pdf?id=ryzECoAcY7)

### Multi-Agent RL

- **Multi-Agent RL papers**, [[github]](https://github.com/Psyche-mia/MARL-Papers)


### Policy gradient 

- **A survey on policy search algorithms for learning robotics**, [[paper]](https://arxiv.org/pdf/1807.02303.pdf)

## OpenAI Gym

- **OpenAI Wiki**, [[website]](https://github.com/openai/gym/wiki/Environments)

### MuJoCo
- **Download**, [[website]](http://www.mujoco.org/)
- **Using MuJoCo from Python3: mujoco-py**, Including MuJoCo installation steps, [[github]](https://github.com/openai/mujoco-py)

*Solve errors you may encounter installing mujoco-py on Ubuntu:* 
1. Install from repo by ```pip3 install -e .```
1. Remember to add ```EXPORT LD_LIBRARY_PATH=$HOME/.mujoco/mujoco200/bin``` to ~/.bashrc
2. [[Ubuntu installtion troubleshooting]](https://github.com/openai/mujoco-py) 
3. [[Missing Package patchelf]](https://github.com/openai/mujoco-py/issues/147)

- **MuJoCo Wiki**, [[website]](http://mujoco.org/book/index.html)
- **mujoco-py API reference**, [[website]](https://openai.github.io/mujoco-py/build/html/reference.html#mjsim-basic-simulation)

#### Environment
- **Fetch Environment Introduction**, [[website]](https://openai.com/blog/ingredients-for-robotics-research/)
- **Setting up a custom gym Mujoco environment**, [[website]](https://www.andrewszot.com/blog/machine_learning/reinforcement_learning/gym_with_mujoco)
- **Set up custom openai gym env with mujoco**, [[website]](http://deepwater.xin/wp-content/uploads/2019/02/set%20up%20custom%20openai%20gym%20env%20with%20mujoco.html)
- **OpenAI gym with mujoco-py**, [[website]](https://gemst1.github.io/1-OpenaiGym-mujoco-py)
- **Add new environment**, [[website]](https://github.com/openai/gym/wiki/Environments) (*Out of date. No scoreboard in gym)
