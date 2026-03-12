Macroeconomics I - Lecture 6

Alessandro Ferrari March 2026 UPF, CREi, BSE & CEPR

So far

Our focus has been on what "drives" growth in the economy

We have done this in the context of models in which:

there is one sector (or a continuum of identical sectors)

we can generate the Kaldor facts on the income composition of the economy

These models, by design, miss maybe one of the most salient features of economic development

Structural Change - US over time

[Graph: Employment shares of Agriculture, Manufacturing, and Services in the US from 1800 to 2000. Agriculture sharply declines, Services sharply rises, and Manufacturing follows an inverse-U shape.]

Structural Change - Many countries

[Graph: (a) Agriculture share vs. log GDP across many countries. Shows a clear downward trend.]

Structural Change - Many countries

[Graph: (c) Industry share vs. log GDP across many countries. Shows an inverse-U shape peaking around middle income.]

Structural Change - Many countries

[Graph: (b) Services share vs. log GDP across many countries. Shows a clear upward trend.]

Structural Change

Most economies that undergo significant economic growth feature:

movement out of agriculture into manufacturing

movement out of manufacturing into services

The models we studied so far simply cannot generate these patterns

Candidate explanations for SC:

Demand: as agents get richer they spend less of their income on food and more on services

Supply: if technological progress occurs at the sector level at different rates, shifts in the sectoral composition will follow simply by appropriately allocating resources

Structural Change - Demand

The key hurdle to the demand-side explanation for SC is one assumption we have made throughout: homotheticity of preferences

We have assumed this because it makes our problem much easier but now we need to get rid of it.

Homotheticity (formally):

Preferences are said to be homothetic if the utility function is homogeneous of degree 1.

Define the Engel curve as $x_{i}=x_{i}(I,p_{i})$, at a given $p$, then Engel curves are linear if preferences are homothetic

Structural Change - Demand

If Engel curves are linear, then doubling one's income implies doubling demand for all goods

there cannot be any demand-driven structural change

Engel curve special case you are probably familiar with:

normal good: EC is increasing

inferior good: EC is decreasing

necessities: EC is increasing and concave

Structural Change - Demand

Suppose EC is increasing and concave

this implies that $x^{\prime}>0$ but also $x^{\prime}I-x(I)<0$

Define the share of the expenditure spent on good $x$ as


$$s_{x}=\frac{px}{I}$$

then


$$s^{\prime}=\frac{px^{\prime}}{I}-\frac{px}{I^{2}}\propto x^{\prime}-\frac{x}{I}$$

which is negative if $x$ is concave

Structural Change - Demand

Engel's "Law": as income increases, the percentage spent on food decreases, even though the total amount of food expenditure increases.

food is a necessity

luxury good: EC is increasing and convex

alternative (equivalent) definitions in terms of income elasticities $\epsilon_{I}$

necessities: $\epsilon_{I}<1$

luxury: $\epsilon_{I}>1$

Now: a model with non-homothetic preferences to generate demand-driven structural change

Structural Change - Demand

At the heart of the model: Stone-Geary preferences


$$c_{t}=(c_{t}^{A}-\gamma^{A})^{\eta_{A}}c_{t}^{M^{\eta_{M}}}(c_{t}^{S}+\gamma^{S})^{\eta_{S}}$$


where $\gamma^{A}, \gamma^{S}>0$ and $\eta_{S}+\eta_{M}+\eta_{A}=1$

Special case of


$$c=\prod_{i}(c_{i}-\gamma_{i})^{\eta_{i}} \text{ with } \sum_{i}\eta_{i}=1$$

Generalization of Cobb-Douglas $(\gamma_{i}=0,\forall i)$

$\gamma_{i}>0 =$ subsistence level

need to consume $\gamma_{i}$ before additional utility is obtained

Structural Change - Demand

Derive the demand schedule from


$$\max_{\{c_{i}\}}\mathcal{L}=\prod_{i}(c_{i}-\gamma_{i})^{\eta_{i}}+\lambda\left[I-\sum_{i}p_{i}c_{i}\right]$$

whose FOC is


