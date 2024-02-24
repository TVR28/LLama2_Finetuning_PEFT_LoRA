# Fine-Tuning Llama2 and Google Gemma Models Using LoRA and PEFT

![image](https://github.com/TVR28/LLama2_Finetuning_PEFT_LoRA/assets/91713140/49021b63-30ef-4689-9ec4-0dcf514c0aac)


This repository contains two notebooks demonstrating the fine-tuning process for the Llama2 and Google Gemma models Low Rank Adaptation (LoRA) with Parameter Efficient Fine Tuning(PEFT) and Transformer Reinforcement Learning on custom datasets.

Credits to the official **LoRA: Low-Rank Adaptation of Large Language Models** [Paper](https://arxiv.org/abs/2106.09685)
and 🤗 **PEFT: State-of-the-art Parameter-Efficient Fine-Tuning (PEFT) methods** [GitHub](https://github.com/huggingface/peft)

## Contents
- `Llama2_Fine_Tuning_HF.ipynb`: Fine-tunes the Llama2 model using LoRA and PEFT on a custom dataset in a resource-constrained environment like Google Colab.
- `Finetuning_Google_Gemma.ipynb`: Demonstrates the fine-tuning of the Google Gemma models (2B and 7B) using LoRA and PEFT.

## Getting Started

### Prerequisites
- Google Colab or a similar Jupyter notebook environment.
- Basic knowledge of Python, machine learning, and natural language processing.

### Dependencies
For `Llama2_Fine_Tuning_HF.ipynb`:
-`python 3.10`
- `torch`
- `transformers`
- `peft`
- `bitsandbytes`
- `trl` (for transformer reinforcement learning)
- `huggingface_hub`


The `Finetuning_Google_Gemma.ipynb` notebook may require similar dependencies, which are typically installed within the notebook.

### Installation
Clone this repository and open the notebooks in your preferred Jupyter environment. I prefer running them in Google Colab with the free tire T4 GPU. Ensure you have the required dependencies installed by running the installation commands provided in the notebooks.

## Usage

### Llama2 Fine-Tuning
1. Load the `llama-2-7b` model.
2. Train the model on my custom dataset, referred to as "mental_health_data" in the notebook, or any hugging face dataset of choice.
3. The notebook guides you through fine-tuning the model, visualizing training plots through tensor board, performing inference, and storing the fine-tuned model.

### Google Gemma Fine-Tuning
1. Load the `gemma-7b` model as described in the notebook.
2. Follow the instructions to fine-tune the model on your dataset (either custom or a hugging face dataset).
3. Test the outputs of the fine-tuned model.

## Additional Notes
- Fine-tuning large language models requires careful consideration of resource constraints, especially in environments like Google Colab.
- The notebooks provide insights into parameter-efficient fine-tuning, data preparation, and model evaluation through tensor board.

## Contributing
Contributions to improve the notebooks or the fine-tuning processes are welcome. Please ensure to follow the standard pull request process.
