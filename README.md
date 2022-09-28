# JurassikChained-marketplace
A Helios smart contract for Cardano Blockchain

The contract is compiled with Helios playgound that you can find here https://hyperion-bt.github.io/Helios-Playground/
You can download the plutus file from the playground

## How does it work?

We store in the datum the pubkey and stakekey of the seller in this way we can build the address for paying,
We store the policy and asset of the token, with a price and also the price in ADA, if the user wants to sell also in ADA the datum will have a field that is set to 1

Endpoints are:
* Cancel: to cancel the listing
* BuyToken: To buy using tokens
* BuyAda: To buy using ADA if allowed
