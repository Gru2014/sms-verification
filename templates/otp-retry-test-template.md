# OTP Retry A/B Test Template

## Experiment overview

- Experiment name:
- Owner:
- Start date:
- End date:
- Audience segment:
- Goal metric (verification success rate, time to code, refund rate):

## Hypothesis

If we change **[variable]** from **[control]** to **[variant]**, we expect **[impact]** because **[reason]**.

## Test design

- Variable tested: (single variable only)
- Control approach:
- Variant approach:
- Sample size per variant:
- Randomization method:
- Confidence target: (for example, 95%)

## Guardrails

- Max refund rate:
- Max unresolved case rate:
- Minimum verification success rate:
- Pause criteria:

## Execution checklist

- [ ] Country assignment logic validated
- [ ] Number type (one-time/rental) defined
- [ ] Retry timing logic validated
- [ ] Variant assignment logged
- [ ] Support fallback defined

## Results table

| Metric | Control | Variant | Lift | Notes |
| --- | --- | --- | --- | --- |
| Verification success rate |  |  |  |  |
| Avg time to receive code |  |  |  |  |
| Refund rate |  |  |  |  |
| Retry count per successful verification |  |  |  |  |
| Support tickets per 1,000 activations |  |  |  |  |

## Decision

- Winner:
- Rollout plan:
- Follow-up test idea:
