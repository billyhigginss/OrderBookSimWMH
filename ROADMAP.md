# Roadmap

Agent-based limit order book simulator. Built to understand market making, adverse selection and order book mechanics. All modelling assumptions are written down in `ASSUMPTIONS.md`.

## Plan

- [ ] **Week 1:** core order book (price levels, queues, price-time priority), event loop with timestamps, noise traders, tests
- [ ] **Week 2:** market maker agent with queue position, inventory and skew
- [ ] **Week 3:** informed traders (Bayesian updating, trade only if edge beats the spread) and markouts to measure adverse selection
- [ ] **Week 4:** time bars vs volume bars, analysis, README with charts and limitations

## Rules for this project

- Every assumption goes in `ASSUMPTIONS.md` in plain English.
- After each piece, the author explains the code back in their own words before moving on.
