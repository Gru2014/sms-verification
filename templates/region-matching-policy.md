# Region Matching and Verification Policy Template

## Policy purpose

Define rules for country selection, IP matching, and retry handling to improve verification success.

## Scope

- Product areas: one-time activations and rental numbers
- Flows covered: number purchase, OTP receive, retry, cancel, refund
- Regions covered:

## Region matching rules

- Primary rule: user IP country should match selected number country
- Fallback rule: if mismatch is unavoidable, provide explicit warning
- High-risk mismatch threshold:

## Exceptions

- Platforms known to tolerate cross-region verification
- Emergency account recovery cases
- Manual support-approved overrides

## Retry and cancellation policy

- Max retries before recommending new number:
- Cancellation allowed after:
- Rental "request another SMS" eligibility:
- Refund eligibility conditions:

## Price-tier guidance

- Low tier: acceptable for non-critical verification
- Mid tier: default recommendation
- High tier: recommended for strict platforms or repeated failures

## Compliance checks

- [ ] IP-country validation is shown before OTP request
- [ ] Failed reason taxonomy is logged consistently
- [ ] Country/platform failure trends reviewed weekly
- [ ] Support scripts reflect current retry policy

## Ownership

- Policy owner:
- Last reviewed:
- Review cadence:
