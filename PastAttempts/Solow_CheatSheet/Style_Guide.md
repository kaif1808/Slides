# LaTeX Cheatsheet Style Guide

## Overview

This style guide provides conventions for creating exam-focused LaTeX cheatsheets from lecture markdown files. It documents the structure, formatting, and LaTeX patterns used in the Solow Model cheatsheet (`Solow_CheatSheet.tex`) to ensure consistency across future cheatsheets.

---

## 1. Document Structure

### 1.1 Recommended Section Order

```
1. Title and Metadata
2. Notation and Definitions
3. Model Setup / Assumptions
4. Core Equations / Fundamental Results
5. Derivations (step-by-step)
6. Special Cases (e.g., Cobb-Douglas)
7. Dynamic Analysis (stability, transitions)
8. Comparative Statics / Policy
9. Problem-Solving Templates
10. Common Pitfalls
11. Quick Reference Formulas
12. Implementation Notes (optional)
```

### 1.2 Sectioning Commands

```latex
\section{...}          % Main section
\subsection*{...}       % Subsection (unnumbered)
\subparagraph*{...}    % Sub-subsection
```

- Use `\subsection*{}` for exam-focused cheatsheets (less clutter)
- Use `\clearpage` between major sections

---

## 2. LaTeX Preamble

### 2.1 Required Packages

```latex
\documentclass[a4paper,11pt]{article}

\usepackage{geometry}
\geometry{margin=1in}

\usepackage{amsmath}
\usepackage{amssymb}
\usepackage{mathtools}
\usepackage{graphicx}
\usepackage{xcolor}

\usepackage{siunitx}
\sisetup{detect-all}

\usepackage[colorlinks=true,linkcolor=blue3,citecolor=blue3,urlcolor=blue3]{hyperref}

\usepackage{cleveref}

\usepackage{tcolorbox}
\tcbuselibrary{skins,breakable}

\usepackage{booktabs}
\usepackage{enumitem}
```

### 2.2 Custom Commands

Define consistent notation commands at the preamble:

```latex
% Custom notation commands
\newcommand{\ktilde}{\tilde{k}}
\newcommand{\ytilde}{\tilde{y}}
\newcommand{\ctilde}{\tilde{c}}
```

### 2.3 Color Definitions

```latex
\definecolor{blue3}{RGB}{0,0,180}
\definecolor{green3}{RGB}{0,120,0}
\definecolor{orange3}{RGB}{200,100,0}
```

### 1.4 Tcolorbox Environments

```latex
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
```

---

## 3. Equation Formatting

### 3.1 Basic Display Math

```latex
% Single equation (centered)
\[
E = mc^2
\]

% Aligned equations (multiple lines)
\begin{align*}
    x &= y + z \\
    z &= x - y
\end{align*}
```

### 3.2 Equation Tags

Use `\tag{}` within `align*` or `gather*` environments:

```latex
\begin{align*}
    y = f(x) + c
    \tag{Equation Name}
\end{align*}
```

### 3.3 Boxed Equations

```latex
\[
\boxed{E = mc^2}
\]
```

### 3.4 Consistency Rules

- Use `\ktilde` not `\tilde{k}` for per-effective variables
- Use `k^*` not `k*` (asterisk in math mode needs braces: `k^{*}`)
- Wrap inline math with `$...$` not `\(...\)` for compatibility
- Use `\diff` from `mathtools` or define: `\newcommand{\diff}{\mathrm{d}}`

---

## 4. Tables

### 4.1 Booktabs Style

```latex
\begin{center}
\begin{tabular}{lcc}
\toprule
Parameter & Effect on $x$ & Effect on $y$ \\
\midrule
$\uparrow s$ & $\uparrow$ & $\downarrow$ \\
$\uparrow n$ & $\downarrow$ & $\uparrow$ \\
\bottomrule
\end{tabular}
\end{center}
```

### 4.2 Column Alignment

- `l` = left aligned
- `c` = center aligned  
- `r` = right aligned
- `p{width}` = paragraph column

---

## 5. Figures and Diagrams

### 5.1 TikZ Phase Diagrams

```latex
\begin{center}
\begin{tikzpicture}[scale=0.9]
    \draw[->] (-0.3,0) -- (5.5,0) node[right] {$x$};
    \draw[->] (0,-0.3) -- (0,4) node[above] {$\dot{x}$};
    
    % Function curve
    \draw[domain=0:5,smooth,variable=\x,blue,thick] 
        plot ({\x},{2.2 * (1 - exp(-0.9*\x))}) 
        node[above right,blue] {$f(x)$};
    
    % Linear line
    \draw[domain=0:4.5,smooth,variable=\x,red,thick] 
        plot ({\x},{0.55*\x}) 
        node[above right,red] {$gx$};
    
    % Intersection point
    \draw[fill=black] (2.2,1.21) circle (0.07);
\end{tikzpicture}
\end{center}
```

---

## 6. Lists and Enumerations

### 6.1 Itemize (Bulleted)

```latex
\begin{itemize}
    \item First item
    \item Second item
    \begin{itemize}
        \item Nested item
    \end{itemize}
\end{itemize}
```

### 6.2 Enumerate (Numbered)

```latex
\begin{enumerate}
    \item First step
    \item Second step
    \item Third step
\end{enumerate}
```

