Macroeconomics I - Lecture 2

Instructor: Alessandro Ferrari

Date: January 2026

Institution: UPF, CREi, BSE & CEPR

The Ramsey/Cass/Koopmans Model

There are at least three sources of dissatisfaction with the Solow model:

Differences in long-run growth depend on technical progress.

We need a theory of technical progress.

Endogenous growth theories developed following Romer (JPE 1986).

The savings rate is a key determinant of per capita output.

We need a theory of household consumption and saving.

In this section, a consumption/savings theory is embedded into the Solow model.

Population growth is a key determinant of per capita output.

We need a theory of fertility to endogenize it.

The Welfare Theorems

We will solve the competitive equilibrium (the decentralized economy), although the basic model (without taxes, externalities, public goods, and so on) could be solved by use of the social planner problem. (The social planner problem is an abstraction to characterize pareto-optimal allocations).

First Fundamental Welfare Theorem: Under certain conditions, every competitive equilibrium is Pareto-optimal.

Second Fundamental Welfare Theorem: Under certain conditions, every Pareto-optimal allocation can be achieved as a competitive equilibrium.

The Ramsey Model: Environment

(To compare with the Solow model)

Single homogeneous good that can be either invested or consumed.

Closed economy.

Households choose how much to consume and how much to save every period.

Population grows at an exogenous and constant rate, $n$.

Technology level grows at an exogenous and constant rate, $x$.

Decentralized Solution

There is a representative household and a representative firm.

There are three (competitive) markets: capital, labor, and final good (numeraire).

1. Households

They live forever ($\infty$ periods) and discount future utilities by $\rho > 0$.

We have to think of them as families (or dynasties).

The size of the representative family at a given period $t$ is $N_{t} = N_{0}e^{nt}$ (where we can normalize $N_{0}=1$).

They own the production factors and rent them to firms.

They buy the final good from firms.

2. Firms

Access to a neoclassical production function.

They rent capital and labor from households to produce the homogeneous good of the economy.

They sell the final good to households.

Household Problem

Households have one unique decision margin: consumption versus saving in each period of time $t$. The budget constraint they face every period $t$ is given by:

$$\dot{A}_{t} = N_{t}w_{t} + r_{t}A_{t} - C_{t} \Rightarrow c_{t} + \dot{a}_{t} + na_{t} = w_{t} + r_{t}a_{t}$$

That is to say, the resources obtained from working $w_{t}$ and the interest payments on asset holdings $r_{t}a_{t}$ have to be used for consumption $c_{t}$, increasing the asset holdings $\dot{a}_{t}$, and providing assets for the new family members $na_{t}$. Negative values of $a_{t}$ imply that the household is in debt.

The No-Ponzi Game Condition

If the household could borrow as much as it wanted, there would be an easy solution for its consumption-savings problem:

Borrow infinity and never repay.

Borrow and when the time to repay comes, simply roll over the debt across all periods (this is what is known as a Ponzi Scheme).

So we impose that households cannot borrow unlimited amounts to finance arbitrarily high levels of consumption. The present value of current and future assets must be asymptotically non-negative. This implies that:

Households cannot borrow infinitely until the end of their life.

Household's debt cannot grow faster than the interest rate.

Utility Maximization

Period utility $u(c_{t})$ has the usual properties: $u_{c} > 0$ and $u_{cc} < 0$.

A representative household chooses the path of consumption $\{c_{t}\}_{t=0}^{\infty}$ that maximizes the discounted sum of utilities for all its members:

$$\int_{0}^{\infty} u(c_{t}) N_{t} e^{-\rho t} dt$$

In doing so, the household has to satisfy its budget constraints taking the sequence of prices $\{r_{t}, w_{t}\}_{t=0}^{\infty}$ as given.

Therefore, the optimization problem is given by:

$$\max_{\{c_{t}, a_{t}\}_{t=0}^{\infty}} \left\{ \int_{0}^{\infty} u(c_{t}) e^{-(\rho-n)t} dt \right\}$$

Subject to:

$c_{t} + \dot{a}_{t} + na_{t} \le w_{t} + r_{t}a_{t}$

$a_{0}$ given

$\lim_{t\rightarrow\infty} a_{t} \exp\left(-\int_{0}^{t} (r(s)-n) ds\right) \ge 0$ (No Ponzi Scheme)

Intuition in Discrete Time

To build intuition, consider the household problem in discrete time (and no population growth):

$$\max_{a_{t}, c_{t}} \sum_{t=0}^{\infty} \beta^{t} u(c_{t})$$


