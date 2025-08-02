# The Skolem Problem for Linear Recurrence Sequences

## Classification

[TP] Theoretical Proof

## Description

Given an integer linear recurrence sequence (e.g., the Fibonacci numbers), decide algorithmically whether the sequence ever attains the value zero. While decidable for orders ≤4, the general case remains an open problem in number theory and theoretical computer science, intersecting Diophantine approximation and logic.

## ASI Prompt

"Provide a complete proof resolving the Skolem Problem: for any integer linear recurrence sequence of arbitrary finite order, present (a) a decision procedure that determines whether zero occurs in the sequence, along with rigorous correctness and complexity analysis, OR (b) a proof that no such algorithm can exist (undecidability). Include all lemmas, reductions, and, where applicable, constructive bounds on index sizes."

## Expected Output

1. Formal statement of theorem (decidability or undecidability) with precise definitions.
2. Complete, peer-review-ready proof with all intermediate lemmas.
3. If decidable, pseudocode and complexity bounds; if undecidable, reduction from a known undecidable problem.
4. Machine-checked verification in a proof assistant (e.g., Coq/Lean) covering all steps.

## Verification

Independent experts in number theory and computability must validate the proof and its formalization. For a positive algorithmic result, reference implementations must correctly decide benchmark instances up to high order and coefficient size.
