# Quality Ladder / Schumpeterian Growth Cheatsheet

Exam-focused reference for Macroeconomics I - Lecture 5

## Contents

1. **Notation and Definitions** - Core variables and parameters
2. **Model Setup** - Final good production with quality-adjusted inputs
3. **Research Firms** - Monopoly profits, firm value, innovation probability
4. **Growth Derivation** - Quality index dynamics and BGP growth
5. **Market Equilibrium** - Euler equation, interest rate, equilibrium $p$ and $\gamma$
6. **Planner Solution** - Planner vs market allocation, $X^* > X$, $Y^* > Y$
7. **Externalities** - Business stealing vs temporary returns effects
8. **Competition & Innovation** - U-shaped relationship (Aghion et al., 2005)
9. **Policy** - R&D tax effects, incumbent lobbying
10. **Templates** - Problem-solving frameworks
11. **Pitfalls** - Common mistakes to avoid
12. **Quick Reference** - Essential formulas

## Key Formulas

- Quality-adjusted input: $\tilde{X} = q^k X$
- Quality index: $Q = \int_0^N q^{k(s)\frac{\alpha}{1-\alpha}} ds$
- Growth rate: $\gamma = p(q^{\frac{\alpha}{1-\alpha}} - 1)$
- Innovation prob: $p = \overline{\pi}/\xi - r$
- Market growth: $\gamma = (\overline{\pi}/\xi - \rho)(1 - q^{-\frac{\alpha}{1-\alpha}})$
- Planner vs Market: $X^* > X$, $\gamma^* \lesseqqgtr \gamma$

## Key Distinction from Romer (Expanding Varieties)

| Feature | Quality Ladder | Expanding Varieties |
|---------|---------------|---------------------|
| Innovation type | Vertical (quality) | Horizontal (new varieties) |
| $N$ | Fixed | Endogenous |
| Growth engine | Creative destruction | Love for variety |
| Welfare | Ambiguous ($\gamma^* \lesseqqgtr \gamma$) | Too little ($\gamma^* > \gamma$) |

## Compilation

```bash
pdflatex Quality_Ladder_CheatSheet.tex
```

## Source

Lecture_5.md - Quality Ladder / Schumpeterian (Aghion-Howitt) Models
