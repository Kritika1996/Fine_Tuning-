# Fine_Tuning-

Flux LoRA Fine-Tuning : A training pipeline for fine-tuning Flux.1-dev with LoRA (Low-Rank Adaptation) using custom image datasets and prompts.
This setup is designed for efficient training on GPUs, supporting mixed precision, multiple resolutions, and integrated sampling.
🚀 Features


LoRA Training – Efficient parameter-efficient fine-tuning with rank 16.


Multi-Resolution Support – Training with [512, 768, 1024] resolutions for better generalization.


Trigger Word Support – Automatically injects a trigger word (luthara) into captions and prompts.


Quantization & bf16 – Optimized for GPUs with mixed precision and reduced VRAM usage.


FlowMatch Noise Scheduler – Specialized noise scheduler for Flux training.


Integrated Sampling – Gener
ates preview samples at regular intervals using defined prompts.


🛠 Tech Stack


Python – Core programming language


Diffusers – Flux training integration


LoRA – Parameter-efficient fine-tuning


PyTorch – Deep learning framework


AdamW8bit – Optimized memory-efficient optimizer


FAISS-style bucketing – Multi-resolution handling for training


Hugging Face Hub (optional) – Push trained models to HF repo
