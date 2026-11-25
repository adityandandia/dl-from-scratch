# Deep Learning from Scratch

My self-paced rebuild of deep learning fundamentals: from backprop to a GPT, and then to
measuring training efficiency. No deadlines. Each stage is finished properly before the next
one starts.

## Sources

- Aurélien Géron, *Hands-On Machine Learning with Scikit-Learn and PyTorch* (O'Reilly, 2025)
- Andrej Karpathy, *Neural Networks: Zero to Hero*

All code in this repo is written by me. Where I followed a video line by line, the stage
README says so.

## How each stage works

- Read the Géron chapter closely and run its notebook.
- Watch the Karpathy video, pausing and coding along.
- Rebuild the code from a blank file, without looking.
- Write the stage README (what I built, what broke, what I learned) and add a `LOG.md` entry.
- Do a recall check, explaining the ideas in my own words, before moving on.

## Study order

### Stage 1: Backprop and training basics (`stage1-backprop/`)
- [ ] Géron Ch 4, Training Models
- [ ] Karpathy: micrograd
- [ ] Géron Ch 9, Introduction to Artificial Neural Networks
- [ ] Géron Appendix A, Autodiff

### Stage 2: PyTorch fluency (`stage2-pytorch/`)
- [ ] Géron Ch 10, Building Neural Networks with PyTorch
- [ ] Karpathy: makemore, parts 1 and 2

### Stage 3: Training deep nets properly (`stage3-training-deep-nets/`)
- [ ] Géron Ch 11, Training Deep Neural Networks
- [ ] Karpathy: makemore, parts 3 and 4

### Stage 4: Transformers (`stage4-transformers/`)
- [ ] Géron Ch 14, only embeddings, tokenization, and the attention mechanism
- [ ] Géron Ch 15, Transformers for NLP and Chatbots
- [ ] Karpathy: Let's build GPT
- [ ] Karpathy: Let's build the GPT Tokenizer

### Stage 5: Efficiency (`stage5-efficiency/`)
- [ ] Géron Appendix B, Mixed Precision and Quantization
- [ ] Géron Ch 17, Speeding Up Transformers
- [ ] Géron Ch 12, only the GPU RAM requirements section
- [ ] Karpathy: Reproduce GPT-2 (124M)
- [ ] Measure tokens/sec and peak memory: fp32 vs bf16 vs `torch.compile`

### Stage 6: Optional, only when a project needs it
- [ ] Géron Ch 3, performance measures (precision/recall, PR trade-off)
- [ ] Géron Ch 6, boosting and gradient boosting
- [ ] Géron Ch 18, autoencoders, GANs, and diffusion models

### Skipped for now
- Géron Ch 2, 5, 7, 8, 13, 16, 19

## Repo layout

```
dl-from-scratch/
├── README.md              this file
├── LOG.md                 raw daily notes
├── stage1-backprop/       stage 1 code, plots, README
├── stage2-pytorch/
├── stage3-training-deep-nets/
├── stage4-transformers/
├── stage5-efficiency/
└── posts/                 blog and LinkedIn post templates
```

## Write-ups

- One blog post per stage on Hashnode (links added to each stage README)
- One short LinkedIn post per stage
- A final summary post after Stage 5

## Log

Raw daily notes are in [LOG.md](LOG.md).