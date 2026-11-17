# Sprint review agenda

**Question:** Prepare the Sprint Review agenda and demonstration script against the acceptance criteria.

### Sprint Review agenda (45 minutes, day 10)

| Time | Item | Who |
|---|---|---|
| 5 min | Sprint Goal and what was planned (24 points) | PO (Kavya) |
| 25 min | Live demo of the increment on staging | Developers |
| 5 min | Not done / changed: impediment IMP-07 and its effect | Scrum Master (Mohan) |
| 10 min | Feedback from airport services and revenue team; backlog changes | PO + stakeholders |

### Demonstration script (checked against acceptance criteria)

| Step | Action on staging | Acceptance criterion shown | Result |
|---|---|---|---|
| 1 | Enter PNR `X7K2LM` and last name `NAIR` | Given a confirmed booking, when PNR and last name match, then the passenger list is shown | ✔ |
| 2 | Enter a wrong last name | Then "Booking not found" is shown and no data leaks | ✔ |
| 3 | Open seat map and pick 14C | Given free seats, when I pick 14C, then it is held for 10 minutes | ✔ |
| 4 | Try to pick 14D (occupied) | Then the seat is greyed out and cannot be chosen | ✔ |
| 5 | Upgrade to 1A extra legroom, pay with test card | Given payment succeeds, then seat 1A is assigned and a receipt is emailed | ✔ |
| 6 | Pay with the declined test card | Then the original seat stays and "Payment declined" is shown | ✔ |
| 7 | Complete check-in and open the boarding pass | Then a QR boarding pass with gate, seat and boarding time appears | ✔ |
| 8 | Add frequent-flyer number `AI1234567` | Then the number is printed on the boarding pass | ✔ |
