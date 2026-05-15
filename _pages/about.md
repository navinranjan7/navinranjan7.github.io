---
permalink: /
title: "Navin Ranjan"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

**PhD Candidate in Computer Vision**  
**Efficient AI · Model Compression · Vision Foundation Models · Edge AI**

I am a PhD Candidate in Electrical and Computer Engineering at the Rochester Institute of Technology, working in the Vision and Image Processing Lab under Prof. Andreas Savakis. My research focuses on building efficient, adaptable, and deployable computer vision models, especially transformer-based architectures and vision foundation models.

My work spans model compression, low-bit quantization, knowledge distillation, parameter-efficient fine-tuning, and sensitivity analysis. I am particularly interested in making large vision models such as Vision Transformers, SAM/SAM3, VLMs, and VLA models practical for real-world and edge AI deployment.

## Research Overview

Modern vision models are increasingly powerful, but their size, memory cost, and computational requirements make them difficult to deploy in practical settings. My research addresses this challenge from three connected directions:

1. **Compressing large vision models** through post-training quantization, mixed-precision quantization, and knowledge distillation.
2. **Adapting vision foundation models** using parameter-efficient methods such as LoRA and adapters for domain-specific tasks.
3. **Understanding model sensitivity** using explainability, perturbation analysis, and Topological Data Analysis to identify which components are most critical for performance.

The goal is not only to reduce model size, but also to preserve task behavior, visual reasoning, segmentation quality, and deployment efficiency.

## Research Interests

- Efficient AI and model compression
- Post-training and mixed-precision quantization
- Knowledge distillation for Vision Transformers
- Vision Transformers and transformer-based foundation models
- SAM/SAM3 adaptation and quantization
- LoRA and adapter-based fine-tuning for remote sensing segmentation
- Sensitivity analysis and explainability-guided compression
- Topological Data Analysis for model behavior analysis
- Efficient VLM and VLA models
- Edge AI deployment using PyTorch, CUDA, ONNX, and TensorRT

## Current Research Directions

### Quantization and Model Compression

I work on reducing the memory and computational cost of transformer-based vision models through fixed-precision and mixed-precision quantization. A key part of this work is identifying which layers or components are most sensitive to low-bit quantization and assigning precision accordingly.

This includes studying the behavior of attention layers, MLP blocks, projection layers, Softmax, and activation functions under aggressive compression. My goal is to design compression methods that maintain strong task performance while reducing model size, BitOps, and deployment cost.

### Vision Foundation Models: SAM and SAM3

I am working on efficient adaptation and compression of Segment Anything-style models for dense prediction tasks. This includes both fine-tuning and quantization of SAM/SAM3-like models.

For remote sensing segmentation, I study parameter-efficient fine-tuning methods such as LoRA and adapters to adapt large foundation models without full model retraining. I am also interested in how quantization affects prompt-conditioned segmentation, spatial detail preservation, and mask quality.

### Knowledge Distillation for Efficient Vision Transformers

I have also worked on knowledge distillation for Vision Transformer quantization. In this direction, the full-precision model acts as a teacher to guide the compressed or quantized model. This helps improve the performance of low-bit models by preserving intermediate representations, prediction behavior, or task-specific knowledge from the original model.

This direction connects compression with training-time guidance and is especially useful when direct low-bit quantization causes a large accuracy drop.

### Topological Data Analysis for Sensitivity Analysis

Another direction of my work explores Topological Data Analysis for understanding model behavior under perturbation or quantization-like changes. Instead of only measuring final accuracy drop, this direction studies how internal representations change when layers or activations are perturbed.

I use this type of analysis to investigate which parts of a model are structurally important and how representation geometry changes under compression. This provides another way to study model sensitivity beyond standard gradient-based or loss-based metrics.

### Efficient Multimodal Models

I am also interested in efficient vision-language and vision-language-action models. These models combine perception, language understanding, and action prediction, which makes compression more challenging than standard image classification.

My current interest is to analyze how quantization affects not only the final output, but also internal task context, multimodal grounding, and action-related decision behavior.

### Edge AI and Deployment

A major goal of my research is to connect compression algorithms with real deployment constraints. I am interested in practical deployment workflows using CUDA, ONNX, TensorRT, and hardware-aware evaluation.

I focus on metrics such as model size, memory usage, BitOps, latency, throughput, and accuracy-efficiency tradeoffs, with the goal of making large vision models practical for edge and resource-constrained platforms.

## Selected Projects

### Mixed-Precision Quantization for Vision Transformers

This project studies how to assign different bit-widths to different transformer layers based on their importance and quantization sensitivity. The goal is to improve the accuracy-efficiency tradeoff compared with uniform low-bit quantization.

### SAM/SAM3 Fine-Tuning for Remote Sensing

This project adapts SAM/SAM3-style vision foundation models for remote sensing segmentation using parameter-efficient fine-tuning methods such as LoRA and adapters. The focus is on adapting large pretrained models to domain-specific segmentation tasks with reduced training cost.

### Quantization of SAM/SAM3

This project investigates fixed-precision and mixed-precision quantization of Segment Anything-style models. The goal is to reduce memory and computation while preserving prompt-conditioned segmentation quality and spatial detail.

### Knowledge Distillation for Vision Transformer Quantization

This project studies how knowledge distillation can improve the performance of quantized Vision Transformers by transferring information from a full-precision teacher model to a compressed student model.

### Topological Data Analysis for Model Sensitivity

This project uses Topological Data Analysis to study how internal representations change under perturbation or quantization-like noise. The goal is to identify sensitive layers and better understand model robustness.

### Efficient VLM/VLA Quantization Analysis

This project explores quantization sensitivity in vision-language and vision-language-action models, where compression can affect visual grounding, language-conditioned reasoning, and action prediction.

## Technical Skills

**Research Areas:** Efficient AI, model compression, quantization, knowledge distillation, parameter-efficient fine-tuning, sensitivity analysis, edge AI

**Models and Architectures:** Vision Transformers, DeiT, Swin Transformer, SAM/SAM3, VLMs, VLA models, transformer-based segmentation models

**Methods:** Post-training quantization, mixed-precision quantization, LoRA, adapters, knowledge distillation, Topological Data Analysis, perturbation-based analysis, explainability-guided sensitivity analysis

**Tools and Frameworks:** Python, PyTorch, CUDA, ONNX, TensorRT, Hugging Face, timm, OpenCV

**Applications:** Image classification, semantic segmentation, remote sensing, vision-language reasoning, action-oriented multimodal models, edge AI deployment
