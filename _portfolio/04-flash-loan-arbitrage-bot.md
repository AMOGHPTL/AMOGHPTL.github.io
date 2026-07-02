---
title: "Flash-Loan Arbitrage Bot"
excerpt: "Cross-DEX arbitrage using Morpho flash loans — no upfront capital. Deployed on Base."
collection: portfolio
permalink: /portfolio/flash-loan-arbitrage-bot/
---

An automated bot that detects and executes cross-DEX arbitrage opportunities using Morpho flash loans, requiring no upfront capital. The borrow, two-leg swap, and repay all run atomically on-chain.

- Live multi-chain, multi-DEX price monitor that emits opportunity events.
- Execution engine that validates opportunities and submits the transaction.
- Flash-loan + two-leg swap smart contract (deployed on Base).
- Offline scanning tools that quantify whether a spread is actually profitable before risking gas.
- Tested with unit, fork, real-DEX, invariant/fuzz, and Halmos symbolic proofs.

Repo: [github.com/AMOGHPTL/OpenI_the_arb_bot_core](https://github.com/AMOGHPTL/OpenI_the_arb_bot_core)
