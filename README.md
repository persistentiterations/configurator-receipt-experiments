# CONFIGURATOR Receipt Experiments

Deterministic grid simulations exploring **Emergent Temporal Ordering** via irreversible local state transitions recorded as cryptographic receipts.

Part of the Cognitive Basin / Natural Math research program (Synaptient / cross-model reasoning team).

## Files

- `CONFIGURATOR_v0.3.py` — Hardened version with:
  - Exact rational arithmetic (`fractions.Fraction`)
  - SHA-256 receipt chains (pre-state hash + composite receipt hash)
  - True cross-replay verification
  - Explicit first-divergence locus reporting
  - Cross-grammar structural divergence diagnostics
  - Soft semantic invariant (grid sum)

## Core Claim Tested

A recorded rational **Witness** + deterministic local transition grammar is sufficient to make terminal morphology a causal consequence of the receipt stream. Temporal ordering and identity emerge from the irreversible accumulation of these scars rather than from a global clock.

## Running

```bash
python3 CONFIGURATOR_v0.3.py
```

Requires only the Python standard library.

## Status

v0.3 confirms self-consistency, witness-induced divergence (first divergence at step 50), and grammar-induced structural divergence inside a finite, fully-observed grid. Open hinges remain open-world witness selection and multi-agent merge.