$$\eta_{i}(c_{i}-\gamma_{i})^{-1}\prod_{k}(c_{k}-\gamma_{k})^{\eta_{k}}=\lambda p_{i}$$

dividing by the $j$ FOC


$$\frac{\eta_{i}}{\eta_{j}}\frac{c_{j}-\gamma_{j}}{c_{i}-\gamma_{i}}=\frac{p_{i}}{p_{j}}$$

Structural Change - Demand

we can follow the usual steps to obtain the demand schedule


$$c_{j}=\gamma_{j}+\frac{\eta_{j}(I-\sum_{i}p_{i}\gamma_{i})}{p_{j}}$$

Suppose all subsistence levels are satisfied, then the household spends according to the shares $\eta_{j}$.

The Engel curve is still linear! but it does not start from 0. (Engels curve is weakly concave)

When income is low (e.g., too low to cover the subsistence level), the household only buys necessity goods.

When $\gamma_{j}<0$ (e.g., in services), the demand is negative at low income. (Engels curve is weakly convex).

Structural Change - Demand

We can now go back to our specific 3 sector preferences.

Assume that sectors have a production function of the type


$$Y_{it}=B_{i}F(K_{it},X_{t}L_{it}) \quad i=\{A,M,S\}$$

Namely, there are sector-specific time-invariant TFP differences $B$ and time-varying labour-augmenting productivity $X_{t}$.

all sectors have an identical neo-classical production function $F$

Suppose, for simplicity, that technological progress occurs at rate $g>\frac{\rho-n}{1-\sigma}$

Structural Change - Demand

Market clearing conditions


$$\sum_{i}K_{it}=K_{t} \quad \text{and} \quad \sum_{i}L_{it}=L_{t}$$

Important assumption: investment good is made out of manufacturing good

Note: no depreciation

Market clearing for A and S


$$Y_{t}^{A}=c_{t}^{A}L_{t}$$

$$Y_{Mt}=\dot{K}_{t}+c_{t}^{M}L_{t}$$


and


$$Y_{t}^{S}=c_{t}^{S}L_{t}$$

Structural Change - Demand

Assume factor market are competitive, which implies MP equalization


$$w_{t}=MPL_{it}, \forall i \quad \text{and} \quad r_{t}=MPK_{it}, \forall i$$

This and the common production function directly implies


$$\frac{K_{it}}{X_{t}L_{it}}=k_{t}\forall i$$

Suppose the manufacturing good is the numeraire then


$$p_{t}^{A}=\frac{B_{M}}{B_{A}} \quad \text{and} \quad (p_{t}^{M}=1,\forall t) \quad \text{and} \quad p_{t}^{S}=\frac{B_{M}}{B_{S}}$$

Structural Change - Demand

Suppose the household has intertemporal preferences given by


$$\int_{t}e^{-(\rho-n)t}\frac{c_{t}^{1-\sigma}-1}{1-\sigma}$$

Suppose that the following holds


$$Y_{At}=B^{A}F(K_{A0},X_{0}L_{A0})>\gamma^{A}L_{0}$$

Namely, there is enough food to cover the sustenance level

Then we are in the well-behaved part of the consumption schedule and the usual EE holds of the manufacturing good


$$\frac{\dot{c}_{t}^{M}}{c_{t}^{M}}=\frac{r_{t}-\rho}{\sigma}$$

Structural Change - Demand

Finally, from the intratemporal optimization, we have


$$\eta^{M}\frac{B_{M}(c_{t}^{A}-\gamma^{A})}{B_{A}\eta^{A}}=c_{t}^{M}=\eta^{M}\frac{B_{M}(c_{t}^{S}+\gamma^{S})}{B_{S}\eta^{S}}$$

The first result we can state in this model is that if either $\gamma^{A}>0$ and/or $\gamma^{S}>0$ we cannot have an equilibrium where all sectors grow at the same rate

Intuitive implication from the fact that our preferences feature Engel's Law.

As the economy grows food consumption increases less than 1-for-1 with income, while service consumption more than 1-for-1

Structural Change - Demand

