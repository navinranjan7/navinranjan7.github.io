---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

# Navin Ranjan

**PhD Candidate in Computer Vision**  
**Efficient AI · Model Compression · Vision Foundation Models · Edge AI**

I am a PhD Candidate in Electrical and Computer Engineering at the Rochester Institute of Technology, working in the Vision and Image Processing Lab under Prof. Andreas Savakis. My research focuses on making large vision models more efficient, practical, and deployable through model quantization, mixed-precision optimization, and layer-wise sensitivity analysis.

My work centers on efficient Vision Transformers, Segment Anything Models, vision-language models, and vision-language-action models, with a focus on reducing memory, computation, and deployment cost while preserving task performance.

## Research Focus

- Efficient AI and model compression
- Post-training and mixed-precision quantization
- Vision Transformers and transformer compression
- Vision foundation models, including SAM/SAM3
- VLM and VLA model efficiency
- Layer-wise sensitivity analysis and explainability-guided quantization
- Edge AI deployment using PyTorch, CUDA, ONNX, and TensorRT

## Current Research

My current work focuses on quantization and compression of large vision models. I am especially interested in understanding which layers and components are most sensitive to low-bit quantization, and how this sensitivity can be used to design better mixed-precision quantization methods.

I work on both algorithmic and deployment-oriented aspects of efficient AI, including layer-wise bit allocation, calibration, transformer component analysis, and practical inference optimization for edge AI systems.

## Selected Projects

### Mixed-Precision Quantization for Vision Transformers

I study mixed-precision quantization methods for Vision Transformers, where sensitive layers are assigned higher precision and less sensitive layers are compressed more aggressively. This work focuses on improving the accuracy-efficiency tradeoff under model size and computational constraints.

### Quantization of SAM/SAM3

I work on fixed-precision and mixed-precision quantization of Segment Anything Models. The goal is to reduce memory and computation while preserving segmentation quality, prompt-conditioned behavior, and spatial detail.

### Efficient VLM/VLA Quantization

I am exploring quantization sensitivity analysis for multimodal models, including vision-language and vision-language-action systems. This work studies how quantization affects not only final outputs, but also internal task evidence and context preservation.

### Edge AI Implementation

I am interested in connecting model compression research with practical deployment using CUDA, ONNX, TensorRT, and hardware-aware evaluation. My goal is to make efficient vision foundation models practical for real-world and edge AI applications.

## Technical Skills

**Research Areas:** Efficient AI, model compression, quantization, mixed-precision optimization, Vision Transformers, vision foundation models, edge AI  
**Models:** ViT, DeiT, Swin Transformer, SAM/SAM3, VLMs, VLA models  
**Tools:** Python, PyTorch, CUDA, ONNX, TensorRT, Hugging Face, OpenCV  
**Tasks:** Image classification, semantic segmentation, object detection, multimodal vision-language reasoning
