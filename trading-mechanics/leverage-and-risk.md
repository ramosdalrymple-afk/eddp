# Leverage and Risk

#### What is leverage on EveryX?

Leverage lets users control a larger position in an Outcome while only risking a smaller amount of their own cash (the “cash portion”).

* Maximum leverage is 10x for now (this can change over time).
* Users always know their maximum loss: the cash portion of their trade.

Example (just to illustrate the idea):

* You risk $50 of your own money with 10x leverage.
* The system gives you $500 worth of exposure to that Outcome.
* If the market moves against you and hits your stop-loss, your position closes and your loss is capped to the $50 cash you put in.

No interest is charged on the “borrowed” portion of a leveraged trade.

#### The stop-loss

Every leveraged position has a stop-loss, expressed as a probability level:

* When choosing leverage levels, you’ll see the associated stop probability before opening the trade.
* If the Outcome’s probability falls to or below that level, the system automatically closes your position.
* This protects you from losing more than your cash portion.

You can:

* Use a stop that is closer (higher potential returns, but more likely to be hit), or
* Set it further away (lower potential returns, but less likely to be hit).

You can also add margin later to reduce leverage and move the stop further away from the current probability.

## Risk management and limits

EveryX has multiple layers of risk control

#### User-level risk

* Max loss = cash portion of the trade.
* Stop-loss closes positions before losses exceed that cash portion.
* Users can set stop warnings to get alerts when their position is close to being stopped-out, giving them a chance to add margin to move the stop further away.

#### Event-level risk

Each Event can have:

* Maximum leverage settings per Outcome.
* Limits based on how much cash is in the Event overall.
* Rules to limit market impact so one very large trade doesn’t destabilize prices.

These settings can differ between Events (e.g., a high-profile, well-funded Event vs. a small niche Event).

#### System-level risk

At the platform level, EveryX:

* Monitors overall exposure and cash in all pools.
* Adjusts allowed leverage when Events are very small or unbalanced.<br>

The goal is simple:

Users can take meaningful risk and use leverage, without the platform taking on hidden liabilities it cannot cover.

<br>