As a consequence, we need a new definition of BGP

Call a constant growth path (CGP) a situation where the consumption aggregate grows at a constant rate but sectoral consumptions do not.

because sectoral consumption is not a constant share of consumption, neither is output of total output or employment of total employment.

You can show that a CGP exists (unique) iff $\gamma^{A}/B_{A}=\gamma^{S}/B_{S}$.

Structural Change - Demand

In the CGP, the following holds


$$\frac{\dot{c}_{t}^{A}}{c_{t}^{A}}=g\frac{c_{t}^{A}-\gamma^{A}}{c_{t}^{A}} < g$$

$$\frac{\dot{c}_{t}^{M}}{c_{t}^{M}}=g$$

$$\frac{\dot{c}_{t}^{S}}{c_{t}^{S}}=g\frac{c_{t}^{S}+\gamma^{S}}{c_{t}^{S}} > g$$

The economy grows at the exogenous rate of technological progress $g$

Agricultural consumption shrinks while service consumption expands as a fraction of consumption

Structural Change - Demand

Similarly, for employment


$$\frac{\dot{L}_{At}}{L_{At}}=n-g\frac{\gamma^{A}L_{t}}{B_{A}L_{At}X_{t}F(k^{*},1)} < n$$

$$\frac{\dot{L}_{Mt}}{L_{Mt}}=n$$

$$\frac{\dot{L}_{St}}{L_{St}}=n+g\frac{\gamma^{S}L_{t}}{B_{S}L_{St}X_{t}F(k^{*},1)} > n$$

Structural Change - Demand

This model delivers structural change on the CGP

It does so exclusively via preferences:

If we assume that agents follow Engel's Law, we have a declining employment share in agriculture and an increasing employment share in services

by making manufacturing non-homothetic, we can also explain the rising share of employment

Competing (possibly complementary) explanation: supply-side

Structural Change - Supply

Core idea: Baumol's cost disease

If two sectors grow at different rates and they share common production factors there will be reallocation between them

there cannot be a BGP with constant sectoral shares

Structural Change - Supply

Suppose the size of two A, B sectors is fixed (in quantities): Leontief aggregator over sectoral output

Suppose sector A productivity grows faster than B's and that they both only use labor

Workers will arbitrage any wage differences away, which implies that in eqm, the wage must be equal to the MPL in A.

at constant quantities, more and more workers (as a share of total population) have to be employed in B, and the rel. price of B goods must increase over time

Structural Change - Supply

[Graph: Price changes over time for various sectors like College tuition, Medical care, Housing, vs. Toys, Televisions. Services generally increase in price while manufactured goods decrease.]

Structural Change - Supply

What do we know about productivity growth differentials?

Duarte & Restuccia: measure productivity as


$$\frac{\text{VA}}{\text{hours worked}}$$

1956-2004 avg growth

Agriculture: 3.8%

Manufacturing: 2.4%

Services: 1.3%

holds for most countries in the sample

Structural Change - Supply

A model of supply-side driven structural change

To focus on supply side: drop all non-homotheticities in preferences: final good aggregator (equiv. to consumption aggregator)


$$Y_{t}=[\omega Y_{1t}^{\frac{\epsilon-1}{\epsilon}}+(1-\omega)Y_{2t}^{\frac{\epsilon-1}{\epsilon}}]^{\frac{\epsilon}{\epsilon-1}}$$


with $\epsilon>0$, $\omega\in(0,1)$.

Capital is created out of output (no depreciation) requires


$$\dot{K}_{t}+L_{t}c_{t}\le Y_{t}$$

Sector-specific production functions


$$Y_{it}=A_{it}K_{it}^{\alpha_{i}}L_{it}^{1-\alpha_{i}}$$

Structural Change - Supply

Suppose, wlog, that


$$\alpha_{1}<\alpha_{2}$$

sector 1 is more labour-intensive than sector 2.

Suppose also that productivity growth is exogenous and follows


$$\frac{\dot{A}_{it}}{A_{it}}=a_{i}>0$$

Finally, usual market clearings for factors


