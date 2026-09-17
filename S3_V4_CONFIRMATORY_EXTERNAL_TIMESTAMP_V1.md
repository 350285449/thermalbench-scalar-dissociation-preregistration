# S3 V4 Confirmatory External Timestamp V1

This public GitHub commit records a prospective external hash commitment for the finalized S3 V4 confirmatory role-binding study before confirmatory collection begins.

## Frozen identities

- External preregistration package SHA-256: `476ae9ac56fccdf19811bdcfc76864f50cc1e435c954fdc1b7f58c03e2551e7b`
- Final freeze root SHA-256: `29ba956a585776e5fa65960fe82b58d8bb0b0750c9da952a4ea682438b4b52c0`
- Request-population commitment root: `5f1ffd871228fec7e864fca168c9e391e6d65b31861c8e602d0c49a9b44ad26b`

## Frozen confirmatory population

- Independent base selections: `219`
- Logical rows: `127458`
- Frozen confirmatory requests: `764748`
- New random selection after repair: `NO`

## Pre-collection state at this public commitment

- `MODEL_CALLS = 0`
- `HELD_OUT_REQUESTS_EXECUTED = 0`
- `STARTED_SCIENTIFIC_REQUEST_COUNT = 0`
- `CONFIRMATORY_COLLECTION_AUTHORIZED = NO`
- Final preauthorization freeze status: `PASS`

The corrected population preserves the original 219 prospective selections; the earlier pre-execution materialization affected by the generator defect was formally invalidated before any scientific model execution. The corrected freeze passed pair-invariance, model-visible leakage, execution-order, clean-root, and offline integrity checks before this commitment.

This GitHub commit is used as an external public timestamp/hash commitment. GitHub is not asserted to be a formal preregistration registry. The cryptographic identities above bind the exact locally frozen preregistration package, final freeze root, and request population.
