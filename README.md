# BEP-20-Token, 5% Fee
This is a BEP-20 Token smart contract with an included 5% fee. The fee is deducted from every transaction and then split and transferred to the owner's wallet and/or to a marketing wallet address. The marketing wallet address can be set by the owner, as well as the percentage that it receives from the 5% fee.

## 5% Fee
The Owner Wallet gets everything if he doesn't set a marketing address. If the marketing address is set, the marketing wallet receives 20% of the 5% fee by default. The percentage that the marketing address receives can be changed by the owner and has to stay between 0 and 100.
Also, addresses can be excluded from the fee, so they don't need to pay it.
