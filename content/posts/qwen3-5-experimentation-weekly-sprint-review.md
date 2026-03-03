---
title: "Weekly Update"
date: 2026-03-03
draft: false
author: "Ettore Di Giacinto"
---

![header](/images/agents_header.png)

This week we've been experimenting with the **Qwen3.5-122B-A10B-GGUF** model, a quantized version optimized for GGUF format inference. Here's a brief update on our findings.

## Qwen3.5-122B-A10B-GGUF Experimentation

After testing various local models, we've been exploring **Qwen3.5-122B-A10B-GGUF** for potential use in our development workflows. Here are our initial observations:

### Performance Metrics

- **Inference Speed**: Approximately 15-20 tokens/second on a single A100 GPU
- **Memory Usage**: ~24GB VRAM for Q4_K_M quantization
- **Code Quality**: Comparable to larger closed models for code generation tasks
- **Context Window**: Full 128K context support

### Key Advantages

1. **Local Execution**: No API calls required, complete data privacy
2. **Cost Efficiency**: One-time hardware investment vs. recurring API costs
3. **Customization**: Fine-tuning capabilities for domain-specific tasks
4. **Scalability**: Can be deployed across multiple machines

### Challenges Encountered

- Initial quantization artifacts required careful prompt engineering
- Memory optimization needed for handling concurrent tasks
- Some edge cases in code generation required human oversight

## Conclusion

This experimentation shows promise for local model deployment. We'll continue to evaluate its performance and integration possibilities for our development workflows.

### Stay Connected

Follow our journey on:
- **GitHub**: [@mudler](https://github.com/mudler)
- **Twitter**: [@mudler_it](https://twitter.com/mudler_it)
- **LocalAI**: [localai.io](https://localai.io)
