# Provider Router Promotion Decision Card

Package: [[../../Generated-Packages/Cloudflare Grok Provider Router Kit/README|Cloudflare Grok Provider Router Kit]]
Prepared: 2026-06-09

## Purpose
A fillable promote / workflow-specific / iterate / hold gate for the next real provider-routing trial. Complete it only after the handoff checklist, trial packet, and evidence preset have real workflow evidence.

## Required evidence before decision
- [ ] Real workflow or product request is named.
- [ ] Candidate providers/models are listed with why each was considered.
- [ ] Routing rule or fallback path is written before judging the output.
- [ ] Observed latency, cost, quality, and failure behavior are captured.
- [ ] Human reviewer notes whether the route was better than the default provider path.

## Decision options
Choose exactly one:

- [ ] **Promote route pattern** — reusable enough to encode in a provider-router recipe or skill draft.
- [ ] **Workflow-specific only** — useful for this task, but too narrow for a general route.
- [ ] **Iterate recipe** — evidence exposed missing provider, fallback, cost, latency, or quality fields.
- [ ] **Hold** — no clear win or evidence is incomplete.

## Decision record
| Field | Fill after trial |
|---|---|
| Selected option | |
| Evidence links | |
| Winning provider / fallback | |
| Why default routing was insufficient | |
| What to change before next trial | |
| Owner / next date | |

## Follow-up patch list
- [ ] Link this card from the filled Provider Router Trial Packet.
- [ ] Update package and loop changelogs with the real decision.
- [ ] Mirror any filled evidence into the isolated repo.
- [ ] Promote, pilot, iterate, or hold only according to the selected option above.
