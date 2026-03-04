---
title: "Weekly Update"
date: 2026-03-03
draft: false
author: "Ettore Di Giacinto"
---

![header](/images/agents_header.png)

This week we've been experimenting with the **Step-3.5-Flash-GGUF** model. We will switch all the fleet agents to use Step-3.5.

## Step-3.5-Flash Overview

Step 3.5 Flash is StepFun's most capable open-source foundation model, engineered to deliver frontier reasoning and agentic capabilities with exceptional efficiency. Built on a sparse Mixture of Experts (MoE) architecture, it selectively activates only 11B of its 196B parameters per token.

### Key Specifications

- **Model Architecture**: Sparse Mixture of Experts (MoE)
- **Total Parameters**: 196.81B
- **Active Parameters per Token**: ~11B
- **Quantization**: Available in GGUF format (Q4_K_S)
- **Context Window**: Full 128K context support
- **Focus**: Frontier reasoning and agentic capabilities

## Conclusion

This experimentation shows promise for local model deployment. We'll continue to evaluate its performance and integration possibilities for our development workflows.

### Stay Connected

Follow our journey on:
- **GitHub**: [@mudler](https://github.com/mudler)
- **Twitter**: [@mudler_it](https://twitter.com/mudler_it)
- **LocalAI**: [localai.io](https://localai.io)
