Macroeconomics I: Lecture 5

Alessandro Ferrari | UPF, CREi, BSE & CEPR | February 2026

So far

Models of exogenous growth:

Solow/Ramsey: capital accumulation fosters growth but not in an autonomous way. Always driven by either population or technological progress.

Models of (semi-)endogenous growth:

External effects undo the natural decay in the returns to capital accumulation.

Technological progress can happen mechanically (lab-equipment and learning-by-doing models) or as a consequence of optimal choices in an economic activity (Romer).

Growth occurs through the introduction of new varieties.

KEY: new products do not replace old products!

Today

Today: growth occurs through improvement in the same set of products.

These are called quality ladder models of growth.

The key engine of growth is the replacement of old products with new better ones.

Schumpeter: notion of creative destruction.

A Schumpeterian Model of Creative Destruction

Vertical vs Horizontal differentiation

The setting is very similar to before, but instead of horizontal differentiation (new different products), we look at vertical differentiation (quality improvements on the same products).

Simple quality differentiation: quality ladder.

Suppose there are $N$ different products.

$q$ space of rungs of the quality ladder: $q^1, q^2, q^3, ..., q^{k_j}$ for sector $j$.

Sequential single rung improvements: go from $q^i$ to $q^{i+1}$.

A Schumpeterian Model of Growth: Vertical Innovation

The same actors as before: (i) producer of final goods, (ii) R&D firms, (iii) consumers.

The final goods production looks very similar:


$$Y_t = L^{1-\alpha} \int_0^N \tilde{X}_t^\alpha(s) ds$$

We have two key differences:

$N$ is fixed: no innovation of new products.

$\tilde{X}_t(s) := q^{k(s)}X_t(s)$ is the quality-adjusted intermediate input.

$q > 1$, in fact $q \ge \frac{1}{\alpha}$ and $k(s) = 1, 2, ...$ is the quality ladder of the good.

Improvements occur stochastically at random dates $t_{k(s)}$, and $t_{k(s)+1} - t_{k(s)}$ is the time where rung $k(s)$ is in use for good $X(s)$.

Innovation Dynamics

We assume that the cost of production of intermediate goods is not quality-dependent.

The innovator has a cost advantage that makes it a (temporary) monopolist.

Replacement of old variety with new variety.

This is not generally true. It is here because we assumed that $q \ge \alpha^{-1}$.

Absent this assumption (innovations are more "modest"), the old and new varieties compete.

Not monopoly pricing, rather limit pricing (Bertrand).

[Image Placeholder: Bar chart showing "Distribution of Quality Across Sectors", with product numbers 1 to N on the x-axis and random Quality-ladder numbers on the y-axis]

[Image Placeholder: Step-function graph showing "The Quality Process in one Industry", with time $t$ on the x-axis and Quality-ladder number $k$ on the y-axis, jumping up at random dates $t_1, t_2, ..., t_k$]

Aghion-Howitt (1992) Model: Innovation step $q$ large

[Image Sequence Placeholder: A visualization of a vertical quality line $q$. Firm 1 is initially in. Firm 2 enters higher up the ladder, pushing Firm 1 out. Then Firm 3 enters, pushing Firm 2 out. Then Firm 4 enters, pushing Firm 3 out.]

A Schumpeterian Model: Final good

The quality of each good is embedded into the good and it increases productivity in the final good sector:


$$\max_{L,X_t(s)} Y_t - w_t L - \int_0^N P_t(s)X_t(s) ds$$

$$\text{s.t. } Y_t = L^{1-\alpha} \int_0^N (q^{k(s)}X_t(s))^\alpha ds$$

The First Order Conditions (FOCs) are as before:


$$w_t = (1-\alpha)L^{-\alpha} \int_0^N \tilde{X}_t^\alpha(s) ds = (1-\alpha)\frac{Y_t}{L}$$

$$P_t(s) = \alpha L^{1-\alpha} q^{\alpha k(s)} X_t(s)^{\alpha-1} \implies X_t(s) = L \left( \frac{\alpha q^{\alpha k(s)}}{P_t(s)} \right)^{\frac{1}{1-\alpha}}$$

Schumpeterian Model: Research Firms

Only entrants can innovate.

In the previous model, this was clear; here, we assume this to be the case.

Note, however, that if the steps $q$ are very large, the fringe firms have strong incentives to innovate: they obtain the whole market.

While the incumbents only obtain the profits associated with the marginal higher quality.

R&D firms choose (i) innovation investment and (ii) quality/price:


$$\max_{X_t(s)} \pi_t(s) = [P_t(s) - 1]X_t(s)$$

$$\text{s.t. } X_t(s) = L \left( \frac{\alpha q^{\alpha k(s)}}{P_t(s)} \right)^{\frac{1}{1-\alpha}}$$

Optimal price (note the marginal cost $mc=1$ and $\epsilon/(\epsilon-1) = 1/\alpha$):


$$P_t(s) = \frac{1}{\alpha}$$

Profits change over $s$, but depend only on the rung $k(s)$:


