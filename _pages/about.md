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

I am a PhD Candidate in Electrical and Computer Engineering at the Rochester Institute of Technology, working in the Vision and Image Processing Lab under Prof. Andreas Savakis. My research focuses on efficient deep learning for large-scale vision models, with an emphasis on quantization, mixed-precision optimization, and deployment-aware model compression.

My work aims to make modern vision models such as Vision Transformers, Segment Anything Models, vision-language models, and vision-language-action models more practical for real-world deployment. I study how low-bit quantization affects different parts of these models and develop methods to preserve accuracy, task behavior, and efficiency under strict memory and computation constraints.

## Research Focus

My research is centered on the following areas:

- Efficient AI and model compression for large vision models
- Post-training quantization and mixed-precision quantization
- Vision Transformers and transformer-based foundation models
- Quantization of SAM/SAM3 and segmentation-oriented vision models
- Sensitivity analysis for attention, MLP, Softmax, and activation layers
- Efficient VLM and VLA models for multimodal reasoning and action prediction
- Edge AI deployment using PyTorch, CUDA, ONNX, and TensorRT

## Current Research

A major direction of my current research is understanding why some layers in transformer-based vision models are highly sensitive to quantization while others can be compressed aggressively. Instead of applying the same bit-width to every layer, I investigate layer-wise and component-wise sensitivity to guide better mixed-precision quantization.

I am especially interested in quantization methods for vision foundation models, where preserving only classification accuracy is not enough. For models such as SAM, VLMs, and VLA systems, quantization must preserve spatial detail, prompt-conditioned behavior, multimodal reasoning, and task-relevant internal representations.

My broader goal is to connect model compression research with practical deployment by considering not only accuracy, but also memory cost, computation, latency, throughput, and hardware support.

## Selected Research Directions

### Mixed-Precision Quantization for Vision Transformers

I develop mixed-precision quantization methods for Vision Transformers, where sensitive layers are assigned higher precision and robust layers are compressed more aggressively. This direction focuses on improving the accuracy-efficiency tradeoff under model size and BitOps constraints.

### Quantization of Vision Foundation Models

I study fixed-precision and mixed-precision quantization for Segment Anything Models and related vision foundation models. The goal is to reduce memory and computation while preserving segmentation quality, spatial structure, and prompt-conditioned prediction behavior.

### Sensitivity Analysis for Transformer Components

I analyze how different transformer components respond to low-bit quantization, including attention blocks, MLP layers, Softmax operations, GELU activations, and projection layers. This helps identify which parts of a model require higher precision and which parts can be compressed more safely.

### Efficient VLM and VLA Models

I am exploring quantization sensitivity in vision-language and vision-language-action models, where compression can affect not only final predictions but also multimodal grounding, task context, and action-related decision behavior.

### Edge AI and Deployment

I am interested in practical deployment of compressed vision models using CUDA, ONNX, TensorRT, and hardware-aware evaluation. My goal is to make efficient vision foundation models usable on real-world and resource-constrained platforms.

## Technical Skills

**Research Areas:** Efficient AI, model compression, post-training quantization, mixed-precision quantization, Vision Transformers, vision foundation models, edge AI  

**Models and Architectures:** ViT, DeiT, Swin Transformer, SAM/SAM3, VLMs, VLA models, transformer-based segmentation and detection models  

**Tools and Frameworks:** Python, PyTorch, CUDA, ONNX, TensorRT, Hugging Face, OpenCV, timm  

**Core Methods:** Layer-wise sensitivity analysis, explainability-guided quantization, calibration, low-bit inference, mixed-precision bit allocation, deployment-aware evaluation  

**Applications:** Image classification, semantic segmentation, object detection, vision-language reasoning, action-oriented multimodal models
