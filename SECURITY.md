# Security Policy

## Reporting a Vulnerability

Contact: pyramidheadshark (GitHub DM or commit an encrypted note)

Do NOT open a public issue for security vulnerabilities.

## Known Historical Issues

- techcon_infra_yac: YC API token in git history (pre-2026-03-17). Token has been rotated.

## Incident Response

In the event of an infrastructure incident, follow the runbook in `techcon_hub`:

```
knowledge/standards/incident-response-runbook.md
```

**Severity classification:**
- P0 — Production down or data loss (controller VM destroyed, DB corruption)
- P1 — Service degraded, significant impact (GPU worker offline, monitoring dark)
- P2 — Partial failure, workaround available
- P3 — Non-urgent, no user impact

**Contacts:** pyramidheadshark (primary), Chaberis (monitoring/ops)

Post-incident: create report in `knowledge/incidents/YYYY-MM-DD-<name>.md` within 24 hours.
