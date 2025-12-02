---
permalink: /paper-reading-ai-for-em-design
title: ""
excerpt: ""
author_profile: true

---


# 📝 AI for Electromagnetics Design

 - `IEEE Trans. Antennas Propag. 2022` **Multibranch Machine Learning-Assisted Optimization and Its Application to Antenna Design**. [PDF](reading/chen-multibranch-machine-learning-assisted-optimization-and-its-application-to-antenna-design.pdf) *TL;DR: Proposes a multibranch machine learning-assisted optimization (MB-MLAO) framework using a multifidelity GPR surrogate with multiple LCB branches plus retraining and reprediction, significantly reducing high-fidelity EM simulations while keeping antenna design and worst-case performance searches robust and efficiently convergent.*
 - `IEEE Trans. Ind. Electron. 2025` **Reinforcement Learning-Based Predictive Control for Power Electronic Converters**. [PDF](reading/wan-reinforcement-learning-based-predictive-control-for-power-electronic-converters.pdf) *TL;DR: Uses reinforcement learning in two ways for finite-set MPC of converters—DDPG to automatically tune weighting factors for different THD/switching-frequency trade-offs, and a DQN-based imitation controller that learns the optimal switching policy without any system model—both trained offline and experimentally validated to match conventional FS-MPC performance with lower design effort and online complexity.* 
 - `IEEE Trans. Ind. Electron. 2025` **Generative Physics Informed Machine Learning Method for DC-Link Capacitance Estimation**. [PDF](reading/qie-generative-physics-informed-machine-learning-method-for-dc-link-capacitance-estimation.pdf) *TL;DR: Proposes a GPIML framework that fuses diffusion-model-based data generation with a physics-informed LSTM to estimate dc-link capacitance during precharging. The diffusion model expands a small experimental dataset (50 traces) into physically consistent synthetic data, while the PILSTM enforces both statistical learning and capacitor PDE constraints. Experiments on traction hardware show >99.9% accuracy, fast convergence, strong noise robustness, and superior generalization over RLS/RELS, even for capacitance values unseen during training.*