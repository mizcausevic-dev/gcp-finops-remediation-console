# gcp-finops-remediation-console

Board-readable Kinetic Gain proof repo for **GCP** platform and company signal coverage.

## Product thesis

GCP spend issues are difficult to act on when budget alerts, BigQuery cost, owners, and remediation status live in separate systems.

This repo turns that problem into a small, inspectable product surface: synthetic fixture data, a deterministic CLI, a tested scoring model, a JSON report, and a static brief that explains the business and technical value of the signal.

## Buyer and operator fit

- **Primary audience:** Cloud platform leaders, FinOps teams, engineering managers, and CFO operators
- **Signal domain:** Cloud / FinOps
- **Executive question:** Where is this system creating exposure, waste, or decision latency?
- **Product motion:** The product routes budget pressure, unlabeled spend, query-cost spikes, and owner gaps into a single remediation posture.
- **Value architecture:** Leaders can distinguish unavoidable cloud investment from waste, leakage, and governance work that should be automated.

## What this repo proves

- **Normalize:** messy GCP operating evidence is represented as explicit lanes.
- **Score:** risk and evidence depth are measured separately so weak proof is not hidden by high urgency.
- **Route:** each lane has an owner and next action instead of a vague status.
- **Package:** CLI output, tests, JSON report, and static page all tell the same board-ready story.

## Integration boundary

Focus area: GCP billing exports, BigQuery usage, labels, budgets, owner maps, and remediation tickets.

This is synthetic proof only. It does not connect to live GCP tenants, call private APIs, store secrets, publish credentials, or expose customer data.

## Local run

```bash
npm install
npm test
npm run build
npm run demo
```

## Public surface

The generated site is in `site/index.html`. The data report is in `site/report.json`.

## Keywords

- GCP
- BigQuery
- FinOps
- cloud cost
- budget remediation
