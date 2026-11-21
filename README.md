This repository contains the source of the **O13** Cosmochrony paper  
*Asymptotic Stability of Exact Weil-Block Capacity on Heisenberg Graphs:
Extended Prime Range, Variance Reduction, and Requalification of the δ–β* Tension*.

This work extends the **spectral admissibility sub-programme** by testing the
finite-size hypothesis left open in **O12**, through an extension of the exact
Weil-block computation to larger primes.

**O12** measured a higher finite-$q$ decay exponent than the proxy and
identified a tension with the phenomenological target for $\beta^*$; its
corrective revision shows that finite-$q$ value is a crossover statistic, not
an intrinsic asymptotic exponent, and derives the intrinsic unfolded exponent
exactly ($\delta_{\mathrm{exact}}=3$), independent of the central coordinate
$\gamma$. O12 originally left open whether the finite-$q$ mismatch could be
explained as a finite-size effect.

The present work answers this question by extending the computation to
\[
q \in \{101, 151, 211\},
\]
and by analysing both convergence behaviour and variance structure.

The central observable remains the **exact incremental block capacity**
\[
\Sigma_n^{(c)} = \frac{\Delta r_n^{(c)}}{|S_n|},
\]
measured within irreducible Weil blocks of the Heisenberg Cayley graph.

# Core Result

The paper establishes that the exact decay exponent does **not drift upward**
toward the historical comparison range $[7.4,10.6]$ at larger primes.

Starting from:

- the O7 capacity observable $\Sigma_n$
- the O9 Heisenberg graph setting
- the O11 proxy-level extraction
- the O12 exact Weil-block observable

the analysis shows that:

- the sequence of exact exponents
  \[
  \hat\delta_{\mathrm{exact}} = 4.42,\,4.80,\,4.51,\,4.27,\,3.59
  \]
  at $q \in \{29,61,101,151,211\}$ exhibits **one non-monotone step**
  ($4.42 \to 4.80$, from $q=29$ to $q=61$), **followed by a strict monotone
  decrease from $q = 61$ to $q = 211$** ($4.80\to4.51\to4.27\to3.59$) — the
  sequence as a whole is not monotone
- the measurement quality improves with $q$:
    - fitting window length increases from 4 to 11 points
    - inter-block variance decreases from $V_n^{\max} = 5.20$ to $0.30$
    - $R^2 > 0.993$ throughout
- condition (E2) is satisfied at $q \geq 151$, establishing **block-by-block
  universality**
- no fitting strategy produces $\delta_\infty > 5.0$ — and O12's corrective
  revision independently derives, in closed form, the exact value this
  sequence converges toward: $\delta_\infty = \delta_{\mathrm{exact}} = 3$

Thus:

- the exponent decreases precisely where the measurement becomes most reliable
- the observed trend is not a numerical artefact
- the finite-size hypothesis is **ruled out in its strong form**

# Structural Role of O13

O13 performs the decisive test left open by O12:

- **O11**: proxy-level extraction
- **O12**: exact Weil-block extraction and tension identification
- **O13**: asymptotic test and falsification of the finite-size explanation

O13 tests and rejects the strong finite-size hypothesis that the measured exponent would drift
upward toward the historical comparison range. This does not establish a discrepancy with a derived
physical prediction: O6 supplies only a conditional upper bound and a countermodel to reciprocal equality.

# What O13 Adds

O13 introduces several decisive advances:

- extension of the exact computation to larger primes
- identification of a **strict monotone decreasing regime** of
  $\hat\delta_{\mathrm{exact}}$ from $q=61$ to $q=211$ (not from $q=29$: the
  sequence rises from $q=29$ to $q=61$ before decreasing)
- a systematic analysis of convergence:
    - failure of $1/q$ scaling
    - log-linear behaviour without plateau
- a quantitative law for variance reduction:
  \[
  V_n^{\max}(q) \sim 754 \cdot q^{-1.41}
  \]
- identification of the correlation:
    - **measurement quality increases while $\delta$ decreases**

# Interpretation of the Result

The main conceptual outcome is that the mismatch with the phenomenological
window for $\beta^*$ cannot be explained by finite-size effects — and, per
O12's corrective revision, cannot be explained by a central-coordinate
mechanism either, since the observable is exactly, algebraically blind to
$\gamma$.

No numeric $\beta^*$ value is propagated from O13's own $\hat\delta_{\mathrm{exact}}$
sequence. O12's revision shows this construction carries several structurally
distinct quantities — the finite-$q$ fitted slope, the unfolded intrinsic
exponent $\delta_{\mathrm{exact}}=3$, and a saturation-scale scaling function —
none of which derives the historical reciprocal equality. O6 supplies only its conditional upper bound
and a countermodel to equality. The independent observable mismatch cannot repair that implication.

