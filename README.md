# Local AI Model Library

A curated collection of GGUF models for `llama.cpp`.

## Requirements

- `llama.cpp` installed
- Internet connection
- A `models.txt` file containing one model per line

Example:

```txt
Qwen/Qwen2.5-7B-Instruct-GGUF:Q4_K_M
ggml-org/gemma-3-4b-it-GGUF:Q4_K_M
bartowski/Meta-Llama-3.1-8B-Instruct-GGUF:Q4_K_M
```

## Download all models

```bash
xargs -a models.txt -I{} llama download -hf "{}"
```

The command downloads each model in order. Models are cached locally by Hugging Face, so running it again is safe. Previously downloaded models will be reused instead of downloaded again.

## Notes

- Keep exactly **one model per line** in `models.txt`.
- Do not add empty lines.
- Use trusted publishers such as:
  - Official organizations (e.g. `Qwen`)
  - `ggml-org`
  - `bartowski`
  - `unsloth`

- Prefer CPU-friendly quantizations such as `Q4_K_M` (or `Q4_0` where appropriate).

## Run the server

```bash
llama serve
```

Open the local URL shown in the terminal, then select a downloaded model from the model list.

## Update llama.cpp

```bash
llama update
```
