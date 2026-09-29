# Mayher Adil

Sophomore at Connecticut College, class of 2029. International Relations, with a second major in mathematics or computer science still to be declared.

I build tools that separate what is actually verified from what people repeat.

---

### [registered-backtests](https://github.com/mayherprog/registered-backtests)

A pre-registered replication of twelve published trading strategies. Both gates were registered before any result was computed, and both are reported. Auditing my own code found seven defects, documented in `ERRATA.md`; correcting one of them, a Sortino ratio built on the wrong denominator, overturned my own published conclusion.

Python. Includes a Black-Scholes implementation with a textbook test, calibrated to a single day's live options surface — historical implied-volatility surfaces are paywalled, so its options numbers carry a documented 10–20% uncertainty band.

### [internship-fineprint](https://github.com/mayherprog/internship-fineprint) · [live site](https://mayherprog.github.io/internship-fineprint)

What internship programs actually state about eligibility: 227 programs at 95 firms at the current count. Every quoted line is traced to the page it came from and re-checked by an automated weekly sweep that flags drift rather than silently correcting it.

It records what firms state and never returns a verdict, because a firm's silence is not permission. Python and TypeScript, with a React front end and CI.

### [mental-math](https://github.com/mayherprog/mental-math) · [live site](https://mayherprog.github.io/mental-math)

A timed arithmetic drill built on exact rational arithmetic, running in the browser with no dependencies. When I could not support a claim I had made about its test coverage, I wrote the harness that made the claim true rather than softening it; the generator is now verified in the browser as well as in Python.

---

Summer 2026: UX intern, internal tools @ Cisco. Looking for quantitative research and software engineering internships for Summer 2027.