$$\pi(k(s)) = \frac{1-\alpha}{\alpha} \alpha^{\frac{2}{1-\alpha}} L q^{\frac{\alpha}{1-\alpha}k(s)}$$

Since successful innovation grants a perpetual patent, the value of the firm is the discounted value of the profits.

Value of the research firm if quality level $k(s)$ is used between any two dates $t_1$ and $t_2$:


$$V_{t_1}^{t_2}(k(s)) = \int_{t_1}^{t_2} \pi(k(s)) e^{-\int_{t_1}^\tau r_\omega d\omega} d\tau$$

Recall: Value of the research firm if used between date $t_1 = t_{k(s)}$ and $t_2 = t_{k(s)+1}$:


$$V_{t_{k(s)}}^{t_{k(s)+1}}(k(s)) = \int_{t_{k(s)}}^{t_{k(s)+1}} \pi(k(s)) e^{-\int_{t_{k(s)}}^\tau r_\omega d\omega} d\tau$$

The term $\int_{t_{k(s)}}^\tau r_\omega d\omega$ is the average interest rate between $t_{k(s)}$ and $\tau$.

Innovation is a Poisson process, so, given $t_{k(s)}$, the date $t_{k(s)+1}$ is random.

If innovation occurs, the old quality makes zero profits thereafter.

Suppose the probability of getting an innovation during time $dt$ is $p(k(s))dt$.

If we assume $r_t \equiv r$, the expected value of the innovation is:


$$V(k(s)) := \mathbb{E}[V_{t_{k(s)}}^{t_{k(s)+1}}(k(s))] = \frac{\pi(k(s))}{r + p(k(s))}$$

Since there is a time-constant probability of jumping to zero profits:


$$V_t(k(s)) = \int_t^\infty \pi(k(s)) e^{-(p(k(s))+r)(\tau-t)} d\tau = V(k(s))$$

Recall:


$$V(k(s)) = \frac{\pi(k(s))}{r + p(k(s))}$$


where $\pi(k(s)) = \overline{\pi} q^{\frac{\alpha}{1-\alpha}k(s)}$

Assumption: The innovation probability is $p(k(s)) = Z(k(s))\phi(k(s))$ where $Z$ is the resources invested and $\phi$ is the probability of getting an innovation if we invest 1 unit.

To simplify the problem, assume that:


$$\phi(k(s)) = \xi^{-1} q^{-\frac{\alpha}{1-\alpha}(k(s)+1)}$$


so that:


$$p(k(s)) = \frac{Z}{\xi q^{\frac{\alpha}{1-\alpha}(k(s)+1)}}$$

This implies that the higher in the ladder we are, the harder it is to innovate.

Then, the innovator's problem solves:


$$\max_{Z \ge 0} \frac{Z}{\xi q^{\frac{\alpha}{1-\alpha}(k(s)+1)}} V(k(s)+1) - Z$$

To have $Z > 0$, the FOCs are:


$$\frac{V(k(s)+1)}{\xi q^{\frac{\alpha}{1-\alpha}(k(s)+1)}} = 1 \implies \frac{\overline{\pi}}{\xi(r+p)} = 1 \implies p = \frac{\overline{\pi}}{\xi} - r$$

$$\implies Z^*(k(s)) = \xi q^{\frac{\alpha}{1-\alpha}(k(s)+1)} p = q^{\frac{\alpha}{1-\alpha}(k(s)+1)} (\overline{\pi} - r\xi)$$

Note that $p = \frac{\overline{\pi}}{\xi} - r$ implies that the probability of an innovation is the same across sectors: it does not depend on the current rung of the sector.

This is a special case induced by our assumption on $\phi$.

Clear implication: since the probability of success is the same for all sectors but sectors on higher rungs have lower research productivity $\implies$ more resources are devoted to higher rung sectors.


$$Z^*(k(s)) = q^{\frac{\alpha}{1-\alpha}(k(s)+1)} (\overline{\pi} - r\xi) \implies \frac{\partial Z^*(k(s))}{\partial k(s)} > 0$$

Schumpeterian Model: Aggregation

Let the aggregate quality index be:


$$Q := \int_0^N q^{k(s)\frac{\alpha}{1-\alpha}} ds$$

Then:


$$Y_t = L^{1-\alpha} \overline{X}^\alpha Q_t = \alpha^{\frac{2\alpha}{1-\alpha}} L Q_t$$

Although innovations occur at random, and progress will be unevenly distributed across sectors, $Q_t$ will change deterministically by the law of large numbers.

The aggregate amount of resources used in research:


$$Z := \int_0^N Z^*(k(s)) ds = q^{\frac{\alpha}{1-\alpha}} Q (\overline{\pi} - r\xi)$$

The resources constraint reads:


$$Y = C + X + Z$$


where $X := \int_0^N X(k(s)) ds$ is the total resources used in intermediates.

Note that $Y, Z, X$ are linear in $Q$, by resource constraint then $C$ has to be linear in $Q$ too. Therefore, in a Balanced Growth Path (BGP), it has to be that:


