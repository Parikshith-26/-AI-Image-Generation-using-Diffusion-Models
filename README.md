# -AI-Image-Generation-using-Diffusion-Models
Diffusion models are generative models that create new data (like images).   They start with pure noise (like a static TV screen) and gradually remove noise step by step until a clear image forms — guided by your **text prompt**.  

Overview

Diffusion models learn to denoise random noise into realistic images through a gradual reverse process.
This repo provides:

A minimal DDPM implementation (with optional DDIM sampler) you can train on small/medium datasets.

A ready-to-use Stable Diffusion path via diffusers for text-to-image without heavy re-implementation.

Utilities for evaluation (FID / CLIPScore), experiment tracking, and image grids.

Features

🔧 Modular PyTorch code: UNet backbone, beta schedules, EMA, mixed precision

🚀 Training from scratch (DDPM) on class/image datasets

🖼️ Sampling with DDPM or DDIM (fast inference steps)

🧠 Text-to-Image via Stable Diffusion + classifier-free guidance

📊 Metrics: FID (pytorch-fid) and CLIPScore

📝 Checkpointing, resume, and image grid exports

📈 Optional W&B logging (or pure CSV logging)
