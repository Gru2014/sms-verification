# SMS Verification Compliance and Abuse Checklist

> Operational guidance only, not legal advice.

## Account and access controls

- [ ] User accounts require verified email
- [ ] Login and payment endpoints are rate-limited
- [ ] Suspicious behavior triggers manual review
- [ ] API/admin actions are logged for audit

## Fraud and abuse prevention

- [ ] Excessive activation attempts per user are throttled
- [ ] Disposable abuse patterns are flagged
- [ ] High-risk services/countries have stricter limits
- [ ] Refund abuse patterns are monitored

## Data handling

- [ ] SMS content retention period is defined
- [ ] Personally identifiable information is minimized
- [ ] Access to activation logs is role-restricted
- [ ] Data deletion and export flows are documented

## Policy transparency

- [ ] Terms clearly define allowed and prohibited use
- [ ] Refund and cancellation policy is published
- [ ] Number reuse limitations are clearly explained
- [ ] Rental behavior and expiry terms are explicit

## Operational governance

- [ ] Compliance owner is assigned
- [ ] Abuse-response playbook is documented
- [ ] Support escalation path is defined for blocked numbers
- [ ] Weekly review of complaints, bans, and refund reasons
