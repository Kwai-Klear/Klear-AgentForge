# Klear-AgentForge: Forging Agentic Intelligence through Posttraining Scaling


---

## News
- **2025-11-12** — Released the Klear-AgentForge-8B checkpoint and published our technical report. We present the Klear-AgentForge models, a series of agentic variants based on Qwen3, designed for complex tasks like tool use and coding. Currently, we provide two models:  
  * **Klear-AgentForge-8B-SFT**: Trained from the Qwen3-8B base model via Supervised Fine-Tuning (SFT) on a mixture of data from various agentic tasks.  
  * **Klear-AgentForge-8B**: Further trained from the Klear-AgentForge-8B-SFT model using reinforcement learning, followed by a model merge.

- **2025-10-23** — Released the **Klear-AgentForge-8B-SFT** checkpoint and published the initial SFT training data. New SOTA results on SWE-bench Verifed *(~8B models)*.

👉 [Klear-AgentForge-8B](https://huggingface.co/Kwai-Klear/Klear-AgentForge-8B) ·  
[Klear-AgentForge-8B-SFT](https://huggingface.co/Kwai-Klear/Klear-AgentForge-8B-SFT) ·  
[Training Data](https://huggingface.co/datasets/Kwai-Klear/SWE-smith-mini_swe_agent_plus-trajectories-66k) ·  
[mini-swe-agent-plus](https://github.com/Kwai-Klear/mini-swe-agent-plus)
---


## Overview
Our research project Klear-AgentForge focuses on developing agentic AI capabilities through systematic post-training scaling. We will progressively update and opensource our models, data and training recipes.

## Models
``` Coming Soon!```


## Evaluation results

### Tool Use Performance

| Model | BFCL v3 | Tau Bench Retail | Tau Bench Airline |
|-------|---------|------------------|-------------------|
| Qwen3-30A3B-2507-Instruct | 65.1 | 59.1 | 40.0 |
| Qwen3-30A3B-2507-Thinking | 72.4 | 67.8 | 48.0 |
| Qwen3-8B (Non-Thinking) | 60.2* | 35.7* | 12.0* |
| Qwen3-8B (Thinking) | 68.1* | 45.2 | 25.0 |
| xLAM-2-8B-fc-r  | 72.8 | 58.2 | 35.2 |
| AgentScaler-8B | — | 50.2 | 42.0 |
| **Klear-AgentForge-8B** | **71.5** | **56.7** | **41.5** |

**Note**: Results with * are our reproductions; all other baseline results are from official reports. 

### Coding Performance

| Model | SWE-bench Verified | Aider Polyglot |
|-------|-------------------|----------------|
| Qwen3-30A3B-2507-Instruct | 17.6* | 35.6 |
| Qwen3-8B (Non-Thinking) | 8.0* | 16.4* |
| Qwen3-8B (Thinking) | 9.8* | 17.3* |
| SWE-Mirror-LM-7B  | 22.8 | — |
| SWE-agent-LM-7B | 15.2 | — |
| **Klear-AgentForge-8B** | **39.4** | **33.8** |




**Note**: Results with * are our reproductions; all other baseline results are from official reports. SWE-bench Verified was evaluated with [mini-swe-agent-plus](https://github.com/Kwai-Klear/mini-swe-agent-plus).

## SFT training data

**[SWE-smith-mini_swe_agent_plus-trajectories-66k](https://huggingface.co/datasets/Kwai-Klear/SWE-smith-mini_swe_agent_plus-trajectories-66k)** 



## Contact
For questions or collaborations, please open an issue in this repository.

## Citation
If you find this project is useful in your own work, please consider citing as follows:
```
@misc{klear_codetest,
    title = {Klear-AgentForge: Forging Agentic Intelligence through Posttraining Scaling},
    url = {https://github.com/Kwai-Klear/Klear-AgentForge},
    author = {{Qi Wang, Hongzhi Zhang, Jia Fu, Kai Fu, Yahui Liu, Tinghai Zhang, Chenxi Sun, Gangwei Jiang, Jingyi Tang, Xingguang Ji, Yang Yue, Jingyuan Zhang, Fuzheng Zhang, Kun Gai, Guorui Zhou}},
    month = {November},
    year = {2025}
}
```


---
<div align="center">

**Stay tuned for updates!**

⭐ Star this repository to follow our progress

</div>
