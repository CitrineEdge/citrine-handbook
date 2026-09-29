# Reading Backtests, Fees And Funding

A meaningful comparison starts with the same instrument, dates, timezone, starting
funds, allocation and cost assumptions. Paper, Shadow, historical replay and live
execution do not have identical inputs or fills.

## A Comparison Worksheet

Record these beside both results before comparing a final dollar amount:

| Input | Why it matters |
| --- | --- |
| Product and direction | BTC and ETH contracts are not interchangeable; spot and futures are different products |
| Start/end time and timezone | A different boundary can include another entry, close or funding event |
| Starting funds and allocation | Different capacity can change contract quantities |
| Closed trades and any open exposure | A completed trade total is not the same as an account containing an open position |
| Execution prices and fees | Simulated execution and live fills can differ; account fees and default fees are not interchangeable |
| Funding coverage and sign | A credit, a debit, a verified zero and unavailable information mean different things |
| Accounting basis and period | An exchange-reported balance component is not automatically the result of one session |

## Do Not Subtract The Same Fee Twice

Hypothetical arithmetic only: suppose gross closed-trade PnL is **+$24**, trading
fees are **$4**, and included funding is a **+$1** credit. If the reported realized
trade result is already net of those fees, it is **+$20**. Adding the funding
credit gives **+$21**. Subtracting the $4 again would double-count it.

That example explains the reconciliation principle; it is not a universal formula
for every screen or exchange statement. Read the result's stated basis, included
costs, funding coverage and any open exposure. Funding belongs to its own accounting
component and need not be part of the closed-trade result.

## Missing Is Not Zero

A numeric zero can represent a known zero. Missing funding coverage does not prove
there was no charge or credit. Historical replay uses eligible available funding
data; inspect the result details before comparing it with exchange settlement.
Do not infer exact funding from the difference between two rounded balances.

## Drawdown Is Not Just The Worst Trade

Maximum drawdown measures a decline from a prior peak on the selected equity or
balance series. A hypothetical series of **$1,000 -> $1,030 -> $1,018** has a
**$12** peak-to-trough decline even though it ends above its starting balance.
Several losing trades can contribute to one drawdown.

The sampling basis matters. An exit-based series is different from continuously
marked open-position equity and may not show its intratrade low. Use the basis
described by Citrine's result details; do not treat an exit-based figure as the
largest possible live loss or assume stop orders guarantee a particular fill.

## When Two Runs Differ

Compare quantities and execution timestamps first, then prices, fee provenance,
funding and open exposure. Keep the original exports unchanged. For support,
describe the discrepancy and provide only the information actually requested;
do not post full account exports publicly.

[Backtesting methodology](https://citrineedge.com/backtesting/) |
[Safe troubleshooting](safe-troubleshooting.md) |
[Back to handbook](../README.md)
