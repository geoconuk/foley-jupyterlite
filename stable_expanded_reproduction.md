---
layout: default
---

<script>
window.MathJax = {
  tex: { inlineMath: [['$', '$'], ['\\(', '\\)']] }
};
</script>
<script src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>

# Model 2 Summary: Reproduction-Led Accumulation with Wage Finance Constraint

In Model 2 we reconsider the realisation problem raised by Foley in Chapter 5 by changing the **closure of the system**, while keeping his core production, inventory, and markup structure intact. The objective is not to deny monetary constraints, but to **localise** them more precisely.

### 1. What is retained from Foley

The model preserves the essential temporal and structural features of Foley’s analysis:

- Production requires advance outlays \(C_j(t)\) and occurs with a **production lag** \(T_P\).
- Output passes through inventories and is sold after a **realisation lag** \(T_R\).
- A **markup \(q_j\)** is realised at the point of sale:
  \[
  S_j(t) = (1+q_j)\,C_j(t-T_P-T_R).
  \]
- Capital outlays are decomposed into variable and constant capital via fixed shares \(k_j\).

Thus, the circuit \(C \rightarrow P \rightarrow S\) with delays and markups is exactly as in Foley.

---

### 2. The key change: a reproduction-led closure

What differs from Foley’s finance-led model is **how expanded reproduction is coordinated**.

Instead of imposing the condition that *all* spending at time \(t\) must be financed by sales realised at \(t-T_F\), Model 2 distinguishes between different uses of money and different roles of sales.

Specifically:

- **Accumulation of means of production** is treated as a *real* process.
- **Capitalist consumption** is flexible and adjusts to clear the consumption-goods department.
- **Only the purchase of labour-power requires cash in advance.**

This change introduces a new object:
\[
A_I(t) := S_I(t) - c_I(t) - c_{II}(t),
\]
the **net accumulation of means of production**, defined as the part of Department I output not required to replace current constant capital.

---

### 3. Interpretation of \(A_I(t)\)

\(A_I(t)\) represents **new productive capacity created by current production**.

- It is **not inventory** (which arises from timing).
- It is **not part of current constant-capital requirements**.
- It does **not require contemporaneous monetary validation**.

Instead, \(A_I(t)\) feeds directly into productive capacity and determines the future scale of production. In the endogenous version of Model 2, this is made explicit by a capacity-accumulation equation:
\[
\dot K(t) = A_I(t),
\]
with production outlays proportional to capacity.

Thus, accumulation is governed by **reproduction feasibility**, not by current cash flow.

---

### 4. The role of money and the finance lag \(T_F\)

Money is not eliminated from the model, but its role is **narrowed**.

In the version adopted here:

- **Wages must be financed out of lagged sales receipts**:
  \[
  v_j(t) \le S_j(t-T_F).
  \]
- Workers spend wages immediately once paid:
  \[
  D_W(t) = v_I(t) + v_{II}(t).
  \]

Thus, the finance lag \(T_F\):

- constrains **employment and current production**,
- but does **not** constrain:
  - accumulation of means of production,
  - interdepartmental coordination,
  - capitalist consumption.

This sharply contrasts with Foley’s diagnostic case, where *all* spending is finance-constrained.

---

### 5. Why Foley’s paradox disappears

In Foley’s finance-led closure, exponential growth combined with a uniform finance lag implies:
\[
D(t) = S(t-T_F) = e^{-gT_F} S(t),
\]
leading mechanically to insufficient aggregate demand.

In Model 2:

- Accumulation is coordinated through \(A_I(t)\), not through money demand.
- Department I output expands productive capacity directly.
- Department II output is absorbed by workers’ consumption and flexible capitalist consumption.
- The finance lag affects wages only and does not generate a systematic shortfall of demand.

As a result, **expanded reproduction is feasible without an inherent realisation problem**.

---

### 6. Conceptual implication

The apparent paradox identified by Foley is not a general contradiction of capitalist reproduction, but a consequence of a particular closure in which **money circulation is required to coordinate all aspects of reproduction**.

Model 2 shows that:

- once accumulation is treated as a reproduction-led process,
- and monetary constraints are applied selectively (to labour-power purchase),

the paradox disappears.

