How to use:
- Keep it concise; fill only sections that apply. Delete unused sections.
- Link issues (#123), ADRs, design docs, and dashboards.
- Prefer actionable, verifiable points over prose.
-->

## Summary
<!-- What & why in 2–3 sentences. Context first. -->

## Type of change
- [ ] Feature
- [ ] Fix
- [ ] Refactor
- [ ] Docs
- [ ] Chore / Build / CI
- [ ] Performance
- [ ] Security

## Linked issues
<!-- e.g., Closes #123, Relates to #456 -->
Closes #

## Context
<!-- Problem statement, constraints, key decision(s). Link ADRs/design docs. -->

## Changes
<!-- Bullet the user-visible or system-level changes. -->
-

## Screenshots / Demos (UI/CLI)
<!-- Before/after images, GIFs, or terminal output with brief captions. -->
**Before:**

**After:**

## Testing
- [ ] Unit tests added/updated
- [ ] Integration tests added/updated
- [ ] E2E / manual QA performed
- [ ] Lint / Typecheck / Build clean

**Test plan (steps + expected/actual):**
1.
2.

**Coverage / results:**
<!-- Attach reports or numbers if relevant. -->

## Backward compatibility / Migrations
- [ ] No breaking changes
- [ ] Breaking change (explain below)

**Migration steps & backout plan (if breaking):**
-

## Performance
- [ ] N/A
- [ ] Benchmarked (numbers below)

| Metric           | Baseline | This PR | Δ  |
|------------------|---------:|--------:|---:|
| p95 latency (ms) |          |         |    |
| Memory (MB)      |          |         |    |
| Build time (s)   |          |         |    |

## Security & Privacy
- [ ] No secrets/credentials committed
- [ ] Access control & auth paths reviewed
- [ ] Handles PII appropriately (collection, storage, logging)
- [ ] Dependency changes audited (`pip-audit` / `npm audit` / `cargo audit`)
- [ ] Logging & observability appropriate
- [ ] Threat model updated (if applicable)

<details>
<summary><strong>ML/AI-specific (fill if applicable)</strong></summary>

### Data & Reproducibility
- [ ] Dataset sources & versions documented
- [ ] Data splits correct; no leakage
- [ ] Seeds fixed; runs reproducible

### Metrics & Quality
- [ ] Baseline vs. PR metrics reported (table/plot)
- [ ] Model card updated

### Fairness & Explainability
- [ ] Bias/fairness checks executed; results noted
- [ ] Explainability reviewed (e.g., SHAP/LIME)

### Federated Learning
- [ ] Aggregation changes (e.g., FedAvg, secure aggregation) described
- [ ] Client sampling / participation rate documented
- [ ] Rounds, LR schedule, early stopping specified
- [ ] Differential Privacy parameters documented (ε/δ, noise, clipping)

### Foundry/Ontology (if used)
- [ ] Ontology entities/relationships impacted listed
- [ ] Permissions / lineage impacts assessed

</details>

## Documentation
- [ ] README / user docs updated
- [ ] ADRs updated/added
- [ ] CHANGELOG entry added

## Deployment & Rollout
- [ ] Feature flag / gradual rollout plan
- [ ] Affected envs: dev / staging / prod
- [ ] Backout plan described

## Risk
<!-- What could go wrong? Mitigations, edge cases, unknowns. -->
-

## Reviewer notes
<!-- How to review: focus areas, file order, quick-start commands, follow-ups. -->
-

## Merge readiness
- [ ] CI is green
- [ ] Required approvals received
- [ ] No blocking TODOs / comments remain

