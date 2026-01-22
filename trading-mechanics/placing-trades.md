# Placing Trades

When a user trades on EveryX, they decide three main things:

1. Which Event and Outcome they want to trade.
2. Trade size (how much cash to risk).
3. Leverage and stop-loss level (how aggressively to amplify the position, and where to cut losses).

The interface focuses on probability, not prices:

* Users see the current probability (%) of each Outcome.
* They choose how much to risk and whether to use leverage.
* They set a stop-loss probability for their position.

When the Event resolves:

* If the user picked the correct Outcome, they receive a payout from the losers.
* If the user picked the wrong Outcome, they lose the cash portion they put at risk (or less, if they closed early).&#x20;
