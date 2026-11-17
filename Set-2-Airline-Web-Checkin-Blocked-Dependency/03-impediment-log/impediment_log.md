# Impediment log

**Question:** Log the impediment (description, impact, owner, escalation path, expected resolution) and show how the Scrum Master would remove it.

### Impediment log

| Field | Entry |
|---|---|
| ID | IMP-07 |
| Raised | Day 4 stand-up by Deepa (backend) |
| Description | The payment-gateway sandbox returns HTTP 503 for every request since the gateway's maintenance on day 3 evening. |
| Impact | CHK-203 seat upgrade (8 points, part of the Sprint Goal) cannot be integrated or tested. About 1/3 of the sprint at risk. |
| Owner | Mohan (Scrum Master) |
| Escalation path | 1) Gateway support ticket (P2) → 2) airline's payments vendor manager → 3) IT Head of Digital if not fixed by day 6 |
| Expected resolution | Day 6 (gateway's estimate) |
| Status | Resolved on day 6, 2 PM – sandbox back after escalation to vendor manager |

### How the Scrum Master removes it

1. Day 4: raises a P2 ticket with the gateway and asks for an ETA; shares the ticket number on the board.
2. Day 4: works with the team on a workaround – Deepa builds the upgrade flow against a **mock payment service** with the
   same API contract, so front-end and QA work continues.
3. Day 5: no ETA from support, so escalates to the vendor manager; asks the PO to tell the business that CHK-203 may slip.
4. Day 6: sandbox restored; the team switches from the mock to the real sandbox and runs the payment tests.
5. Retrospective: add "check third-party sandbox health daily" to the stand-up checklist.
