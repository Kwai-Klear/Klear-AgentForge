# Klear-AgentForge: Forging Agentic Intelligence through Posttraining Scaling


---

## News

- **2025-10-23** — Released the **Klear-AgentForge-8B-SFT** checkpoint and published the initial SFT training data. New SOTA results on SWE-bench Verifed *(~8B models)*.
- 
  👉 [Models](https://huggingface.co/Kwai-Klear/Klear-AgentForge-8B-SFT) · [Training Data](#) · [mini-swe-agent-plus](https://github.com/Kwai-Klear/mini-swe-agent-plus)

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
| **Klear-AgentForge-8B-SFT** | **66.5** | **53.0** | **32.0** |

**Note**: Results with * are our reproductions; all other baseline results are from official reports. 

### Coding Performance

| Model | SWE-bench Verified | Aider Polyglot |
|-------|-------------------|----------------|
| Qwen3-30A3B-2507-Instruct | 17.6* | 35.6 |
| Qwen3-8B (Non-Thinking) | 8.0* | 16.4* |
| Qwen3-8B (Thinking) | 9.8* | 17.3* |
| SWE-Mirror-LM-7B  | 22.8 | — |
| SWE-agent-LM-7B | 15.2 | — |
| **Klear-AgentForge-8B-SFT** | **38.2** | **34.2** |




**Note**: Results with * are our reproductions; all other baseline results are from official reports. SWE-bench Verified was evaluated with [mini-swe-agent-plus](https://github.com/Kwai-Klear/mini-swe-agent-plus).

## SFT training data
``` Coming Soon!```


## Contact
For questions or collaborations, please open an issue in this repository.


---
<div align="center">

**Stay tuned for updates!**

⭐ Star this repository to follow our progress

</div>
