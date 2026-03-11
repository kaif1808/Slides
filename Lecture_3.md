Macroeconomics I: Lecture 3

Alessandro Ferrari January 2026

UPF, CREI, BSE & CEPR

Growth Accounting

99% of modern macroeconomics is "done" using theory and data

Models may be useful for:

Getting intuitions/insights

Measuring stuff

Growth accounting uses the structure of standard growth models to measure the sources of growth.

Quantify the role of each production factor in the growth experience of a given country or region.

Take:


$$Y_{t}=F(K_{t},B_{t}L_{t})$$


where $Y_{t}$, $K_{t}$, and $L_{t}$ are output, capital, and labor per capita.

Given a growth rate of output per worker, how much is due to the increase in capital, labor, and productivity?

Rewrite the production function as:


$$Y_{t}=A_{t}F(K_{t},L_{t})$$


where $A_{t}$ is the total factor productivity (TFP).

Take logs and time derivatives:


$$\frac{\dot{Y}}{Y}=\frac{\dot{A}}{A}+\left(\frac{F_{K}K}{F}\right)\frac{\dot{K}}{K}+\left(\frac{F_{L}L}{F}\right)\frac{\dot{L}}{L} \Rightarrow \gamma_{Y}=\gamma_{A}+\alpha_{t}\gamma_{K}+(1-\alpha_{t})\gamma_{L}$$


where $\alpha_{t}$ is the capital share.

Everything in this equation is observable, except for $\gamma_{A}$. But we can compute it as a residual (indeed, it is the Solow residual):


$$\gamma_{A}=\gamma_{Y}-\alpha_{t}\gamma_{K}-(1-\alpha_{t})\gamma_{L}$$

What goes into $\gamma_{A}$?

Everything except for measured capital and labor.

Technology

Misallocation (market efficiency, government regulation, cronyism, etc.)

Mismeasurement of capital and labor

TFP Measurement Over Time

Initial accounting exercises gave a very high share of growth to TFP, in the order of 70%.

This was the measure of our ignorance.

Recent measurements reduce the importance of TFP to $1/3 - 1/2$.

Problem: poor measurement of the quality of inputs.

Labor quality has increased: The labor force's education level has been increasing. A way to account for this is to weigh every person's hours by the relative wage of her education category.

Capital quality has increased even more: Relative price of capital equipment has declined in the last decades. A computer today is much faster than 30 years ago. Need to measure capital in efficiency units not in dollars.

Measuring Capital Stock

The stock of capital is not easy to measure. One approach is to build it with the perpetual-inventory method. It basically requires applying the law of motion:


$$K_{t+1}=(1-\delta)K_{t}+I_{t}$$


We have good measures of $I_{t}$ in the national accounts. $\delta$ is easy to estimate. Then, we just need an initial estimate of $K_{0}$. This is the most complicated part. However, if we have a series for $I_{t}$ long enough, the effects of $K_{0}$ vanish.

Historical Growth Accounting Results

"Recent" measurements reduce the importance of TFP.

Still, it accounts for more than $1/3$ and in some countries by $1/2$ of output growth.

Country

$\gamma_{Y}$

$\alpha\frac{\gamma_{K}}{\gamma_{Y}}$

$(1-\alpha)\frac{\gamma_{L}}{\gamma_{Y}}$

$\frac{\gamma_{A}}{\gamma_{Y}}$

1947-1973









US

4.02%

42.7%

23.7%

33.6%

UK

3.73%

47.2%

0.9%

51.9%

Fr

5.42%

41.5%

3.9%

54.5%

Ger

6.61%

40.6%

2.8%

56.6%

1960-1990









US

3.10%

45.2%

41.5%

13.2%

UK

2.49%

52.3%

-4.2%

51.9%

Fr

3.50%

58.1%

0.5%

41.4%

Ger

3.20%

58.7%

-8.1%

49.4%

This is useful, but it does not imply any causality.

