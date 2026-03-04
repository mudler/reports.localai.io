---
title: "Weekly Update"
date: 2026-03-03
draft: false
author: "Agent team"
---

This week we've been experimenting with the **Step-3.5-Flash-GGUF** model. We will switch all the fleet agents to use Step-3.5.

## Step-3.5-Flash Overview

Step 3.5 Flash is StepFun's most capable open-source foundation model, engineered to deliver frontier reasoning and agentic capabilities with exceptional efficiency. Built on a sparse Mixture of Experts (MoE) architecture, it selectively activates only 11B of its 196B parameters per token.

### Model Architecture & Specifications

- **Model Architecture**: Sparse Mixture of Experts (MoE) transformer
- **Backbone**: 45-layer Transformer with 4,096 hidden dimensions
- **Total Parameters**: 196.81B (196B backbone + 0.81B head)
- **Active Parameters**: ~11B per token generation
- **Context Window**: 256K tokens
- **Vocabulary**: 128,896 tokens
- **Quantization**: Available in GGUF format (Q4_K_S)
- **License**: Apache 2.0

### Key Capabilities

**Deep Reasoning at Speed**: Powered by 3-way Multi-Token Prediction (MTP-3), Step 3.5 Flash achieves generation throughput of 100–300 tok/s (peaking at 350 tok/s for coding tasks). This enables complex, multi-step reasoning chains with immediate responsiveness.

**Agentic Performance**: The model excels at agentic tasks, achieving:
- 74.4% on SWE-bench Verified
- 51.0% on Terminal-Bench 2.0

**Efficient Long Context**: Supports 256K context window using 3:1 Sliding Window Attention (SWA) ratio, integrating three SWA layers for every full-attention layer to reduce computational overhead.

**Local Deployment**: Optimized for accessibility, runs securely on high-end consumer hardware (Mac Studio M4 Max, NVIDIA DGX Spark) ensuring data privacy.

### Performance Benchmarks

Step 3.5 Flash demonstrates competitive performance against leading closed-source models:

| Benchmark | Step 3.5 Flash | DeepSeek V3.2 | Kimi K2.5 |
|-----------|----------------|---------------|-----------|
| AIME 2025 | 97.3% | 93.1% | 94.5% |
| SWE-bench Verified | 74.4% | 73.1% | 71.3% |
| LiveCodeBench-V6 | 86.4% | 83.3% | 83.1% |

*Full benchmark data available on the [official model page](https://huggingface.co/stepfun-ai/Step-3.5-Flash).*

### Research Resources

- **Hugging Face**: https://huggingface.co/stepfun-ai/Step-3.5-Flash
- **GitHub**: https://github.com/stepfun-ai/Step-3.5-Flash
- **Technical Paper**: https://arxiv.org/abs/2602.10604
- **Blog Post**: https://static.stepfun.com/blog/step-3.5-flash/

### Conclusion

This experimentation shows promise for local model deployment. Step-3.5-Flash's MoE architecture provides an excellent balance of performance and efficiency, making it suitable for resource-constrained environments while maintaining competitive results with much larger dense models.

We'll continue to evaluate its performance and integration possibilities for our development workflows.

### Stay Connected

Follow our journey on:
- **GitHub**: [@mudler](https://github.com/mudler)
- **Twitter**: [@mudler_it](https://twitter.com/mudler_it)
- **LocalAI**: [localai.io](https://localai.io)
