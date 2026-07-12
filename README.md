This repository contains the source of the **O13** Cosmochrony paper  
*Asymptotic Stability of Exact Weil-Block Capacity on Heisenberg Graphs:
Extended Prime Range, Variance Reduction, and Requalification of the δ–β* Tension*.

This work extends the **spectral admissibility sub-programme** by testing the
finite-size hypothesis left open in **O12**, through an extension of the exact
Weil-block computation to larger primes.

While **O12** established that the exact Weil projection yields a higher decay
exponent than the proxy and identified a tension with the phenomenological
target for $\beta^*$, it left open whether this mismatch could be explained
as a finite-size effect.

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
toward the phenomenological target range at larger primes.

Starting from:

- the O7 capacity observable $\Sigma_n$
- the O9 Heisenberg graph setting
- the O11 proxy-level extraction
- the O12 exact Weil-block observable

the analysis shows that:

- the sequence of exact exponents
  \[
  \hat\delta_{\mathrm{exact}} = 4.42,\,4.80,\,4.52,\,4.27,\,3.59
  \]
  at $q \in \{29,61,101,151,211\}$ exhibits a **strict monotone decrease**
  from $q = 61$ onward
- the measurement quality improves with $q$:
    - fitting window length increases from 4 to 11 points
    - inter-block variance decreases from $V_n^{\max} = 5.20$ to $0.30$
    - $R^2 > 0.993$ throughout
- condition (E2) is satisfied at $q \geq 151$, establishing **block-by-block
  universality**
- no fitting strategy produces $\delta_\infty > 5.0$

Thus:

- the exponent decreases precisely where the measurement becomes most reliable
- the observed trend is not a numerical artefact
- the finite-size hypothesis is **ruled out in its strong form**

# Structural Role of O13

O13 performs the decisive test left open by O12:

- **O11**: proxy-level extraction
- **O12**: exact Weil-block extraction and tension identification
- **O13**: asymptotic test and falsification of the finite-size explanation

O13 is the first step where the discrepancy between theory and phenomenology
is shown to be **structural rather than numerical**.

# What O13 Adds

O13 introduces several decisive advances:

- extension of the exact computation to larger primes
- a **monotone decreasing regime** of $\hat\delta_{\mathrm{exact}}$
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
window for $\beta^*$ cannot be explained by finite-size effects.

Using the structural relation:
\[
\beta^* = \frac{1}{\delta + \tfrac12},
\]
the observed values imply:
\[
\beta^* \approx 0.19\text{--}0.26,
\]
well above the target range $(0.09, 0.13)$.

The paper shows that:

- no upward drift toward the target range occurs
- improved statistics reinforce the discrepancy
- the mismatch is therefore **structural**

# Requalification of the δ–β* Tension

O13 reclassifies the tension identified in O12:

- not a finite-size artefact (**S1 rejected**)
- but a **structural mismatch** in the exact observable (**S2**)

The source of the mismatch is identified as:

- the presence of the central coordinate $\gamma$ in the exact observable
- the normalisation of $\Sigma_n^{(c)}$ by $|S_n|$
- the absence of these effects in the proxy-level derivation of $\delta \mapsto \beta^*$

# Relation to Previous Steps

O13 preserves all previous structural results:

- spectral admissibility (Step 1)
- binary-polyhedral maximality (Step 2)
- ADE stratigraphy (Step 3)
- ordering via O1
- amplification via O3
- structural bound via O4
- admissible-frontier dynamics via O5
- no-go via O6
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
- the asymptotic trend is downward
- the mismatch with phenomenology is intrinsic

# What O13 Resolves

O13 provides:

- a direct test of the finite-size hypothesis
- a falsification of its strong form
- a robust asymptotic trend for $\delta_{\mathrm{exact}}$
- a precise localisation of the structural gap

# Residual Open Problem

The remaining problem is now clearly identified:

- the mapping $\delta \mapsto \beta^*$ is not valid in the exact-block setting

The task is to:

- re-derive the relation using the exact observable
- incorporate the contribution of the central phase
- understand the role of block normalisation

# Open Directions

1. **Exact-block δ → β* relation (O13-O1)**  
   Derive the structural mapping in the exact Weil setting

2. **Scaling exponent α (O13-O2)**  
   Derive the correction law in:
   \[
   \delta(q) = \delta_\infty + \frac{a}{q^\alpha}
   \]

3. **Second-seed validation (O13-O3)**  
   Quantify inter-seed variability at $q \in \{151, 211\}$

4. **Larger-prime extension**  
   Confirm persistence of the decreasing trend

5. **Analytical derivation of δ**  
   Connect the exponent to metaplectic structure and BFS geometry

# Status

This framework is now:

- free of algebraic obstruction (**O6**)
- free of geometric obstruction (**O8 → O9**)
- free of representation obstruction (**O10 → O11 → O12**)
- tested asymptotically (**O13**)

It does not assume:

- convergence toward the phenomenological target
- equivalence between proxy and exact observables
- validity of the O7 relation in the exact setting

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
