Macroeconomics I - Lecture 4

Alessandro Ferrari February 2026 UPF, CREi, BSE & CEPR

So far

The Solow and Ramsey models feature growth through capital accumulation driven by exogenous technological progress

they lack an autonomous engine of growth

namely, absent tech. progress, growth dies in the long run

effectively, not theories about why countries grow at different rates or why there are long-run differences

The AK model

We study a special case that actually may be a simple answer to this dissatisfaction

Some detective work: underlying the lack of autonomous long-run growth is one assumption: decreasing returns to capital

Simple fix: assume not

AK model:


$$y=f(k)=Ak$$


This is a very simple model skeleton: Solow with $\alpha=1 \Rightarrow f_{kk}=0$

Key property → Absence of diminishing returns to capital. That is to say, accumulation of a productive resource does not get exhausted.

Some background

Stated like this, this seems like a crazy (special case) model

Historically, this model (Harrod-Domar) comes from assuming that the production function is


$$Y=\min\{AK,BL\}$$

and that $K/L < B/A$ which implies that the economy is constrained by the amount of capital

The consequence is that the effective production function used is


$$Y=AK$$

With a constant and exogenous saving rate, we have that


$$\dot{K}=sY-\delta K=sAK-\delta K$$

Which implies


$$\gamma_{k}=\frac{\dot{K}}{K}=sA-\delta$$

which is also the growth rate of output since $Y$ is proportional to $K$.

Note, however, that output per worker is increasing if $\gamma_{y}-n>0$

But if $\gamma_{y}-n>0$, then in finite time $K$ is not the limiting factor as $K/L$ is eventually larger than $A/B$

but if the factor constraining the economy is $L$, then we use a technology


$$Y=BL$$

which implies that output will be proportional to labor and, therefore, output per capita will be constant.

growth has stopped.

so we need a model where $Y=AK$ is the only technology.

What's the rationale?

Arrow's learning-by-doing

The idea is that when we accumulate capital, as a byproduct (external), we generate improvements in $A$ that undo the diminishing return to factors

Arrow - Frankel

Suppose that a continuum of firms indexed by $j$ operates the production function


$$Y_{j}=\overline{A}K_{j}^{\alpha}L_{j}^{1-\alpha}$$


with


$$\overline{A}=A_{0}\left(\int_{i}K_{i}\right)^{\eta} \quad \text{and} \quad \eta>0$$

By market clearing we have that $\int_{i}k_{i}=K$ and since goods are perfect substitutes $Y=\int_{i}Y_{i}$


$$Y=A_{0}K^{\eta+\alpha}L^{1-\alpha}$$

rewrite this as


$$Y=AK^{\eta+\alpha}, \quad A \equiv A_{0}L^{1-\alpha}$$

the capital law of motion with exogenous saving rate is


$$\dot{K}=sY-\delta K=sAK^{\eta+\alpha}-\delta K$$

Hence the growth rate of the economy is


$$\gamma_{K}=sAK^{\eta+\alpha-1}-\delta$$

Growth Scenarios

If $1-\alpha-\eta>0$, we are back in the Solow model we solved whereby if there is no exogenous technological growth, eventually all growth subsides. We converge to


$$K^{*}=\left(\frac{sA}{\delta}\right)^{\frac{1}{1-\alpha-\eta}}$$

If $1-\alpha-\eta<0$, we have explosive growth. Capital accumulation has increasing returns, so any capital level is unstable.

The case we want to think about is the knife-edge case $1-\alpha-\eta=0$.

The Solow-AK model

First, note that this is the special case in which the externality $\eta$ exactly undoes the decreasing returns to capital accumulation $\alpha$.

Effectively, accumulating capital improves $A$ of the exact amount required to keep MPK constant despite the curvature of the individual firm production function.

Notice that in this case,


$$\dot{k}_{t}=sy_{t}-\delta k_{t}$$


and since $y_{t}=Ak_{t}$ and $c_{t}=(1-s)y_{t}$


$$\gamma_{k}=sA-\delta$$

$$\gamma_{y}=\gamma_{k} \quad \text{and} \quad \gamma_{c}=\gamma_{k}$$

If $sA>\delta$ then there is sustained growth of per capita variables. No need for technological progress.

$\gamma_{k}$ depends on behavioral parameters. Choices of $s$ and $n$ do affect the growth rate in the long run. (we could have a Ramsey-AK with endog. $s$)

No convergence prediction.

Importance of Non-Diminishing Returns

As the AK model illustrates, it seems that we need non-diminishing returns to factor accumulation.

However, we can have diminishing returns to capital accumulation and sustained growth.

Sustained growth means $\lim_{t\rightarrow\infty}\gamma_{k,t}>0$

Take any given $f(k)$:


$$\gamma_{k,t}=s\frac{f(k_{t})}{k_{t}}-\delta \Rightarrow \lim_{t\rightarrow\infty}\gamma_{k,t}=s \lim_{t\rightarrow\infty}\frac{f(k_{t})}{k_{t}}-\delta$$

Hence,


$$\lim_{t\rightarrow\infty}\gamma_{k,t}>0 \Leftrightarrow \lim_{t\rightarrow\infty}f_{k}(k_{t})>\frac{\delta}{s}$$

If $f_{k}(k_{t})$ converges to something (a constant) larger than $\delta/s$ then we obtain sustained growth even if $\frac{f(k_{t})}{k_{t}}$ falls with $k_{t}$.

We now can make the following observation on the importance of the Inada condition:

If there is a lower bound in the diminishing returns to capital and this lower bound is large enough, then factor accumulation will ensure eternal growth.

Does the Cobb-Douglas production function allow for sustained growth with capital accumulation?

Is the AK model an appealing approach to sustained growth?

Simple is beautiful. But,

Knife-edge case: production function has to be exactly linear in capital

Technical progress is a major factor in economic development.

We want a model that lets us understand why some countries experience technological development and others do not.

Testing AK models

A key testable implication of the Solow-AK models is that the rate of growth of output per capita depends on the savings rate.

This suggests that permanent changes in the investment rate of a given country should lead to permanent changes in the rate of growth of this country.

Jones (QJE 1995) uses post WWII data from developed economies to reject this hypothesis and therefore the Solow-AK model.

However, McGrattan (MPLS QR 1996), using both a longer time series and a mixture of developed and developing countries, finds evidence supporting this implication of the model.

It is now perceived we should move beyond this model.

AK-Ramsey - Romer (1986)

We can derive an endogenous consumption/saving version of the model, effectively looking at the AK version of Ramsey.

For simplicity, directly assume CRRA


$$U(0)=\int_{0}^{\infty}\frac{c^{1-\sigma}-1}{1-\sigma}e^{(n-\rho)t}dt$$

Usual flow budget constraint

Production function such that $\lim_{k\rightarrow\infty}F_{k}>0$

Implies the capital law of motion


$$\dot{k}_{t}=Ak_{t}-c_{t}-(\delta+n)k_{t}$$

and, by competitive factor markets, we have


$$r_{t}=A-\delta$$

Consumer optimization given by Euler Equation (EE) and Transversality Condition (TVC):


$$\frac{\dot{c}}{c}=\frac{r_{t}-\rho}{\sigma}=\frac{A-\delta-\rho}{\sigma} \quad \text{(EE)}$$

$$\lim_{t\rightarrow\infty}k_{t}e^{(n-r)t}=0 \quad \text{(TVC)}$$

By EE, we must have that consumption grows at a constant rate, and that growth is positive iff $A>\delta+\rho$ (which we assume to be the case).

Externalities and Inefficiency

The presence of externalities immediately takes us away from the kind of economies we studied so far

When some agent does not internalize fully the consequences of their action, typically the economy is inefficient

The key issue here is that the private and social returns to capital accumulation are different

Firm set the gross rental rate such that


$$R_{t}=\alpha AK_{i}^{\alpha-1}L_{i}^{1-\alpha}$$

This is because the individual firm optimizes over $K_{i}$, taking $A$ as given

As a consequence, the rental rate is


$$r_{t}=\alpha AK_{i}^{\alpha-1}L_{i}^{1-\alpha}-\delta$$

From the EE, we have that


$$\frac{\dot{c}}{c}=\frac{\alpha AK_{i}^{\alpha-1}L_{i}^{1-\alpha}-\delta-\rho}{\sigma} = \frac{\alpha A_{0}K^{\eta}K_{i}^{\alpha-1}L_{i}^{1-\alpha}-\delta-\rho}{\sigma}\equiv\gamma_{c}$$

Social Planner Solution

Consider instead a Social Planner choosing the full capital stock $K$

The optimal amount of capital equates the social marginal cost to the social marginal product, given by


$$R_{t}^{SP}=(\alpha+\eta)A_{0}K^{\alpha+\eta-1}L^{1-\alpha}$$

The social marginal cost is still given by the utility cost of consuming less (also accounting for depreciation and time discounting)


$$\frac{\dot{c}}{c}=\frac{(\alpha+\eta)A_{0}K^{\alpha+\eta-1}L^{1-\alpha}-\delta-\rho}{\sigma}\equiv\gamma_{c}^{SP}$$

Given our assumptions on $\eta$ we immediately have that $\gamma_{c}^{SP}>\gamma_{c}$

The presence of externalities implies that the social and private returns are different

As a consequence, provided that the private and social marginal cost are the same, agents and social planners will choose different allocations

Since the externality is positive, agents do too little

Social MP of capital accumulation > Private MP = Private MC = Social MC $\Rightarrow$ too little saving and capital in equilibrium

As the planner saves more, accumulates more capital and, exploiting the positive external effects, induces higher SS consumption growth.

The converse result holds: suppose $\eta<0$ namely there is a negative externality associated to capital accumulation. Agents accumulate too much capital from a social perspective, meaning growth is higher in the equilibrium relative to the planner solution. Does it mean that the social planner is doing worse than private agents?

Summary (AK Models)

We built a model in which growth comes from an external effect of capital accumulation

However, we still have no theory on endogenous growth

Since all the growth in this economy comes from external increases in $A$ associated with capital accumulation

What is more, since it is external, this technological improvement is unremunerated

Ideally, we want to move to a theory where technological progress is the outcome of an endogenous choice by agents

Endogenous Growth

Most of modern growth theory is (semi-) endogenous growth

Most endogenous growth models boil down to the AK model

Intuitively, it has to be! If the only force at play is diminishing returns to capital, at some point, the returns to capital accumulation are too low

Something else in the economy must undo/offset the decreasing returns

this something is typically an improvement in technology, much like in the AK model with external effects

A step back

We tend to think of production functions as having decreasing returns in inputs and (often) constant returns to scale

The underlying idea is that of replication: suppose I create a twin Earth, output doubles

Key insight of modern growth: one part of the production function does not, in fact, need to be replicated: knowledge

Knowledge is a non-rival partly excludable good

Non-rival: the use of knowledge by one agent does not preclude its use by another.

Partly Excludable: patents, trade secrecy, imitation, or adaptation costs allow an innovator to temporarily exclude other firms.

What motivates innovation?

Expected returns to innovation: eg, lifetime value of a patent

important: cost of research is fixed and upfront: there is no marginal cost in research production! Market size matters.

This is known as endogenous technical change

Leading Endogenous Growth Models

Romer (1990): growth comes from the creation of new products

Aghion Howitt (1992): growth comes from Schumpeterian dynamics of quality improvements (old products/firms exit, replaced by new/better ones) $\Rightarrow$ creative destruction

Key common element: researchers choose how much to innovate and endogenously drive the rate of technological change

Romer (1990) - Final Good Production

Household side very similar to Ramsey, for simplicity, assume CRRA directly

No population growth

Key difference is on the production side

There are (for now) 2 sectors: final good $Y$ and a measure $M_{t}$ of intermediate goods $x_{i}$


$$Y_{t}=\frac{L^{1-\alpha}}{\alpha}\int_{0}^{M_{t}}x_{i}^{\alpha}di \quad \alpha\in(0,1)$$

Variety Effect

Why do varieties matter?

Because $\alpha\in(0,1)$ implies imperfect substitutability between $x_{i}$

Having a larger measure $M_{t}$ is isomorphic to having a higher aggregate productivity

Simple proof: define the total amount of intermediate goods used in production


$$X_{t}=\int_{0}^{M_{t}}x_{i}^{\alpha}di$$

Suppose that intermediate goods producers are symmetric, so that $x_{i}=x \ \forall i$

Then using $x=X_{t}/M_{t}$ in the aggregate production function we obtain


$$Y_{t}=\frac{M_{t}^{1-\alpha}}{\alpha}L^{1-\alpha}X_{t}^{\alpha}$$

Conditional on a given total amount $X_{t}$, more production occurs if we spread it on more $x_{i}$

This is driven by decreasing returns to each individual variety

Resource Constraint

The remainder of the model is almost all familiar

There is a competitive firm aggregating the intermediate goods

The final good is used to either consume or save/invest

importantly, note that in an economy with intermediate goods $Y_{t}$ is not GDP, which is given by


$$GDP_{t}=Y_{t}-X_{t}$$

Research Firms

The unfamiliar part is the market structure on the intermediate goods market

We assume that firms are monopolistically competitive

Monopolistically: they do NOT take output prices as given as they are the only provider of their specific variety

Competitive: there are very many of these producers, such that despite their market power in their specific product market, they are price-takers on everything aggregate, such as wages and the price of $Y$

Research Firms Problem

The Monopolistic competition problem is given by


$$\max_{x_{i}} p_{i}(x_{i})x_{i}-c_{i}x_{i}$$

Where $p_{i}(x_{i})$ is the inverse demand for good $i$.

The FOC of the problem is


$$p_{i}^{\prime}x_{i}+p_{i}=c_{i}$$

Define $\epsilon(x_{i})=-\frac{\partial \log x_{i}}{\partial \log p_{i}}$, the optimal price is


$$p_{i}=\frac{\epsilon(x_{i})}{\epsilon(x_{i})-1}c_{i}$$

Final Good Firm Problem

Assume that intermediate good producers have a CRS, turning final good into their intermediate good

To compute the optimal price, we need the inverse demand from the final good producer

The profit maximization problem of the final good is


$$\max_{\{x_{i}\}_{i}} \frac{L^{1-\alpha}}{\alpha}\int_{0}^{M_{t}}x_{i}^{\alpha}di-\int_{i}p_{i}x_{i}-wL$$

The FOC of the problem is


$$p_{i}=L^{1-\alpha}x_{i}^{\alpha-1}$$

Research Firm Price & Profits

This FOC defines the inverse demand for variety $x_{i}$

We can plug the demand in the monopolist problem


$$\pi_{i}=L^{1-\alpha}x_{i}^{\alpha-1}x_{i}-c_{i}x_{i}$$

The FOC implies


$$\alpha L^{1-\alpha}x_{i}^{\alpha-1}=c_{i}$$

Normalize $c_{i}=\alpha$, the optimal production quantity is $x_{i}=L$

Note this implies $p_{i}=1, \ \forall i$. Here, the trick is that the monopoly markup is $1/\alpha$ and we set the marginal cost to $\alpha$.

Plugging this solution into the profit function, we get


$$\pi_{i}=L(1-\alpha)$$

Conditional on a successful innovation, research firms obtain profit $\pi_{i}=\pi, \ \forall i$ every period, then the value of a firm with a perpetual monopoly is


$$V=\int_{t}^{\infty}\pi e^{-\int_{t}^{\tau}r_{\omega}d\omega}d\tau$$

In a Balanced Growth Path (BGP), this simplifies. Conjecture in the BGP $r_{\omega}=r$:


$$V=\int_{t}^{\infty}\pi e^{-r\int_{t}^{\tau}d\omega}d\tau=\int_{t}^{\infty}\pi e^{-r(\tau-t)}d\tau$$

Changing the bound by setting $s=\tau-t$, this is


$$V=\int_{0}^{\infty}\pi e^{-rs}ds=\pi\int_{0}^{\infty}e^{-rs}ds=\pi\left(-\frac{1}{r}e^{-rs}\Big|_{0}^{\infty}\right)$$

Which gives $V=\frac{\pi}{r}$.

Aggregation and Growth

At this point, we know what is the value of a firm with a perpetual patent, but we have not yet determined how variety creation happens.

Why does this matter? Ask what the growth rate of the economy is.

Plugging the symmetric solution $x_{i}=x$ into the aggregate production function we get


$$Y_{t}=\frac{LM_{t}}{\alpha}$$

Even if CRS in L, the economy has increasing returns since there is endogenous creation of $M$.

Definition of $GDP \Rightarrow GDP_{t}=Y_{t}-X_{t}=LM_{t}/\alpha-xM_{t}=M_{t}(L/\alpha-x)$

From this, we immediately note that


$$\frac{\partial \log GDP_{t}}{\partial t}=\frac{\partial \log M_{t}}{\partial t}$$

So we have that the growth rate of GDP is proportional to the growth rate of the number of available varieties

We need to close the model by figuring out how varieties grow.

Suppose that there is an R&D sector, such that $R_{t}$ resources are spent in research.


$$\dot{M}_{t}=\lambda R_{t}$$

Interest Rate

We assume that the research sector is competitive and that researchers obtain the profits associated with product creation (discounting at the market rate $r$)

Underlying assumption is one of perpetual fully-enforced patents: the inventor of the machine has perpetual monopoly rights to it


$$\pi^{R}=\left(\frac{\pi}{r}\right)\lambda R-R$$

To have no profit, we need the interest rate to be such that


$$\pi^{R}=0 \iff r=\lambda\pi$$

Underlying assumption: there is free entry into research, so we need to arbitrage any profit away.

Savings and Growth

We assumed that there is no capital in this economy. How does the household transfer resources across periods?

Effectively the household saves by investing in R&D

Consider the resource constraint for the final good


$$Y_{t}-X_{t}\ge c_{t}+R_{t}$$

Since the household side is standard, under CRRA, we obtain the usual Euler Equation.

What is the asset that transfers resources over time?

The household saves assets that turn into firm equity: household owns a balanced portfolio of all firms/patents


$$\frac{\dot{c}}{c}=\frac{r-\rho}{\sigma}$$

Who owned the firms in the Ramsey model? The household! But it did not matter cause in eqm they made zero profits. Here it matters because, due to monopolistic competition, profits are positive.

Consumption and GDP must grow at the same rate, so


$$\frac{\partial \log GDP}{\partial t}=\frac{r-\rho}{\sigma}$$

Plugging in the interest rate and profits we obtain


$$\frac{\partial \log GDP}{\partial t}=\frac{\lambda(1-\alpha)L-\rho}{\sigma}$$

This has to be positive for the TVC to hold

Note that growth is increasing in research productivity $\lambda$ and in the size of the economy $L \Rightarrow$ scale effects

Romer (1990) - Summary Market Allocation

Constant growth economy $\gamma=\frac{\lambda(1-\alpha)L-\rho}{\sigma}$

Quantities: $x_{i}=x=L, \ \forall i$ so that $X_{t}=LM_{t}$ and, therefore, $Y_{t}=\frac{M_{t}L}{\alpha}$

Net of the cost of production of inputs, output is


$$\tilde{Y}=Y_{t}-\alpha X_{t}=\frac{M_{t}L}{\alpha}-\alpha M_{t}L=\frac{M_{t}L}{\alpha}(1-\alpha^{2})$$

Is this allocation efficient? $\Rightarrow$ solve the planning problem

Romer (1990) - Planner Problem

Break down the problem between a static and a dynamic choice:

Static: given a number of varieties $M_{t}$ choose how much to produce of each variety $x_{i}$ and, therefore, total output $Y_{t}$

Dynamic: given the optimal static choice, choose how to allocate output between consumption and research (savings)

Static Planner Problem

Static Problem is


$$\max_{\{x_{i}\}_{i}} \frac{L^{1-\alpha}}{\alpha}\int_{0}^{M_{t}}x_{i}^{\alpha}di-\alpha\int_{0}^{M_{t}}x_{i}di$$

Planner accounts for the production cost of each variety directly.

Then, the FOC is


$$L^{1-\alpha}x_{i}^{\alpha-1}=\alpha$$

Note that the LHS is the social marginal cost of more variety $x_{i}$, and it is the same as in the market allocation.

The RHS is the social marginal cost, while in the market allocation, we had the price $p_{i}$. Importantly $SMC=\alpha < p_{i}=1$.

The difference is exactly the monopoly markup $1/\alpha$.

The planner therefore chooses $x_{i}^{*}=L\alpha^{\frac{1}{\alpha-1}}>L=x_{i}, \ \forall i.$

Plugging back to find output


$$Y_{t}^{*}=\frac{M_{t}}{\alpha}L\alpha^{\frac{\alpha}{\alpha-1}}>\frac{M_{t}}{\alpha}L=Y_{t}$$

And net output


$$\tilde{Y}_{t}^{*}=\frac{M_{t}}{\alpha}L\alpha^{\frac{\alpha}{\alpha-1}}(1-\alpha)$$

Dynamic Planner Problem

Planner solves


$$\max_{c_{t}} \int_{0}^{\infty}\frac{c_{t}^{1-\sigma}-1}{1-\sigma}e^{-\rho t}dt$$


constrained by the law of motion of varieties


$$\dot{M}_{t}=\lambda(\tilde{Y}_{t}-c_{t})=\lambda\frac{M_{t}}{\alpha}L\alpha^{\frac{\alpha}{\alpha-1}}(1-\alpha)-\lambda c_{t}$$

Write the present-value Hamiltonian


$$\mathcal{J}=\frac{c_{t}^{1-\sigma}-1}{1-\sigma}e^{-\rho t}+\nu_{t}\left[\lambda\frac{M_{t}}{\alpha}L\alpha^{\frac{\alpha}{\alpha-1}}(1-\alpha)-\lambda c_{t}\right]$$

The necessary conditions for an optimum are:


$$\mathcal{J}_{c}=0 \Rightarrow c_{t}^{-\sigma}e^{-\rho t}=\lambda\nu_{t}$$

$$\mathcal{J}_{M}=-\dot{\nu} \Rightarrow -\dot{\nu}_{t}=\nu_{t}\frac{\lambda L\alpha^{\frac{\alpha}{\alpha-1}}(1-\alpha)}{\alpha}$$

$$\mathcal{J}_{\nu}=\dot{M} \Rightarrow \dot{M}_{t}=\lambda\frac{M_{t}}{\alpha}L\alpha^{\frac{\alpha}{\alpha-1}}(1-\alpha)-\lambda c_{t}$$

Plus the transversality condition,


$$\lim_{t\rightarrow\infty}(\nu_{t}M_{t})=0$$

Doing the same steps as in the Ramsey model


$$\frac{\dot{c}_{t}}{c_{t}}=-\frac{1}{\sigma}\left(\frac{\dot{\nu}_{t}}{\nu_{t}}+\rho\right)$$

Combining with the second condition


$$\gamma^{*}\equiv\frac{\dot{c}_{t}^{*}}{c_{t}^{*}}=\frac{1}{\sigma}\left(\frac{\lambda L\alpha^{\frac{\alpha}{\alpha-1}}(1-\alpha)}{\alpha}-\rho\right)$$

Market vs. Planner Comparison

We can now compare the market and planner solutions. Since $\alpha^{\frac{1}{\alpha-1}}>1$:


$$\gamma^{*}\equiv\frac{\dot{c}_{t}^{*}}{c_{t}^{*}}=\frac{1}{\sigma}\left(\frac{\lambda L\alpha^{\frac{\alpha}{\alpha-1}}(1-\alpha)}{\alpha}-\rho\right) > \frac{\lambda(1-\alpha)L-\rho}{\sigma}=\gamma$$

Planner economy always grows faster than the market economy

Planner uses the machines ($x$) more intensively (no markup) and produces more

Optimal policy intervention is a subsidy to the use of machines $\alpha$ so that the marginal cost for firms is $\alpha^{2}$ and therefore the market price is $\alpha^{2}/\alpha=\alpha$ which is the social marginal cost.

Scale Effects

Recall that growth in this economy always scales with $L \Rightarrow$ scale effects

Why are there scale effects?

Because of the nature of the research process, larger economies are those in which the returns to innovation are higher

Hence, research investment is higher, and so is research output and, therefore, growth

The key prediction is, therefore, that larger economies grow faster

Empirics & Data

Larger economies do not necessarily grow faster (Jones, 1995)

If the returns to innovation were constantly growing at the same rate as the economy, we would see that the R&D sector is a constant fraction of the economy

Jones points out that the number of researchers has increased more than 10 times since the '50s but growth has not accelerated.

(Reference: Figure 1 shows US GDP per capita from 1880-2010 tracking a steady ~2.0% per year growth line without structural acceleration.)

(Reference: Figure 2 shows US R&D spending share climbing from under 1% in 1930 to roughly 5% in 2010.)

(Reference: Figure 3 shows the research share of total population increasing steadily across the US, OECD, and other nations since 1950.)

Moving Away From Scale Effects

What's behind scale effects?

First, is the assumption that the innovation rate is constant with respect to research input

Another important element is that we use a reproducible factor as the input in the production of ideas (lab-equipment model: turn output into machines)

Fix #1: use a scarce resource as input in making blueprints (labor), then there cannot be endogenous growth absent spillovers from previous R&D.

No Scale Effects - First Attempt

The model so far (lab-equipment model) implies that output is linear in the accumulable factor (the stock of varieties)

Basically an AK model $\Rightarrow$ we can try using the scarce factor as the input in research

In this case, there cannot be sustained growth without spillovers: we need spillovers to make labour more and more productive

The first attempt to eliminate scale effects is to make blueprints produced out of the scarce factor:


$$\frac{\partial \log M_{t}}{\partial t}=\lambda L_{t}^{R}$$

$$\dot{M}_{t}=\lambda M_{t}L_{t}^{R}$$

With the labor market clearing


$$L\ge L_{t}^{E}+L_{t}^{R}$$


Where $L_{t}^{E}$ is labor used for production

The rents associated with new products are given by


$$\pi^{R}=\frac{\Pi}{r}\lambda L_{t}^{R}M_{t}-w_{t}L_{t}^{R}$$

Which implies


$$\lambda M_{t}\frac{\Pi}{r}=w_{t}$$

To solve for the movements in $M$, we need to solve for the wage rate.

Note that the wage rate cannot be constant since higher $M_{t}$ increases MPL. From the FOC of the final good producer


$$w_{t}=MPL_{t}=\frac{1-\alpha}{\alpha}L^{-\alpha}x^{\alpha}M_{t}=\frac{1-\alpha}{\alpha}M_{t}$$

Combining with the FOC, the Free Entry condition implies


$$\lambda M_{t}\frac{(1-\alpha)L_{t}^{E}}{r}=\frac{1-\alpha}{\alpha}M_{t}$$

Which gives us the equilibrium interest rate


$$r=\alpha\lambda L^{E}$$

Then the Euler Eq (with population growth) gives us


$$\frac{\dot{c}}{c}=\frac{\alpha\lambda L^{E}-\rho}{\sigma}$$

Labor Allocation

Note that we are not done, since $L^{E}$ is an endogenous object. To determine the growth rate of the economy, we need to pin down how production vs research labor evolves.

The research technology implies


$$\dot{M}_{t}=\lambda M_{t}L_{t}^{R}$$

Using the labor market clearing condition


$$\frac{\dot{M}_{t}}{M_{t}}=\lambda(L-L_{t}^{E})$$

We know that GDP grows at the rate of the number of varieties


$$\gamma=\lambda L^{R}=\lambda(L-L^{E})$$

Combining with the EE, we get


$$\gamma=\frac{\alpha\lambda L-\rho}{\alpha+\sigma}$$

Result: We still have scale effects since $\gamma$ still increases in $L$.

No Scale Effects - Jones (1995)

Jones' fix: ideas get harder to find: $\dot{A}/A=TFP^{R}\cdot R$

Decreasing returns to blueprint production!

Consider an economy whose population grows at the exponential rate $n$

Suppose further that, differently from before, the knowledge spillovers of the R&D sector are limited, and that innovation uses labor as an input:


$$\dot{M}_{t}=\lambda M_{t}^{\phi}L_{t}^{R}$$

with $\phi<1$ and $L_{t}^{R}$ is labor employed for research

We can follow similar steps as before to find the equilibrium research investment and growth rate

The researcher's profits are given by


$$\pi_{R}=\Pi\lambda M^{\phi}L_{R}/r-wL_{R}$$

Firm profits are still $\Pi=L_{E}(1-\alpha)$ which implies that the researcher FOC is


$$L_{E}\lambda\alpha M^{\phi-1}/r=1$$

Taking logs


$$\log L_{E}-\log r+\log \lambda+\log \alpha+(\phi-1)\log M=0$$

Differentiating wrt time


$$\dot{L}_{E}/L_{E}+(\phi-1)\dot{M}/M=0$$

On the BGP $L_{E}/L=\text{const}$, hence $\dot{L}_{E}/L_{E}=n$

Substituting in, we find


$$\frac{\dot{M}}{M}=\frac{n}{1-\phi}$$

Since we know that GDP per capita grows at the rate of the number of varieties we obtain


$$\gamma_{C}=\frac{n}{1-\phi}$$

Conclusions of Jones (1995)

Note that this does not depend on L, so there are no scale effects anymore.

But, absent population growth, there is no growth at all.

Key difference is that spillovers are limited.

Absent population growth, these spillovers would affect the level of output, but not strong enough to sustain growth.

Population growth increases the market size for new technologies steadily and generates growth from these limited spillovers.n