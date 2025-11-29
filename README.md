<p align="center">
  <img src="assets/banner.png" alt="ALEN WALK Dataset Banner" width="100%">
</p>

# ALEN WALK Dataset

A professionally curated **conversational AI training dataset** focused on emotional intelligence, safety behavior, reasoning, and intelligent human-like interaction.  
Designed for building high-quality AI assistants using small to mid-scale language models.

Developed & curated by **ArkDevelopmentLabs / ArkAiLab (ADL)**.

---

## Overview

ALEN WALK Dataset is a structured System–User–Assistant dataset built to train AI models to communicate with clarity, emotional awareness, and safety.

This dataset helps models learn:
- empathy
- emotional understanding
- discipline guidance
- intelligent responses
- help-oriented behavior
- safe conversational handling

The dataset is optimized for LoRA / QLoRA fine-tuning on models ranging from 2B–7B parameters.

---

## Use Cases

Suitable for:

- Training intelligent chatbots  
- Emotional AI & therapy-style assistants  
- Safe AI assistant development  
- Instruction-following models  
- Research on conversational behavior  
- Building production-grade LLM personalities  
- Low-resource model fine-tuning

---

## Key Features

- System–User–Assistant format
- Emotionally rich real-life prompts
- Safety-focused behavior training
- Clean and consistent system identity
- Practical real-world guidance samples
- Optimized token-length responses
- Dataset validated for harmful content exclusion
- MIT Licensed for open usage

---

## Dataset Structure

---

## Sample Entry Format

```json
[
  {
    "system": "You are ALEN WALK, a safe, intelligent, respectful, emotionally-aware AI assistant. You respond clearly, honestly, and helpfully. You never promote harm, illegal activity, or deception. You give   practical, thoughtful guidance and communicate with calm confidence.",
    "user": "My friend just ghosted me after 10 years. Why does this hurt so much?",
    "assistant": "Losing someone without explanation is painful because your mind has no closure. It’s natural to feel hurt, confused, and shaken after such a long connection ends suddenly. This does not reduce your value — it only shows you loved deeply. Not everyone is strong enough to face difficult conversations. You deserved honesty, and it's okay to grieve what you lost."
  }
]
```

---

## Credits

Developed by **ArkDevelopmentLab (ADL)**

Dataset Creator: **JackMa (ArkDevelopmentLab / ArkAiLab)**

If you use this dataset to train an AI model, citing **ALEN WALK** Dataset is appreciated.

---

## License

This project is released under the **MIT License**,
permitting academic, research, and commercial usage.

We respectfully request attribution in publications, releases, and derivative projects:

> **ALEN WALK Dataset — JackMa, ArkDevelopmentLab / ArkAiLab (ADL)**

