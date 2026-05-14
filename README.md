# Incident Postmortems

> **Blameless post-incident review documentation following industry-standard RCA formats.**

## Overview

A collection of structured postmortems from production incidents, written using a consistent template. Each report documents the timeline, root cause, contributing factors, and actionable follow-ups to prevent recurrence.

## Postmortems

| # | Incident | File |
| --- | ---------- | ------ |
| 01 | API Gateway Timeout | `postmortems/2026/01-api-gateway-timeout.md` |
| 02 | IAM Misconfiguration — S3 Access | `postmortems/2026/02-iam-misconfig-s3.md` |
| 03 | Database Connection Exhaustion | `postmortems/2026/03-database-conn-exhaustion.md` |
| 04 | Security Group Rollout Failure | `postmortems/2026/04-security-group-rollout.md` |
| 05 | Disk Full — Log Rotation Gap | `postmortems/2026/05-disk-full-logrotate.md` |
| 06 | VPC Peering Outage | `postmortems/2026/06-vpc-peering-outage.md` |

## Template

Use [`postmortems/TEMPLATE.md`](postmortems/TEMPLATE.md) when writing new postmortems.

## Structure

```text
.
├── postmortems/
│   ├── 2026/
│   │   ├── 01-api-gateway-timeout.md
│   │   ├── 02-iam-misconfig-s3.md
│   │   ├── 03-database-conn-exhaustion.md
│   │   ├── 04-security-group-rollout.md
│   │   ├── 05-disk-full-logrotate.md
│   │   └── 06-vpc-peering-outage.md
│   └── TEMPLATE.md
└── docs/
    ├── Incident_Response_Lifecycle.md
    └── maintenance.log
```

---
Maintained by Harrison Vance — Technical Support & Operations