subject to:


$$c_{t} + a_{t+1} - a_{t} \le r a_{t} + w_{t}$$

$$\lim_{t\rightarrow\infty} a_{t} = 0$$

Call $\lambda_{t}$ the Lagrange multiplier for period $t$, then:


$$\mathcal{L} = \sum_{t=0}^{\infty} \beta^{t} u(c_{t}) + \sum_{t=0}^{\infty} \lambda_{t} [(1+r)a_{t} + w_{t} - c_{t} - a_{t+1}]$$

The FOCs of the problem are:

$\beta^{t} u'(c_{t}) = \lambda_{t}$

$\lambda_{t}(1+r) = \lambda_{t-1}$

We can rewrite the second one as: $\lambda_{t} - \lambda_{t-1} = \Delta\lambda_{t} = -r\lambda_{t}$.

Solving the Continuous Time Problem (Hamiltonian)

Using optimal control theory, we write the present value Hamiltonian:

$$\mathcal{J}(c_{t}, a_{t}, \nu_{t}, t) = u(c_{t})e^{-(\rho-n)t} + \nu_{t}[w_{t} + (r_{t}-n)a_{t} - c_{t}]$$

The necessary conditions for an optimum are:

$\mathcal{J}_{c} = 0 \Rightarrow \nu_{t} = u_{c}(c_{t})e^{-(\rho-n)t}$

$\mathcal{J}_{a} = -\dot{\nu} \Rightarrow \dot{\nu}_{t} = -(r_{t}-n)\nu_{t}$

$\mathcal{J}_{\nu} = \dot{a} \Rightarrow \dot{a}_{t} = w_{t} + (r_{t}-n)a_{t} - c_{t}$

Plus the transversality condition (TVC):


$$\lim_{t\rightarrow\infty}(\nu_{t}a_{t}) = 0$$

The Euler Equation

Take the first FOC and take logs:


$$\log \nu_{t} = \log u_{c}(c_{t}) - (\rho-n)t$$

Take a derivative with respect to time $t$:


$$\frac{\dot{\nu}_{t}}{\nu_{t}} = \frac{u_{cc}\dot{c}_{t}}{u_{c}} - (\rho-n)$$

Divide and multiply by $c_{t}$:


$$\frac{\dot{\nu}_{t}}{\nu_{t}} = \frac{u_{cc}c_{t}}{u_{c}} \frac{\dot{c}_{t}}{c_{t}} - (\rho-n)$$

Use the second FOC to obtain:


$$-r_{t} + n = \frac{u_{cc}c_{t}}{u_{c}} \frac{\dot{c}_{t}}{c_{t}} - (\rho-n)$$

Finally, we can rearrange this to obtain the Euler Equation:

$$\frac{\dot{c}_{t}}{c_{t}} = \left[ -\frac{u_{cc}(c_{t})c_{t}}{u_{c}(c_{t})} \right]^{-1} (r_{t} - \rho)$$

Households will choose between saving and consumption such that their consumption profile will be increasing (decreasing) if the return on savings exceeds (falls short of) their subjective discount rate.

The quantitative importance of the difference $(r_{t}-\rho)$ is inversely proportional to the curvature of the utility function.

The higher the curvature of $u(c_{t})$, the lower the effect of $(r_{t}-\rho)$ in the chosen consumption profile.

CRRA Utility Function

A utility function with constant curvature $\left[-\frac{u_{cc}(c)c}{u_{c}(c)}\right]$ is very useful. The class of functions with this property is known as the Constant Relative Risk Aversion (CRRA) function, and takes the form:

$$u(c) = \frac{c^{1-\sigma}-1}{1-\sigma}$$

In this case, the Euler Equation becomes:

$$\frac{\dot{c}_{t}}{c_{t}} = \frac{1}{\sigma}(r_{t} - \rho)$$

The household chooses a constant consumption path if $r = \rho$.

If $r > \rho$, then the household saves and, therefore, over time, consumption grows.

If the elasticity $\sigma$ is very large, then the household saves little unless $r >> \rho$.

The Transversality Condition

The TVC is a terminal condition. Given that the household problem is characterized by two first-order differential equations, we need two terminal conditions to pick the optimal consumption path. One is $a_{0}$. The other is the TVC, which tells that for a consumption path to be optimal, nothing of value can be left behind in the last period.

Firm Problem

A representative firm rents capital and labor every period in perfectly competitive markets. Output is produced by use of a neoclassical production function:

$$Y_{t} = F(K_{t}, B_{t}L_{t})$$

