# dry-roy2

## Before

Recorded 2026-11-06 23:42 PST (2026-11-07 07:42 UTC), right after the first GitOps deploy (app version `b23e02b`).
Radar Checks, namespace `team-dry-roy2`: 0 critical, 0 high, 4 medium, 0 low (1 resource).

Medium:
- automountServiceAccountToken (Security): Deployment/team-dry-roy2/app
- readOnlyRootFs (Security): Deployment/team-dry-roy2/app, container `app`
- missingPDB (Reliability): Deployment/team-dry-roy2/app
- missingTopologySpread (Reliability): Deployment/team-dry-roy2/app
