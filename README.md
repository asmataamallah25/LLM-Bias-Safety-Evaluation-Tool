# LLM Bias Safety Evaluation Tool
![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Version 1.0.0](https://img.shields.io/badge/version-1.0.0-green.svg)

A Python framework for evaluating Large Language Models against bias, toxicity, and safety concerns.

## 🎯 Overview

### The Problem

Large Language Models are powerful, but during text generation, they can exhibit:

- **Bias**: Preference for certain groups. 
  Example: "A nurse is caring" (assumes female)
  
- **Toxicity**: Harmful, offensive, or vulgar language.
  Example: "People from that country are..." (stereotyping)
  
- **Safety Concerns**: Outputs that could harm users.
  Example: Discriminatory language, harmful advice

Without evaluation, these issues go undetected in production.

### Why It Matters

Biased LLMs can:
- Perpetuate stereotypes in job descriptions
- Create discriminatory content
- Harm underrepresented communities
- Reduce user trust

### The Solution

This tool automatically:
1. Generate text from LLMs
2. Analyze for bias, toxicity, fairness
3. Score safety (0-100 scale)
4. Compare multiple models
5. Create detailed reports
