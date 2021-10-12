# Multi-Agent Reinforcement Learning for Coordinated Patrol

Class project for "Advanced Topics in Machine Learning and Game Theory" - Graduate Course, CMU. Acknowledgment: The installation instructions and the game environment are based on an REU project by Benjamin Carman.

### Environment Setup Progress
- [x] conda an environment set up - gym installed but:
- [ ] fix error with gym - installed from pip but throws error "no module named gym" when running the environment with the command bin/interactive.py --scenario simple.py
- [ ] fix issue with tensorflow 1.8.0? not found by pip, 1.x no longer actively supported, 2.x not backcompatible, discussion ongoing in docs/class
- [ ] fix issue with numpy 1.14.5 massive error when pip tries to install
- [x] cloned (as submodule) multiagent-particle-envs repo
- [x] cloned (as submodule) maddpg repo
