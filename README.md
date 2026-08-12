# shinka — Actor Evolution Scheduler

Canonical repository: `etzhayyim/actor-shinka`.

Shinka schedules bounded evolution and repair work for Etzhayyim actors. EDN
contracts and manifests are canonical; protocol projections live under `wire/`.

Within the Tamaki artificial organism, shinka is the evolution-scheduling organ.
It may measure coverage, rank typed candidates, and propose actor-scoped work.
It cannot rewrite another actor's identity or policy, publish as that actor, or
cause external effects without that actor's scoped capability, review, canary,
and promotion gates. Model output remains a candidate, never governance.

Run the CLJC suite with `clojure -M:test`.
