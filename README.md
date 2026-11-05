# Evidence Freshness Check

Creator: Helix Protocol

Check whether earlier verification still applies after files, configuration, versions, or external state change; identify stale and unverifiable claims.

Read [SKILL.md](SKILL.md) to use the workflow. Place this folder in your agent's documented skill location, or supply the Markdown instructions directly. Automatic discovery and tool access depend on the host. No runtime is required for Free.

| Edition | Included |
| --- | --- |
| Free | Complete core workflow, examples, and synthetic scenario specifications |
| Pro | Local SHA-256 dependency manifests, impact reports, and an explicit reviewed-command rerun mode. The helper compares declared files and does not certify passing tests or deployments. |

## Agensi

- Free listing: not published yet; add the verified URL after approval.
- Pro listing: not published yet; add the verified URL after approval and licensing review.

Direct use of this repository remains available under [MIT](LICENSE). Pro is a separate standalone package. Do not copy private premium source into this public repository to demonstrate it.

## Verification and limits

Read [release readiness](release/READINESS.md) for remaining checks. [Scenario specifications](evals/scenarios.json) are synthetic and are not claims that an agent passed. This workflow cannot guarantee safety, enforce permissions, or establish results inaccessible to the agent.

## Development disclosure

The creator reports testing all five skills and finding them working correctly. Local automated checks are documented in the verification reports.
