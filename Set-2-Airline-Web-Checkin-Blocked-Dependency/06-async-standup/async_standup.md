# Async standup

**Question:** Run one stand-up in written, asynchronous format for a distributed team across two time zones and compare it with a live stand-up.

### Asynchronous written stand-up (Chennai IST + Toronto EST, 10.5 hours apart)

Posted in the team channel `#checkin-standup` by 10:00 local time; the Scrum Master reads all posts at 18:00 IST /
07:30 EST, which is inside both teams' working hours.

> **Deepa (Chennai, day 5)**
> ✅ Yesterday: upgrade flow running against the mock payment service.
> 🎯 Today: error handling for declined cards; PR for review by Toronto.
> 🚧 Blocker: payment sandbox still down (IMP-07) – Mohan escalated.
>
> **Arjun (Chennai, day 5)**
> ✅ Yesterday: seat-hold timer (10 min) done and merged.
> 🎯 Today: boarding pass QR layout.
> 🚧 Blocker: none.
>
> **Lisa (Toronto, day 5)**
> ✅ Yesterday: reviewed Arjun's seat-hold PR, tested CHK-202 – passed.
> 🎯 Today: test cases for CHK-203 against the mock; review Deepa's PR when it lands.
> 🚧 Blocker: need test card numbers for the declined-payment case → @Deepa please add them to the wiki.
>
> **Mohan (SM, day 5)**: gateway support gave no ETA, escalated to vendor manager. Will update by 12:00 EST.

### Live vs asynchronous stand-up

| | Live (video, 15 min) | Asynchronous (written) |
|---|---|---|
| Time zones | Someone joins very early or late | Each person posts in their own morning |
| Speed of help | Blockers discussed immediately | Answer can take up to half a day |
| Record | Lost unless someone writes notes | Written history, easy to search |
| Team feeling | Better connection and quick clarifications | Can feel isolated; needs a weekly live call |
| Risk | Turns into status reporting to the SM | Posts become copy-paste; blockers may be missed |

The team uses async posts on four days and one live overlap call (08:30 EST / 19:00 IST) on Mondays.
