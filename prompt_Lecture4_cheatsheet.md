Task: Generate an enhanced, exam-focused Endogenous Growth (AK + Romer Model) cheatsheet, sourced from @Lecture_4.md and aligned with the emphasis and structure in @Key_Focuses.md. Remove historical context and any fluff; include only material directly useful for exam problems. Deliver a compact, highly organized cheatsheet suitable for quick problem solving, with a LaTeX-ready format that can be imported into study slides or notes without further editing.

Process and structure (multi-agent, task-division workflow):
- Employ a distributed workflow with specialized parallel sub-agents to maximize accuracy and coherence. Each agent produces a self-contained, LaTeX-ready module that is then consolidated into a single cheatsheet.

  - Agent A (Notation and Core Definitions): Establish uniform notation for the AK model and Romer model. Define: Y = output, K = capital, L = labor, A = technology (or M = varieties), s = savings rate, δ = depreciation, n = population growth, g = technology growth, α = capital share, σ = risk aversion, ρ = time preference. Define per-capita forms: k = K/L, y = Y/L. For Romer model: M = number of varieties, x_i = intermediate goods, λ = research productivity, π = monopoly profits, r = interest rate.

  - Agent B (AK Model Core): Present the basic AK production function, derive the growth rate under exogenous savings, discuss the key property (no diminishing returns to capital), present the growth condition (sA > δ for positive growth), explain why there is no convergence prediction in the AK model.

  - Agent C (AK-Ramsey Model): Derive the consumption-savings choice in the AK framework. Present the Euler Equation: γ_c = (A - δ - ρ)/σ. Show the law of motion: ḳ_t = Ak_t - c_t - (δ + n)k_t. Discuss the transversality condition. Explain how growth depends on behavioral parameters (s affects growth in AK, unlike Solow).

  - Agent D (Externalities and Inefficiency in AK): Explain the Arrow learning-by-doing framework with externality η. Derive the difference between private and social marginal product of capital. Show: private MPK = αA, social MPK = (α+η)A. Discuss the inefficiency result: with positive externalities, the market under-accumulates capital relative to the planner.

  - Agent E (Romer Model - Market Equilibrium): Present the Romer (1990) framework with expanding varieties. Cover: (1) Final good production: Y = (L^(1-α)/α)∫x_i^α di; (2) Intermediate goods under monopolistic competition; (3) Optimal pricing: p_i = 1/α (markup over marginal cost); (4) Monopoly profits: π_i = L(1-α); (5) Firm value: V = π/r; (6) Free entry in R&D: r = λπ. Derive the market growth rate: γ = (λ(1-α)L - ρ)/σ.

  - Agent F (Romer Model - Social Planner): Derive the planner solution. Show that the planner uses machines more intensively (x*_i > x_i). Derive planner growth rate: γ* = (1/σ)(λLα^(1/(α-1))(1-α)/α - ρ). Compare: γ* > γ (planner grows faster due to elimination of monopoly distortion). Discuss optimal policy: subsidy to machine use.

  - Agent G (Scale Effects and Jones Fix): Explain the scale effects problem in Romer (growth increases with L). Present Jones (1995) critique: larger economies do not grow faster empirically. Present Jones' fix: decreasing returns to R&D with φ < 1: Ṁ = λM^φ L_R. Derive: γ = n/(1-φ). Discuss how this eliminates scale effects but requires population growth for sustained growth.

  - Agent H (Comparative Analysis): Compare Solow, AK, and Romer models. Present key distinguishing features: (1) Source of growth: exogenous (Solow) vs endogenous (AK, Romer); (2) Convergence: conditional (Solow) vs no convergence (AK) vs scale effects (Romer); (3) Role of savings: only affects level in Solow, affects growth rate in AK; (4) Market structure: perfect competition (Solow) vs monopolistic competition (Romer).

  - Agent I (Problem-Solving Templates): Deliver templates for common exam prompts: (a) Derive growth rate in AK model; (b) Compare market vs planner in Romer; (c) Solve for equilibrium interest rate with free entry in R&D; (d) Analyze scale effects; (e) Compute TFP gains from removing monopoly distortion.

  - Agent J (Pitfalls and Tips): Compile frequent exam mistakes: (1) Confusing AK (α=1) with Solow (α<1); (2) Forgetting that AK has no transitional dynamics; (3) Missing the difference between private and social returns with externalities; (4) Confusing scale effects in Romer (growth ∝ L) with Solow (no scale effects); (5) Forgetting that Romer requires monopolistic competition for positive profits to fund R&D; (6) Mixing up the markup formula (1/α) and its implications.

  - Agent K (Quick Reference): Assemble compact formulas: AK growth: γ = sA - δ; AK-Ramsey: γ_c = (A - δ - ρ)/σ; Romer market growth: γ = (λ(1-α)L - ρ)/σ; Romer planner growth: γ* = (λLα^(1/(α-1))(1-α)/α - ρ)/σ; Jones no-scale: γ = n/(1-φ); Markup: p = 1/α; Monopoly profits: π = L(1-α); Firm value: V = π/r; Free entry: r = λπ.

