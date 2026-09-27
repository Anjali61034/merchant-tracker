# Escalation Log Template — Merchant Onboarding

> Use this table to log any onboarding issue that needs follow-up, manager attention, or product escalation.

| Date | Merchant ID | Issue Category | Description | Root Cause | Resolution | TAT (hours) | Status |
|------|-------------|----------------|-------------|------------|------------|--------------|--------|
| 2026-09-27 | MCH-001 | Product | Ad rejected 3 times — image text >20% | Merchant provided cluttered product photo | Re-shot clean photo, resubmitted | 4.5 | Resolved |
| 2026-09-27 | MCH-005 | Tech | WhatsApp OTP not received | SMS gateway delay | Resent OTP, verified manually | 1.0 | Resolved |
| 2026-09-27 | MCH-008 | Sales Handoff | Merchant says agent promised ₹0 budget | Miscommunication during handoff | Clarified minimum ₹100/day, got acceptance | 12.0 | Open |
| 2026-09-27 | MCH-003 | Other | Shop closed for renovation — can't take photos | Seasonal closure | Rescheduled photo shoot next week | — | Pending |

## Category Definitions

- **Product** — AI tool / ad product bug, rejection, creative issue
- **Tech** — Login, OTP, API, dashboard not loading
- **Sales Handoff** — Promise mismatch between sales & onboarding teams
- **Other** — Merchant unavailable, documentation missing, etc.

## TAT SLA

| Priority | Target TAT |
|----------|------------|
| P1 — Merchant unable to operate | 2 hours |
| P2 — Campaign delayed | 8 hours |
| P3 — Minor query | 24 hours |

## Status Values

`Open` → `In Progress` → `Resolved` → `Closed`

Use `Escalated` if issue needs manager/product team involvement.
