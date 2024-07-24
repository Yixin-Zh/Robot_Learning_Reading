# Robot-Learning-Reading

## Overview


- [Robot-Learning-Reading](#robot-learning-reading)
  - [Overview](#overview)
  - [Surveys](#surveys)
  - [Planning \& Reasoning](#planning--reasoning)
    - [Applications](#applications)
    - [Classic + Learning](#classic--learning)
    - [Reasoning](#reasoning)
  - [Manipulation](#manipulation)
    - [Skills](#skills)
    - [Online Learning](#online-learning)
    - [Imitation Learning](#imitation-learning)
    - [Scene Understanding](#scene-understanding)
    - [Chaining](#chaining)
    - [Diffuser](#diffuser)
    - [Key Point Descriptions](#key-point-descriptions)
  - [Not yet included](#not-yet-included)

## Surveys
- "Understanding the planning of LLM agents: A survey", *arXiv, Feb 2024.* [[Paper](https://arxiv.org/abs/2402.02716)]
- "Integrated Task and Motion Planning", *arXiv, Oct 2020.* [[Paper](https://arxiv.org/pdf/2010.01083)]
- "A Survey of Optimization-based Task and Motion Planning: From Classical To Learning Approaches", *arXiv, Apr 2024.*  [[Paper](https://arxiv.org/pdf/2404.02817)]
## Planning & Reasoning
### Applications
- **FLAIR:** "Feeding via Long-horizon AcquIsition of Realistic dishes", *Robotic Science and Systems (RSS), 2024*. [[Website](https://flair-robot.github.io/)] [[Paper](https://flair-robot.github.io/assets/flair.pdf)]
- **DAG-Plan:** "Generating Directed Acyclic Dependency Graphs for Dual-Arm Cooperative Planning", *arXiv, June 2024*. [[Paper](https://arxiv.org/pdf/2406.09953)]
- **PIGINet:** "A Transformer-based Plan Feasibility Predictor for Robotic Rearrangement in Geometrically Complex Environments", *Robotic Science and Systems (RSS), 2023*. [[Website](https://piginet.github.io/)] [[Paper](https://arxiv.org/pdf/2211.01576)] [[Code](https://github.com/Learning-and-Intelligent-Systems/kitchen-worlds)]
### Classic + Learning
- **PDSketch:** "Integrated Domain Programming, Learning, and Planning", *NeurIPS, 2022*. [[Website](https://pdsketch.csail.mit.edu/)] [[Paper](https://arxiv.org/pdf/2303.05501)] [[Code](https://github.com/vacancy/PDSketch-Alpha-Release)]
### Reasoning
- "Learning Reusable Manipulation Strategies", *Conference on Robot Learning (CoRL), 2023*.  [[Paper](https://arxiv.org/pdf/2311.03293)]
- "Large Language Models as General Pattern Machines", *arXiv, Oct 2023.* [[Website](https://general-pattern-machines.github.io/)] [[Paper](https://arxiv.org/pdf/2307.04721)]

## Manipulation
### Skills
- **EquiBot:** "SIM(3)-Equivariant Diffusion Policy for Generalizable and Data Efficient Learning", *arXiv, July 2024*. [[Website](https://equi-bot.github.io/)] [[Paper](https://arxiv.org/pdf/2407.01479)]
- **RoboPack:** "Learning Tactile-Informed Dynamics Models for Dense Packing", *Robotic Science and Systems (RSS), 2024*. [[Website](https://robo-pack.github.io/)] [[Paper](https://arxiv.org/pdf/2407.01418)]
- **DP3:** "Generalizable Visuomotor Policy Learning via Simple 3D Representations", *Robotic Science and Systems (RSS), 2024*. [[Website](https://3d-diffusion-policy.github.io/)] [[Paper](https://arxiv.org/pdf/2403.03954)] [[code](https://github.com/YanjieZe/3D-Diffusion-Policy)]
### Online Learning
- **Practice Makes Perfect:** "Planning to Learn Skill Parameter Policies", *Robotic Science and Systems (RSS), 2024*. [[Website](https://ees.csail.mit.edu/)] [[Paper](https://arxiv.org/pdf/2402.15025)] [[Code](https://github.com/bdaiinstitute/predicators/releases/tag/planning-to-practice-ees)]
### Imitation Learning
- **CLIPort:** "What and Where Pathways for Robotic Manipulation", *Conference on Robot Learning (CoRL), 2021*. [[Website](https://cliport.github.io/)] [[Paper](https://arxiv.org/pdf/2109.12098)] [[Code](https://github.com/cliport/cliport)]
- **PerAct:** "Perceiver-Actor: A Multi-Task Transformer for Robotic Manipulation", *Conference on Robot Learning (CoRL), 2022*. [[Website](https://peract.github.io/)] [[Paper](https://peract.github.io/paper/peract_corl2022.pdf)] [[Code](https://github.com/peract/peract)] [[Talk](https://www.youtube.com/watch?v=QcuXwmQgurE&t=3290s)]
- **ChainedDiffuser:** "Unifying Trajectory Diffusion and Keypose Prediction for Robotic Manipulation", *Conference on Robot Learning (CoRL), 2023*. [[Website](https://chained-diffuser.github.io/)] [[Paper](https://openreview.net/pdf?id=W0zgY2mBTA8)] [[Code](https://github.com/zhouxian/act3d-chained-diffuser)]
- **ACT:** "Learning Fine-Grained Bimanual Manipulation with Low-Cost Hardware", *Robotic Science and Systems (RSS), 2023*. [[Website](https://tonyzhaozh.github.io/aloha/)] [[Paper](https://arxiv.org/pdf/2304.13705)] 
- **Act3D:** "3D Feature Field Transformers for Multi-Task Robotic Manipulation", *Conference on Robot Learning (CoRL), 2023*. [[Website](https://act3d.github.io/)] [[Paper](https://arxiv.org/pdf/2306.17817)] [[Code](https://github.com/zhouxian/act3d-chained-diffuser)]
- **Genima**: "Generative Image as Action Models", *arXiv, July 2024*. [[Website](https://genima-robot.github.io/)] [[Paper](https://arxiv.org/pdf/2407.07875)] [[Code](https://github.com/MohitShridhar/genima)]

### Scene Understanding
- **VoxPoser:** Composable 3D Value Maps for Robotic Manipulation with Language Models, *Conference on Robot Learning (CoRL), 2023*. [[Website](https://voxposer.github.io/)] [[Paper](https://voxposer.github.io/voxposer.pdf)] [[Code](https://github.com/huangwl18/VoxPoser)]
- **Clio:** "Real-time Task-Driven Open-Set 3D Scene Graphs", *arXiv, Apr 2024*. [[Paper](https://arxiv.org/pdf/2404.13696)] [[Code](https://github.com/MIT-SPARK/Clio)]
- **VLFM:** "Vision-Language Frontier Maps for Zero-Shot Semantic Navigation", *International Conference on Robotics and Automation (ICRA), 2024*. [[Website](http://naoki.io/portfolio/vlfm)] [[Paper](https://arxiv.org/pdf/2312.03275)] [[Code](https://github.com/bdaiinstitute/vlfm)]
### Chaining
- **Generative Skill Chaining:** "Long-Horizon Skill Planning with Diffusion Models", *Conference on Robot Learning (CoRL), 2023*. [[Website](https://generative-skill-chaining.github.io/)] [[Paper](https://generative-skill-chaining.github.io/assets/2023_Generative_Skill_Chaining.pdf)] [[Code](https://github.com/generative-skill-chaining/gsc-code)]
- **NOD-TAMP:** "Generalizable Long-Horizon Planning with Neural Object Descriptors", *arXiv, Nov 2023*. [[Website](https://nodtamp.github.io/)] [[Paper](https://arxiv.org/pdf/2311.01530)] 

### Diffuser
- **Diffusion Forcing:** "Next-token Prediction Meets Full-Sequence Diffusion", *arXiv, July 2024*. [[Website](https://boyuan.space/diffusion-forcing/)] [[Paper](https://arxiv.org/pdf/2407.01392)] [[Code](https://github.com/buoyancy99/diffusion-forcing)] 

### Key Point Descriptions
- **Neural Descriptor Fields:** "SE(3)-Equivariant Object Representations for Manipulation", *arViv, Dec 2021.* [[Paper](https://arxiv.org/abs/2112.05124)]
- **D3Fields:** "Dynamic 3D Descriptor Fields for Zero-Shot Generalizable Robotic Manipulation", *arXiv, Oct 2023.* [[Website](https://robopil.github.io/d3fields/)] [[Paper](https://robopil.github.io/d3fields/d3fields.pdf)] [[Code](https://github.com/WangYixuan12/d3fields)]
- **kPAM:** "KeyPoint Affordances for Category-Level Robotic Manipulation", *arXiv, Oct 2019*. [[Paper](https://arxiv.org/pdf/1903.06684)]
- **Dense Object Nets:** "Learning Dense Visual Object Descriptors By and For Robotic Manipulation", *arXiv, Sep 2018*. [[Paper](https://arxiv.org/pdf/1806.08756)]
- **DINO-ViT:** "Deep ViT Features as Dense Visual Descriptors", *arXiv, Oct 2022*. [[Paper](https://arxiv.org/pdf/2112.05814)]
## Not yet included
- **Affordance-Centric Policy Decomposition:** "Generalisable and Sample Efficient Robot Policy Learning for Multi-Object, Long-Horizon Manipulation", *Robotic Science and Systems (RSS), 2024*. [[Website](https://policy-decomposition.github.io/)] [[Paper](https://policy-decomposition.github.io/Images/paper.pdf)]
