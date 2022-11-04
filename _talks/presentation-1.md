---
name: Behavioural Cloning based RL Agents for District Energy Management
speakers:
  - Sharath Ram Kumar
  - Arvind Easwaran
  - Remy Rigo-Mariani
  - Benoit Delinchant
categories:
  - presentation
permalink: "/:collection/:categories/Presentation 1"
---

##### Abstract
In this work, we discuss a method to incorporate domain knowledge into a Reinforcement Learning (RL) environment through the process of behavioral cloning, in the context of a district energy management system. Prior knowledge, encoded into heuristic rule-based programs, is used to initialize a policy network for an RL agent, after which an RL algorithm is used to improve on this by optimizing against a reward function. The key ideas are implemented in the CityLearn framework, where the resulting controller is used to manage the electrical energy storage for 5 buildings in a district. We demonstrate that the resulting agents offer measurable performance gains compared to existing baselines, offering a 3.8% improvement over the underlying rule-based controller, and a 20% improvement over a pure RL based controller. We also illustrate the possibility of using imitation learning to develop agents with desirable characteristics without explicit reward shaping.