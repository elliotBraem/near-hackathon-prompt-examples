# 12. Social Money

**Track id:** `social` · **Tagline:** Coordinate value together

Build shared budgets, programmable rewards, collective ownership and reputation-based access on top of Sputnik DAO and Trezu. Leave the multisig alone and build what communities do with it.

**Lean on:** Sputnik DAO, Trezu, named accounts

## Start here

- [Sputnik DAO contract](https://github.com/near-daos/sputnik-dao-contract)
- [Trezu docs](https://github.com/NEAR-DevHub/trezu-docs)
- [Trezu repo](https://github.com/NEAR-DevHub/trezu)

## Prompt

```text
Track: Social Money (id: social).

Build [a bounty board with earned trust] for a community that already runs its treasury on Sputnik DAO or Trezu. Members post small bounties, contributors claim and finish them, and payouts flow from the treasury. People who finish bounties build a track record, and a good track record raises how much they can be paid without a full council vote.

Requirements:
- Use the existing DAO or Trezu treasury for custody and approvals. Don't write a new multisig.
- Reputation is tied to named accounts and every point is traceable to a finished bounty.
- Tiers: small payouts auto-approve for trusted contributors, mid-size ones need one council member, large ones become a normal DAO proposal.
- A public board showing open bounties, claims, payouts and each contributor's record.

Read the Sputnik DAO contract and the Trezu docs first, then tell me which approval flows already exist and which ones we need to add.
```
