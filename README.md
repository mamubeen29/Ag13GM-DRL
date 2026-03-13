# Ag13GM
# DRL Framework for Ag13 Nanocluster Global Minimum (GM) Search
This repository contains the implementation of the Deep reinforcement learning (DRL) agent, employed for the identification of Ag13 nanoclusters using Deep Reinforcement Learning (DRL). The aims is to efficiently explore GM nanocluster configurations. This is an adapted version of the DRL framework from [clusgym_drl](https://github.com/rajeshkochi444/clusgm_drl) J. Phys. Chem. A 2024, 128, 42, 9122–9134. We thank the authors for making the code available on github. However, our framework has been adapted to tackle the additional challenges that are present for Silver nanoclusters for specific symmetries such as icosahedral. We modified the code to work with Silver nanoclusters.
# How to Run the Code
1.  Set Up the Environment: Install the required Conda environment using the DRLAg13_env.yaml file
    ```
    conda env create -f DRLAg13_env.yml
    ```
2. Run the Simulation:
   ```
   python Ag13.py
   ```
