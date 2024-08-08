# 🌋 LLaVA: Large Language and Vision Assistant with Qwen2 as base language model

Here I modified original LLaVA code to adapt Qwen2 as base language model. Now I have updated starting training scripts under `script\v1_5` folder, for both pretraining phase and fine-tuning phase.
You can start pretraining `llava-qwen2` by following command,
```shell
bash scripts/v1_5/pretrain_qwen2.sh
```
By same mean, you start fine-tuning `llava-qwen2` by this command,
```shell
bash scripts/v1_5/finetune_qwen2.sh
```
For detailed preparation and other questions, please refer [original repo](https://github.com/haotian-liu/LLaVA/blob/c121f0432da27facab705978f83c4ada465e46fd/README.md).

I would love to see you have any modification and creation on my repo! A pull request is all you need.

Thanks original creator for LLaVA project, and other maintainer of this project.
