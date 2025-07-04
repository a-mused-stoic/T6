# T6 Evaluation Framework

[![Python Version](https://img.shields.io/badge/python-3.8%2B-blue.svg)]()

A tier-based AI evaluation and coin system implementing the **T6 Framework** — a novel approach to measuring signal vs. noise in human-AI interactions. This framework enables semantic evaluation of inputs across six tiers (Curiosity → Paradigm Shift), rewarding meaningful contributions and supporting paradigm-scale resets.

---

## Overview

The **T6 Framework** provides a structured, axiomatic method for evaluating conversations, research, and AI-generated content. It focuses on:

- Filtering noise and enhancing signal quality in human-AI synergy  
- Grading input across 6 tiers:  
  - **T1: Curiosity**  
  - **T2: Analogy**  
  - **T3: Insight**  
  - **T4: Truth**  
  - **T5: Groundbreaking**  
  - **T6: Paradigm Shift**  
- Assigning tier-specific coin rewards to incentivize quality  
- Handling fractal resets and societal shifts based on consensus  
- Seamlessly integrating semantic similarity for novelty and noise detection  

This system is designed to complement symbolic AI architectures like **Tensor**, serving as a signal-focused evaluation module.

---

## Repository Structure

```plaintext
t6_eval/
├── t6_eval/
│   ├── tiers.py            # Tier definitions and scoring logic
│   ├── signal_noise.py     # Signal and noise evaluation (lexical + semantic)
│   ├── coins.py            # Coin economy and conversion mechanisms
│   ├── reset.py            # Reset and consensus logic
│   ├── models.py           # Model loading and inference wrappers
│   ├── processor.py        # Main processing pipeline
│   ├── utils.py            # Utility functions
│   └── __init__.py
├── tests/                  # Unit and integration tests
├── examples/               # Demo scripts and sample datasets
├── notebooks/              # Interactive exploration and visualization
├── docs/                   # Whitepaper and documentation
├── README.md
├── requirements.txt
└── setup.py
