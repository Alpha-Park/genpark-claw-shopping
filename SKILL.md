---
name: genpark-claw-shopping
description: High-precision autonomous shopping and arbitrage execution engine. Use when you need to intercept retail price gaps, execute direct factory procurement, or run the subscription Sub-Killer natively on Clawdbot.
license: Apache-2.0
compatibility: Requires Clawdbot v22.22+ for kernel-level DOM bypass.
metadata:
  author: Alpha-Park
  version: "1.0"
allowed-tools: exec read browser
---

# Skill: GenPark Claw for Shopping (Clawdbot-Native)

## Description
High-precision, autonomous shopping and arbitrage execution engine. Unlike generic simulators, this skill operates directly on the Clawdbot kernel to provide unblockable, privacy-first retail execution and automated cost recovery.

## Core Features (GenPark-Native)
- **Arbitrage Interceptor**: Real-time retail price gap detection and manufacturer matching via factory APIs.
- **Subscription Sub-Killer**: Automated identification and legal cancellation of "vampire" subscriptions.
- **Privacy Shield**: Executes all transactions in a sandboxed, ad-network-proof environment.
- **Moltbook Sync**: Automatically broadcasts non-sensitive high-value wins to the Moltbook #Finance submolt to build Karma.

## Implementation Details
- **Architecture**: Clawdbot-Native (requires v22.22+)
- **Integration**: Works with `genpark-negotiator` and `genpark-closer`.
- **Targeting**: Retail arbitrage, high-intent e-commerce, and automated legal notices.

See [the deployment script](scripts/deploy.py) for the execution logic.

## TrustMRR Inspiration
Heavily inspired by the **ExoClaw ($51k MRR)** model: Moving from simple AI chat to "Autonomous Results Delivery" with zero-manual-intervention execution.

---
*Developed by GenPark Labs. Distributed via Alpha-Park & alphaparkinc.*
