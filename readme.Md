Custom Text-to-Image Fine-Tuning using LoRA

This project demonstrates parameter-efficient fine-tuning of Stable Diffusion v1.5 using LoRA (Low-Rank Adaptation) adapters on a custom multi-class image-caption dataset.

Project Overview

The objective of this project was to adapt a pre-trained diffusion model to generate domain-specific images (cars and pets) while maintaining computational efficiency through LoRA-based fine-tuning instead of full model retraining.

What I Implemented

Built and curated a custom image-caption dataset (cars and pets)

Structured dataset into training-ready CSV format

Implemented a PyTorch data loading pipeline

Integrated LoRA adapters into UNet attention layers

Performed mixed-precision (fp16) training for memory efficiency

Saved LoRA checkpoints after each epoch

Generated domain-specific images using custom prompts

Training Details

Base Model: Stable Diffusion v1.5

Fine-Tuning Method: LoRA

Framework: Hugging Face Diffusers

Optimizer: AdamW

Scheduler: DDPMScheduler

Training Environment: Google Colab GPU

Loss values were monitored during training, and checkpoints were saved after each epoch to track performance progression.

Results

The fine-tuned model demonstrates improved alignment with the custom dataset categories compared to the base model.

Training logs and generated samples are available in the results/ folder.

Security Note

API credentials, authentication tokens, and private dataset paths have been removed for security reasons. The repository contains a clean and reproducible project structure.
