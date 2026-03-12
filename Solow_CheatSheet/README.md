# Solow Model Cheatsheet

## Overview
This is an exam-focused LaTeX cheatsheet for the Solow Growth Model, designed for quick problem-solving and rapid review.

## File Structure
```
Solow_CheatSheet/
├── Solow_CheatSheet.tex    # Main LaTeX document
└── README.md               # This file
```

## Usage
- Compile with pdflatex or XeLaTeX
- Import directly into study slides or notes
- All formulas are in LaTeX math mode

## Section Guide

| Section | Content |
|---------|---------|
| Notation and Definitions | Core variables (K, L, Y, A, s, δ, n, g), per-worker and per-effective transformations |
| Model Setup | Production function with CRS, capital accumulation, dynamic equations |
| Core Equations | Steady-state conditions, growth rates in SS, per-effective to per-worker translation |
| Special Case: Cobb-Douglas | Closed-form solutions, Golden Rule derivation, convergence speed |
| Dynamic Path, Stability, and Growth | Phase diagrams, stability analysis, transitional dynamics, conditional convergence |
| Long-Run Growth and Growth Accounting | Growth rates, comparative statics table |
| Policy Shocks and Comparative Statics | 4-step template for policy analysis |
| Graphical Intuition | Phase diagram visualizations with TikZ |
| Problem-Solving Templates | Step-by-step guides for common exam prompts (a)-(e) |
| Common Pitfalls and Tips | Frequent mistakes to avoid |
| Quick Reference Formulas | Compact formula sheet for rapid recall |

## Key Formulas to Memorize

1. **Dynamic equation**: $\dot{\tilde{k}} = sf(\tilde{k}) - (n+g+\delta)\tilde{k}$
2. **Steady state**: $sf(\tilde{k}^*) = (n+g+\delta)\tilde{k}^*$
3. **Cobb-Douglas SS**: $\tilde{k}^* = [s/(n+g+\delta)]^{1/(1-\alpha)}$
4. **Golden Rule**: $f'(\tilde{k}_{GR}) = n+g+\delta$
5. **Convergence speed**: $\beta = (1-\alpha)(n+g+\delta)$
6. **Growth rates in SS**: $k$ grows at $g$, $y$ grows at $g+n$, $Y$ grows at $g+n$

## Notation Conventions
- Tildes ($\tilde{}$) denote per-effective-worker variables
- Lowercase denote per-worker variables
- Stars ($*$) denote steady-state values
- $GR$ denotes Golden Rule values
