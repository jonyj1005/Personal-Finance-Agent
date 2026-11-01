# Finance Agent (MVP)

A personal finance dashboard that pulls Fidelity, Vanguard, 401(k), checking and credit card
data through [Plaid](https://plaid.com) and shows net worth, liquid assets, investments,
liabilities and cash flow in one place.

## Roadmap

1. **Integration (in progress):** link accounts via Plaid, store balances, holdings, transactions
2. Net worth math and daily snapshots
3. Dashboard with net worth history chart

## Setup

```bash
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
cp .env.example .env   # then fill in the values
```