$$K_{t}=K_{1t}+K_{2t} \quad \text{and} \quad L_{t}=L_{1t}+L_{2t}$$

Structural Change - Supply

Make $Y_{t}$ the numeraire so that $P_{t}=1$, from the household optimization we have demand schedules


$$p_{1t}=\omega Y_{1t}^{-\frac{1}{\epsilon}}Y_{t}^{\frac{1}{\epsilon}} \quad \text{and} \quad p_{2t}=(1-\omega)Y_{2t}^{-\frac{1}{\epsilon}}Y_{t}^{\frac{1}{\epsilon}}$$

The FOCs of the firm equating factor prices to MRP of inputs imply


$$w_{t}=(1-\alpha_{1})\omega Y_{1t}^{-\frac{1}{\epsilon}}Y_{t}^{\frac{1}{\epsilon}}\frac{Y_{1t}}{L_{1t}}=(1-\alpha_{2})(1-\omega)Y_{2t}^{-\frac{1}{\epsilon}}Y_{t}^{\frac{1}{\epsilon}}\frac{Y_{2t}}{L_{2t}}$$

$$r_{t}=\alpha_{1}\omega Y_{1t}^{-\frac{1}{\epsilon}}Y_{t}^{\frac{1}{\epsilon}}\frac{Y_{1t}}{K_{1t}}=\alpha_{2}(1-\omega)Y_{2t}^{-\frac{1}{\epsilon}}Y_{t}^{\frac{1}{\epsilon}}\frac{Y_{2t}}{K_{2t}}$$

Note that we are assuming competitive firms and therefore $MRP=p\times MP$

Structural Change - Supply

Towards solving the model, define $k_{t}$ and $\lambda_{t}$ as the fraction of capital and labor used in sector 1:


$$k_{t}\equiv\frac{K_{1t}}{Kt} \quad \text{and} \quad \lambda_{t}=\frac{L_{1t}}{L_{t}}$$

Using these definitions and the equalized MRPs, we can obtain


$$\alpha_{1}\omega Y_{1t}^{-\frac{1}{\epsilon}}\frac{Y_{1t}}{K_{1t}}=\alpha_{2}(1-\omega)Y_{2t}^{-\frac{1}{\epsilon}}\frac{Y_{2t}}{K-K_{1t}}$$

which we can simplify to


$$k_{t}=\left[1+\frac{1-\omega}{\omega}\frac{\alpha_{2}}{\alpha_{1}}\left(\frac{Y_{2t}}{Y_{1t}}\right)^{\frac{\epsilon-1}{\epsilon}}\right]^{-1}$$

Structural Change - Supply

with the same steps for labor we obtain


$$\lambda_{t}=\left[1+\frac{1-\alpha_{2}}{1-\alpha_{1}}\frac{\alpha_{1}}{\alpha_{2}}\frac{1-k_{t}}{k_{t}}\right]^{-1}$$

Note that $\lambda_{t}$ is increasing in $k$, which implies that labor and capital are reallocated towards the same sector

(not surprising since Cobb-Douglas implies that if the rel-price is constant, so is the optimal mix, and we only have Hicks-neutral tech. change)

Structural Change - Supply

Based on this, you can show that


$$\frac{\partial \log k_{t}}{\partial \log K_{t}}>0 \iff (\alpha_{2}-\alpha_{1})(1-\epsilon)>0$$

Namely, if

sector 2 is more capital intensive, and goods are complements or

sector 1 is more capital intensive, and goods are substitutes

Then, as the economy expands, capital flows towards sector 1.

If $K\uparrow$ and $k$ is constant, then the capital-intensive sector expands relative to the labour-intensive. If the goods are complements (substitutes), you want to reallocate capital towards (away from) the labour-intensive one

Structural Change: Capital Allocation Response

We know


$$k_{t}=\left[1+\frac{1-\omega}{\omega}\frac{\alpha_{2}}{\alpha_{1}}\left(\frac{Y_{2t}}{Y_{1t}}\right)^{\frac{\epsilon-1}{\epsilon}}\right]^{-1}$$

taking logs and differentiating wrt $\log K_{t}$:


