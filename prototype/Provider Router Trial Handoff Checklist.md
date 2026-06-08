# Provider Router Trial Handoff Checklist

Package: [[../../Generated-Packages/Cloudflare Grok Provider Router Kit/README|Cloudflare Grok Provider Router Kit]]
Related preset: [[Real Workflow Evidence Preset - Provider Router]]
Prototype: [[index.html|Provider Router Recipe Builder]]
Status: ready for the next real provider-routing trial; no latency, cost, or quality proof has been invented.

## Purpose

Turn the provider-router evidence preset into a single preflight and post-run handoff so a real VinClawLabs workflow can be tested without losing source context or over-claiming results.

## 1. Preflight before using the builder

- [ ] Name the workflow being routed, or use a private alias if needed.
- [ ] Capture the request shape: modality, input size, expected output type, and failure tolerance.
- [ ] Pick at least two candidate providers/models to compare.
- [ ] Define the primary routing criterion before the run: `cost`, `latency`, `quality`, `context window`, `multimodal support`, or `fallback reliability`.
- [ ] Open `index.html` and generate the route recipe/checklist.
- [ ] Fill [[Real Workflow Evidence Preset - Provider Router]] during the run, not afterward from memory.

## 2. Trial capture fields

| Field | Fill during real trial |
| --- | --- |
| Workflow/request name |  |
| Request shape |  |
| Candidate provider/model A |  |
| Candidate provider/model B |  |
| Routing criterion |  |
| Observed latency |  |
| Observed cost/token notes |  |
| Observed output-quality notes |  |
| Failure/fallback behavior |  |
| Reviewer/evaluator |  |

## 3. Route decision gate

Choose exactly one after review:

- [ ] **Promote route** — evidence supports a reusable default or fallback rule.
- [ ] **Workflow-specific only** — route works for this workflow but is not general enough.
- [ ] **Iterate recipe** — builder/preset needs another field before reuse.
- [ ] **Hold** — evidence is inconclusive or the route is not worth operationalizing.

Decision rationale:

> 

## 4. Follow-up update checklist

- [ ] Update [[Real Workflow Evidence Preset - Provider Router]] with the real route evidence.
- [ ] Add before/after notes only if both sides were actually observed.
- [ ] Update [[../../Generated-Packages/Cloudflare Grok Provider Router Kit/README|package backlog]] with the selected route decision.
- [ ] Update [[../../Improvement-Loops/Cloudflare Grok Provider Router Kit Loop|improvement loop]] `next_focus` based on the decision.
- [ ] Do not promote a Hermes skill until at least one filled preset supports repeatable route behavior.
