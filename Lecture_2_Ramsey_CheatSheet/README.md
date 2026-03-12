# Ramsey/Cass/Koopmans Model Cheatsheet

## Overview

This cheatsheet covers the Ramsey/Cass/Koopmans model from Lecture 2 of the Macroeconomics I course. It provides an exam-focused summary of the model, its derivations, and solution methodologies.

## File Structure

```
Lecture_2_Ramsey_CheatSheet/
├── Ramsey_CheatSheet.tex    # Main LaTeX source
├── Ramsey_CheatSheet.pdf    # Compiled PDF
└── README.md                # This file
```

## Compilation

To compile the LaTeX document:

```bash
pdflatex -interaction=nonstopmode Ramsey_CheatSheet.tex
```

Requires: LaTeX distribution with packages (amsmath, amssymb, mathtools, graphicx, xcolor, siunitx, cleveref, hyperref, tcolorbox, booktabs, enumitem)

## Contents

1. **Notation and Definitions** - Variable transformations (per-worker, per-effective-worker)
2. **Model Setup** - Environment, production function, technology growth
3. **Household Optimization** - Hamiltonian method, FOCs, Euler equation derivation
4. **Firm Problem and Equilibrium** - Profit maximization, market clearing
5. **Dynamic System** - Capital accumulation, efficiency units transformation
6. **Steady State Analysis** - Modified Golden Rule, Cobb-Douglas case
7. **Transversality Condition** - TVC derivation, dynamic efficiency
8. **Phase Diagram** - Loci, saddle path stability, transitional dynamics
9. **Comparative Statics** - Parameter effects on steady state
10. **Problem-Solving Templates** - Step-by-step guides for common problems
11. **Common Pitfalls** - Key mistakes to avoid
12. **Quick Reference Formulas** - Essential equations

## Key Formulas

- **Euler Equation**: $\dot{c}/c = (r - \rho)/\sigma$
- **Modified Golden Rule**: $f'(k^*) = \delta + \rho + \sigma x$
- **Steady State Interest**: $r^* = \rho + \sigma x$
- **TVC**: $n + (1-\sigma)x < \rho$
- **Cobb-Douglas SS**: $k^* = [\alpha/(\delta+\rho+\sigma x)]^{1/(1-\alpha)}$

## Navigation Tips

- Use `\tableofcontents` for quick reference to sections
- Derivation boxes (blue) show step-by-step derivations
- Result boxes (green) highlight key final formulas
- Phase diagram in Section 7 shows dynamic behavior
- Comparative statics table in Section 8 summarizes parameter effects

## Related Materials

- Lecture 2.md - Original lecture notes
- Key_Focuses.md - Emphasized concepts and solution methodologies
- Solow_CheatSheet/ - Solow model cheatsheet for comparison
