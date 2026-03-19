# Prompt: Generate Lecture Cheatsheet

Use this prompt to generate exam-focused LaTeX cheatsheets from lecture markdown files.

---

## Task Description

You are tasked with creating an exam-focused LaTeX cheatsheet from lecture content.

---

## Input Files

- @Lecture_3.md - Main lecture content
- @Key_Focuses.md - Emphasized concepts and solution methodologies
- @Solow_CheatSheet/Style_Guide.md
Utilise multiple parallel agents to enact this swiftly and to minimise the risk of context overload in an individual agent.
---

## Output Requirements

Create a LaTeX cheatsheet at `[Course]_Cheatsheet/[Course]_Cheatsheet.tex` with the following structure:

### Preamble

```latex
\documentclass[a4paper,11pt]{article}

\usepackage{geometry}
\geometry{margin=1in}

\usepackage{amsmath}
\usepackage{amssymb}
\usepackage{mat{graphicx}
htools}
\usepackage\usepackage{xcolor}
\definecolor{blue3}{RGB}{0,0,180}
\definecolor{green3}{RGB}{0,120,0}
\definecolor{orange3}{RGB}{200,100,0}

\usepackage{siunitx}
\sisetup{detect-all}

\usepackage[colorlinks=true,linkcolor=blue3,citecolor=blue3,urlcolor=blue3]{hyperref}
\usepackage{cleveref}

\usepackage{tcolorbox}
\tcbuselibrary{skins,breakable}

\newtcolorbox{derivationbox}[1][]{
    colback=blue!10,
    colframe=blue3,
    coltitle=blue3,
    title={Derivation:},
    fonttitle=\bfseries,
    #1
}

\newtcolorbox{resultbox}[1][]{
    colback=green!10,
    colframe=green3,
    coltitle=green3,
    title={Result Summary:},
    fonttitle=\bfseries,
    #1
}

\usepackage{booktabs}
\usepackage{enumitem}

% Custom notation commands
\newcommand{\ktilde}{\tilde{k}}
\newcommand{\ytilde}{\tilde{y}}
\newcommand{\ctilde}{\tilde{c}}

\begin{document}
% ... content ...
\end{document}
```

### Document Structure

1. **Title and Metadata**
2. **Notation and Definitions** - Core variables and notation
3. **Model Setup / Assumptions** - Production function, constraints
4. **Derivation of Core Results** - Step-by-step derivations with narrative
5. **Special Cases** - e.g., Cobb-Douglas, CES
6. **Dynamic Analysis** - Stability, transitions, phase diagrams
7. **Comparative Statics / Policy Analysis** - Parameter effects
8. **Problem-Solving Templates** - Step-by-step guides for common problems
9. **Common Pitfalls** - Frequent mistakes to avoid
10. **Quick Reference Formulas** - Compact formula summary
11. **Implementation Notes** - Documentation of changes

### Formatting Rules

- Use `\subsection*{}` for sections (unnumbered for cheatsheets)
- Use `\begin{align*} ... \end{align*}` for multi-line equations
- Use `\tag{}` for equation labels inside align environments
- Use `\boxed{}` for final results
- Use `derivationbox` for step-by-step derivations
- Use `resultbox` for final formulas
- Include TikZ diagrams for phase plots
- Use `booktabs` for tables (`\toprule`, `\midrule`, `\bottomrule`)

### Content Guidelines

- Include ONLY material directly useful for exam problems
- Remove historical context and non-essential narrative
- Provide derivations with intermediate steps
- Use consistent notation throughout (define once, use everywhere)
- Add "Common Pitfalls" section with frequent mistakes
- Make derivations self-contained (include enough context)

### Key Formulas to Always Include

For Solow Model:
- Dynamic equations (per-worker and per-effective)
- Steady-state conditions
- Golden Rule derivation
- Cobb-Douglas closed forms
- Convergence speed formula
- Growth rates in steady state

For other models, include:
- Optimization conditions (FOCs)
- Steady-state equations
- Key comparative statics
- Transition dynamics

---

## Example: Solow Model Sections

```
\section{Notation and Definitions}
\subsection*{Core Variables}
\subsection*{Per-Worker Variables}
\subsection*{Per-Effective-Worker Variables}

\section{Model Setup}
\subsection*{Production Function}
\subsection*{Capital Accumulation}

\section{Derivation of Core Results}
\subsection{Derivation 1: Per-Worker Form}
\subsection{Derivation 2: Per-Effective-Worker Form}
\subsection{Derivation 3: Steady-State}
\subsection{Derivation 4: Golden Rule}

\section{Special Case: Cobb-Douglas}
...

\section{Quick Reference Formulas}
```

---

## Source Material Processing

1. **Read lecture file** - Extract key equations, derivations, and concepts
2. **Read Key_Focuses.md** - Note emphasized solution methodologies
3. **Identify exam-useful content** - Filter out historical context
4. **Structure logically** - Follow the document structure above
5. **Add derivations** - Show intermediate steps for core results

---

## Compilation

```bash
pdflatex -interaction=nonstopmode Solow_CheatSheet.tex
```

---

## Customization for Other Lectures

For different lecture topics (Ramsey, Romer, etc.), adapt:

1. **Notation commands** - Define model-specific symbols
2. **Section content** - Replace with relevant equations
3. **Templates** - Create problem-solving templates for common questions
4. **Pitfalls** - Add model-specific mistakes to avoid

---