- Consolidation step: The lead assistant should merge modules A–K into a single, coherent LaTeX document, ensuring:
  - Consistent notation across sections (M for varieties, λ for research productivity, etc.).
  - Clear sectioning with explicit labeling and minimal narrative, prioritizing compact derivations and formulae.
  - Cross-references where necessary (e.g., how market vs planner compare).
  - No extraneous historical context; content strictly aligned with exam utility and derived from the specified sources.
  - Ensure optimal and nice formatting using derivationbox and resultbox environments. It should be easily readable.

Delivery format and output requirements:
- Output as a clean, exam-oriented LaTeX cheatsheet in its own directory Lecture_4_Endogenous_Growth_CheatSheet/.
- Files:
  - Lecture_4_Endogenous_Growth_CheatSheet/Endogenous_Growth_CheatSheet.tex: main LaTeX document with clearly labeled sections, compact derivations, and minimal narrative.
  - Optionally: README.md with a brief guide to navigating the cheatsheet (no extra content beyond navigation tips).
- Structure of the LaTeX document (recommended sections, clearly labeled):
  - Notation and Definitions
  - AK Model: Basic Setup and Growth
  - AK-Ramsey: Endogenizing Consumption
  - Externalities and Market Inefficiency
  - Romer Model: Market Equilibrium
  - Romer Model: Social Planner Solution
  - Scale Effects and Jones Fix
  - Comparative Analysis (Solow vs AK vs Romer)
  - Problem-Solving Templates
  - Common Pitfalls
  - Quick Reference Formulas
- Formatting constraints:
  - Use LaTeX math mode for all formulas.
  - Keep derivations concise; use one or two lines where possible.
  - Equations should be aligned and clearly labeled for reference.
  - Use derivationbox for step-by-step derivations and resultbox for final formulas.
  - The cheatsheet must be import-ready into a study document or slide deck without additional editing.
- Style and clarity:
  - Ensure uniform notation across all sections.
  - Emphasize exam-ready content: growth rate derivations, market vs planner comparison, scale effects, equilibrium conditions.
  - Provide clear comparisons between models.

Notational and mathematical conventions to enforce:
- AK production: y = Ak (or y = Ak^α for Solow-AK hybrid)
- AK growth: γ_k = sA - δ; γ_c = (A - δ - ρ)/σ
- Romer final good: Y = (L^(1-α)/α)∫x_i^α di
- Romer intermediate pricing: p_i = 1/α (markup = 1/α over marginal cost α)
- Monopoly profits: π = L(1-α)
- Firm value: V = π/r
- Free entry: r = λπ (or r = αλL for labor-based R&D)
- Market growth: γ = (λ(1-α)L - ρ)/σ
- Planner growth: γ* = (λLα^(1/(α-1))(1-α)/α - ρ)/σ
- Jones no-scale: γ = n/(1-φ) with Ṁ = λM^φ L_R

Constraints and references:
- Source content exclusively from @Lecture_4.md; incorporate emphasis and structure from @Key_Focuses.md.
- Exclude historical context and non-essential material; include only exam-useful content.
- The final deliverable must be a single, self-contained LaTeX cheatsheet within the specified directory structure, ready for import.
- Match the style and formatting conventions from @Solow_CheatSheet/Solow_CheatSheet.tex and @Solow_CheatSheet/Style_Guide.md.
