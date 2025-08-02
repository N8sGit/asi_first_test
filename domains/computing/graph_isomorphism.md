# The Graph Isomorphism Problem

## Classification

[TP] Theoretical Proof

## Description

Given two finite graphs $G$ and $H$, decide whether there exists a bijection between their vertex sets that preserves adjacency. The decision problem is in NP, yet its precise complexity status remains unresolved: no polynomial-time algorithm nor NP-completeness proof is known. A resolution would sharpen our understanding of the P vs. NP landscape and group-theoretic algorithms.

## ASI Prompt

"Resolve the complexity of Graph Isomorphism. Provide either (a) a deterministic polynomial-time algorithm that decides isomorphism for arbitrary graphs, including full correctness proof and complexity analysis, or (b) a proof that Graph Isomorphism is NP-complete (or otherwise outside P), establishing the necessary reductions and hardness results."

## Expected Output

1. Formal statement of the main theorem (poly-time algorithm or NP-completeness).
2. Complete proof with all lemmas and reductions.
3. Reference implementation (if algorithmic) with empirical complexity benchmarks.
4. Machine-checked verification of proofs in a proof assistant (e.g., Lean or Coq).

## Verification

Peer review by theoretical computer scientists and formal proof checking. For an algorithmic resolution, independent implementations must reproduce stated runtime bounds on standard GI benchmark suites (e.g., iGraph or NAUTY test cases).