$$\gamma := \frac{\dot{C}}{C} = \frac{\dot{Q}}{Q} = \frac{\dot{Y}}{Y} = \frac{\dot{Z}}{Z} = \frac{\dot{X}}{X}$$

Schumpeterian Model: Households

The $L$ households solve the usual problem leading to the usual Euler Equation (EE):


$$\frac{\dot{c}_t}{c_t} = \frac{1}{\sigma} [r_t - \rho]$$

Recall that $r_t = r = \frac{\overline{\pi}}{\xi} - p$ and hence:


$$\gamma = \frac{\dot{c}}{c} = \frac{1}{\sigma} \left[ \frac{\overline{\pi}}{\xi} - p - \rho \right] = \frac{1}{\sigma} \left[ \frac{\frac{1-\alpha}{\alpha}\alpha^{\frac{2}{1-\alpha}}L}{\xi} - p - \rho \right]$$

Assets = shares in firms doing R&D.

...then what is $p$?

Schumpeterian Model: Quality over time

We want to understand how quality grows since it determines the growth of everything in the economy.

Start from the definition:


$$Q := \int_0^N q^{k(s)\frac{\alpha}{1-\alpha}} ds$$

In some sector $s$, $q^{k_s}$ is unchanged with probability $1-p$ and moves to $q^{k_s+1}$ if innovation is successful. Hence:


$$\mathbb{E}(\Delta Q) = \int_0^N p \left[ q^{(k(s)+1)\frac{\alpha}{1-\alpha}} - q^{k(s)\frac{\alpha}{1-\alpha}} \right] ds$$

We can simplify this to:


$$\mathbb{E}(\Delta Q) = p (q^{\frac{\alpha}{1-\alpha}} - 1) \int_0^N q^{k(s)\frac{\alpha}{1-\alpha}} ds = p (q^{\frac{\alpha}{1-\alpha}} - 1) Q$$

In growth rate terms, we then have:


$$\mathbb{E}(\Delta Q / Q) = p (q^{\frac{\alpha}{1-\alpha}} - 1)$$

If $N$ is large (we want $Q$ differentiable), the Law of Large Numbers (LLN) implies that we can write this as:


$$\frac{\dot{Q}}{Q} = p \left[ q^{\frac{\alpha}{1-\alpha}} - 1 \right]$$

Recovering the Values

We can solve the model completely by combining this with the EE and $\dot{Q}/Q = \dot{C}/C = \gamma$.

For simplicity, assume log intertemporal preferences ($\sigma = 1$). We have:


$$\gamma = \left[ \frac{\overline{\pi}}{\xi} - \rho \right] - p \quad \text{and} \quad \gamma = p \left[ q^{\frac{\alpha}{1-\alpha}} - 1 \right]$$

Solving these gives:


$$p = \left[ \frac{\overline{\pi}}{\xi} - \rho \right] q^{-\frac{\alpha}{1-\alpha}}$$

$$\gamma = \left[ \frac{\overline{\pi}}{\xi} - \rho \right] \left[ 1 - q^{-\frac{\alpha}{1-\alpha}} \right]$$

$$r = \frac{\overline{\pi}}{\xi} \left[ 1 - q^{-\frac{\alpha}{1-\alpha}} \right] + \rho q^{-\frac{\alpha}{1-\alpha}}$$

Some observations

These results are very similar to those we derived for the expanding variety model.

Next, note that the growth of the economy depends on the ability to generate improvements in the products $q$.

Is this economy efficient?

Schumpeterian Model: Planner

The planner maximizes HHs welfare subject to the economy's resource and technology constraints:


$$\max_{\{(X_t(s), Z_t(k(s)))_{s=1}^N\}_{t=0}^\infty} \left\{ L \int_0^\infty \frac{(c_t)^{1-\sigma} - 1}{1-\sigma} e^{-\rho t} dt \right\}$$


subject to


$$Y_t = X_t + Z_t + L c_t$$


and


$$\dot{Q}_t = \frac{Z_t \left[ 1 - q^{-\frac{\alpha}{1-\alpha}} \right]}{\xi}$$

$$Y_t = L^{1-\alpha} \int_0^N (q^{k(s)}X_t(s))^\alpha ds$$

Start from the $X$ choice (static). The market allocates based on the private optimality condition:


$$P_t(s) = \frac{1}{\alpha} = \alpha L^{1-\alpha} q^{\alpha k(s)} X_t(s)^{\alpha-1} \implies X_t(s) = L \alpha^{\frac{2}{1-\alpha}} q^{\frac{\alpha k(s)}{1-\alpha}}$$

The planner optimally sets the price equal to marginal cost: 1. Hence chooses:


$$P_t^*(s) = 1 = \alpha L^{1-\alpha} q^{\alpha k(s)} X_t^*(s)^{\alpha-1} \implies X_t^*(s) = L \alpha^{\frac{1}{1-\alpha}} q^{\frac{\alpha k(s)}{1-\alpha}}$$

