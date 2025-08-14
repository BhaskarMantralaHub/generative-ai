# Generative AI Course Notes

## Overview: AI Model Types

AI models built on **Deep Learning (Neural Networks)** fall into two main categories:

## Discriminative AI
**Purpose**: Classify, predict, and analyze existing data
- **Capabilities**: Pattern recognition, classification, prediction
- **Examples**:
  - Email spam detection (Gmail, Outlook)
  - Image recognition ("Is this the Golden Gate Bridge?")
  - Medical diagnosis (detecting tumors in X-rays)
  - Credit score assessment
  - Fraud detection in banking

## Generative AI
**Purpose**: Create new content based on learned patterns from training data

**Input/Output**: Text, images, audio, code, video → New content in same or different format

### Key Capabilities
- **Creative content generation**: Text, images, music, code
- **Multimodal interactions**: Text-to-image, image-to-text, etc.

### Real-World Examples
- **Text**: ChatGPT (GPT-5), Claude 4 writing articles or code
- **Images**: DALL-E 4 creating "Golden Gate Bridge with Spider-Man"
- **Code**: GitHub Copilot generating functions with GPT-5
- **Music**: AIVA composing symphonies, Suno v4
- **Video**: RunwayML Gen-3, Pika Labs, Luma Dream Machine

## Core Generative AI Architectures

### 1. GANs (Generative Adversarial Networks)
- **Use Cases**: High-quality image generation, deepfakes
- **Examples**: NVIDIA StyleGAN (realistic faces), ArtBreeder

### 2. VAEs (Variational Autoencoders)
- **Use Cases**: Image reconstruction, data compression
- **Examples**: Medical imaging enhancement, anomaly detection

### 3. Transformers
- **Use Cases**: Language models, translation, code generation
- **Examples**: GPT-5, Claude 4, BERT, T5, GitHub Copilot

### 4. Diffusion Models
- **Use Cases**: High-quality image and video generation
- **Examples**: DALL-E 4, Midjourney v7, Stable Diffusion 3.5, Adobe Firefly 3, RunwayML Gen-3

## Large Language Models (LLMs)
**Definition**: Transformer-based models trained on massive text datasets

### Current Market Leaders (2025)
- **OpenAI**: GPT-5, GPT-4o, ChatGPT
- **Anthropic**: Claude 4 (Sonnet), Claude 3.5 (Opus, Sonnet, Haiku)
- **Google**: Gemini Ultra 2.0, Gemini Pro 2.0
- **Meta**: Llama 4, Llama 3.3
- **Microsoft**: Copilot (GPT-5 based), Phi-4
- **xAI**: Grok-3
- **DeepSeek**: DeepSeek-V3

### Applications
- Conversational AI, content creation, code generation, research assistance, language translation

## Foundation Models (LLMs / Generative AI)

**Definition**: Large-scale pre-trained models that serve as the base for various AI applications

### Key Techniques

#### Prompting
**Definition**: Crafting input text to guide AI model responses
- **Zero-shot**: Direct instruction without examples ("Translate this to French")
- **Few-shot**: Providing examples in the prompt
- **Chain-of-thought**: Step-by-step reasoning prompts
- **Examples**: 
  - GPT-5: "Write a Python function to sort a list"
  - Claude 4: "Explain quantum computing in simple terms"

#### Data Tuning
**Types of model customization**:
- **Fine-tuning**: Training on domain-specific data
  - Examples: Medical GPT for healthcare, CodeT5 for programming
- **Instruction tuning**: Training to follow human instructions
  - Examples: ChatGPT, Claude 4's helpful assistant behavior
- **RLHF** (Reinforcement Learning from Human Feedback)
  - Examples: GPT-5's advanced safety alignment, Claude 4's constitutional AI

### Advantages
- **Performance**: 
  - Superior accuracy on complex tasks vs. traditional models
  - Examples: GPT-5 scoring 95th percentile on bar exam, Claude 4 solving PhD-level math
- **Productivity**: 
  - Automated content creation, code generation, research assistance
  - Examples: GitHub Copilot increases developer productivity by 65% (2025 data)

### Disadvantages
- **Computing Cost**: 
  - Training costs: GPT-5 estimated $500M+, Claude 4 ~$200M
  - Inference costs: $0.05-0.20 per 1K tokens for premium models (2025)
- **Trust & Reliability**:
  - Hallucinations: Models generating false information confidently
  - Bias: Reflecting training data biases in outputs
  - Examples: ChatGPT creating fake citations, bias in resume screening



