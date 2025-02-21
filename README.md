---
license: MIT License
tasks:
  - voice-clone
frameworks:
  - pytorch 
language:
  - en
  - zh
tags:
  - TTS
  - GPT-SoVITS
base_model: AI-ModelScope/GPT-SoVITS
base_model_relation: finetune
domain:
  - audio
---

# Liang Voice

**Liang Voice**, a voice clone model of the character `Liang Yue` in *Reverse: 1999*, fine-tuned based on [GPT-SoVITS v3](https://github.com/RVC-Boss/GPT-SoVITS).

- Platform: [AutoDL](https://www.codewithgpu.com/i/RVC-Boss/GPT-SoVITS/GPT-SoVITS)
- Hardware: Nvidia RTX 4090 * 1
- models: [Liang-Voice](https://www.modelscope.cn/models/msforms/Liang-Voice)

examples: [examples/](./examples/README.md)
 