Remember that the Solow and Ramsey models state that in the BGP all growth in capital per capita is also due to technology.

Alternative Framework

$$Y_{t}=K_{t}^{\alpha}(B_{t}L_{t})^{1-\alpha} \Rightarrow \frac{Y_{t}}{N_{t}}=B_{t}\frac{L_{t}}{N_{t}}\left(\frac{K_{t}}{Y_{t}}\right)^{\frac{\alpha}{1-\alpha}}$$

Hence, the growth of output per capita $Y_{t}/N_{t}$ is decomposed in:

Growth of Solow residual

Growth of labor units per capita

Capital deepening: the increase in the capital-to-income ratio

Results (US data. Source: Jones (2015))

Period

$Y/N$

$B$

$L/N$

$K/Y$

1948-2013

2.5

2.0

0.3

0.1

1948-1973

3.3

3.2

0.3

-0.2

1973-1995

1.6

0.8

0.4

0.4

1995-2007

2.8

2.2

0.3

0.2

2007-2013

1.7

1.1

0.5

0.1

Capital deepening of little importance: US close to BGP

Large importance of Solow residual

We observe a productivity slowdown in the 70's and 80's, also from 2007 on...

The Dual Approach

What we have used so far is the so-called primal approach to growth accounting.

The alternative dual approach starts from the accounting equation (absent profits):


$$Y_{t}=w_{t}L_{t}+r_{t}K_{t}$$

Taking log derivatives wrt time:


$$\dot{Y}/Y=\alpha_{k}(\dot{R}/R+\dot{K}/K)+\alpha_{L}(\dot{w}/w+\dot{L}/L)$$

Which implies that we can rewrite TFP growth as:


$$\gamma_{A}=\alpha_{K}\dot{R}/R+\alpha_{L}\dot{w}/w$$

This approach relies on national accounting identities without assumptions on social marginal products.

Should in principle coincide with the primal approach, but in practice, they are often not the same (Hsieh, 2002).

Country

Primal

Dual

Hong Kong ('66-'91)

2.3%

2.7%

Singapore ('72-'90)

-0.7%

2.2%

South Korea ('66-'90)

1.7%

1.5%

Taiwan ('66-'90)

2.1%

3.7%

A Few Observations on Elasticity vs. Factor Shares

Consider the basic growth accounting equation:


$$\frac{\partial \log Y}{\partial t}=\frac{\partial \log F(x)}{\partial t}=\sum_{x}\frac{\partial \log F}{\partial \log x}\frac{\partial \log x}{\partial t}$$

We argued before that we can use measured income shares for the production function elasticity. Why can we do that? Consider an optimizing firm:


$$\max_{x}\pi(x)=pF(x)-\sum_{x}w_{x}x$$


The profit maximization problem has FOCs of the type:


$$F_{x}p=w_{x}$$


which we can rewrite as:


$$\frac{F_{x}x}{Y}=\frac{w_{x}x}{pY}$$


The LHS is the elasticity we would like to measure, the RHS is the factor share.

Problem 1: Market Power

What if the firm has market power?


$$\max_{x}\pi(x)=p(F(x))F(x)-\sum_{x}w_{x}x$$


which implies:


$$p^{\prime}F_{x}F+pF_{x}=w_{x}$$


Which we can manipulate to:


$$\frac{\epsilon_{D}-1}{\epsilon_{D}}\frac{F_{x}x}{Y}=\frac{w_{x}x}{pY}$$


With $\epsilon_{D}$ being the elasticity of demand. So we cannot simply take the measured factor share. Note, however, that under CRS of the production function:


$$\mu=\frac{\epsilon_{D}}{\epsilon_{D}-1} \quad \text{and} \quad C(Y)=\frac{pY}{\mu}$$


Hence we can recover:


$$\frac{F_{x}x}{Y}=\frac{w_{x}x}{C}$$


So the elasticity is the cost share whenever firms have profits.