Immediately we note that $X_t^* > X_t$ since $\alpha^{\frac{1}{1-\alpha}} < 1$.

As a consequence, output in the market vs planner allocations is:


$$Y_t = L \alpha^{\frac{2\alpha}{1-\alpha}} Q_t < L \alpha^{\frac{\alpha}{1-\alpha}} Q_t = Y_t^* \quad \text{at a given } Q_t$$

Like in the equilibrium, the planner allocation has the growth rate of output equal to that of the quality index since $Y_t \propto Q_t$.

The technology constraint (return to R&D) implies that the only determinant of the growth of $Q$ is R&D investment $Z$.

We can write the Hamiltonian of the planner by substituting out for $Z_t$ dynamic problem:


$$\mathcal{J} = \frac{c_t^{1-\sigma} - 1}{1-\sigma} e^{-\rho t} + \nu_t \frac{(1 - q^{-\frac{\alpha}{1-\alpha}})}{\xi} [Y_t - X_t - L c_t]$$

We can substitute our result on output $Y = L\alpha^{\frac{\alpha}{1-\alpha}}Q$ and inputs $X = \int_s X(s) = L\alpha^{\frac{1}{1-\alpha}}Q$:


$$\mathcal{J} = \frac{c_t^{1-\sigma} - 1}{1-\sigma} e^{-\rho t} + \nu_t \frac{(1 - q^{-\frac{\alpha}{1-\alpha}})}{\xi} \left[ L Q_t \frac{1-\alpha}{\alpha} \alpha^{\frac{1}{1-\alpha}} - L c_t \right]$$

We can use our sufficient conditions:


$$\mathcal{J}_c = 0$$

$$\mathcal{J}_Q = -\dot{\nu}$$

$$\mathcal{J}_\nu = \dot{Q}$$

Deriving (for ease of notation call $\frac{(1 - q^{-\frac{\alpha}{1-\alpha}})}{\xi} \equiv \mathcal{A}$):


$$\mathcal{J}_c = 0 \iff e^{-\rho t} c^{-\sigma} = L \nu \mathcal{A}$$

$$\mathcal{J}_Q = -\dot{\nu} \iff -\dot{\nu} = \mathcal{A} \nu L \frac{1-\alpha}{\alpha} \alpha^{\frac{1}{1-\alpha}}$$

$$\mathcal{J}_\nu = \dot{Q} \implies \dot{Q} = \mathcal{A} L Q \frac{1-\alpha}{\alpha} \alpha^{\frac{1}{1-\alpha}} - L c \mathcal{A}$$

Usual steps: start from the first and take logs:


$$-\rho t - \sigma \log c = \log L + \log \nu + \log \mathcal{A}$$

Take time derivatives:


$$-\rho - \sigma \frac{\dot{c}}{c} = \frac{\dot{\nu}}{\nu}$$

Use the second FOC to write:


$$-\frac{\dot{\nu}}{\nu} = \mathcal{A} L \frac{1-\alpha}{\alpha} \alpha^{\frac{1}{1-\alpha}}$$

And combine to get:


$$\gamma^* = \frac{\dot{c}}{c} = \frac{1}{\sigma} \left[ \mathcal{A} L \frac{1-\alpha}{\alpha} \alpha^{\frac{1}{1-\alpha}} - \rho \right]$$

From this it is immediate that the implicit interest rate for the planner is:


$$r^* = \mathcal{A} L \frac{1-\alpha}{\alpha} \alpha^{\frac{1}{1-\alpha}}$$

To start comparing with the market allocation, note that the implicit profits for the planner are:


$$\pi^* = L \frac{1-\alpha}{\alpha} \alpha^{\frac{1}{1-\alpha}}$$


so we can rewrite the interest rate as (using the $\mathcal{A}$ definition):


$$r^* = \frac{\pi^*}{\xi} \left[ 1 - q^{-\frac{\alpha}{1-\alpha}} \right]$$

Recall that the market rate was:


$$r = \frac{\overline{\pi}}{\xi} \left[ 1 - q^{-\frac{\alpha}{1-\alpha}} \right] + \rho q^{-\frac{\alpha}{1-\alpha}}$$

Comparing Planner vs Eqm

Consider the interest rate for the planner $r^*$ and CE $r$.


$$r^* = \frac{\pi^*}{\xi} \left[ 1 - q^{-\frac{\alpha}{1-\alpha}} \right]$$

$$r = \frac{\overline{\pi}}{\xi} \left[ 1 - q^{-\frac{\alpha}{1-\alpha}} \right] + \rho q^{-\frac{\alpha}{1-\alpha}}$$

One difference is again, $\pi^*$ vs $\overline{\pi}$:


$$\pi^* = \frac{1-\alpha}{\alpha} \alpha^{\frac{1}{1-\alpha}} L \quad \text{vs} \quad \overline{\pi} = \frac{1-\alpha}{\alpha} \alpha^{\frac{2}{1-\alpha}} L$$

$\pi^* > \overline{\pi}$: the planner values innovation more than individual inventors.

