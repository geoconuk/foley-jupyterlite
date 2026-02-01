---
layout: default
---

<script>
window.MathJax = {
  tex: { inlineMath: [['$', '$'], ['\\(', '\\)']] }
};
</script>
<script src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>

## Model 2 Summary: Reproduction-Led Accumulation with Wage Finance Constraint

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
