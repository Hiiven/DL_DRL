# DL-DRL
***
The code of "DL-DRL: A double-layer deep reinforcement learning approach for large-scale task scheduling of multi-UAV"
# Get Started
***
1. Install python 3.8, pytorch 1.9.0
2. Train the model. We provide the scripts of different number of UAVs under different folders as follows:
```python
# UAV4
./U4_upper/run.py
# UAV6
./U6_upper/run.py
```
3. Modification of hyperparameters, We provide the scripts of different number of UAVs under different folders as follows:
```python
# lower-level model
./lower/options.py
# upper-level model of UAV4
./U4_upper/options.py
# upper-level model of UAV6
./U6_upper/options.py
```