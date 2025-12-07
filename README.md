Few-Shot Image Generation with Hybrid Attention
Overview

This project implements a few-shot image generation model capable of synthesizing diverse and high-quality images using only 2–10 training samples.
The method builds upon the ConSinGAN / DEff-GAN multi-stage pyramid framework and introduces a Hybrid Attention Mechanism that combines Self-Attention (SA) and Vision Transformer (ViT) modules to enhance both local texture modeling and global semantic consistency.
Key Features
Multi-Stage Pyramid Generator

Gradually increases image resolution from coarse to fine, learning textures and structures at each scale.

Hybrid Attention Mechanism

Self-Attention: Strengthens local textures, fine details, and edges.

Vision Transformer: Models long-range dependencies and improves global semantic alignment.

This hybrid strategy significantly improves quality and stability under limited data.

 Multi-Task Objective

Includes adversarial loss, reconstruction loss, and auxiliary classification loss to enhance realism, structural fidelity, and semantic consistency.
