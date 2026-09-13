# Continuous-estimand amendment (2026-09-13)

The original categorical affine-match primary endpoint is preserved in the
draft and is now secondary/descriptive. Excluded V3/V3R1 development produced
1 affine classification among 71 valid finalized responses, making that event
near-degenerate. **The continuous primary estimand was designed after
inspecting excluded development data and before any held-out observation
existed.** No held-out request has occurred.

The primary response field is the arithmetic mean of the two parsed finite
forecast values. This symmetric scalar preserves within-response dependence;
the fixture, not either query coordinate, is the inferential unit.

Primary finite-difference estimands are, for each pinned model configuration:

- `OUTCOME`: mean forecast under the +11 displayed-second-outcome
  counterfactual minus its matched semantic-canonical coherent control.
- `QUERY`: mean forecast under query list B minus list A, averaged over the
  four representation/wording variants while history is fixed.

There is no primary action effect: the held-out design has no independent
action manipulation with outcome and query held fixed. The two retained arms
are identifiable: outcome tracking predicts +11 for OUTCOME and zero QUERY;
query echo predicts zero OUTCOME and the mean-query displacement for QUERY;
task-consistent forecasting predicts zero OUTCOME and the oracle mean change
for QUERY; invariant behavior predicts zero for both. Exact-match labels and
continuous distances to candidate predictions are secondary/descriptive.

The primary family contains six two-sided tests (three configurations by two
estimands), Holm-adjusted at familywise alpha .05. Direct model-by-estimand
interactions are secondary. Valid paired members are required; no generated
response is imputed. Invalid, missing, ambiguous, prepared-not-dispatched, and
not-started identities remain in all-attempted completion tables. Potentially
dispatched identities are never retried. A cross-model contrast requires the
prespecified members for all compared configurations; fixture-complete results
are a sensitivity analysis.

The design uses 240 independent fixtures, one nested seed repetition, and
9,360 requests. It is precision-oriented: 240 fixture-level paired contrasts
per model/estimand are retained without using a development mean as an SESOI.
Development variance is used only for implementation/range validation, never
for a directional claim or endpoint selection.