**Important**: Always use `\item` for each list entry.

---

## 7. Content Guidelines

### 7.1 Exam-Focused Principles

- Include only material directly useful for exam problems
- Remove historical context and non-essential narrative
- Provide step-by-step derivations for core results
- Add "Result Summary" boxes for key formulas
- Include common pitfalls section

### 7.2 Derivation Block Template

```latex
\begin{derivationbox}{Derivation Name}
\textbf{Step 1:} Starting equation
\[
\text{equation}
\]

\textbf{Step 2:} Transformation
\[
\text{equation}
\]

\textbf{Step 3:} Final result
\[
\text{result}
\]
\end{derivationbox}

\begin{resultbox}
\[
\boxed{\text{final formula}}
\tag{Label}
\]
\end{resultbox}
```

### 7.3 Notation Consistency

| Symbol | Meaning |
|--------|---------|
| `k` | Capital per worker |
| `k̃` | Capital per effective worker |
| `y` | Output per worker |
| `ỹ` | Output per effective worker |
| `*` | Steady-state (use `k^*` not `k*`) |
| `GR` | Golden Rule |

---

## 8. Compilation

### 8.1 Commands

```bash
pdflatex -interaction=nonstopmode filename.tex
```

### 8.2 Required Output Files

- `.tex` - Main source
- `.pdf` - Compiled output
- `README.md` - Navigation guide (optional)

---

## 9. Replication Prompt

Use the following prompt to generate cheatsheets from lecture markdown files:

---

### PROMPT: Generate Lecture Cheatsheet

```
You are tasked with creating an exam-focused LaTeX cheatsheet from lecture content.

## Input Files
- @[lecture_file].md - Main lecture content
- @Key_Focuses.md - Emphasized concepts and solution methodologies

## Output Requirements
Create a LaTeX cheatsheet at Solow_CheatSheet/Solow_CheatSheet.tex with:

### Preamble
- Use article class with a4paper, 11pt
- Include packages: amsmath, amssymb, mathtools, graphicx, xcolor, siunitx, cleveref, hyperref, tcolorbox, booktabs, enumitem
- Define custom notation commands (e.g., \ktilde, \ytilde)
- Create derivationbox and resultbox tcolorbox environments
- Load hyperref BEFORE cleveref

### Document Structure
1. Notation and Definitions
2. Model Setup / Assumptions
3. Derivation of Core Results (with step-by-step narrative)
4. Special Cases (Cobb-Douglas, etc.)
5. Dynamic Path and Stability
6. Comparative Statics / Policy Analysis
7. Problem-Solving Templates
8. Common Pitfalls
9. Quick Reference Formulas

### Formatting Rules
- Use \subsection*{} for sections in cheatsheet
- Use \begin{align*} for multi-line equations
- Use \tag{} for equation labels inside align
- Use \boxed{} for final results
- Use derivationbox for step-by-step derivations
- Use resultbox for final formulas
- Include TikZ diagrams for phase plots
- Use booktabs for tables

### Content Guidelines
- Include only exam-useful material
- Remove historical context
- Provide derivations with intermediate steps
- Use consistent notation throughout
- Add common pitfalls section

### Key Formulas to Include
- Dynamic equations (per-worker and per-effective)
- Steady-state conditions
- Golden Rule derivation
- Cobb-Douglas closed forms
- Convergence speed
- Growth rates in steady state

## Source Material
Extract content from @Lecture_1.md and structure according to @Key_Focuses.md emphasis.
```

---

## 10. Changelog Format

Add an implementation notes section at the end:

```latex
\section{Implementation Notes}

\subsection*{Changes from Original Version}
\begin{itemize}
    \item \textbf{Enhanced Preamble}: Added packages X, Y, Z
    \item \textbf{Derivation Boxes}: Created custom environments
    \item \textbf{Equation Formatting}: Used align* with \tag{}
\end{itemize}

\subsection*{Packages Used}
\begin{itemize}
    \item amsmath, amssymb, mathtools: Mathematics
    \item graphicx: Graphics
    \item xcolor: Color support
    \item siunitx: Number formatting
    \item cleveref: Cross-references
    \item hyperref: Hyperlinks
    \item tcolorbox: Colored boxes
    \item booktabs: Tables
\end{itemize}

\subsection*{Compilation}
Compile with: \texttt{pdflatex} or \texttt{lualatex}
```

---

## Quick Reference Card

| Task | LaTeX Command |
|------|----------------|
| New section | `\section{Name}` |
| New subsection | `\subsection*{Name}` |
| Display equation | `\[ ... \]` |
| Aligned equations | `\begin{align*} ... \end{align*}` |
| Boxed result | `\boxed{...}` |
| Equation tag | `\tag{Name}` |
| Derivation box | `\begin{derivationbox} ... \end{derivationbox}` |
| Result box | `\begin{resultbox} ... \end{resultbox}` |
| Table | `\begin{tabular}{...} ... \end{tabular}` |
| Figure | `\begin{tikzpicture} ... \end{tikzpicture}` |
| Page break | `\clearpage` |
| Italics | `\textit{text}` |
| Bold | `\textbf{text}` |

---

*Last Updated: March 2026*
*Based on Solow_CheatSheet.tex v1.0*
