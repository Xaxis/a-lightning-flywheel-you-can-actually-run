
Routing revenue scales with volume and price. Lease income scales with parked capacity and market rates. Service revenue scales with humans you help. If routing is quiet for a season, leases and services keep the lights on. When traffic spikes, routing carries the month.

## Where rebalancing actually pays

Two traps here. The first is thinking rebalancing makes money by itself. It does not. It only unlocks more routing if you were bottlenecked on the profitable side. The second is thinking you can script this perfectly. You cannot. The network moves.

Use these simple guardrails.

- Only rebalance when a channel is earning and congestion on your side is the obvious limiter.  
- Cap the cost of circular rebalances to a strict percent of expected additional fees, for example do not spend more than 20 percent of the last week’s earnings from that channel to free it up.  
- Prefer organic counter flow. One more well placed peer that naturally returns flow is better than endless circular swaps.

## Risk, reality, and avoiding clown traps

- **Custodial sirens**  
  Any product that offers double digit yield on Lightning and requires you to deposit to their wallet is not Lightning yield. It is credit risk. If you want counterparty risk, at least be paid like a lender and get terms. This article is about not doing that.

- **Operational slop**  
  Downtime kills reputation. A flakey node can take months to recover in the gossip graph and in human memory. If you cannot keep a box up, rent a server in a boring data center and stop pretending your apartment ISP is special.

- **Fee chart addiction**  
  Over tuning wastes your time and annoys your peers. Set clear rules. Adjust on a schedule. Trust the loop.

- **Regulatory drift**  
  If you cross into selling payment services to third parties, read the rules in your jurisdiction. There is a line between routing packets and contracting to be a money transmitter. Know it.

## A map for your first 90 days

You do not need to be clever on day one. You need to be real.

**Week 1**  
Install, secure, back up. Open two anchor channels to reliable routers. Open one edge to a place where people buy or pay. Set modest ppm, tiny base. Turn on alerts. Sleep.

**Week 2**  
Watch forwards. If nothing moves, your placement is wrong. Nudge fees down. Consider one more demand peer. Do not throw capacity at the wall. Keep total sats smaller than what you would be sad to lose for a week.

**Week 3**  
Pick a rebalance budget, small. Free one channel that is jammed if it was earning before. If it was not earning, do not rebalance, move capacity.

**Week 4**  
Decide whether to lease 10 to 20 percent of capacity into a term you understand. If lease pricing is anemic, skip and add one new productive peer instead.

**Month 2**  
Splice up one channel that is clearly working. Prune one that is dead. Try a micro service deal with someone real. That can be your friend’s store. Put the promise in writing. Track uptime and payments.

**Month 3**  
Automate your weekly fee rules. Automate alerts you keep ignoring. Add one more service client or expand the first. Look at your shape. If routing is starting to cover your costs, you are on track. If nothing moves, accept that placement is the problem, not Lightning itself, and change peers.

## Service patterns that punch above weight

You do not need to become a bank to earn service revenue. Two simple patterns work well for individuals.

- **Merchant inbound concierge**  
  Guarantee a small shop always has inbound, success rate above a threshold, and hand holding for refunds. Charge a flat monthly fee. Price it like a web hosting plan. Back it with your channels and your phone number.

- **Community hub**  
  Act as the anchor node for a small online group. You run well connected channels, publish a join guide, and handle escalations. You charge the group a monthly pool that pays you for uptime and admin. People will gladly pay to avoid channel puzzles.

These are not glamorous. They are sticky. Sticky revenue turns a routing hobby into a business.

## When to add mining, fedimints, or other layers

There are natural extensions if you enjoy complexity.

- **Mining plus Lightning**  
  If you mine at home or remote, rolling block rewards into channels makes sense. The miner subsidizes your liquidity, and Lightning shortens the time from reward to spendable capacity. You also gain a narrative that is easy to sell to service clients. Energy in. Payments out. Loop closed.

- **Fedimints**  
  Community mints want solid Lightning bridges. If you are already the trusted ops person, you can be paid in sats or goodwill to keep that bridge healthy. This blends routing with social capital. Be clear about responsibilities.

- **DLCs and hedged liquidity**  
  For the advanced crowd, you can hedge volatile months by attaching small discrete log contracts that pay if routing volumes crater. Only do this if you actually understand it. Otherwise you are adding sharp edges to a simple machine.

## A short checklist

- Node up for 30 days straight  
- Two anchor peers with constant flow  
- Two edges tied to real commerce  
- Fees that move weekly, not hourly  
- One tiny service contract with a human name on it  
- Rebalance budget with teeth  
- Earnings automatically spliced or opened  
- Written rule for pruning dead channels  
- No custodial yield games

If you have that, you have a flywheel.

## The quiet part

Lightning yield today will not impress your greedy friend. That is fine. The point is not to chase numbers on a screen. The point is to own a small piece of open payments infrastructure, get paid for being useful, and compound a thing that keeps getting stronger as more humans use it. If you want to speculate, there are a thousand other places to gamble. If you want to build, Lightning will pay you little by little, then all at once when flow finds your node.

I will take boring cash flow with zero counterparty risk over flashy promises all day. Build the loop. Keep it simple. Let it spin.