Problem 2: Fixed Costs

Note another complication: suppose that some costs are not variable:


$$\max_{x}\pi(x)=pF(x)-\sum_{x}w_{x}x-w_{x}\Gamma$$


Suppose that $\Gamma$ is paid by hiring units of input x at the price $w_{x}$. The optimization problem from before still holds, and we obtain:


$$\frac{F_{x}x}{Y}=\frac{w_{x}x}{pY}$$


But the RHS is not the $x$ factor share, since that is given by $\frac{w_{x}(x+\Gamma)}{pY}$.

Root Cause: Going from factor share to elasticities requires that firms:

Equate REVENUE marginal products to input prices (true under perfect competition).

Variable costs are the only costs.

Problem 3: Externalities

So far, we have been jumping seamlessly from firm-level to aggregates. Underlying is an assumption on "no externalities" — namely that firms' private marginal returns are equal to the social marginal returns. If there is a positive externality, firms equate MC to private MP, but in the aggregates, Social MP is higher.

More problems exist in economies with:

Taxes

Multiple sector/inputs

Quality upgrading

Endogenous technological progress

Nonetheless, we persevere (for good reasons).

Can a country grow without improving its productivity? (Yes, through capital/labor accumulation, as seen in the Spanish data).

Development Accounting

Similar exercise, but comparing a cross-section of countries at a given point in time:


$$\log Y_{i}=\log A_{i}+\alpha \log K_{i}+(1-\alpha)\log L_{i}$$


Caselli (2005) claims that TFP differences account for more than $1/2$ of variation in income per capita between countries.

Sample

obs

$y_{90}/y_{10}$

the xx (variance explained)

Whole sample

105

24.8

61.5%

OECD

24

1.7

39.4%

Non OECD

81

14.7

64.4%

Improving capital quality measures and allowing for non Cobb-Douglas production functions are important to reduce these numbers.

Where are productivity differences coming from? (Hall and Jones, 1999, QJE)

Income/worker in the USA = $35 \times$ income/worker in Niger

Hall and Jones carry out one of the "first" development accounting exercises.

Goal: understanding what part of these differences is due to:

Efficiency in the use of factors

Amount of factors

Conceptually: Income = F(Factors, Efficiency)

Production function for a country $i$:


$$Y_{i}=K_{i}^{\alpha}(A_{i}H_{i})^{1-\alpha}$$

$K_{i}$: stock of physical capital

$H_{i}$: human capital adjusted labor factor ($H_{i}=e^{\phi(E_{i})}L_{i}$)

$A_{i}$: labor productivity

$E_{i}$: years of schooling

Output per worker $y \equiv \frac{Y}{L}$:


$$y_{i}=\left(\frac{K_{i}}{Y_{i}}\right)^{\alpha/(1-\alpha)}h_{i}A_{i}$$


where $h_{i}\equiv \frac{H}{L}$. This expression allows us to decompose differences in output per worker into:

capital-output ratio ($\frac{K_{i}}{Y_{i}}$)

human capital ($h_{i}$)

productivity ($A_{i}$)

Data Sources:

Hall and Jones use Penn World Tables (PWT) 5.6 (Data on GDP, labor, investment for 1988).

Barro and Lee provide data on years of schooling ($E$).

Returns on education $\phi(s)$:

First 4 years: 13.4% $\Rightarrow \phi(s)=0.134 \times s$

Years 4-8: 10.1% $\Rightarrow \phi(s)=0.134\times 4+0.101\times(s-4)$

Year 9 onwards: 6.8% $\Rightarrow \phi(s)=0.134\times 4+0.101\times 4+0.068\times(s-8)$

Construct series of $K_{i}$ using the "perpetual inventory method":


$$K_{t}=I_{t}+(1-\delta)K_{t-1}$$


Initial capital is fixed as $K_{0}=\frac{I_{0}}{g+\delta}$.

We measure $A_{i}$ as a residual:


$$A_{i}=\frac{y_{i}}{\left(\frac{K_{i}}{Y_{i}}\right)^{\alpha/(1-\alpha)}h_{i}}$$


We use $\alpha=1/3$.

Results: Productivity Calculations (Ratios to U.S. Values)

Country

$Y/L$

$(K/Y)^{\alpha/(1-\alpha)}$

$H/L$

$A$

United States

1.000

1.000

1.000

1.000

Canada

0.941

1.002

0.908

1.034

Italy

0.834

1.063

0.650

1.207

West Germany

0.818

1.118

0.802

0.912

France

0.818

1.091

0.666

1.126

United Kingdom

0.727

0.891

0.808

1.011

Hong Kong

0.608

0.741

0.735

1.115

Singapore

0.606

1.031

0.545

1.078

Japan

0.587

1.119

0.797

0.658

Mexico

0.433

0.868

0.538

0.926

Argentina

0.418

0.953

0.676

0.648

U.S.S.R.

0.417

1.231

0.724

0.468

India

0.086

0.709

0.454

0.267

China

0.060

0.891

0.632

0.106

Kenya

0.056

0.747

0.457

0.165

Zaire

0.033

0.499

0.408

0.160

Average, 127 countries:

0.296

0.853

0.565

0.516

Most of the income differences come from differences in $A_{i}$:

$y_{China}=0.06 \times y_{USA}$

If China had $A_{USA} \dots y_{China}=0.50 \times y_{USA}$

$y_{top 5}=31.7 \times y_{bottom 5}$

Decomposing this difference: $y_{top 5}= 1.8 (\text{Capital}) \times 2.2 (\text{Human Cap}) \times 8.3 (A) \times y_{bottom 5}$

What is behind $A_{i}$?

Can we relate $A_{i}$ with any observable?
Hypothesis: Better "Social infrastructure" (institutions) $\Rightarrow A_{i} \uparrow \Rightarrow y_{i} \uparrow$

Formally:


$$\log y_{i}=\gamma+\beta S_{i}+\epsilon_{i}$$


Problem: reverse causality (higher income allows countries to improve institutions).


$$S_{i}=\mu+\sigma \log y_{i}+X_{i}\theta+\eta_{i}$$

Solution by HJ: Instrumental variables.
Find variables that influence institutions but don't directly affect current levels of $y_{i}$.

Distance from the equator

Percentage of the local population that speaks Western languages

Predicted trade share (Frankel, Romer (1996))

How do we measure $S$ in the data?

"Government antidiversion policies (GADP)" index.

Measures law and order, quality of bureaucracy, laws against corruption, expropriation risk, contract enforcement.

Basic Results for Output per Worker ($log Y/L = \alpha + \beta\tilde{S} + \tilde{\epsilon}$)

Specification

Social infrastructure

OverID test (p-value)

Coeff test (p-value)

$\hat{\sigma}_z$

1. Main specification

5.1432 (.508)

.256 (Accept)

.812 (Accept)

.840

2. Instruments: Distance, Frankel-Romer

4.998 (.567)

.208 (Accept)

.155 (Accept)

.821

3. No imputed data (79 countries)

5.323 (.607)

.243 (Accept)

.905 (Accept)

.889

4. OLS

3.289 (.212)

-

.002 (Reject)

.700

Results for Components (Component $= \alpha + \beta\tilde{S} + \tilde{\epsilon}$)

Dependent variable

$\frac{\alpha}{1-\alpha}\log K/Y$

$\log H/L$

$\log A$

Social infrastructure

1.052 (.164)

1.343 (.171)

2.746 (.336)

OverID test (p)

.784

.034

.151

Test result

Accept

Reject

Accept

Summary of Accounting

Huge income differences across countries. Most are accounted for by differences in TFP.

Growth/Development Accounting is a useful tool, but it is not a way to investigate the causes of growth. It is purely accounting.

If technological progress is labor augmenting at rate $x$:


$$\delta \log Y=\alpha\delta \log K+(1-\alpha)x$$

By growth accounting, you would conclude that the TFP growth is $\hat{\gamma}_{A}=(1-\alpha)x$, and attribute $\alpha$ of the observed growth to capital deepening. This is an incorrect causal statement since without $x$ no growth would occur.

Misallocation (Hsieh and Klenow, 2009)

What is $A$? TFP is a black box where we put all that we cannot properly measure. A prominent recent literature has focused on the role of misallocation.

Misallocation is an inefficient allocation of finite resources across production units (firms/plants).

A Null Result (When does allocation NOT matter?)

Suppose firms have the same productivity: $y_{i}=k_{i}^{\alpha}l_{i}^{1-\alpha}$
If firms are competitive, make perfectly substitutable goods, and maximize profits:


$$\pi_{i}=Py_{i}-rk_{i}-wl_{i}$$


From the usual FOC, we get:


$$\frac{\alpha}{1-\alpha}\frac{w}{r}=\frac{k_{i}^{*}}{l_{i}^{*}} \quad \forall i$$


Total output is the sum of individual firms' output:


$$Y=\int_{i}y_{i} = \int_{i}k_{i}^{\alpha}l_{i}^{1-\alpha}=\int_{i}k^{\alpha}l_{i} = k^{\alpha}L$$


Since $K=\int_{i}kl_{i}$, we get $Y=K^{\alpha}L^{1-\alpha}$.
Bottom line: If firms are competitive, operate the same CD CRS function, in the same factor markets, the allocation of resources is irrelevant.

Hsieh and Klenow (2009) Setup

Goal: Use a model to quantify cross-country differences in misallocation. How much of the difference between US and India is driven by misallocation?

Households: CES preferences over imperfectly substitutable varieties.


$$C=\left(\int_{i}{c_{i}}^{\frac{\sigma-1}{\sigma}}\right)^{\frac{\sigma}{\sigma-1}}, \quad \sigma>1$$


Ideal price index $P=\left(\int_{i}p_{i}^{1-\sigma}\right)^{\frac{1}{1-\sigma}}$. Demand schedule: $c_{i}=p_{i}^{-\sigma}P^{\sigma}C$.

Firms: Operate CRS Cobb-Douglas with heterogeneous productivities $A_{i}$:


$$y_{i}=A_{i}k_{i}^{\alpha}l_{i}^{1-\alpha}$$


Compete under monopolistic competition. Maximize profits:


$$\pi_{i}=p_{i}(y_{i})y_{i}-wl_{i}-rk_{i}$$

Optimal pricing rule:


$$p_{i}=\frac{\sigma}{\sigma-1}\frac{x}{A_{i}}$$


where marginal cost $x := \left(\frac{r}{\alpha}\right)^{\alpha}\left(\frac{w}{1-\alpha}\right)^{1-\alpha}$.

Firm's output relative to productivity:


$$y_{i} \propto A_{i}^{\sigma}$$


Firms differ in size based on $A_i$, but their marginal revenue products (MRPs) are all equalized ($MRPK_i = r, MRPL_i = w$).

The Planner's Problem

A social planner maximizing output finds the same relative market shares:


$$\frac{y_{i}}{y_{j}}=\frac{A_{i}}{A_{j}}\left(\frac{k_{i}}{k_{j}}\right)^{\alpha}\left(\frac{l_{i}}{l_{j}}\right)^{1-\alpha}=\frac{A_{i}}{A_{j}}\left(\frac{y_{i}}{y_{j}}\right)^{\frac{\sigma-1}{\sigma}} \Rightarrow y_{i} \propto A_{i}^{\sigma}$$


The market and planner allocate the same shares across firms. No cross-sectional misallocation here. The total factor supply is completely utilized.

Solow Residual in the Undistorted Economy

