# Fine-Tuning Llama2 and Google Gemma Models Usinf Low Rank Adaptation (LoRA) with Parameter Efficient Fine Tuning(PEFT) and Transformer Reinforcement Learning

This repository contains two notebooks demonstrating the fine-tuning process for the Llama2 and Google Gemma models using parameter-efficient techniques and custom datasets.

## Contents
- `Llama2_Fine_Tuning_HF.ipynb`: Fine-tunes the Llama2 model using LoRA and PEFT on a custom dataset in a resource-constrained environment like Google Colab.
- `Finetuning_Gemma_2b (1).ipynb`: Demonstrates the fine-tuning of the Google Gemma model.

## Getting Started

### Prerequisites
- Google Colab or a similar Jupyter notebook environment.
- Basic knowledge of Python, machine learning, and natural language processing.

### Dependencies
For `Llama2_Fine_Tuning_HF.ipynb`:
- `accelerate`
- `peft`
- `bitsandbytes`
- `transformers`
- `trl` (for transformer reinforcement learning)

The `Finetuning_Gemma_2b (1).ipynb` notebook may require similar dependencies, which are typically installed within the notebook.

### Installation
Clone this repository and open the notebooks in your preferred Jupyter environment. Ensure you have the required dependencies installed by running the installation commands provided in the notebooks.

## Usage

### Llama2 Fine-Tuning
1. Load the `llama-2-7b-chat-hf` model.
2. Train the model on your custom dataset, referred to as "icare_chat_data" in the notebook.
3. The notebook guides you through fine-tuning the model, visualizing training plots, performing inference, and storing the fine-tuned model.

### Google Gemma Fine-Tuning
1. Load the Google Gemma model as described in the notebook.
2. Follow the instructions to fine-tune the model on your dataset.
3. Test the outputs of the fine-tuned model.

## Additional Notes
- Fine-tuning large language models requires careful consideration of resource constraints, especially in environments like Google Colab.
- The notebooks provide insights into parameter-efficient fine-tuning, data preparation, and model evaluation.

## Contributing
Contributions to improve the notebooks or the fine-tuning processes are welcome. Please ensure to follow the standard pull request process.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
