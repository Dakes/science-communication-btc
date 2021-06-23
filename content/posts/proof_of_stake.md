---
title: Proof of Stake
date: 2021-06-23T21:50:16+02:00
lastmod: 2021-06-23T21:50:16+02:00
author: Sebastian Brueckl
# avatar: /img/author.jpg

# authorlink: https://author.site

# https://blokt.com/guides/proof-of-stake
cover: https://cdn.blokt.com/wp-content/uploads/2019/05/proof-of-stake.jpg
categories:
  - Intermediate
tags:
  - Ethereum
  - Cardano
  - Crypto Currency
  - Intermediate
  
# nolastmod: true
draft: false
---

Proof of Stake is a way to validate blocks for the blockchain without providing a big amount of computing power. It's used for many newer crypto currencies and some established ones are even shifting from the [Proof of Work](/science-communication-btc/posts/proof_of_work) concept to Proof of Stake.


<!--more-->
------------

# What is Proof of Stake (POS)?

Proof of stake is a type of consensus mechanism used by blockchain networks to achieve distributed consensus.  
It requires users to stake their coins to become a validator in the network. Validators are responsible for the same thing as miners in Proof of Work: ordering transactions and creating new blocks so that all nodes can agree on the state of the network.  
Proof-of-stake comes with a number of improvements to the Proof of Work system:  

- better energy efficiency – you don't need to use lots of energy mining blocks
- lower barriers to entr due to reduced hardware requirements – you don't need elite hardware to stand a chance of creating new blocks
- stronger immunity to centralization – Proof of Stake should lead to more nodes in the network


# Proof of Stake, Staking and Validators

Proof of Stake is the underlying mechanism that activates validators upon receipt of enough stake.  
For example for Ethereum, users will need to stake 32 ETH to become a validator.  
Validators are chosen at random to create blocks and are responsible for checking and confirming blocks they don't create.  
A user's stake is also used as a way to incentivise good validator behavior.  
For example, a user can lose a portion of their stake for things like going offline (failing to validate) or their entire stake for deliberate collusion.  


# How validation works

When you submit a transaction on a shard, a validator will be responsible for adding your transaction to a shard block. Validators are algorithmically chosen by the blockchain to propose new blocks.  

# Attestation

If a validator isn't chosen to propose a new shard block, they'll have to attest to another validator's proposal and confirm that everything looks as it should.  
It's the attestation that is recorded in the blockchain rather than the transaction itself.  
At least a specified number of validators are required to attest to each shard block – this is known as a "committee."  
The committee has a time-frame in which to propose and validate a shard block.  
This is known as a "slot."  
Only one valid block is created per slot, and there are 32 slots in an "epoch."  
After each epoch, the committee is disbanded and reformed with different, random participants. This helps keep shards safe from committees of bad actors.  


# Crosslinks

Once a new shard block proposal has enough attestations, a "crosslink" is created which confirms the inclusion of the block and your transaction in the beacon chain.  
Once there's a crosslink, the validator who proposed the block gets their reward.


# Finality

In distributed networks, a transaction has "finality" when it's part of a block that can't change.  
To do this in proof-of-stake a finality protocol, gets validators to agree on the state of a block at certain checkpoints. So long as 2/3 of the validators agree, the block is finalised. Validators will lose their entire stake if they try and revert this later on via a 51% attack.  
This is like a miner participating in a 51% attack, causing their mining hardware to immediately burn down.  


# Proof of Stake and Security

The threat of a 51% attack still exists in Proof of Stake, but it's even more risky for the attackers. To do so, you'd need to control 51% of the staked coin. Not only is this a lot of money, but it would probably cause the coins value to drop. There's very little incentive to destroy the value of a currency you have a majority stake in. There are stronger incentives to keep the network secure and healthy.  
Stake slashings, ejections, and other penalties exist to prevent other acts of bad behavior. Validators will also be responsible for flagging these incidents.


# Pros and Cons

+ Staking makes it easier for you to run a node. It doesn't require huge investments in hardware or energy, and if you don't have enough coins to stake, you can join staking pools.
+ Staking is more decentralized. It allows for increased participation, and more nodes doesn't mean increased % returns, like with mining.	
+ Staking allows for secure sharding. Shard chains allow Ethereum to create multiple blocks at the same time, increasing transaction throughput. Sharding the network in a Proof of Work system would simply lower the power needed to compromise a portion of the network.

- Proof of Stake is still in its infancy, and less battle-tested, compared to Proof of Work


# Sources

[Ethereum: Proof of Stake](https://ethereum.org/en/developers/docs/consensus-mechanisms/pos/#top)  
[Ethereum: Further Infromation on the Proof of Stake blockchain](https://ethos.dev/beacon-chain/)  
[Proof of Stake in general](https://consensys.net/blog/blockchain-explained/what-is-proof-of-stake/)  
[Proof of Stake in general](https://www.investopedia.com/terms/p/proof-stake-pos.asp)  
[Proof of Stake in general](https://academy.binance.com/en/articles/proof-of-stake-explained)  
[Cover Image](https://blokt.com/guides/proof-of-stake)
