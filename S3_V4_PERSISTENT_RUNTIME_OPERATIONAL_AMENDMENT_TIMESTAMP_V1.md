# S3 V4 Persistent Runtime Operational Amendment — External Timestamp V1

This public GitHub commit records the prospective operational amendment governing S3 V4 confirmatory execution from ordinal 2 onward.

## Amendment identity

- Operational amendment SHA-256: `ed61461ad39bf25d61fdd1443b013d0e744452f646ccb78b8aea99a06f54d321`
- Qualified instrumented runtime bundle SHA-256: `1057368f1ad312b2f3678ffc36d5ea4c27e76287cf6d2874fa02117bc6b77bd2`

## Original frozen experiment identities

- Final freeze root SHA-256: `29ba956a585776e5fa65960fe82b58d8bb0b0750c9da952a4ea682438b4b52c0`
- Request-population commitment root: `5f1ffd871228fec7e864fca168c9e391e6d65b31861c8e602d0c49a9b44ad26b`
- External preregistration package SHA-256: `476ae9ac56fccdf19811bdcfc76864f50cc1e435c954fdc1b7f58c03e2551e7b`
- Original external timestamp commit: `fa20b099c2e91c6d9685f147b0d43857fbb6a21e`

## Execution lifecycle amendment

- Ordinals `0–1`: original frozen fresh-process runtime.
- Ordinals `2–764747`: qualified persistent instrumented runtime with mandatory explicit reset and pre-dispatch empty-state evidence before every request.

The following remain unchanged:

- all 764,748 frozen model-visible request bytes;
- execution order;
- request identities and seeds;
- model weights/configurations;
- scientific hypotheses and endpoints;
- statistical analysis;
- no-retry semantics;
- durable STARTED-before-dispatch semantics;
- storage semantics.

## Qualification result

Persistent-runtime qualification passed for all three frozen configurations:

- old frozen fresh-process vs new instrumented fresh-process equivalence: `PASS`;
- configuration 1 persistent equivalence: `PASS`;
- configuration 2 persistent equivalence: `PASS`;
- configuration 3 persistent equivalence: `PASS`;
- generated-token-ID mismatches: `0`;
- cached-prompt-token violations: `0`;
- reset violations: `0`;
- state-leakage violations: `0`;
- persistent synthetic throughput: `6.356 requests/second`.

## State at this amendment timestamp

- Scientific requests already committed before this amendment: `2` (ordinals 0 and 1).
- Ambiguous scientific requests: `0`.
- No additional held-out scientific requests were executed during persistent-runtime qualification.
- Scientific collection is paused before ordinal `2` pending amendment timestamp binding and replacement execution authorization.

This commit is an external public timestamp/hash commitment for the operational amendment. GitHub is not asserted to be a formal preregistration registry.