What about $\rho q^{-\frac{\alpha}{1-\alpha}}$? In general, there are two main externality effects:

'Business stealing effect': entrants do not internalize that they destroy incumbent profits. Innovators see $V$ and not only $\Delta V$ as a return (potential for too much innovation).

'Temporary returns': present innovators do not realize that next innovators will benefit as the next rung can be obtained only after the previous one. They only see that they lose profits with probability $p$ (potential for too little innovation).

Since $\rho q^{-\frac{\alpha}{1-\alpha}} > 0$: In this model the first externality dominates: The extraction of the monopoly profit is the amount taken from one's predecessor. The treatment of an innovation as temporary is equivalent to ignoring the rents that will be taken by one's followers.

Since $\pi^* > \overline{\pi}$, the final result on $r$ and $\gamma$ compared to $r^*$, $\gamma^*$ is ambiguous.

We can have too little or too much growth!

Comparing Planner vs Eqm - Summary

Lab-equipment model: positive externality associated to research $\implies$ too little investment in the market eqm.

Expanding Variety (EV): positive externality associated to research $\implies$ too little investment in the market eqm.

Common cause: monopoly distortion in production + invention makes next invention more likely. Contrary to Hsieh and Klenow, where this distortion can, at most, affect levels (under elastic factor supply), here it reduces growth.

Quality Ladder (QL): positive + negative externalities $\implies \gamma^* \lesseqqgtr \gamma$

Additional force: innovation partly expropriate the returns to past innovators $\implies$ negative externality.

Key difference with EV: growth generates a conflict of interest between innovators and incumbents.

Implies the existence of winners and losers which may distort the incentives to do policy.

Consider an economy with a tax on R&D.

In EV, it is immediate we want to subsidize R&D ($\tau < 0$) so that innovation $\uparrow$.

Policy

The tax changes the steady-state value of having a patent:


$$V(k(s)+1) = \frac{\pi(k(s))}{r(\tau) + p(\tau)}$$


Note that $\pi$ does not depend on $\tau$ since $\pi$ is the solution of a static problem that only depends on the current stock of knowledge, not the future one.

The free entry condition now implies:


$$\frac{V(k(s)+1)}{\xi q^{\frac{\alpha}{1-\alpha}(k(s)+1)}} = 1 + \tau$$

$V$ is increasing in $\tau$ since now R&D is more costly $\implies$ for Free Entry to hold the benefit has to be higher.

Combining the two and rearranging:


$$r(\tau) = \frac{\pi q^{-\frac{\alpha}{1-\alpha}(k(s)+1)}}{\xi(1+\tau)} - p(\tau)$$

And from the EE:


$$\gamma(\tau) = \frac{1}{\sigma} [r(\tau) - \rho]$$

It is immediate that $p(\tau)$ is decreasing in $\tau$ and, therefore, so is $r$ and the growth rate $\gamma$.

Lower growth when we tax R&D - not very surprising.

Note, however, that current monopolists would be in favor of taxing R&D.

Suppose we ban R&D altogether ($\tau \rightarrow \infty$).

Current monopolists' value increases a lot since now they do not face competition from future inventors.

If they could, innovators would innovate and then immediately lobby against innovation.

What if current monopolists could lobby?

Innovation and Competition

Effect of Competition - Theory

So far: models where profits motivate innovation with two obvious shortcomings:

Incumbents do a lot of innovation, which in our model is absent.

Competition is obviously bad since it erodes profits and the incentives to innovate.

We can challenge these observations in the context of a simple model of step-by-step innovation.

Suppose households live for one period and have Cobb-Douglas preferences over a set of varieties in the unit line:


$$u_t = \int_0^1 \ln x_{jt} dj$$

Each product line is supplied by a duopoly $\{\alpha, \beta\}$ under the threat of a competitive fringe:


$$x_j = x_{\alpha j} + x_{\beta j}$$

They both use linear technologies with productivities $A_{ij}, i \in \{\alpha, \beta\}$ and TFP on a quality ladder:


$$A_i = \gamma^{k_i}$$

Suppose that $\alpha$ and $\beta$ are always at most one step from one another.

If more than 1 step then the 1 step technology can be imitated by the competitor (e.g., if Apple makes the iPhone 16, then Huawei can make the iPhone 15).

The competitive fringe is always one step behind the worst technology of $\alpha$ and $\beta$.

Everybody can make the iPhone 14.

This implies that industries can be of two types:

Neck-and-neck: $\alpha$ and $\beta$ have the same technology level, and the fringe lags by one.

Unlevel: one firm has a better technology than the other, and the fringe is two rungs down.

Firms innovate with probability $\psi \frac{n^2}{2} Y$ by investing $n$ units of the final good. Normalize $Y=1$ as a numeraire.

Followers can imitate for free with probability $h$.

Note: this implies that firms cannot fully appropriate the returns of their investment!

Assume that firms compete Bertrand (recall perfect substitute goods) which implies limit pricing.

