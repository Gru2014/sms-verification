# Activation Troubleshooting Runbook Template

Use this template when a user reports "code not received."

## Case details

- Case ID:
- User ID:
- Platform/service:
- Selected country:
- Number type: one-time / rental
- Price tier:
- Time of request:

## Step 1: Fast triage (first 2 minutes)

- [ ] Confirm activation is still within valid time window
- [ ] Confirm user entered correct number format
- [ ] Confirm IP region matches number country
- [ ] Confirm target platform is currently healthy (no outage)

## Step 2: Retry decision

- [ ] If one-time and no SMS, decide cancel + rebuy path
- [ ] If rental, trigger "request another SMS" action
- [ ] Recommend higher price tier when repeated failures occur
- [ ] Recommend alternative country if platform blocks are suspected

## Step 3: Resolution logging

| Attempt | Action | Result | Time to SMS | Notes |
| --- | --- | --- | --- | --- |
| 1 |  |  |  |  |
| 2 |  |  |  |  |
| 3 |  |  |  |  |

## Step 4: Outcome

- Final status: success / refunded / unresolved
- Root cause category: region mismatch / number quality / platform block / unknown
- Follow-up needed:

## Weekly insights rollup

- Top failing platforms:
- Top failing countries:
- Best performing price tiers:
- Recommended policy updates:
