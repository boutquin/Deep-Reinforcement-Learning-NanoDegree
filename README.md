[image1]: https://user-images.githubusercontent.com/10624937/42135602-b0335606-7d12-11e8-8689-dd1cf9fa11a9.gif "Trained Agents"
[image2]: https://user-images.githubusercontent.com/10624937/42386929-76f671f0-8106-11e8-9376-f17da2ae852e.png "Kernel"

# Deep-Reinforcement-Learning-NanoDegree

![Trained Agents][image1]

Exercices and assignments from Udacity's [Deep Reinforcement Learning Nanodegree](https://www.udacity.com/course/deep-reinforcement-learning-nanodegree--nd893) program.

## Core Exercices
+ - [ ] **01. Monte Carlo Control** 
+ - [ ] **02. Temporal Difference Control**
+ - [ ] **03. Discretization**
+ - [ ] **04. Tile Coding**
+ - [ ] **05. Deep Q-Networks**
+ - [ ] **06. Robotics**
+ - [ ] **07. Hill Climbing**
+ - [ ] **08. Cross Entropy**
+ - [ ] **09. REINFORCE**
+ - [ ] **10. Proximal Policy Optimization (PPO)**
+ - [ ] **11. Deep Deterministic Policy Gradients (DDPG)**
+ - [ ] **12. Multi-Agent DDPG**
+ - [ ] **13. AlphaZero**

## Extra-Curricular Exercices
+ - [ ] **E01. Dynamic Programming**

## Labs and Graded Projects
+ - [ ] **P0. Taxi** - general RL.
+ - [ ] **P1. Navigation** - value-based methods.
+ - [ ] **P2. Continuous Control** - policy-based methods.
+ - [ ] **P3. Collaboration and Competition** - multi-agent RL.

## Dependencies

To set up your python environment to run the code in this repository, follow the instructions below.

1. Create (and activate) a new environment with Python 3.6, either using Anaconda Navigtor or with:

	- __Linux__ or __Mac__: 
	```bash
	conda create --name drlnd python=3.6
	source activate drlnd
	```
	- __Windows__: 
	```bash
	conda create --name drlnd python=3.6 
	activate drlnd
	```
	
2. Follow the instructions in [this repository](https://github.com/openai/gym) to perform a minimal install of OpenAI gym.  
	- Next, install the **classic control** environment group by following the instructions [here](https://github.com/openai/gym#classic-control).
	- Then, install the **box2d** environment group by following the instructions [here](https://github.com/openai/gym#box2d).
	
3. Clone the repository (if you haven't already!), and navigate to the `python/` folder.  Then, install several dependencies.
```bash
git clone https://github.com/boutquin/Deep-Reinforcement-Learning-NanoDegree.git
cd Deep-Reinforcement-Learning-NanoDegree/python
pip install .
```

4. Create an [IPython kernel](http://ipython.readthedocs.io/en/stable/install/kernel_install.html) for the `drlnd` environment.  
```bash
python -m ipykernel install --user --name drlnd --display-name "drlnd"
```

5. Before running code in a notebook, change the kernel to match the `drlnd` environment by using the drop-down `Kernel` menu. 

![Kernel][image2]
