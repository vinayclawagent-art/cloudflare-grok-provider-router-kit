# Provider Router Post-Trial Debrief Template

Status: template-ready; no validation proof recorded yet.

Use this after the [[Provider Router Trial Packet]] and [[Provider Router Promotion Decision Card]] have been filled for one real workflow. It keeps the evidence review separate from the decision gate so the package can improve without overstating what happened.

## 1. Trial identity

- Workflow / repo / product surface:
- Date:
- Operator:
- Reviewer:
- Linked trial packet:
- Linked evidence preset:
- Linked promotion decision card:

## 2. Route outcome summary

| Question | Evidence-backed answer |
| --- | --- |
| What request shape was routed? |  |
| Which providers/models were compared? |  |
| What routing rule was actually used? |  |
| What latency/cost/quality tradeoff was observed? |  |
| What failure or fallback behavior appeared? |  |
| What human-review note changed the decision? |  |

## 3. Keep / change / remove

- Keep in the recipe:
- Change before next run:
- Remove or avoid:
- Missing measurement to add:

## 4. Reusable-route claim check

Mark only one:

- [ ] Promote route pattern — evidence is strong enough for repeated use in the same workflow class.
- [ ] Workflow-specific only — keep this as a local recipe, not a general rule.
- [ ] Iterate recipe — revise route criteria and run again.
- [ ] Hold — evidence is incomplete or the route is not worth repeating.

## 5. Follow-up patch queue

- [ ] Patch README with a source-backed lesson.
- [ ] Patch prototype checklist fields if the trial exposed missing measurements.
- [ ] Patch skill draft only if the same rule is likely to recur.
- [ ] Link this debrief from the improvement loop.

## Guardrail

Do not fill this from memory. Every claim above should point to a packet field, log, cost/latency screenshot, evaluator note, or diff from the real workflow.