In an unlevel sector, the leader prices at the marginal cost of the follower $\implies$ markup is equal to $\gamma$.


$$\pi_1 = \left(1 - \frac{1}{\gamma}\right) p_j x_j = \frac{\gamma - 1}{\gamma}$$

Follower gets zero payoff.

In neck-and-neck sectors:

If the firms compete $\implies$ zero profits for both firms.

If the firms collude $\implies$ they can get monopoly profits equal to $\pi_1$.

Suppose each firm gets:


$$\pi_0 = (1 - \Delta) \pi_1$$


where $\Delta$ parameterizes the degree of competition/collusion: $\Delta \rightarrow 1$ means competition.

Given these payoffs, firms make innovation decisions maximizing profits (myopic firms since agents live only one period).

In an unlevel sector, the leader has no incentive to innovate: payoffs only depend on the distance, and the distance can never be larger than 1.

Laggard firm innovates at rate $n_{-1}$ by solving:


$$\max_{n_{-1}} (n_{-1} + h)\pi_0 - \psi n_{-1}^2 / 2$$


which implies:


$$n_{-1} = (1 - \Delta) \frac{\pi_1}{\psi}$$

In a level sector, suppose only one firm has an innovation opportunity and chooses $n_0$:


$$\max_{n_0} n_0 \pi_1 + (1 - n_0)\pi_0 - \psi n_0^2 / 2$$


which implies:


$$n_0 = \frac{\Delta \pi_1}{\psi}$$

Note the key difference:

In unlevel sector, competition reduces the incentives to innovate by reducing the monopoly rents (Schumpeterian effects).

In level sector, competition incentivizes innovation to escape competition and obtain monopoly rents.

To evaluate the aggregate consequence, we need to think about the sector composition of the economy.

Each period, unlevel sectors turn level with probability $n_{-1} + h$.

While level sectors become unlevel with probability $n_0$.

In steady state, the composition must be constant so that $\mu_0$ (level) and $\mu_1$ (unlevel) are:


$$(n_{-1} + h)\mu_1 = n_0(1 - \mu_1)$$

Hence, in steady state:


$$\mu_1 = \frac{n_0}{n_0 + n_{-1} + h}$$

Which implies a flow of innovation $I$:


$$I = (n_{-1} + h) \times \frac{n_0}{n_0 + n_{-1} + h} + n_0 \times \frac{n_{-1} + h}{n_0 + n_{-1} + h}$$

Simplifying and using the optimal investments:


$$I = \frac{2\pi_1}{\psi(1 + \frac{\psi h}{\pi_1})} \Delta \left( 1 - \Delta + \frac{\psi h}{\pi_1} \right)$$

The derivative of innovation with respect to competition is:


$$\frac{\partial I}{\partial \Delta} = \frac{2\pi_1}{\psi(1 + \frac{\psi h}{\pi_1})} \left( 1 - 2\Delta + \frac{\psi h}{\pi_1} \right) \propto 1 - 2\Delta + \frac{\psi h}{\pi_1}$$

When competition is low ($\Delta < 1/2$), more competition increases growth.

Relatively few unlevel industries $\implies$ escape from competition dominates.

When competition is high ($\Delta$ close to 1).

Most sectors are unlevel which makes Schumpeterian forces dominate $\implies$ little innovation in level industries.

Note that imitation is good here since it makes more sectors level.

Effect of Competition - Empirics (Aghion et al., 2005)

The model predicts a U-shaped relation between the intensity of competition and the rate of innovation.

Aghion et al. (2005) test this on UK firms between '73 and '94.

Measurement:

Innovation is measured by the citations-weighted average number of patents in an industry.

Competition is measured by the Lerner Index:


$$1 - L_{jt} = \frac{1}{N_{jt}} \sum_{i \in j} \frac{\pi_{it} - r_{it}}{R_{it}}$$


$N_{jt}$: number of firms industry $j$, $\pi_{it}$ operating profits of firm $i$, $r_{it}$ estimated cost of capital, $R_{it}$ sales.

$L_{jt} = 1$ when firms have no market power.

[Image Placeholder: Scatter Plot of Innovation on Competition (Aghion et al., 2005). The graph shows an inverted U-shape. X-axis: 1 - Lerner (0.85 to 1). Y-axis: Citation weighted patents (0 to 20).]

[Image Placeholder: Scatter Plot of log(R&D Salary) vs Weighted Price Gap (Domestic - Mode Import) by Atalar, 2026. Graph also shows an inverted U-shape fitted line.]

Bonus: Efficiency in Varieties Models

Efficiency of the Number of Varieties

The models with imperfect substitutes we have studied so far all have the property that their equilibrium is not socially optimal.

A natural question at this point is whether the number of available varieties (or equivalently the investment in R&D) can ever be socially optimal.

We study this question in a more general but simpler framework.

Consider an economy with $N$ identical firms each producing a quantity $q_N$ such that $Q = N q_N$.

There is a demand for these goods, such that the willingness to pay is $P(Q) = P(N q_N)$.

Firms produce at total cost $c(q_N)$.

