# contracts
Big Ape Token uses in their ecosystem a lot of contracts. That contracts are open source and accessible to everyone to be transparent as possible.


BigApeToken.sol:

Contains Token Contract and Presale Contract.
It creates both contract while deploying BigApeToken, and send the 11% that are planned for Private Sale to the Presale Contract and approves this amount.
Private Sale will get a linear vesting. Every 2nd day 10% of their Amount will get sellable.

In the first 3 Blocks the buyers will get high taxed, since it is assumed that they sniped.

BATSINGLESTAKING.sol:

Contains the staking for Big Ape Token.
The staking is emission-based and 5% of the Total Supply will get released in 365 days.
Each deposit will claim the pending Rewards.
It is possible to add up to 3 BATNFTs as booster in this staking.
You'll get a boost up to x1.30 per NFT!

BATSINGLESTAKINGLOCKED.sol:

Contains the locked staking for Big Ape Token.
The staking is emission-based and 20% of the Total Supply will get released in 365 days.
If you stake, your stake amount is locked for 60 days in this contract. You are able to claim your rewards everytime.
In case you want to withdraw earlier, you'll pay a 20% penalty fee
Each deposit will claim the pending Rewards.
It is possible to add up to 3 BATNFTs as booster in this staking.
You'll get a boost up to x1.30 per NFT!