$$\frac{\partial \log k_{t}}{\partial \log K_{t}}=-\frac{\frac{1-\omega}{\omega}\frac{\alpha_{2}}{\alpha_{1}}\left(\frac{Y_{2t}}{Y_{1t}}\right)^{\frac{\epsilon-1}{\epsilon}}}{1+\frac{1-\omega}{\omega}\frac{\alpha_{2}}{\alpha_{1}}\left(\frac{Y_{2t}}{Y_{1t}}\right)^{\frac{\epsilon-1}{\epsilon}}}\cdot\frac{\epsilon-1}{\epsilon}\cdot\frac{\partial \log(Y_{2t}/Y_{1t})}{\partial \log K_{t}}$$

Note that


$$k_{t}\left[1+\frac{1-\omega}{\omega}\frac{\alpha_{2}}{\alpha_{1}}\left(\frac{Y_{2t}}{Y_{1t}}\right)^{\frac{\epsilon-1}{\epsilon}}\right]=1$$

Therefore


$$\frac{\partial \log k_{t}}{\partial \log K_{t}}=-(1-k_{t})\cdot\frac{\epsilon-1}{\epsilon}\frac{\partial \log(Y_{2t}/Y_{1t})}{\partial \log K_{t}}$$

Structural Change: Capital Allocation Response

From the production functions


$$\frac{Y_{2t}}{Y_{1t}}=\frac{A_{2t}}{A_{1t}}\left(\frac{1-k_{t}}{k_{t}}\right)^{\alpha_{2}}\left(\frac{1-\lambda_{t}}{\lambda_{t}}\right)^{1-\alpha_{2}}K_{t}^{\alpha_{2}-\alpha_{1}}L_{t}^{\alpha_{1}-\alpha_{2}}$$

Taking logs:


$$\log\frac{Y_{2t}}{Y_{1t}}=\log\frac{A_{2t}}{A_{1t}}+\alpha_{2}\log\frac{1-k_{t}}{k_{t}}+(1-\alpha_{2})\log\frac{1-\lambda_{t}}{\lambda_{t}}+(\alpha_{2}-\alpha_{1})\log K_{t}+(\alpha_{1}-\alpha_{2})\log L_{t}$$

Differentiating


$$\frac{\partial \log(Y_{2t}/Y_{1t})}{\partial \log K_{t}}=\alpha_{2}\frac{\partial \log\frac{1-k_{t}}{k_{t}}}{\partial \log K_{t}}+(1-\alpha_{2})\frac{\partial \log\frac{1-\lambda_{t}}{\lambda_{t}}}{\partial \log K_{t}}+(\alpha_{2}-\alpha_{1})$$

Using $\log\frac{1-\lambda_{t}}{\lambda_{t}} = \log\frac{1-k_{t}}{k_{t}} + \text{const}$ (from factor market clearing)


$$\frac{\partial \log(Y_{2t}/Y_{1t})}{\partial \log K_{t}}=-\frac{\partial \log\frac{k_{t}}{1-k_{t}}}{\partial \log K_{t}}+(\alpha_{2}-\alpha_{1})$$

Structural Change: Capital Allocation Response

compute


$$\frac{\partial \log\frac{k_{t}}{1-k_{t}}}{\partial \log K_{t}}=\frac{\partial \log k_{t}}{\partial \log K_{t}}-\frac{\partial \log(1-k_{t})}{\partial \log K_{t}}$$

$$=\frac{\partial \log k_{t}}{\partial \log K_{t}}+\frac{k_{t}}{1-k_{t}}\frac{\partial \log k_{t}}{\partial \log K_{t}}=\frac{1}{1-k_{t}}\frac{\partial \log k_{t}}{\partial \log K_{t}}$$

hence


$$\frac{\partial \log(Y_{2t}/Y_{1t})}{\partial \log K_{t}}=-\frac{1}{1-k_{t}}\frac{\partial \log k_{t}}{\partial \log K_{t}}+(\alpha_{2}-\alpha_{1})$$

substituting in