Firms obtain profits equal to:


$$\pi_N = P(N q_N) q_N - c(q_N) - K$$

where $K$ is the fixed cost to set up a new firm.

A free entry equilibrium is one in which firms enter until the profits are arbitraged away:


$$\pi_{N^e} = 0$$

where $N^e$ is the equilibrium number of firms with free entry.

A social planner maximizes social welfare subject to the same technology constraints ($c(\cdot)$ and $K$):


$$\mathcal{W}(N) = \int_0^{Nq_N} P(s) ds - N c(q_N) - N K$$


(why the integral?)

Suppose the three following things hold:

A.1 Total quantity is increasing in how many firms there are:
$Q(N) > Q(N'), \forall N > N'$.

A.2 The quantity produced by each firm decreases in the number of firms:
$\frac{\partial q_N}{\partial N} \le 0, \forall N$.

A.3 Producing firms make non-negative profits:
$P(N q_N) - c'(q_N) \ge 0, \forall N$.

Under these assumptions, we study the socially optimal number of varieties.

The planner's FOC is:


$$\frac{\partial \mathcal{W}(N)}{\partial N} = P(N q_N) \left[ q_N + N \frac{\partial q_N}{\partial N} \right] - c(q_N) - N c' \frac{\partial q_N}{\partial N} - K = 0$$

We can rewrite this condition as:


$$\frac{\partial \mathcal{W}(N)}{\partial N} = P(N q_N) q_N - c(q_N) - K + N \frac{\partial q_N}{\partial N} [P(N q_N) - c']$$

Hence:


$$\frac{\partial \mathcal{W}(N)}{\partial N} = \pi_N + N \frac{\partial q_N}{\partial N} [P(N q_N) - c'] = 0$$

We can evaluate the planner's optimality condition at the market (free entry equilibrium) $N^e$ where $\pi_{N^e} = 0$:


$$\frac{\partial \mathcal{W}(N)}{\partial N} = N^e \frac{\partial q_{N^e}}{\partial N} [P(N^e q_{N^e}) - c'] < 0$$

We conclude that in this model there are too many firms in the economy since the planner would like to have fewer of them.

This is driven by the negative externality (A.2) that entering firms have on the payoff of existing firms.

Again, the market equilibrium is socially inefficient: the planner would like to tax firms so that they do not enter.

This conclusion comes from (among others) our assumption on preferences.

From the way the problem was stated, these firms are making perfectly substitutable goods! $\implies$ why have more than one firm?

Consider the same economy, but the household has the following utility:


$$U = G \left[ \sum_i f(q_i) \right]$$

Assume that both the subutility $f(\cdot)$ and the aggregator $G(\cdot)$ are increasing and concave.

The household optimization implies that the willingness to pay for each good is:


$$G'[N f(q_N)] f'(q_N)$$

Which has to be equal to the price in equilibrium.

Hence, firms' profits are:


$$\pi_N = G'[N f(q_N)] f'(q_N) q_N - c(q_N) - K$$


at the FE eqm. $N^e$ is such that $\pi_{N^e} = 0$.

Consider the planner's problem:


$$\max_N \mathcal{W}(N) = G[N f(q_N)] - N c(q_N) - N K$$

Whose FOC is:


$$G' \left( N f' \frac{\partial q_N}{\partial N} + f \right) - c(q_N) - N c'(q_N) \frac{\partial q_N}{\partial N} - K = 0$$

Rearranging as before:


$$\pi_N + N (G' f' - c') \frac{\partial q_N}{\partial N} + G' (f - f' q_N) = 0$$

Evaluating at the free entry equilibrium $\pi_{N^e} = 0$:


$$N^e (G' f' - c') \frac{\partial q_N}{\partial N} + G' (f - f' q_{N^e}) = 0$$

Recall that $q_N' < 0$ because of the business stealing effect, so the first term is negative.

However, the second term is positive thanks to the aggregate externality: entry of additional varieties increases the WTP for existing ones thanks to $G' > 0$.

There might be a knife-edge case in which the equilibrium is constrained-efficient even in the presence of (offsetting) externalities.

The CES case

Consider now the CES + monopolistic competition case.

We can go about this two ways:

Solve the market and planner allocation and compare.

Apply our general formula and evaluate the externalities directly.

The CES case - Equilibrium

Start from our definition of preferences and implied price index:


$$Q = \left( \int_i q_i^{\frac{\sigma-1}{\sigma}} \right)^{\frac{\sigma}{\sigma-1}} \quad P = \left( \int_i p_i^{1-\sigma} \right)^{\frac{1}{1-\sigma}}$$

Which implies the usual demand for individual varieties:


$$q_i = p_i^{-\sigma} P^\sigma Q$$

All firms produce with the same technology, implicitly defined by:


$$l_i = f + c q_i$$

Firms' profits are:


$$\pi_i = p(q_i) q_i - w c q_i - w f$$

Suppose that the labour endowment is $L$ and set it as the numeraire so $w=1$.

The profit maximization yields the usual optimal pricing:


$$p_i = \frac{\sigma}{\sigma-1}c, \forall i$$


$\implies$ firms choose identical prices, which implies a fully symmetric equilibrium.

We can use this in the quantity and price index to obtain:


$$Q = N^{\frac{\sigma}{\sigma-1}} q$$

$$P = N^{\frac{1}{1-\sigma}} p$$


where $N$ is the measure of active firms.

The household obtains income from labour and potential profits, so that expenditure is:


$$PQ = L + N\pi$$

Consider a Free Entry equilibrium such that:


$$\pi = 0 \iff (p - c)q = f$$

We can simplify this with the optimal price result to:


$$q = \frac{f(\sigma - 1)}{c}$$

Combining this with our results for $P$ and $Q$:


$$PQ = p N^{\frac{1}{1-\sigma}} q N^{\frac{\sigma}{\sigma-1}} = N p q$$

Finally, using the budget constraint and FE ($\pi=0$):


$$PQ = L \iff N = \frac{L}{\sigma f}$$


(you can also derive this from the labour mkt clearing $L = Ncq + Nf$)

Which completes the characterization of the market eqm.

So in the market allocation, firms obtain gross profits $(p-c)q > 0$.

These are not pure rents since the actual rents ($\pi$) are driven down to zero by free entry.

We can now solve the planner and compare.

The CES case - Planner

The planner maximises utility subject to the resource and technology constraints:


$$\max_N Q \quad \text{s.t. } L = N c q + N f$$

It is immediate that, due to love for variety and identical technologies, the planner solution will be symmetric (you can show it following the usual steps).

We can impose symmetry and plug the constraint in the objective function:


$$\max_N N^{\frac{\sigma}{\sigma-1}} \frac{L - N f}{N c}$$

The FOC for this problem immediately implies:


$$N = \frac{L}{\sigma f}$$

Using this solution in the resource constraint:


$$L = \frac{c q L}{\sigma f} + \frac{f L}{\sigma f}$$

Which implies:


$$q = \frac{f(\sigma - 1)}{c}$$

The planner mandates the same allocation as the market in terms of the number of active firms and quantity per firm.

Which immediately implies that the markups obtained by firms in the market allocation are socially desirable.

Why?

Special Case: CES (Direct Externality Evaluation)

We can go back to the two externalities and derive them separately.

Recall that the utility is simply $Q$, which implies we can write the objective function as:


$$Q = I/P$$


with $I$ total expenditure.

To simplify the problem, maximize the log of utility.
(Recall that any monotone transformation preserves extrema since it is rank-preserving $\implies \arg\max \log(f(x)) = \arg\max f(x)$)

Which implies that at the optimum:


$$\frac{\partial U}{\partial N} = 0 \iff \frac{\partial \log I}{\partial N} - \frac{\partial \log P}{\partial N} = 0$$

From our earlier findings, we know that $P = N^{\frac{1}{1-\sigma}} p$. Which implies:


$$\frac{\partial \log P}{\partial N} = \frac{1}{1-\sigma} \frac{1}{N}$$

We know from earlier that $I = L + N\pi$.

We know from earlier that $\pi = \frac{I}{\sigma N} - f$.

Therefore, we have that:


$$\frac{\partial I}{\partial N} = \pi + N \frac{\partial \pi}{\partial N}$$

Which is given by:


$$\frac{\partial I}{\partial N} = \pi + N \left( \frac{\partial I}{\partial N} \frac{1}{\sigma N} - \frac{I}{\sigma N^2} \right)$$

Which simplifies to:


$$\frac{\partial I}{\partial N} = \frac{\pi\sigma}{\sigma-1} - \frac{I}{(\sigma-1)N}$$

Since we are interested in the derivative of $\log I$:


$$\frac{\partial \log I}{\partial N} = \frac{\pi\sigma}{(\sigma-1)I} - \frac{1}{(\sigma-1)N}$$

We can now plug it all in to obtain:


$$\frac{\partial \log U}{\partial N} = \frac{\pi\sigma}{(\sigma-1)I} - \frac{1}{(\sigma-1)N} - \frac{1}{1-\sigma} \frac{1}{N}$$

At the free entry eqm $\pi=0$ so:


$$\frac{\partial \log U}{\partial N} = \underbrace{-\frac{1}{(\sigma-1)N}}_{\text{business stealing}} - \underbrace{\frac{1}{1-\sigma} \frac{1}{N}}_{\text{love of variety}} = 0$$

This is a very special case!

The elasticity that governs the positive externality is $\sigma$ because that is the curvature of demand.

The elasticity that governs the negative externality is also $\sigma$ because that is the elasticity of substitution across varieties.

You can try to do this again with these preferences:


$$U = N^\alpha \left( \int_i q_i^{\frac{\sigma-1}{\sigma}} \right)^{\frac{\sigma}{\sigma-1}}$$

You can show that the love of variety depends on $\alpha$ and efficiency depends on $\alpha \le 0$. The economy is efficient only if $\alpha = 0$.