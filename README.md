# reinforce_project
# Isaac Lab Ant PPO Project

## Environment

- OS: Ubuntu 22.04 
- Python: 3.10
- CUDA / GPU: RTX 5080

## 가상환경 실행

source ~/isaaclab/bin/activate
cd ~/IsaacLab

# 학습 실행

./isaaclab.sh -p scripts/reinforcement_learning/rsl_rl/train.py --task=Isaac-Ant-v0

# 텐서보드(그래프) 실행

./isaaclab.sh -p -m tensorboard.main --logdir logs/robomimic/ant