$$\frac{\partial \log k_{t}}{\partial \log K_{t}}=-(1-k_{t})\cdot\frac{\epsilon-1}{\epsilon}\left[-\frac{1}{1-k_{t}}\frac{\partial \log k_{t}}{\partial \log K_{t}}+(\alpha_{2}-\alpha_{1})\right]$$

Structural Change: Capital Allocation Response

simplifying


$$\frac{\partial \log k_{t}}{\partial \log K_{t}}=\frac{\epsilon-1}{\epsilon}\frac{\partial \log k_{t}}{\partial \log K_{t}}-(1-k_{t})\frac{\epsilon-1}{\epsilon}(\alpha_{2}-\alpha_{1})$$

which implies


$$\frac{\partial \log k_{t}}{\partial \log K_{t}}\cdot\frac{1}{\epsilon}=-(1-k_{t})\frac{\epsilon-1}{\epsilon}(\alpha_{2}-\alpha_{1})$$

Since $(1-k_{t})>0$:


$$\frac{\partial \log k_{t}}{\partial \log K_{t}}>0 \iff (\alpha_{2}-\alpha_{1})(1-\epsilon)>0$$

Structural Change - Supply

You can also show that


$$\frac{\partial \log k_{t}}{\partial \log A_{2t}}=-\frac{\partial \log k_{t}}{\partial \log A_{1t}}>0 \iff \epsilon<1$$

As the technology of a sector increases, if the goods are complements from the perspective of the household (output aggregator), you want to reallocate capital away from it

Recall that labour moves in the same direction as capital

Baumol's cost disease

Structural Change - Supply

You can build the dynamics based on the standard EE governing capital accumulation from the household and obtain our key result:


$$\gamma_{L_{1}}>\gamma_{L_{2}} \iff \gamma_{K_{1}}>\gamma_{K_{2}} \iff \gamma_{Y_{1}}<\gamma_{Y_{2}} \quad \text{if } \epsilon<1$$

$$\gamma_{L_{1}}<\gamma_{L_{2}} \iff \gamma_{K_{1}}<\gamma_{K_{2}} \iff \gamma_{Y_{1}}<\gamma_{Y_{2}} \quad \text{if } \epsilon>1$$

Namely, when goods are complements, reallocation goes the opposite way of sectoral growth

we can immediately prove this statement by differentiating wrt time our equalization of MRPs condition

Structural Change - Supply

Write the condition in logs and take time derivatives


$$\frac{\epsilon-1}{\epsilon}\gamma_{Y_{1}}-\gamma_{K_{1}}=\frac{\epsilon-1}{\epsilon}\gamma_{Y_{2}}-\gamma_{K_{2}}$$

which implies


$$\gamma_{K_{1}}-\gamma_{K_{2}}=\frac{\epsilon-1}{\epsilon}(\gamma_{Y_{1}}-\gamma_{Y_{2}})$$

and therefore


$$\text{sign}(\gamma_{K_{1}}-\gamma_{K_{2}})=\text{sign}(\gamma_{Y_{1}}-\gamma_{Y_{2}}) \iff \epsilon>1$$

doing the same for labour we obtain the second condition.

Structural Change - Supply

In the limit, one sector absorbs all of the factors.

Which one depends on whether $\epsilon\le 1$ and on which sector has the faster exogenous rate of technological change.

If goods are complements, all factors go to the slow-moving sector $\gamma=\min\{\gamma_{Y_{1}},\gamma_{Y_{2}}\}$

If goods are substitutes, all factors go to the fast-moving sector $\gamma=\max\{\gamma_{Y_{1}},\gamma_{Y_{2}}\}$

Structural Change - Supply

Recall we assumed that capital is created from the aggregate output good

This is an important assumption: suppose there are many sectors, but that capital is made only out of one sector, call it $m$

Then, in the limit, employment goes all towards the slowest growing non-$m$ sector and $m$.

The latter survives because of its role in capital creation.

Structural Change - Testing Demand vs Supply

Ideally, for a complete diagnosis of the causes of structural change, we would like to be able to tell apart demand and supply-driven SC

Many papers have tried to do so with mixed results

