# Local LLM Benchmark

## Settings

| Setting       | Value                    |
| ------------- | ------------------------ |
| System Prompt | Default Benchmark Prompt |
| Temperature   | 0.2                      |
| Hardware      | Ryzen 7 7700 / CPU       |
| Quantization  | Mixed (mostly Q4_K_M)    |
| Date          | 2026-07-29               |

---

## Score Legend

| Score | Meaning   |
| ----: | --------- |
|  9–10 | Excellent |
|   7–8 | Good      |
|   5–6 | Average   |
|   3–4 | Weak      |
|   1–2 | Poor      |

---

## Benchmark Results

| Model                                                        | General | Reasoning | Coding | Debugging | Writing | Math | Instruction Following | Hallucination | Context | Long Output |
| ------------------------------------------------------------ | :-----: | :-------: | :----: | :-------: | :-----: | :--: | :-------------------: | :-----------: | :-----: | :---------: |
| GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-V2-Thinking-GGUF:Q8_0 |    3    |     2     |   4    |     5     |    5    |  5   |           1           |       5       |    2    |      2      |
| HuggingFaceTB/SmolLM2-1.7B-Instruct-GGUF:Q4_K_M              |    4    |     5     |   7    |           |         |      |                       |               |         |             |
| Qwen/Qwen2.5-0.5B-Instruct-GGUF:Q4_K_M                       |         |           |        |           |         |      |                       |               |         |             |
| Qwen/Qwen2.5-1.5B-Instruct-GGUF:Q4_K_M                       |         |           |        |           |         |      |                       |               |         |             |
| Qwen/Qwen2.5-3B-Instruct-GGUF:Q4_K_M                         |         |           |        |           |         |      |                       |               |         |             |
| Qwen/Qwen2.5-7B-Instruct-GGUF:Q4_K_M                         |         |           |        |           |         |      |                       |               |         |             |
| Qwen/Qwen2.5-Coder-0.5B-Instruct-GGUF:Q4_K_M                 |         |           |        |           |         |      |                       |               |         |             |
| Qwen/Qwen2.5-Coder-1.5B-Instruct-GGUF:Q4_K_M                 |         |           |        |           |         |      |                       |               |         |             |
| Qwen/Qwen2.5-Coder-3B-Instruct-GGUF:Q4_K_M                   |         |           |        |           |         |      |                       |               |         |             |
| Qwen/Qwen2.5-Coder-7B-Instruct-GGUF:Q4_K_M                   |         |           |        |           |         |      |                       |               |         |             |
| Qwen/Qwen3-0.6B-GGUF:Q8_0                                    |         |           |        |           |         |      |                       |               |         |             |
| Qwen/Qwen3-1.7B-GGUF:Q8_0                                    |         |           |        |           |         |      |                       |               |         |             |
| Qwen/Qwen3-4B-GGUF:Q4_K_M                                    |         |           |        |           |         |      |                       |               |         |             |
| Qwen/Qwen3-8B-GGUF:Q4_K_M                                    |         |           |        |           |         |      |                       |               |         |             |
| bartowski/DeepSeek-R1-Distill-Llama-8B-GGUF:Q4_K_M           |         |           |        |           |         |      |                       |               |         |             |
| bartowski/DeepSeek-R1-Distill-Qwen-7B-GGUF:Q4_K_M            |         |           |        |           |         |      |                       |               |         |             |
| bartowski/HuggingFaceTB_SmolLM3-3B-GGUF:Q4_K_M               |         |           |        |           |         |      |                       |               |         |             |
| bartowski/Llama-3.2-1B-Instruct-GGUF                         |         |           |        |           |         |      |                       |               |         |             |
| bartowski/Llama-3.2-3B-Instruct-GGUF                         |         |           |        |           |         |      |                       |               |         |             |
| bartowski/Meta-Llama-3.1-8B-Instruct-GGUF:Q4_K_M             |         |           |        |           |         |      |                       |               |         |             |
| bartowski/Mistral-7B-Instruct-v0.3-GGUF:Q4_K_M               |         |           |        |           |         |      |                       |               |         |             |
| bartowski/Phi-3.1-mini-4k-instruct-GGUF:Q4_K_M               |         |           |        |           |         |      |                       |               |         |             |
| ggml-org/gemma-3-1b-it-GGUF:Q4_K_M                           |         |           |        |           |         |      |                       |               |         |             |
| ggml-org/gemma-3-4b-it-GGUF:Q4_K_M                           |         |           |        |           |         |      |                       |               |         |             |
| ggml-org/gemma-4-E2B-it-GGUF:Q4_0                            |         |           |        |           |         |      |                       |               |         |             |
| ggml-org/gemma-4-E4B-it-GGUF:Q4_0                            |         |           |        |           |         |      |                       |               |         |             |
| ibm-granite/granite-3.3-2b-instruct-GGUF:Q4_K_M              |         |           |        |           |         |      |                       |               |         |             |
| ibm-granite/granite-3.3-8b-instruct-GGUF:Q4_K_M              |         |           |        |           |         |      |                       |               |         |             |
| ibm-granite/granite-3b-code-instruct-2k-GGUF:Q4_K_M          |         |           |        |           |         |      |                       |               |         |             |
| ibm-granite/granite-8b-code-instruct-4k-GGUF:Q4_K_M          |         |           |        |           |         |      |                       |               |         |             |
| unsloth/Phi-4-mini-instruct-GGUF:Q4_K_M                      |         |           |        |           |         |      |                       |               |         |             |
| unsloth/Phi-4-mini-reasoning-GGUF:Q4_K_M                     |         |           |        |           |         |      |                       |               |         |             |

---

## Final Keepers

### ⭐ Must Keep

-

### 👍 Nice to Have

-

### 🤔 Unsure

-

### ❌ Delete

- ***

## Personal Notes

- Fastest model:
- Best coding model:
- Best writing model:
- Best reasoning model:
- Best tiny model:
- Best overall:
- Biggest surprise:
- Biggest disappointment:
