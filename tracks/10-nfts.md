# 10. NFTs That Do Something

**Track id:** `nfts` · **Tagline:** What comes after the JPEG

Build NFTs as accounts: assets that own money, earn royalties, hold inventory, and carry credentials, memberships or access rights.

**Lean on:** Dynamic NFTs, NEP-171, sub-accounts

## Start here

- [NEP-171 NFT standard](https://github.com/near/NEPs/blob/master/neps/nep-0171.md)
- [Access keys](https://docs.near.org/protocol/accounts-contracts/access-keys)
- [near-smart-contracts agent skill](https://github.com/near/agent-skills/tree/main/skills/near-smart-contracts)

## Prompt

```text
Track: NFTs That Do Something (id: nfts).

Build [a membership NFT that carries its own wallet]. Each NFT maps to a sub-account that holds a share of the club treasury and collects a cut of event ticket sales. Whoever holds the NFT controls that sub-account. Sell the NFT and the wallet, its balance and its access rights all move with it.

Requirements:
- An NEP-171 contract plus the logic that ties each token to its sub-account. Explain in the README exactly how control passes on transfer and what stops the old owner from keeping access.
- A gated page that only current holders can open.
- A history view per NFT: what it earned, what it paid out, who held it.
- Tests for the transfer path, including a sale in the middle of a payout.

Before coding, write down the threat model for the transfer: every way a seller could try to keep the money. Then wait for my OK.
```