Key reason is that the fine details of the model we use matter

Example: the shape of Engel curves is a key determinant of the relative contribution of supply and demand to SC

Structural Change - Testing Demand vs Supply

General point: If you want to understand what explains the behaviour of some variable $Y$ between candidate drivers $X$ and $Z$, you need at least one identifying moment that tells them apart.

namely suppose that $Z$ and $X$ have the same prediction for all the variables you can observe – then you cannot tell if $Z$ or $X$ generated the changes you see in the data

Counterexample: both an increase in demand and an increase in productivity induce higher equilibrium quantity

but suppose you observe prices: higher demand leads to higher prices while higher productivity to lower prices

with both quantity and prices you can tell demand and supply shocks apart

Structural Change - Testing Demand vs Supply

The equivalent when it comes to structural change is whether the observed changes in sectoral employment are associated to

changes in income (demand)

changes in relative prices (supply)

Importantly, different models deliver different hard-wired properties of how income and relative prices change at the same time!

for us to give a fair chance at both stories we need a model with both non-homotheticities and differential productivity growth across sectors

Structural Change - Testing Demand vs Supply

But supply-side changes affect income, and non-homotheticities affect relative prices

The bulk of the discussion in the literature has to do with the fact that assuming different preferences implies different predictions for demand- vs supply-driven SC

Structural Change - Testing Demand vs Supply

Buera and Kaboski (2009):

Stone-Geary preferences + sector-biased technological progress

A plausible quantified model has the following shortcomings:

cannot account for the steep decline in manufacturing and rise in services in the later data

requires implausibly low elasticity of substitution across goods to match the consumption and output data

the behavior of consumption and output shares differs significantly from that of employment shares

Structural Change - Testing Demand vs Supply

[Graph: Evolution of value-added shares: agriculture, manufacturing, services in the United States, 1860-2000. Shows model fit against data]

Structural Change - Testing Demand vs Supply

Buera and Kaboski (2009):

We cannot match services and manufacturing because of Stone-Geary: the subsistence level only really matters at low-income levels, so when the income get higher, the non-homotheticity goes away

Problem for the model's ability to match the data is that the price of services is going up yet households are substituting towards them. The negative subsistence level estimated for services is not enough

Structural Change - Testing Demand vs Supply

Herrendorf, Rogerson and Valentinyi (2013):

important measurement issue: final expenditure vs value added

Suppose you see expenditure on a €10 cotton shirt: with a final expenditure approach this is €10 of manufacturing production

alternatively, you can think that the cotton shirt is actually made of €4 worth of raw cotton (agriculture), €3 of processing (manufacturing), and €3 of retail and distribution (services)

To test the two stories and two approaches, consider a model combining non-homotheticities (in CES) and supply-side changes

Structural Change - Testing Demand vs Supply

[Graph: Figure 1. Expenditure Shares (Final Expenditure) showing Services expanding rapidly, Agriculture declining, Manufacturing relatively flat]

Structural Change - Testing Demand vs Supply

[Graph: Figure 9. Expenditure Shares (Value Added) showing slightly different baseline levels but similar trends]

Structural Change - Testing Demand vs Supply

[Graph: Figure 2. Price Indices (1947 = 1) showing Services prices growing much faster than Manufacturing and Agriculture]

Structural Change - Testing Demand vs Supply

[Graph: Figure 10. Price Indices (1947 = 1) for Value Added]

Structural Change - Testing Demand vs Supply

[Graph: Figure 3. Quantity Indices (2005 chained dollars, 1947 = 1) Final Expenditure]

Structural Change - Testing Demand vs Supply

[Graph: Figure 11. Quantity Indices (2005 chained dollars, 1947 = 1) Value Added]

Structural Change - Testing Demand vs Supply

Consider the preferences


$$u_{t}=\left[\sum_{i=a,m,s}\omega_{i}^{\frac{1}{\sigma}}(c_{it}-\overline{c}_{i})^{\frac{\sigma-1}{\sigma}}\right]^{\frac{\sigma}{\sigma-1}}$$

