# COS 435 Final Project – Reinforcement Learning Algorithms  
_Princeton University, Spring 2025_

This repository contains the full code-base and experimental results for our COS 435 final project.  
The work is a joint effort by:

- **Donggeon Oh** — do9948@princeton.edu  
- **Richard Zhou** — rz3911@princeton.edu  
- **Jarod Wille** — jwille@princeton.edu  

---

Acknowledgements:
1. We referenced the skeleton code of Assignment 7, the original SAC paper (Haarnoja et. al., 2018, https://arxiv.org/abs/1812.05905), and the PyTorch implementation of Discor (https://github.com/toshikwa/discor.pytorch) to implement the SAC algorithm.
2. We referenced the original BRO paper (Nauman et. al., 2024, https://arxiv.org/abs/2405.16158), its jax implementation (https://github.com/naumix/BiggerRegularizedOptimistic), and its PyTorch implementation (https://github.com/naumix/BiggerRegularizedOtimistic_Torch) to build upon our SAC implementation and implement the BRO algorithm. We also note that the authors' PyTorch implementation of BRO is not coherent with the original paper or its jax implementation, but is rather an over-simplified version of the jax implementation.
3. We did NOT directly use the aforementioned open-sourced implementations of SAC and BRO for our implementation, although they provided us with insights and hints for debugging purposes. We implemented the neural network classes and the update function ourself.