# ThermalBench Scalar Dissociation

## Prospective Three-Model Held-Out Preregistration V1

This repository records the prospective design and executable identity for a
three-configuration held-out scalar-dissociation experiment.

Models/configurations: Qwen3-8B Q4_K_M, Bonsai-8B Q1_0, and
Llama-3.1-8B-Instruct Q4_K_M.

Independent held-out fixtures: 240. Planned held-out model requests: 9,360.

Primary tests: QWEN_OUTCOME, QWEN_QUERY, BONSAI_OUTCOME, BONSAI_QUERY,
LLAMA_OUTCOME, and LLAMA_QUERY. Family-wise error control is Holm, alpha .05.

Registration packet: `S1_SCALAR_DISSOCIATION_REGISTRATION_PACKET_V1.zip`.
SHA-256: `2A04B25E6A4C03597BB99873EC344F89E6F274EB5D26C9ED386B1CD1BFF96242`.

Held-out freeze root SHA-256:
`C8CA019B54E042DB7BBA50B63DA31245F52FC28F7090CA2C2BC5D0C1AD21BEEA`.

At publication preparation: `HELD_OUT_REQUESTS_STARTED = 0` and
`HELD_OUT_EXECUTION_ALLOWED = false`. No post-registration execution
authorization exists. This public prospective registration/timestamp is made
before the first held-out scientific model request; GitHub is not asserted to
be a formal preregistration registry.

The original exploratory/development work preceded this registration. Excluded
development showed the former categorical exact-match endpoint was
near-degenerate; the final prospective endpoints are controlled continuous
OUTCOME and QUERY finite-difference effects. All bound endpoint, multiplicity,
missingness, fixture, model, schedule, and analysis decisions preceded every
held-out response.

## Pre-Collection Materialization and Durable Execution Amendment V1

This amendment preserves the original prospective preregistration and binds a
V5 freeze of the exact 9,360 model-visible request bodies, output schema, and
validated durable execution workflow. Hypotheses, primary estimands, fixtures,
model panel, schedule, and final scientific analysis are unchanged. Collector
validation occurred before request 1; the documented E25 event was
validation-only and had no scientific impact. No held-out scientific request
occurred before this amendment. The public binding metadata is in
`S1_SCALAR_DISSOCIATION_PRECOLLECTION_MATERIALIZATION_AND_EXECUTION_AMENDMENT_V1.json`.
