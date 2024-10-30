# Training language models to follow instructions with human feedback
阅读时间：1015
## Motivation
- InstructGPT（GPT-3.5），通过RLHF对GPT进行Fine-tune
- 其中包括三个步骤：（1）监督微调（SFT），（2）奖励模型（RM）训练，（3）通过奖励模型上的PPO进行强化学习。
Supervised fine-tuning (SFT)：基于标注者提供的样例数据，使用有监督学习微调GPT-3。
## Idea
好难读