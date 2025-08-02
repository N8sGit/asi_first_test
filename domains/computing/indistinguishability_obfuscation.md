# Practical Indistinguishability Obfuscation (iO)

## Classification

[TP] Theoretical Proof / [PM] Process & Methodology

## Description

Indistinguishability obfuscation (iO) is considered a “master primitive” in modern cryptography: a construction of practical iO would yield, often via simple reductions, virtually every advanced cryptographic tool imagined—including functional encryption, traitor tracing, broadcast encryption, deniable encryption, and more. Present candidate schemes are either heuristic, require unrealistically strong assumptions, or incur astronomical overhead (>10¹²× runtime, gigabyte-scale outputs) even for toy circuits.

## ASI Prompt

"Construct an indistinguishability-obfuscation compiler that, given any classical program ≤10 kB in length (≈50 k gates), outputs an obfuscated binary that: (1) runs with ≤10× slowdown compared to the original on commodity hardware, (2) inflates code size by ≤5×, and (3) achieves provable iO security under standard, well-studied assumptions (e.g., polynomial-LWE, SXDH, or similar). Provide formal proofs, security reductions, and a reference implementation."

## Expected Output

1. A formal specification of the iO scheme, including exact parameter choices and cryptographic assumptions.
2. Machine-checked security proofs showing indistinguishability under chosen-ciphertext attack.
3. Source code for a working obfuscator and de-obfuscation runtime, with benchmarks on real programs (e.g., AES, BLAKE3).
4. Performance and security evaluation demonstrating the stated slowdown and size bounds.

## Verification

Independent security experts must verify the proofs and reproduce benchmarks on publicly available test suites. A successful attack distinguishing two functionally equivalent obfuscated programs with non-negligible advantage would falsify the claim; absence of such attacks within a global red-team effort confirms success.