More generally, the analysis highlights that **expanded reproduction requires coordination at the level of productive capacity**, whether achieved through internal planning, credit systems, vertical integration, or broader social mechanisms. Money may mediate this coordination, but it need not universally constrain it.

---

*This model therefore complements Foley’s Chapter 5 by showing that the “realisation problem” is closure-dependent and that alternative, equally Marxian closures lead to qualitatively different conclusions about the viability of expanded reproduction.*

# Further notes for later on -- other ways to square the circle -- pick these up another day

 Notes on a Two-Department Circuit Model with Finance Lags, Demand Constraints, and Accumulation

## 1. Motivation and scope

These notes develop an extension of Foley’s Chapter 5 circuit models, focusing on the **feasibility of expanded reproduction** once we take seriously:

- production, sales, and finance lags,
- explicit money-financing constraints,
- demand as an **inequality constraint** rather than an identity,
- and the Department I / Department II distinction.

The core question is not whether surplus value is created, but whether it can be **realised, financed, and re-advanced** in a dynamically consistent way.

The analysis deliberately begins from a **strict closure** (no credit, no external demand, departmental self-financing) in order to isolate where and why difficulties arise.

---

## 2. Model structure and equations

### 2.1 Departments and interpretation

We consider two departments:

- **Department I**: production of means of production (MoP)
- **Department II**: production of means of consumption (MC)

All variables are monetary unless otherwise stated.

---

### 2.2 Production

For each department \( i \in \{I, II\} \):

\[
P_i(t) = C_i(t - T_P)
\]

where:
- \( C_i(t) \) is capital outlay at time \( t \),
- \( P_i(t) \) is finished product emerging after production lag \( T_P \).

---

### 2.3 Sales with demand and availability constraints

Sales are **sale-value receipts**, constrained by both effective demand and physical availability.

#### Department I (MoP)

Demand for MoP arises from constant-capital outlays in both departments:

\[
S_I(t) =
\min\!\left(
(1 - k_I) C_I(t) + (1 - k_{II}) C_{II}(t),\;
(1 + q_I) P_I(t - T_R)
\right)
\]

#### Department II (consumption goods)

Demand arises from wages plus capitalist consumption:

\[
S_{II}(t) =
\min\!\left(
k_I C_I(t) + k_{II} C_{II}(t) + D_I(t) + D_{II}(t),\;
(1 + q_{II}) P_{II}(t - T_R)
\right)
\]

where:
- \( k_i \) is the share of variable capital in department \( i \),
- \( q_i \) is the markup rate,
- \( T_R \) is the sales (realisation) lag,
- \( D_i(t) \) is capitalist consumption funded from department \( i \).

---

### 2.4 Capitalist consumption (Style B)

Capitalists consume a fixed share \( (1 - p) \) of **realised surplus**, funded out of **spendable receipts**.

Given pricing \( (1 + q_i) \), the markup share of receipts is:

\[
\frac{q_i}{1 + q_i}
\]

Capitalist consumption is therefore:

\[
D_i(t) =
(1 - p)\,\frac{q_i}{1 + q_i}\,S_i(t - T_F)
\]

where \( T_F \) is the **finance lag**: receipts become spendable only after \( T_F \).

---

### 2.5 Finance stocks and constraint

Finance capital evolves according to:

\[
\dot F_i(t) = S_i(t - T_F) - C_i(t) - D_i(t)
\]

with the **no-borrowing constraint**:

\[
F_i(t) \ge 0 \quad \text{for all } t
\]

This closure enforces strict self-financing: all spending must ultimately be financed from lagged receipts.

---

### 2.6 Inventories and productive capital

Inventories are measured at cost:

\[
\dot X_i(t) = P_i(t) - \frac{S_i(t)}{1 + q_i}
\]

Productive capital evolves as:

\[
\dot N_i(t) = C_i(t) - P_i(t)
\]

All stocks satisfy \( N_i, X_i, F_i \ge 0 \).

---

## 3. Balanced exponential growth and feasibility

We investigate whether **smooth expanded reproduction** is possible, meaning:

\[
C_i(t) = c_i e^{g t}
\]

with constant \( g > 0 \).

To make sense of the delays, we assume **exponential prehistory**: the same exponential form holds for all delayed arguments.