$B_{t}$ is the level of technology that grows at a constant rate $x$ such that: $\frac{\dot{B}_{t}}{B_{t}} = x$ or $B_{t} = B_{0}e^{xt}$.

For a balanced growth path to exist, $B_{t}$ has to be labor-augmenting (Uzawa, REStud 1961).

Without adjustment costs in capital or labor, the firm problem is static.

At every period $t$, the firm will choose the amounts of capital $K_{t}$ and labor $L_{t}$ that maximize profits given a pair of prices $\{r_{t}, w_{t}\}$:

$$\Pi_{t} = F(K_{t}, B_{t}L_{t}) - (r_{t} + \delta)K_{t} - w_{t}L_{t}$$

The first-order conditions are:

$F_{K}(K_{t}, B_{t}L_{t}) = r_{t} + \delta$

$F_{L}(K_{t}, B_{t}L_{t}) = w_{t}$

Let's define per-effective-worker terms:


$$\hat{y}_{t} \equiv \frac{Y_{t}}{B_{t}L_{t}} \quad \text{and} \quad \hat{k}_{t} \equiv \frac{K_{t}}{B_{t}L_{t}}$$

Equilibrium

An equilibrium in this economy will be a sequence of allocations $\{c_{t}, a_{t}, K_{t}, L_{t}\}_{t=0}^{\infty}$ and prices $\{r_{t}, w_{t}\}_{t=0}^{\infty}$ such that:

Given the sequence of prices $\{r_{t}, w_{t}\}_{t=0}^{\infty}$, the sequence $\{c_{t}, a_{t}\}_{t=0}^{\infty}$ satisfies the household problem.

Given a pair of prices $\{r_{t}, w_{t}\}$, the pair of allocations $\{K_{t}, L_{t}\}$ solve the firm problem for every $t$.

The labor market clears: $L_{t} = N_{t} \quad \forall t$

The asset market clears: $K_{t} = N_{t}a_{t} \quad \forall t$

