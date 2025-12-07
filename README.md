이 저장소는 Isaac Lab Ant 환경에서 PPO를 학습한 강화학습개론 프로젝트의 코드/설정 및 발표자료를 포함한다.

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

## Files

- `ant.zip` : Isaac Lab Ant 환경 및 PPO 설정 파일을 모아둔 압축 파일
- `강화학습프로젝트_14조.pptx` : 프로젝트 보고서
