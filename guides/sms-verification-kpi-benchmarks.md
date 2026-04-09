# SMS Verification KPI Benchmarks Guide

Use this guide as a directional baseline for OTP verification operations.

## Core KPIs

- verification success rate
- average time to receive code
- activation timeout rate
- refund rate (no-code scenarios)
- retries per successful verification
- support ticket rate per 1,000 activations

## Directional benchmark ranges

| KPI | Healthy Range | Watch Range | Risk Range |
| --- | --- | --- | --- |
| Verification success rate | 80% to 95% | 65% to 79.9% | < 65% |
| Avg time to receive code | 20s to 90s | 91s to 180s | > 180s |
| Activation timeout rate | 2% to 8% | 8.1% to 15% | > 15% |
| Refund rate | 1% to 6% | 6.1% to 12% | > 12% |
| Retries per success | 1.0 to 1.4 | 1.41 to 1.9 | > 1.9 |

## Interpretation tips

- High timeout rates usually indicate country mismatch or platform-side blocking
- Rising retries with flat success often indicate low number quality tiers
- High refunds concentrated in one platform/country suggest routing or policy issues

## Weekly review framework

1. Compare current week vs trailing 4-week average
2. Break down by platform, country, and price tier
3. Flag segments crossing risk thresholds
4. Create one testable improvement hypothesis per weak KPI

## Improvement playbook by KPI

- Verification success: enforce IP-country checks, prioritize stronger number pools
- Time to code: optimize provider routing and surface realistic wait timers
- Timeout rate: improve retry guidance and platform/country recommendations
- Refund rate: detect low-performing routes early and block known-failing combos
