### Fine-Tuning of Large Language Models (LLMs)

This repository contains two Jupyter notebooks showcasing the fine-tuning of Large Language Models (LLMs) using custom datasets and two different techniques: LoRA and Q-LoRA. The notebooks are named:

1. **Fine_tune_Llama_2.ipynb**
2. **Gemma_Finetuning_notebook.ipynb**

### Large Language Models (LLMs) Used:
- **LLama-2**: LLama meta LLM
- **Gamma**: Google's LLM

### Techniques Utilized:
**1. LoRA (Low-Rank Adaptation):**
- Injects trainable low-dimensional matrices into each layer of the LLM's architecture, typically a Transformer.
- Reduces the number of parameters the model needs to learn, enhancing efficiency.
- Aims to maintain or improve the model's performance on specific tasks compared to training the entire LLM from scratch.

**2. Q-LoRA (Quantized Low-Rank Adaptation):**
- Builds upon LoRA, incorporating an additional layer of efficiency.
- Utilizes quantization to represent the weights of the LoRA adapters with lower precision (e.g., 4 bits instead of 8 bits), reducing memory footprint and storage requirements.
- Offers enhanced memory efficiency, suitable for resource-constrained scenarios.
- Despite compression, Q-LoRA can maintain comparable performance to LoRA.

### Notebooks:
1. **Fine_tune_Llama_2.ipynb**:
   - Demonstrates fine-tuning LLama-2 using LoRA and Q-LoRA techniques.

2. **Gemma_Finetuning_notebook.ipynb**:
   - Illustrates fine-tuning Gamma using LoRA and Q-LoRA methods.

These notebooks provide a comprehensive guide to fine-tuning LLMs on custom datasets using efficient adaptation techniques, offering insights into optimizing model performance while minimizing resource overhead.

For any queries or suggestions, feel free to reach out. Happy fine-tuning!