---

### 3.1 Fundamental feasibility condition

On a balanced exponential path, finance nonnegativity implies (in coefficient form):

\[
c_i \;\le\; (1 - \alpha_i)\, e^{-g T_F}\, s_i
\]

where:
- \( s_i \) is the sales coefficient (\( S_i(t) = s_i e^{g t} \)),
- \( \alpha_i = (1 - p)\frac{q_i}{1 + q_i} \) is the capitalist-consumption leakage share.

Crucially, \( s_i \) itself is bounded by **contemporaneous demand**, which depends on \( C_I, C_{II} \) and on lagged sales via \( D_i \).

Thus today’s spending must be validated by **yesterday’s receipts**.

---

### 3.2 Impossibility result under strict closure

Under the joint assumptions:

1. Two departments (I / II),
2. Departmental self-financing only,
3. Receipts become spendable only after \( T_F > 0 \),
4. No borrowing (\( F_i \ge 0 \)),
5. No external demand or credit,
6. Fixed technical coefficients (\( k_i, q_i, p \)),

we were unable to find any parameter set supporting sustained exponential growth with \( g > 0 \).

This appears to be **structural**, not accidental.

#### Intuition

- Demand must validate production.
- Demand itself is financed from **lagged receipts**.
- With positive trend growth, lagged receipts grow too slowly relative to current outlays.
- The effective financing envelope shrinks by a factor \( e^{-g T_F} < 1 \).

Allowing oscillatory modes (complex \( g \)) does not help: only the real part of \( g \) matters for feasibility. Oscillations permit cycles, but not sustained positive trend growth.

This sharpens Foley’s Part-2 realisation paradox into a **formal feasibility constraint**.

---

## 4. Possible “get-outs”

The impossibility result depends on the strictness of the closure. Several minimal relaxations restore feasibility.

### 4.1 Credit or borrowing

Allow \( F_i(t) \) to become negative up to a bound (debt).  
This breaks the lagged-receipt envelope and corresponds to Kalecki’s credit mechanism.

---

### 4.2 Pooled or planned finance

Replace departmental finance stocks with a single pooled fund \( F \).

This allows cross-financing between departments and corresponds to **planning or coordination** rather than pure market self-financing.

---

### 4.3 External demand

Introduce an exogenous demand term (exports or state spending), typically into Department II.

This is the Luxemburg-style resolution.

---

### 4.4 Bypassing money exchange for part of accumulation

Allow part of Department I output to be **directly reinvested** into productive capacity without passing through sale and monetary validation.

Conceptually:
- accumulation is partly organised in physical/value terms,
- money is strictly required only for labour-power purchases,
- accumulation is no longer fully constrained by the lagged cash circuit.

This yields a **reproduction-led** rather than **exchange-led** interpretation of the circuit.

---

## 5. Relaxing strict proportionality between departments

The analysis above focused on **balanced proportional growth** (fixed \( C_{II} / C_I \)).

The next conceptual step is to **drop this requirement** and allow departments to move out of proportion.

### Expected consequences

- One department (typically I) can temporarily expand faster than the other.
- Demand constraints manifest as **inventory accumulation** rather than outright infeasibility.
- Finance constraints bind intermittently rather than permanently.

### Anticipated dynamics

Under the same strict closure but without proportionality, we expect:

- long transients of expansion followed by contraction,
- endogenous cycles driven by lags and inventory adjustment,
- crisis dynamics as a form of **disproportionality correction**.

Balanced exponential growth remains infeasible, but **meaningful dynamics** (booms, busts, oscillations) become possible.

---

## 6. Next step

When work resumes, the natural continuation is:

1. Build a simulation model (discrete-time or DDE-based) implementing the above equations.
2. Drop the proportionality constraint.
3. Specify a behavioural or control rule for \( C_I(t), C_{II}(t) \) (for example: spend as much as possible subject to \( F_i \ge 0 \)).
4. Explore:
   - transient growth,
   - oscillations,
   - inventory dynamics,
   - sensitivity to \( T_P, T_R, T_F, p, k_i, q_i \).

The aim is to visualise how the realisation problem appears dynamically once it is treated as an inequality-constrained, lagged system rather than a static accounting identity.
