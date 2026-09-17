# S3 V4 Persistent Worker Binding — External Timestamp V1

This public GitHub commit records the prospective binding of the qualified persistent S3 V4 worker before scientific collection resumes at execution ordinal 2.

## Bound identities

- Operational amendment SHA-256: `ed61461ad39bf25d61fdd1443b013d0e744452f646ccb78b8aea99a06f54d321`
- Qualified instrumented runtime bundle SHA-256: `1057368f1ad312b2f3678ffc36d5ea4c27e76287cf6d2874fa02117bc6b77bd2`
- Qualified persistent worker path: `s3_role_binding/production_collector_v1/persistent_worker_v1.py`
- Qualified persistent worker SHA-256: `fcc6662521e543803f45ee3b3bef5a0afb4703326d50f6b6d54eb18f533e8bd6`
- Persistent worker binding addendum SHA-256: `de04ef49bc109f1d145ce6b4e3d38e80b0f6efa25e11e7b0c2701160caa6db32`

## Qualification provenance

The worker is bound to the qualification that established:

- old frozen fresh-process vs new instrumented fresh-process equivalence: `PASS`;
- configuration 1 persistent equivalence: `PASS`;
- configuration 2 persistent equivalence: `PASS`;
- configuration 3 persistent equivalence: `PASS`;
- generated-token-ID mismatches: `0`;
- cached-prompt-token violations: `0`;
- reset violations: `0`;
- state-leakage violations: `0`;
- persistent synthetic throughput: `6.356 requests/second`.

## Scientific state at this timestamp

- Scientific requests already committed: `2` (execution ordinals 0 and 1).
- Next execution ordinal: `2`.
- Ambiguous scientific requests: `0`.
- No additional scientific held-out requests were executed during persistent-runtime or persistent-worker qualification.
- Scientific collection remains paused pending replacement execution authorization that binds this worker identity.

## Original experiment commitments

- Final freeze root SHA-256: `29ba956a585776e5fa65960fe82b58d8bb0b0750c9da952a4ea682438b4b52c0`
- Request-population commitment root: `5f1ffd871228fec7e864fca168c9e391e6d65b31861c8e602d0c49a9b44ad26b`
- External preregistration package SHA-256: `476ae9ac56fccdf19811bdcfc76864f50cc1e435c954fdc1b7f58c03e2551e7b`
- Original freeze timestamp commit: `fa20b099c2e91c6d9685f147b0d43857fbb6a21e`
- Persistent-runtime amendment timestamp commit: `8f3f393f24bf41559eeee2378b56f2671ae2e71a`

This commit is an external public timestamp/hash commitment. GitHub is not asserted to be a formal preregistration registry.