set $\overline{c}_{m}=0$, estimate the rest of the parameters under different specifications first under the final expenditure and then under the value added assumptions

Structural Change - Testing Demand vs Supply

Final Expenditure Parameter Estimates:

$\sigma = 0.85^{**}$

$\overline{c}_{a} = -1,350.38^{**}$

$\overline{c}_{s} = 11,237.40^{**}$

$\omega_{a} = 0.02^{**}$

$\omega_{m} = 0.17^{**}$

$\omega_{s} = 0.81^{**}$

Structural Change - Testing Demand vs Supply

Value Added Parameter Estimates:

$\sigma = 0.002$ (nearly Leontief)

$\overline{c}_{a} = -138.68^{**}$

$\overline{c}_{s} = 4,261.82^{**}$

$\omega_{a} = 0.002^{**}$

$\omega_{m} = 0.15^{**}$

$\omega_{s} = 0.85^{**}$

Structural Change - Testing Demand vs Supply

First, note that the two sets of data give wildly different estimated parameters:

final expenditure implies a little complementarity (not far from 1)

value added implies Leontief!

Why such differences?

you can substitute movies vs going to a football match (final expenditure), but not that much difference in terms of factor composition (building + labour)

Consider food in supermarkets (agriculture) vs meals in restaurants (services), but the factor composition is very similar!

Differences in implied non-homotheticities:

Food from supermarkets is clearly a necessity

Meals in restaurants are clearly a luxury

Structural Change - Testing Demand vs Supply

With the estimated parameters, use the model as a lab

Turn on/off each channel one at a time to understand its relative contribution (how far we get from the data)

Allow them all at once to understand the overall fit

Structural Change - Testing Demand vs Supply

[Graph: Figure 6. Fit of Column 1 with Relative Prices Fixed at 1947 Values. Shows the Income Effect alone]

Structural Change - Testing Demand vs Supply

[Graph: Figure 7. Fit of Column 1 with Income Fixed at 1947 Values. Shows the Price Effect alone]

Structural Change - Testing Demand vs Supply

[Graph: Figure 8. Fit of Homothetic Specification in Column 3]

Structural Change - Testing Demand vs Supply

[Graph: Figure 12. Fit of Column 2]

Structural Change - Testing Demand vs Supply

[Graph: Figure 13. Fit of Homothetic Specification in Column 3]

Structural Change - Testing Demand vs Supply

[Graph: Figure 14. Fit of Column 2 with Prices Fixed at 1947 Value (Income effect)]

Structural Change - Testing Demand vs Supply

[Graph: Figure 15. Fit of Column 2 with Income Fixed at 1947 Value (Price effect)]

Structural Change - Testing Demand vs Supply

Boppart (2014):

Issue: theories of structural change are inconsistent with Kaldor (capital and labour shares move)

Fix: Drop Stone-Geary and use price independent generalized linear (PIGL) preferences

key property: income effects (non-homotheticities) do not vanish

Relative to Stone-Geary, this gives a better shot at the demand-driven explanation.

Conclusion: both channels contribute about 50%

Structural Change - Testing Demand vs Supply

Comin, Lashkari and Mestieri (2021)

Replace PIGL with Non-homothetic CES preferences, since PIGL requires some parametric restrictions

though N-h CES imposes a constant price elasticity, which PIGL does not.

argument for the change:

based on the explanatory power: $R^{2}$ is twice as large for Nh-CES than for Stone-Geary and PIGL

based on the substantive question: PIGL "hard-wires" a strong importance of relative prices that does not need to reflect their true importance

Conclusion: non-homotheticites explain $3/4$ of the observed reallocation across sectors

Structural Change - Testing Demand vs Supply

[Graph: (c) Stone-Geary Fit for Taiwan. Shows model fit for employment shares vs data over time]

Structural Change - Testing Demand vs Supply

[Graph: (d) PIGL Fit for Taiwan. Shows model fit using PIGL preferences]

Structural Change - Testing Demand vs Supply

[Graph: (b) Nonhomothetic CES Fit for Taiwan. Shows much closer fit to the data points than the previous models]