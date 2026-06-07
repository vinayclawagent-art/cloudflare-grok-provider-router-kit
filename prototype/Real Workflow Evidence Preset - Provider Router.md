# Real Workflow Evidence Preset - Provider Router

Package: [[Cloudflare Grok Provider Router Kit]]
Loop: [[Cloudflare Grok Provider Router Kit Loop]]
Prototype: [[Artifacts/Prototypes/cloudflare-grok-provider-router-kit/index.html|Provider Router Recipe Builder]]
Source: https://x.com/xai/status/2062294202625696081

## Purpose

Use this preset when the provider-router prototype is trialed on one real VinClawLabs workflow. It captures routing evidence for Cloudflare AI Gateway + Grok without pretending a production route has already been validated.

## Trial scope

| Field | Value |
| --- | --- |
| Workflow/request type | _TBD during live workflow_ |
| Candidate providers/models | _TBD_ |
| Routing rule tested | _TBD_ |
| Cloudflare AI Gateway config/link | _TBD_ |
| Owner/evaluator | _TBD_ |
| Decision deadline | _TBD_ |

## Evidence capture checklist

- [ ] Attach the request shape: input modality, latency tolerance, budget ceiling, and quality bar.
- [ ] Record candidate provider/model options and why Grok is included.
- [ ] Capture the routing rule chosen: fallback, cost-tier, multimodal-first, quality-first, or manual override.
- [ ] Record observed latency/cost/quality notes from the real run.
- [ ] Record failure behavior: timeout, refusal, tool error, gateway error, or unacceptable output.
- [ ] Decide whether the route is `promote`, `pilot-only`, `hold`, or `retire`.

## Copyable filled-example block

```markdown
### Provider-router evidence - <workflow name>

- Request shape: _TBD during live run_
- Candidate models/providers: _TBD_
- Selected route: _TBD_
- Gateway/config reference: _TBD_
- Observed latency/cost/quality: _TBD_
- Failure behavior: _TBD_
- Decision: _promote / pilot-only / hold / retire_
- Follow-up: _TBD_
```

## Promotion gate

Promote this into a reusable router pattern only after one real workflow fills the evidence checklist and produces a route decision with clear latency, cost, and quality tradeoffs.

## Next action

Run the Provider Router Recipe Builder on one real workflow and fill this preset. No validation proof has been invented in this cron improvement.
