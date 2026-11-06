# API and AI production free-tier tracker

Weekly advisory research into free plans, API quotas, model availability, commercial-use terms, and restrictions for AI video, image, audio, voice, writing, and editing.

**Advisory only:** do not change API keys, billing, provider settings, connected accounts, or repository files automatically.

## Priority providers
- Google Gemini API / AI Studio
- Cloudflare Workers AI
- Hugging Face Inference Providers
- Other providers only when they offer a concrete production advantage.

## Record for each model/service
Provider/product; exact model/endpoint; capability; free allocation and reset period; RPM/TPM/RPD and concurrency; region and billing eligibility; commercial-use terms; data handling; watermark/resolution/duration/export limits; overage pricing; changes since last check; date verified; official source URLs; recommendation.

## Weekly procedure
1. Check official pricing, rate limits, model availability, terms, and release notes.
2. Confirm differences by model, region, tier, or project.
3. Compare with the prior report; do not label unchanged facts as new.
4. Separate confirmed changes from ambiguous claims and community reports.
5. Assess impact on practical production workflows.
6. Recommend a low-cost route without activating paid services.

## Initial snapshot — checked 2026-11-06
| Provider | Published free offer / limit | Qualification | Official source |
|---|---|---|---|
| Gemini API | Free tier for selected models | Limits depend on model/project; check AI Studio. Free-tier data-use terms differ from paid tier. | https://ai.google.dev/gemini-api/docs/pricing ; https://ai.google.dev/gemini-api/docs/rate-limits |
| Cloudflare Workers AI | 10,000 Neurons/day on Workers Free | Resets 00:00 UTC; some models require paid billing method. | https://developers.cloudflare.com/workers-ai/platform/pricing/ |
| Hugging Face Inference Providers | $0.10 monthly credit for Free users | Subject to change; use beyond credits is not free. | https://huggingface.co/docs/inference-providers/pricing |

This is a dated snapshot, not a guarantee. Recheck before production.

## Weekly report
### Summary
Meaningful changes; best new free option; reduced/removed limits; quality-impacting changes; risks requiring manual verification.

### Comparison
| Provider/model | Task | Free quota | Quality/limits | Commercial use | Region/billing | Change | Recommendation |

### Suggested production routing
Writing/planning; images; video; voice/speech; sound/music; editing/subtitles.

### Approval-required actions
List proposed account, billing, key, repository, or workflow changes. Never execute them automatically.