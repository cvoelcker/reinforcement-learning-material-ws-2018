# Reinforcement Learning material for the winter semester 2018
This repository collects supplementary material to study reinforcement learning with a focus on topics covered by the TU Darmstadt IAS lecture on reinforcement learning.

The repository is structured by topics and is basically a collection of ressources which explain or highlight different algorithms and theories covered in the lecture. All material should be categorized into four different tiers: introductory light reading (i.e. medium posts, non-scientific tutorials), research papers (preferably with arxiv links), textbooks (only if they are available via ULB Darmstadt) and code examples.

## Materials by topic

### Background and general foundations

- [TUTORIAL] Matrix cookbook: https://www.math.uwaterloo.ca/~hwolkowi/matrixcookbook.pdf
  - All the pesky matrix and vector gradients, but only useful as a cheatsheet, not as an accessible introduction.
- [TUTORIAL] Lagrangian quickly explained (argmin blog): http://www.argmin.net/2016/05/31/mechanics-of-lagrangians/
  - A very nice and painless intro to lagrangian optimization. Interestingly, you can even derive backprop via lagrangian methods http://www.argmin.net/2016/05/18/mates-of-costate/

### Foundations of MDP and reinforcement learning

- [GITHUB] awesome-rl https://github.com/aikorea/awesome-rl
  - List with a similar focus, and many awesome papers
- [BOOK] THE Sutton book http://incompleteideas.net/book/bookdraft2017nov5.pdf
  - Very good for the intuition, slightly less mathy then Jan Peters' general approach
- [BOOK] Algorithms for Reinforcement Learning https://sites.ualberta.ca/~szepesva/papers/RLAlgsInMDPs.pdf
  - As the name says, an introduction with a strong algorithmic focus
- [TUTORIAL] Outsider's intro to RL (arg min blog): http://www.argmin.net/2018/06/25/outsider-rl/
  - Very detailed in depth tour through reinforcement learning from a strong optimization point of view. Highly opinionated at times, but incredibly interesting. Specific highlights include
   an LQR introduction http://www.argmin.net/2018/02/08/lqr/, a brutal takedown of policy gradient (not necessarily true, but very interesting nonetheless) 
   http://www.argmin.net/2018/02/26/nominal/, a PID control introduction for those who slept through CER http://www.argmin.net/2018/04/19/pid/
- [Tutorial] Jonathan Hui's RL Series: https://medium.com/@jonathan_hui/rl-deep-reinforcement-learning-series-833319a95530
  - Pretty Accessable, explains the background and intuition well
- [PAPER] Survey on RL for Robotics https://www.ias.informatik.tu-darmstadt.de/uploads/Publications/Kober_IJRR_2013.pdf
  - Since it is (co) written by Jan Peters, I expected some references to the Lagrangian and was not disappointed. Section 
   2.2.1 explains the appearance of the Lagrangian and it's relation to the value function in a short but very understandable 
   way

### Policy and value iteration

- [PAPER] Approximate Dynamic Programming with GP: http://mlg.eng.cam.ac.uk/pub/pdf/DeiPetRas08.pdf
  - Jan Peters' paper on Dynamic Programming using Gaussian Processes. Discusses dynamic programming shortly and highlights some of the challenges of state space discretization.

### LQR and classical control


### Temporal difference learning and function approximation

- [PAPER] LSPI introduction paper: http://jmlr.csail.mit.edu/papers/v4/lagoudakis03a.html<Paste>
  - This paper introduces LSPI and gives a tour de force of value function approximation with a strong focus on 
   really explaining projection in value function approximation. One of the best papers I read.
- [PAPER] DQN Nature Paper: https://storage.googleapis.com/deepmind-media/dqn/DQNNaturePaper.pdf
  - This paper gives a good overview of the DQN algorithm as used in the seminal atari video game breakthrough.

### POMDP and filtering

- [PAPER] POMDP introduction paper: https://people.csail.mit.edu/lpk/papers/aij98-pomdp.pdf
  - Leslie Kaelbling's seminal POMDP introduction paper, highlighting a lot of the aspects of the POMDP setting

### Policy Gradient methods

- [PAPER] Policy Gradient Survey https://spiral.imperial.ac.uk:8443/bitstream/10044/1/12051/7/fnt_corrected_2014-8-22.pdf
  - Even though they called this a survey, it is more of a book. Very thorough exploration of the subject.
- [PAPER] REINFORCE paper: http://www-anw.cs.umass.edu/~barto/courses/cs687/williams92simple.pdf
  - The paper introduces the REINFORCE algorithm and gives an introduction to the foundations of policy gradient.
- [PAPER] Natural Gradient paper: https://arxiv.org/pdf/1703.02660.pdf
  - Gives an introduction to natural gradients, but doesn't highlight the derivation or the intuition in detail.
- [PAPER] Natural evolution strategies: http://www.jmlr.org/papers/volume15/wierstra14a/wierstra14a.pdf
  - To be honest, I didn't read it yet
-  [TUTORIAL] Policy Gradient: https://medium.com/@jonathan_hui/rl-policy-gradients-explained-9b13b688b146
  - explained accessible, good start without the complete math
- [Lecture] Policy Search by Pieter Abbeel. Likelihood Ratio Policy Gradient, REINFORCE, Baseline: https://www.youtube.com/watch?v=dEHyTBJ1pSc 
  - slides are available here: https://people.eecs.berkeley.edu/~pabbeel/nips-tutorial-policy-optimization-Schulman-Abbeel.pdf )

## Contribution guidelines

Please feel free to add your own suggestions for interesting material with a short summary on how they are helpful. Just open a pull request to the repository and add all your suggested material to the readme file. Please don't add any papers to the repo, just the relevant links to prevent breaking any copyright issues or cluttering the repository.