And the aggregate resource constraint is satisfied (which happens trivially due to Walras' law).

The Dynamic System

Remember the household budget constraint: $c_{t} + \dot{a}_{t} + na_{t} = w_{t} + r_{t}a_{t}$.
Making use of the equilibrium conditions and Euler's theorem for CRS functions, we get the law of motion for capital per capita:

$$\dot{k}_{t} = y_{t} - c_{t} - (n+\delta)k_{t}$$

This is very similar to the Solow model. The only difference is that in the Solow model $c_{t} = (1-s)y_{t}$, whereas in the Ramsey model $c_{t}$ is determined by the Euler equation of the household problem:

$$\frac{\dot{c}_{t}}{c_{t}} = \left[ -\frac{u_{cc}(c_{t})c_{t}}{u_{c}(c_{t})} \right]^{-1} (F_{K}(k_{t}, B_{t}) - \delta - \rho)$$

So, we have two differential equations in two variables $(k_{t}, c_{t})$.

Steady State Equilibrium

To have an autonomous system, we rewrite these equations with variables transformed into efficiency units:


$$\hat{c}_{t} \equiv \frac{c_{t}}{B_{t}} \quad \text{and} \quad \hat{k}_{t} \equiv \frac{k_{t}}{B_{t}}$$

The system becomes:


$$\dot{\hat{k}}_{t} = f(\hat{k}_{t}) - \hat{c}_{t} - (n+x+\delta)\hat{k}_{t}$$

$$\frac{\dot{\hat{c}}_{t}}{\hat{c}_{t}} + x = \left[ -\frac{u_{cc}(c_{t})c_{t}}{u_{c}(c_{t})} \right]^{-1} (f_{\hat{k}}(\hat{k}_{t}) - \delta - \rho)$$

Where $f(\hat{k}_{t}) := F(\hat{k}_{t}, 1)$ and $f_{\hat{k}}(\hat{k}_{t}) = F_{K}(k_{t}, B_{t})$.

Steady State Definition: $\gamma_{\hat{k}} = 0$ and $\gamma_{\hat{c}} = 0$.
Sufficient Condition: If $\left[-\frac{u_{cc}(c_{t})c_{t}}{u_{c}(c_{t})}\right] = \sigma$ is constant (CRRA), a steady state exists.

In the steady state we have:


$$\gamma_{\hat{k}} = 0 \Rightarrow \hat{c}^{*} = f(\hat{k}^{*}) - (n+x+\delta)\hat{k}^{*}$$

$$\gamma_{\hat{c}} = 0 \Rightarrow f_{\hat{k}}(\hat{k}^{*}) = \delta + \rho + \sigma x$$

Using a Cobb-Douglas production function where $f(\hat{k}^{*}) = (\hat{k}^{*})^{\alpha}$:


$$\hat{k}^{*} = \left( \frac{\alpha}{\delta+\rho+\sigma x} \right)^{\frac{1}{1-\alpha}} \quad \text{and} \quad \hat{y}^{*} = \left( \frac{\alpha}{\delta+\rho+\sigma x} \right)^{\frac{\alpha}{1-\alpha}}$$

Analyzing the Steady State

To determine $\hat{k}^{*}$, we use the Euler equation. In SS, $\frac{\dot{\hat{c}}_{t}}{\hat{c}_{t}} = 0$.
Why? In SS consumption (per efficiency unit of labor) growth will be zero. For households to choose such a consumption path, the interest rate must equal the effective discount rate.

Another way to see it using per-capita variables:


$$\frac{\dot{c}_{t}}{c_{t}} = \frac{1}{\sigma}(f_{\hat{k}}(\hat{k}_{t}) - \delta - \rho)$$


In SS, consumption per capita growth will be equal to $x$. For households to choose such a consumption path, the interest rate must exceed the discount rate by the right amount.

The Phase Diagram

The phase diagram maps the dynamics of $\hat{c}_{t}$ and $\hat{k}_{t}$.

The $\dot{\hat{c}}_{t} = 0$ Locus: This is a vertical line at $\hat{k}^{*} = f_{\hat{k}}^{-1}(\delta + \rho + \sigma x)$.

The $\dot{\hat{k}}_{t} = 0$ Locus: This is an inverted U-shaped curve defined by $\hat{c}_{t} = f(\hat{k}_{t}) - (n+x+\delta)\hat{k}_{t}$. It starts at the origin, peaks at the Golden Rule level of capital $\hat{k}_{g}$, and intersects the x-axis again at a higher level of capital $\bar{\hat{k}}$.

Steady State: The intersection of these two loci is the steady state $(\hat{k}^{*}, \hat{c}^{*})$.

Consumption in Steady State & Golden Rule

As in the Solow model, steady state consumption is not a monotone function of steady state capital.
The level of capital in the Golden Rule steady state maximizes consumption:


$$f_{\hat{k}}(\hat{k}_{g}^{*}) = n + x + \delta$$

Our steady state condition ($\gamma_{\hat{c}}=0$) implies the Modified Golden Rule:


$$f_{\hat{k}}(\hat{k}^{*}) = \delta + \rho + \sigma x$$

Is $\hat{k}^{*} \ge \hat{k}_{g}^{*}$ or $\hat{k}^{*} < \hat{k}_{g}^{*}$?


$$f_{\hat{k}}(\hat{k}_{g}^{*}) - f_{\hat{k}}(\hat{k}^{*}) = n + (1-\sigma)x - \rho$$

Implication of the Transversality Condition (TVC)

Recall the TVC: $\lim_{t\rightarrow\infty} (u_{c}(c_{t})e^{-(\rho-n)t} a_{t}) = 0$.
Making use of equilibrium conditions, CRRA, and transforming to efficiency units, we arrive at:


$$\lim_{t\rightarrow\infty} \hat{c}_{t}^{\sigma} \lim_{t\rightarrow\infty} \hat{k}_{t} \lim_{t\rightarrow\infty} e^{(n+(1-\sigma)x-\rho)t} = 0$$

Since $\hat{c}$ and $\hat{k}$ don't go to zero in steady state, we must have:


$$\lim_{t\rightarrow\infty} e^{(n+(1-\sigma)x-\rho)t} = 0 \Rightarrow n + (1-\sigma)x - \rho < 0$$

Because $n + (1-\sigma)x - \rho < 0$, we know:


$$f_{\hat{k}}(\hat{k}_{g}^{*}) - f_{\hat{k}}(\hat{k}^{*}) < 0 \Rightarrow \hat{k}^{*} < \hat{k}_{g}^{*}$$

Key Insights:

There is no scope for dynamic inefficiency. Households choosing savings optimally do not allow for capital to be excessive.

The Golden Rule steady state is never achieved. Even if we were there, households would choose to eat up part of the assets to enjoy higher consumption today. This is because of the discount rate $\rho$.

Interest Rate and Savings Rate in Steady State

The modified golden rule has a clear implication for the interest rate:


$$r^{*} = \rho + \sigma x$$


The market return on saving increases with the impatience of people ($\rho$), the growth rate of the economy ($x$), and the curvature of the utility function ($\sigma$).

For the savings rate in steady state (Cobb-Douglas case):


$$s^{*} = \alpha \frac{n+x+\delta}{\rho+\sigma x+\delta}$$


From the TVC, we know $n+x < \sigma x + \rho$, which means:


$$s^{*} < \alpha$$


(In SS, the fraction of output saved is always lower than the capital share).

Transitional Dynamics

What happens out of the steady state? The loci $\gamma_{\hat{k}} = 0$ and $\gamma_{\hat{c}} = 0$ divide the phase diagram into four regions.

$\gamma_{\hat{k}} > 0 \Rightarrow \hat{c} < f(\hat{k}) - (n+x+\delta)\hat{k}$. Capital increases below the curve and decreases above.

$\gamma_{\hat{c}} > 0 \Rightarrow f_{\hat{k}}(\hat{k}) > \delta + \rho + \sigma x$. Consumption increases to the left of the vertical line and decreases to the right.

Saddle-Path Stability:
For a given initial capital $\hat{k}_{0}$, there is only one initial consumption $\hat{c}_{0}$ that leads to the steady state (this is the stable arm).

If consumption is larger than $\hat{c}_{0}$, the path of consumption increases too fast, eating up capital stock and eventually hitting zero capital (violating Euler).

If consumption is smaller than $\hat{c}_{0}$, households over-accumulate and end up violating the transversality condition.

Comparative Statics

Consider the effects of changes in parameters:

Increase in Impatience ($\rho \uparrow$): Moves the $\gamma_{\hat{c}}=0$ locus to the left, leaves the $\gamma_{\hat{k}}=0$ curve unchanged. Results in a fall in $\hat{c}^{*}$, $\hat{k}^{*}$, and $\hat{y}^{*}$. Households need a higher interest rate to keep their consumption profile, so they accumulate less capital.

Increase in Curvature ($\sigma \uparrow$): Has the exact same effect as an increase in $\rho$. Higher curvature acts as a higher discount of future utilities.

(Note: $\rho$ and $\sigma$ cannot be separately identified with steady-state data alone).

Comparison to the Solow Model (no technology growth)

In Solow, $k^{*}$ is determined by $\frac{f(k^{*})}{k^{*}} = \frac{\delta+n}{s}$, so $k^{*}$ and $y^{*}$ fall when $n$ increases.

In Ramsey, $k^{*}$ and $y^{*}$ are independent of $n$. The determination of $k^{*}$ comes directly from the Euler equation, where $n$ plays no role.

Data and Application

How to parameterize the Ramsey model?
Suppose we observe: $x=0.02$, $n=0.01$, $\alpha=0.3$.
Measure key macro ratios: $\frac{k^{*}}{y^{*}} = 3$, $\frac{i^{*}}{y^{*}} = 1/4 \Rightarrow \frac{i^{*}}{k^{*}} = 1/12$.

Using the steady-state equations:

$\frac{i^{*}}{k^{*}} = \delta + n + x \Rightarrow \delta = 0.053$

$\alpha \frac{y^{*}}{k^{*}} = \delta + \rho + \sigma x \Rightarrow \rho + \sigma x = 0.047$

Feasibility Check (TVC): $\rho - n + \sigma x > x \Rightarrow 0.047 - 0.01 = 0.037 > 0.02$. This is OK.

The Savings Rate Trajectory

Quantitatively, the Ramsey model predicts declining saving rates along the transition. However, data seems to support the finding that as countries develop, their saving rates increase initially (hump-shaped profiles).

If we take reasonable bounds ($\rho \ge 0$), we get $\sigma \le 2.35$. But the model requires $\sigma > 4$ to match an increasing saving rate trajectory.

If we force an increasing saving rate, we'd need $\sigma > 17.5$ or assume a very high $\alpha = 0.75$ (interpreting it as broad capital including human capital).

Real-world examples of hump-shaped saving rates:

South-East Asian countries starting development in the late 20th century.

Japan since 1955.

Ramsey and the Data:

The standard Ramsey model with Cobb-Douglas is consistent with the second half of the hump (the decline), but not the initial increasing part.

Solutions? Use a CES production function (where K and L are bad substitutes), introduce non-homotheticities in consumption, or add financial frictions at the start of the development process.

Japan: Between 1960 and 2000, Japan evolved towards its steady state as the capital-to-output ratio increased, and the savings rate fell over this period. The Ramsey model can quantitatively account for this phase.

China: China is growing fast in transition to a higher steady state. It is saving a lot now, and presumably, it will save less in the future.