# Daily standup day 3

**Question:** Write a daily stand-up update (yesterday, today, impediment) for three team members on day 3.

### Daily stand-up – day 3

**Karthik (backend)**
- Yesterday: finished the UPI collect-request integration with the sandbox.
- Today: building the webhook that credits the wallet when UPI confirms payment.
- Impediment: the UPI sandbox allows only 50 calls a day and we hit the limit at 4 PM. → Scrum Master to ask the bank for a higher limit.

**Priya (mobile)**
- Yesterday: completed the top-up screen with amount validation (Rs.10 to Rs.10,000).
- Today: start the contact picker for send-money.
- Impediment: none.

**Meena (QA)**
- Yesterday: wrote test cases for top-up success, failure and timeout.
- Today: run them once the webhook is on staging; prepare transfer test data.
- Impediment: staging has no test UPI handles for 20 users. → Karthik will create them after stand-up.

### Impediment log

| # | Raised | Impediment | Impact | Owner | Action | Status |
|---|---|---|---|---|---|---|
| 1 | Day 3 | UPI sandbox limited to 50 calls / day | Top-up and webhook testing stops in the afternoon | Anitha (SM) | Raised with bank's partner team; limit raised to 500 | Closed day 4 |
| 2 | Day 3 | No test UPI handles for 20 users on staging | Cannot test the sprint goal flow | Karthik | Script to create test handles | Closed day 3 |
| 3 | Day 6 | Push notification certificate for iOS expired | Receiver notification (WAL-102) fails on iOS | Arun | Renewed via Apple developer account | Closed day 7 |
