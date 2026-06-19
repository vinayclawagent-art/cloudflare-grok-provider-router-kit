# Provider Router Evidence Quality Rubric

Use this after the next real provider-routing trial to decide whether latency, cost, quality, and fallback proof is strong enough to change package, prototype, or skill wording. This is a blank rubric; it does not claim route validation has happened.

Source package: [[Cloudflare Grok Provider Router Kit]]

## Trial reference
- Trial packet: [[Provider Router Trial Packet]]
- Handoff checklist: [[Provider Router Trial Handoff Checklist]]
- Evidence preset: [[Real Workflow Evidence Preset - Provider Router]]
- Promotion card: [[Provider Router Promotion Decision Card]]
- Debrief: [[Provider Router Post-Trial Debrief Template]]
- Date/run:
- Operator:
- Real workflow/task:
- Evidence links:

## Rubric

| Claim to support | Minimum acceptable proof | Score 0-2 | Notes / evidence link |
|---|---|---:|---|
| Request shape is representative | Real prompt/input type, modality, and success criteria are recorded before provider choice |  |  |
| Candidate providers are comparable | Same task is tested across candidate route(s), with model IDs and gateway settings captured |  |  |
| Latency/cost data is usable | Timestamped latency and cost/token details are captured for each route or explicit unavailable fields are noted |  |  |
| Quality tradeoff is human-reviewed | Human evaluator records quality pass/fail and why the chosen route is acceptable |  |  |
| Fallback behavior is known | Error/timeout/degradation path is tested or the missing fallback test is called out as a blocker |  |  |
| Reusable route wording is justified | Any README/prototype/skill wording cites exact evidence rows and limits scope to the tested workflow |  |  |

Scoring guide:
- 0 = missing or speculative.
- 1 = partial evidence; keep as workflow-specific or iterate.
- 2 = source-backed and specific enough for a narrow reusable route claim.

## Decision gate
- Total score:
- Minimum bar met? (no critical row at 0, no fabricated proof): yes/no
- Recommended action: promote route / workflow-specific only / iterate recipe / hold
- Exact patches allowed by evidence:
  - README:
  - Prototype:
  - Skill draft:
- Claims explicitly **not** allowed yet:

## Follow-up queue
- [ ] Patch only evidence-backed route wording.
- [ ] Add a filled example only if logs and measurements can be linked safely.
- [ ] Keep untested provider/generalization claims in backlog language.
