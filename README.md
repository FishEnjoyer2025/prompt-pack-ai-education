# Karpathy Method: ML Prompt Pack for Deep Builders

20 structured prompts for ML self-learners who want to truly understand neural networks — not just use them. Built around Andrej Karpathy's zero-to-hero teaching style: derive before you run, implement before you import, verify before you train. Every prompt targets hands-on understanding, covering backprop, transformers, tokenization, diagnostics, and paper implementation.

## 🛒 Buy now — $17

**[→ Checkout via Stripe](https://buy.stripe.com/3cIdRabgY6TT8ZE5kBdfG06)**

## What's inside

- 20 ready-to-use prompts organized into 7 use-case groups (backprop, from-scratch builds, attention, debugging, paper reading, tokenization, self-testing)
- Designed for Karpathy's makemore, micrograd, nanoGPT, and minbpe frameworks — plug in your code and get targeted guidance
- Each prompt enforces the "derive first, code second" discipline that separates understanding from cargo-culting
- Includes diagnostic prompts for gradient health checks, loss curve analysis, and pre-training data audits
- Works with any LLM (Claude, GPT-4, Gemini) — prompts are self-contained and require no special setup

## Preview

```
---

## KARPATHY METHOD: ML PROMPT PACK
### 20 Prompts for Self-Learners Building Neural Networks from Scratch

---

### GROUP 1: BACKPROPAGATION & AUTOGRAD (Micrograd Mindset)

**Prompt 1 — Derive Backprop on a Scalar Expression**
```
I am implementing backpropagation from scratch following Karpathy's micrograd approach. Given this scalar expression: [PASTE EXPRESSION e.g. L = (a*b + c) * d], walk me through:
1. The forward pass: compute each intermediate value
2. The computation graph with all nodes labeled
3. The backward pass: derive dL/da, dL/db, dL/dc, dL/dd using the chain rule step by step
Show all intermediate gradients. Do not skip steps. Use the notation Karpathy uses in his micrograd lecture.
```

**Prompt 2 — Implement a Value Class from Scratch**
```
Help me implement a minimal autograd Value class in Python, following the micrograd pattern. It must support: +, *, **, -, /, tanh, relu operations, and a .backward() method that runs reverse-mode autodiff via topological sort. Walk me through each method, explaining the local gradient calculation before writing the code. After each operation, show a tiny test to verify it works.
```

**Prompt 3 — Trace Gradient Flow Through a Computation Graph**
```
I have this neural network layer [PASTE CODE]. Draw the computation graph as ASCII art, label every node with its value and gradient after a backward pass on a dummy input. Then identify: (1) any node where gradients might vanish or explode and why, (2) which weights receive the largest and smallest gradient updates.
```

**Prompt 4 — Explain Why Backprop Works Intuitively**
```
Explain backpropagation to me as if I understand calculus but have never seen a computation graph. Use a 3-node example (two inputs, one output). Avoid matrix notation — keep everything scalar. After the intuition, show me the exact Python code that would compute it manually, then show how micrograd automates the same thing. Make the connection explicit.
```

---

### GROUP 2: BUILD FROM SCRATCH (Zero-to-Hero Style)

**Prompt 5 — Implement a Bigram Language Model**
```
I am following Karpathy's makemore series. Help me build a bigram character-level language model on this dataset: [PASTE DATASET OR DESCRIBE IT]. Steps:
```


🌐 Hosted landing page: https://FishEnjoyer2025.github.io/prompt-pack-ai-education/
