#Self-Alignment of Language Models with Instruction Backtranslation

*   Implemented the Instruction Backtranslation method to self-align a Llama-2-7b language model, enhancing its ability to follow instructions.
*   Trained a backward model ($p(x|y)$) on a subset of the OpenAssistant Guanaco dataset (3000 examples).
*   Generated and curated a dataset of 41 high-quality instruction-output pairs from 150 sampled LIMA examples using a self-curation process.
*   Fine-tuned the base Llama-2-7b model on the curated dataset, demonstrating improved instruction following as shown in generated examples.
*   Utilized advanced techniques including LoRA for efficient fine-tuning and 4-bit quantization for memory optimization on GPU.
*   Leveraged Hugging Face Transformers, PEFT, bitsandbytes, and PyTorch.

This project involves experience with:
*   Large Language Models (Llama-2)
*   Advanced fine-tuning techniques (LoRA, quantization)
*   Self-supervised learning methods
*   Dataset curation and quality control
