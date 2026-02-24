# Custom Text-to-Image Fine-Tuning using LoRA

This project demonstrates parameter-efficient fine-tuning of Stable Diffusion v1.5 using LoRA adapters on a custom dataset.

## What I Did

- Built custom image-caption dataset (cars and pets)
- Converted dataset into structured CSV format
- Fine-tuned Stable Diffusion v1.5 using LoRA
- Applied LoRA to UNet attention layers
- Used mixed precision training
- Generated domain-specific images after training

## Results
## Training Evidence

The model was trained for multiple epochs using LoRA adapters.
Loss values were monitored during training and checkpoints were saved after each epoch.

Example training log:

![Training Log](results/training_log.png)

See results folder for generated images.

## Note


API keys and private dataset paths are excluded for security reasons.
