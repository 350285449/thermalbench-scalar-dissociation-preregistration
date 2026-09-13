# S1 synthetic validation V1

The unchanged hardened production analyzer
`scalar_dissociation_heldout_continuous_v1.py` (SHA256
`4B6C232F59441D281F935AB89A10CE816437A24866A9DF077E32A55C7896D509`)
was exercised by real request-level synthetic schedules and evidence.
`T01--T18` remains 18/18 PASS; `S01--S24` is 24/24 PASS.

The deterministic harness constructs every required CORE, COUNTERFACTUAL and
QUERY_EXTENSION identity, sends it through production ingestion,
reconciliation, schedule-derived pairing, seed aggregation, fixture effects,
interactions, bootstrap, primary statistics, Holm, and missingness reporting.
It covers null, positive/negative, simultaneous, noisy, nested-seed,
multi-coordinate, missing/invalid/ambiguous, model-pair, order, sign, scale,
invalid-design, OTHER-label, and zero-pair cases. The complete expected and
observed record is in `heldout_continuous_v1/synthetic_validation.json`.

The adversarial certificate includes duplicate/unknown/mutated/nonfinite input,
wrong role/key, unplanned Holm family, and model-label checks. Isolated bad
algorithms for duplicate overwrites, seed inflation, nonfinite acceptance,
positional pairing, sign reversal, noncanonical bootstrap, unsorted Holm, and
numeric-zero nonestimability are detected by corresponding validation
invariants.

The excluded V3/V3R1 records were also run through the production lifecycle
and pairing path only as DEVELOPMENT_ONLY, NOT_CONFIRMATORY evidence. They
structurally lack the counterfactual/query paired arms, so all primary effects
are NON_ESTIMABLE; the one Llama ambiguous identity is excluded. This does not
alter any estimand or design. Remaining limitation: synthetic validation proves
analysis mechanics, not real held-out model behavior. No model calls occurred.
