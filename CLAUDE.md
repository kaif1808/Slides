# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This is a study repository for BSE course **14E022 - Macroeconomics I** (instructor: Alessandro Ferrari, UPF/CREI/BSE). The primary workflow is converting lecture markdown notes into exam-focused LaTeX cheatsheets.

## Content Structure

- `Lecture_N.md` — Source lecture notes (Lectures 1–6, covering Solow, Ramsey, Growth Accounting, Endogenous Growth, Quality Ladders, Structural Change)
- `Key_Focuses.md` — Core exam methodologies: Hamiltonian optimization, steady-state analysis, phase diagrams, monopolistic competition, market vs. planner comparisons
- `PastAttempts/` — Previously generated cheatsheets (reference for style and content)
- `prompt_Lecture4_cheatsheet.md` — Example of a detailed multi-agent cheatsheet generation prompt

## Cheatsheet Generation Workflow

Each cheatsheet lives in its own directory: `Lecture_N_[Topic]_CheatSheet/[Topic]_CheatSheet.tex`

**Sources to read before generating any cheatsheet:**
1. `Lecture_N.md` — primary content source
2. `Key_Focuses.md` — what to emphasize for exams
3. `PastAttempts/Solow_CheatSheet/Style_Guide.md` — LaTeX conventions and formatting rules

**Standard prompt pattern** (see `prompt_Lecture4_cheatsheet.md` for full example):
- Use parallel sub-agents for each section to avoid context overload
- Consolidate into a single self-contained `.tex` file

## LaTeX Compilation

```bash
pdflatex -interaction=nonstopmode filename.tex
```

Run twice if cross-references or TOC are needed.

**Required packages:** `amsmath`, `amssymb`, `mathtools`, `graphicx`, `xcolor`, `siunitx`, `hyperref` (before `cleveref`), `cleveref`, `tcolorbox` (with `skins,breakable`), `booktabs`, `enumitem`, `tikz`

## LaTeX Style Conventions

**Custom tcolorbox environments** (must be defined in every cheatsheet preamble):

```latex
\newtcolorbox{derivationbox}[1][]{colback=blue!10, colframe=blue3, title={Derivation:}, fonttitle=\bfseries, #1}
\newtcolorbox{resultbox}[1][]{colback=green!10, colframe=green3, title={Result Summary:}, fonttitle=\bfseries, #1}
```

**Colors:** `\definecolor{blue3}{RGB}{0,0,180}`, `green3={0,120,0}`, `orange3={200,100,0}`

**Custom notation commands:**
```latex
\newcommand{\ktilde}{\tilde{k}}
\newcommand{\ytilde}{\tilde{y}}
\newcommand{\ctilde}{\tilde{c}}
```

**Sectioning:** Use `\subsection*{}` (unnumbered) for cheatsheet sections.

**Equations:** Use `align*` with `\tag{}` for labeled equations; `\boxed{}` for final results.

**Structure of every cheatsheet:**
1. Notation and Definitions
2. Model Setup / Assumptions
3. Core Derivations (step-by-step in `derivationbox`, results in `resultbox`)
4. Special Cases (Cobb-Douglas, etc.)
5. Dynamic Analysis / Phase Diagrams (TikZ)
6. Comparative Statics / Policy
7. Problem-Solving Templates
8. Common Pitfalls
9. Quick Reference Formulas

## Key Notation Conventions

| Symbol | Meaning |
|--------|---------|
| `k`, `y`, `c` | Per-worker capital/output/consumption |
| `\ktilde`, `\ytilde`, `\ctilde` | Per-effective-worker variables |
| `k^*` | Steady-state (never `k*`) |
| `γ` | Growth rate |
| `ρ` | Time preference, `σ` = risk aversion |
| `M` | Number of varieties (Romer), `λ` = research productivity |

## Course Topics by Lecture

- **L1:** Solow model — per-worker/per-effective-worker, Golden Rule, convergence speed β
- **L2:** Ramsey/Cass/Koopmans — Hamiltonian, Euler equation, modified Golden Rule, TVC
- **L3:** Growth accounting — development accounting, misallocation, Hsieh-Klenow
- **L4:** Endogenous growth — AK model, Romer expanding varieties, market vs. planner, Jones scale-effects fix
- **L5:** Quality ladders (Aghion-Howitt) — Schumpeterian growth, creative destruction
- **L6:** Structural change — multi-sector models