Aggregate production function $Y=AK^{\alpha}L^{1-\alpha}$.
By aggregating over all firms, we find the Solow Residual is a geometric average of individual productivities:


$$A=\left(\int_{i}A_{i}^{\sigma-1}\right)^{\frac{1}{\sigma-1}}$$


Note that because of profits, factor shares do NOT equal output elasticities:


$$\Theta_{K}=\alpha\frac{\sigma-1}{\sigma} < \alpha$$

$$\Theta_{L}=(1-\alpha)\frac{\sigma-1}{\sigma} < 1-\alpha$$

Firms with Distortions

Now introduce firm-specific wedges $\tau_{i}^{K}$ (capital distortion) and $\tau_{i}^{Y}$ (output distortion).


$$\max_{y_{i},k_{i},l_{i}}(1-\tau_{i}^{Y})p_{i}(y_{i})y_{i}-wl_{i}-(1+\tau_{i}^{K})rk_{i}$$


The optimal capital-labor ratio becomes distorted:


$$\frac{k_{i}}{l_{i}}=\frac{\alpha}{1-\alpha}\frac{w}{r}\frac{1}{1+\tau_{i}^{K}}$$


MRPs deviate from marginal costs:


$$MRPL_{i}=w\frac{1}{1-\tau_{i}^{Y}} \quad \text{and} \quad MRPK_{i}=r\frac{1+\tau_{i}^{K}}{1-\tau_{i}^{Y}}$$

Distorted marginal cost implies a distorted price:


$$p_{i}=\frac{\sigma}{\sigma-1}\frac{x}{A_{i}}\frac{(1+\tau_{i}^{K})^{\alpha}}{1-\tau_{i}^{Y}}$$


And distorted relative output:


$$y_{i} \propto A_{i}^{\sigma}\left(\frac{1-\tau_{i}^{Y}}{1+\tau_{i}^{K}}\right)^{\sigma}$$

Distorted Solow Residual

Define Total Factor Productivity Revenue (TFPR):


$$TFPR_{i} \equiv p_{i}A_{i}=\frac{\sigma}{\sigma-1}x\frac{(1+\tau_{i}^{K})^{\alpha}}{1-\tau_{i}^{Y}}$$


And the aggregate $TFPR = PA$.
Solving for TFPQ ($A = TFPR/P$), we get:


$$A=\left[\int_{j}\left(A_{j}\frac{TFPR}{TFPR_{j}}\right)^{\sigma-1}\right]^{\frac{1}{\sigma-1}}$$


TFPQ is a weighted geometric average of individual productivities. Since the aggregator is concave, higher dispersion in TFPR reduces aggregate productivity. The cost of misallocation comes from the dispersion in TFPR induced by firm-specific distortions.

Counterfactuals: Applying HK(2009) to Data

What if India, China, and the US had the efficient firm size distribution?
TFP Gains from Equalizing TFPR Within Industries:

Country

Year

% Gain

Year

% Gain

Year

% Gain

China

1998

115.1%

2001

95.8%

2005

86.6%

India

1987

100.4%

1991

102.1%

1994

127.5%

United States

1977

36.1%

1987

30.7%

1997

42.9%

TFP Gains Relative to 1997 U.S. Gains:
| Country | Year | % Gain | Year | % Gain | Year | % Gain |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| China | 1998 | 50.5% | 2001 | 37.0% | 2005 | 30.5% |
| India | 1987 | 40.2% | 1991 | 41.4% | 1994 | 59.2% |

Charts Referenced (Visualizing Misallocation)

Conclusion on Misallocation

We unpack $A$ further by pointing out inefficiencies in how capital and labor are distributed amongst firms.

However, the "dispersion" measured could also capture:

Measurement error

Adjustment costs that are not in the model

Deviations from various assumptions (e.g., CES, CD, CRS, etc.)

These missing elements can overturn the conclusion from HK that dispersion in marginal products is necessarily bad.

With all these caveats, it is still a significant step forward in understanding what we measure as $A$!