The paper shows that:

- no upward drift toward the historical comparison range occurs
- improved statistics reinforce the discrepancy
- the observable distinctions are structural; none derives a physical rate

# Requalification of the δ–β* Tension

O13 reclassifies the tension identified in O12:

- not a finite-size artefact (**S1 rejected**)
- not a central-coordinate effect either — O12's correction proves $\gamma$
  contributes nothing to this observable, at every prime including the ones
  tested here
- the historical reciprocal equality is not derived even in the scalar setting
- the distinct exact-block regimes and shell-size normalisation remain additional issues;
  choosing among them does not derive a physical rate

# Relation to Previous Steps

O13 preserves all previous structural results:

- spectral admissibility (Step 1)
- binary-polyhedral maximality (Step 2)
- ADE stratigraphy (Step 3)
- ordering via O1
- amplification via O3
- structural bound via O4
- admissible-frontier dynamics via O5
- saturation of the O6 Steinberg-matrix fingerprint within a few BFS radii
- capacity formulation via O7
- geometric obstruction via O8
- polynomial-growth resolution via O9
- algorithmic obstruction via O10
- proxy-level extraction via O11
- exact Weil-block regime via O12

It does not modify these steps,
but tests their **asymptotic compatibility**.

# Conceptual Structure

O13 completes the following chain:

1. Observable defined (O7)
2. Geometry resolved (O9)
3. Representation adapted (O11)
4. Exact regime identified (O12)
5. Asymptotic behaviour tested (O13)

The programme now establishes:

- the exact observable is correctly defined
- the exact exponent is reliably measurable
- the asymptotic trend is downward, toward the now-exact value $\delta_{\mathrm{exact}}=3$
- the finite-prime measurements do not drift upward toward the historical comparison range
- no physical tension is derived from the reciprocal equality: that implication already fails
  under the scalar premises, independently of regime choice

# What O13 Resolves

O13 provides:

- a direct test of the finite-size hypothesis
- a falsification of its strong form
- a robust asymptotic trend for $\delta_{\mathrm{exact}}$
- a precise localisation of the structural gap

# Residual Open Problem

No choice among the finite-window slope, unfolded exponent or saturation-scale function derives
the historical reciprocal prescription. O6's countermodel refutes the scalar implication already;
the observable and normalisation mismatches are additional issues.

# Open Directions

1. **Independent capacity-to-rate construction (O13-O1)**
   Supply a growth carrier, account for shell-size versus block-dimension normalisation, and
   independently derive a rate-selection law consistent with the scalar bound and countermodel.

2. **Scaling exponent α (O13-O2)**  
   Derive the correction law in:
   \[
   \delta(q) = \delta_\infty + \frac{a}{q^\alpha}
   \]
   from the combinatorial shell-growth/saturation-depth mechanism of O12,
   not from any central-phase effect

3. **Second-seed validation (O13-O3)**  
   Quantify inter-seed variability at $q \in \{151, 211\}$

4. **Larger-prime extension**  
   Empirically confirm the fitted slope's continued convergence toward the
   now-exact value $\delta_{\mathrm{exact}}=3$

5. **Analytical derivation of δ — resolved by O12**  
   The exponent is derived from Heisenberg shell growth and the block
   saturation-depth law, not from metaplectic structure, which plays no role
   in this observable

# Status

This framework is now:

- beyond the saturating fixed fingerprints of **O5–O6**
- free of geometric obstruction (**O8 → O9**)
- free of representation obstruction (**O10 → O11 → O12**)
- tested asymptotically (**O13**)

It does not assume:

- convergence toward the historical comparison range
- equivalence between proxy and exact observables
- validity of the historical reciprocal equality, even in the scalar setting

# Repository Structure

```text
paper/
├── out/      # Compiled O13 PDF
├── tex/      # LaTeX sources
└── README.md
```
# Citation

If you reference this work, please cite:

J. Beau, Asymptotic Stability of Exact Weil-Block Capacity on Heisenberg Graphs:
Extended Prime Range, Variance Reduction, and Requalification of the δ–β* Tension,
Zenodo, 2026.

# Acknowledgements

Portions of the derivations, conceptual synthesis, numerical strategy,
and editorial refinement benefited from iterative interactions with
large language models used as analytical assistants.
All theoretical results, computations, and interpretations remain the
sole responsibility of the author.

# Contributions

This repository is intended as a research reference.

Critical feedback, independent verification, alternative implementations
of exact Weil-block tracking, and asymptotic extensions to larger primes
are welcome.

Please open an issue to discuss conceptual points,
technical details, or possible extensions.
