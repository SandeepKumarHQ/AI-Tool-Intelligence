# Reproducible enterprise AI software evaluation

Assess: problem fit; capability; task success; integration availability; security/permissions; auditability; reliability/failure recovery; latency; costs (inference+ops+people); maintainability; license; portability; vendor lock-in; deployment mode; evidence quality.

Use weighted scores only when the weights and raw evidence are supplied; a subjective score is never a measured benchmark. Distinguish vendor docs from firsthand test runs.

Test record needs tested version/date, hardware/cloud environment, prompts and datasets (sanitized), model/provider, token and network costs where known, reproduction instructions, errors, failures, output artifacts and exact Git commit. Send results via Knowledgebase `kind: experiment` envelope, then publish linked reviewed finding.

Watchlist links back to AI-Radar official releases; revision alert triggers reevaluation rather than silent score update.
