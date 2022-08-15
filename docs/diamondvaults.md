# Diamond Vaults

A flexible staking solution, supporting plans such as attribute-based rewards.

Get started by joining their [Discord server](https://discord.gg/S4zk4k9j) to find helpful information, such as their [Tutorial Video (v5 in Feb 2022)](https://www.loom.com/share/8c38e17f66dc4aa69ec6c28d3adf56d5).

Twitter: https://twitter.com/DiamondVaults

Features:

- Support for multiple types of plans/campaigns -- standard (same rewards for all NFTs), attribute (different rewards based on NFT attributes), and multiple collections.
- Flexibility by accepting list of tokens that can be rewarded per plan.
- Each staking is its own contract, so even as plans/campaigns change, existing staking contracts honored for their time period.
- Support multiple time periods, such as 7, 15, 30, 60 days. They offer auto-staking options, as well as early unstaking options.
- Staked NFTs are removed from wallet.
- Rewards are calculated daily
- Rewards are paid through a balance of tokens in a wallet.
- For "Total Value Locked" (TVL) calculation, they use Magic Eden to grab current market information.
- Fees:
  - create a vault, which covers costs such as creating ATA (Associated Token Accounts): 1 SOL
  - if auto-staking turned on, additional fee to cover costs. e.g. 1 SOL per 1,000 NFTs
- User verification and role management via Matrica Labs. Verification supports Ledger wallets as well.
- Other services: Raffles

Questions

- what does API provide?
- can UI be customized?
- dashboard feature coming?
