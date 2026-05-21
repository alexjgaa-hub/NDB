# NDB — Trading Platform for Fibonacci Market Maker

## Overview

NDB is an active trading platform for the Fibonacci market maker. It manages trading metrics and runs trading bots on futures markets and DEX across multiple coins. The primary user is a professional trader.

---

## Core Display Requirements (per trading pair)

Every actively traded pair must show at minimum:

- **Price chart** — across multiple exchanges simultaneously
- **Order book (биржевой стакан)** — depth view across multiple exchanges
- **Open Interest** — per exchange, real-time
- **Leverage control** — ability to set and adjust leverage
- **Current position** — size, direction, entry price
- **PNL** — both realized and unrealized, real-time
- **Liquidation zone** — price level at which position is liquidated

---

## Bot Management Panel

A dedicated control panel for trading bots must support:

- **Launch** a trading bot with specified parameters
- **Stop** a running bot gracefully
- **Cancel / Kill** a bot immediately
- **Configure parameters** before and during execution:
  - Target pair and exchange
  - Strategy type
  - Position size / capital allocation
  - Leverage
  - Entry/exit conditions
  - Risk limits

---

## Markets

- **Futures** — CEX futures markets (e.g. Binance, Bybit, OKX, etc.)
- **DEX** — decentralized exchanges, multiple chains and coins

---

## User Profile

Professional trader / market maker. UI must prioritize:
- Speed and density of information
- No unnecessary abstractions or beginner UX
- Full control over all parameters at all times
