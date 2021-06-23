---
title: Proof of Work
date: 2021-06-23T22:06:05+02:00
lastmod: 2021-06-23T22:06:05+02:00
author: Sebastian Brueckl
# avatar: /img/author.jpg

# authorlink: https://author.site

# https://forkast.news/proof-of-work-what-is-it-bitcoin-halving/
cover: https://lh6.googleusercontent.com/FdscZdjcf9kwCqqXgLr5KWV9K4GjTkdeFIj-btc_Afnr7i1Ou_LLMGVKVCPRLFougIhSe-hEcsHtPropEAq6kbCaV_adOQF3veSYMZ4l91meEjYrcKFtayv9byTgi6t9QrCsXN6F
categories:
  - Intermediate
tags:
  - Bitcoin
  - Crypto Currency
  - Intermediate
  
# nolastmod: true
draft: false
---

Proof of Work is the most used and tested way for crypto currencies to build the blockchain.


<!--more-->
------------

The Concept of Proof of Work was first established in the bitcoin blockchain which was published at first in the Bitcoin [Whitepaper](https://bitcoin.org/bitcoin.pdf)


# What is Proof of Work (POW)?

Proof of Work (PoW) is a mechanism that allows a decentralized network to come to consensus, or agree on things like account balances and the order of transactions. This prevents users "double spending" their coins and ensures that a Blockchain is incredibly difficult to attack or overwrite.

# Proof of Work and Mining

Proof of work is the underlying algorithm that sets the difficulty and rules for the work miners do. Mining is the "work" itself. It's the act of adding valid blocks to the chain.  
This is important because the chain's length helps the network spot the valid Blockchain and understands its current state.  
The more "work" done, the longer the chain, and the higher the block number, the more certain the network can be of the current state of things.


# How does a Proof of Work algorithm work

The exapmle below displays the way Proof of Work works with [Ethereum](/science-communication-btc/posts/ethereum).
Ethereum transactions are processed into blocks. Each block has a:  

block difficulty – for example: 3,324,092,183,262,715  
mixHash – for example: 0x44bca881b07a6a09f83b130798072441705d9a665c5ac8bdf2f39a3cdf3bee29  
nonce – for example: 0xd3ee432b4fb3d26b  
This block data is directly related to PoW.  

# The work in proof of work
The Proof of Work protocol requires miners to go through an intense race of trial and error to find the nonce for a block. Only blocks with a valid nonce can be added to the chain.  
When racing to create a block, a miner will repeatedly put a dataset, that you can only get from downloading and running the full chain (as a miner does), through a mathematical function. This is to generate a mixHash that is below a target nonce, as dictated by the block difficulty. The best way to do this is through trial and error.  

The difficulty determines the target for the hash. The lower the target, the smaller the set of valid hashes. Once generated, this is incredibly easy for other miners and clients to verify. Even if one transaction was to change, the hash would be completely different, signalling fraud.  

Hashing makes fraud easy to spot. But PoW as a process is also a big deterrent to attacking the chain.


# Pros and Cons

+ PoW is neutral. 
+ You don't need the currency to get started and block rewards allow you to go from 0 to a positive balance. 
+ PoW is a tried and tested consensus mechanism.
+ Compared to proof-of-stake it's relatively easy to implement.

- PoW uses up so much energy that it's bad for the environment.
- If you want to mine, you need such specialized equipment that it's a big investment to start.
- Due to increasing computation needed, mining pools could potentially dominate the mining game, leading to centralization and security risks.


# Finality

In distributed networks, a transaction has "finality" when it's part of a block that can't change.  
Because miners work in a decentralized way, it's possible for two valid blocks to be mined at the same time. This creates a temporary fork. Eventually one chain will become the accepted chain once a subsequent block has been mined and added, making it longer.  
But to complicate things further, transactions that were rejected on the temporary fork may have been included in the accepted chain. This means it could get reversed. So finality refers to the time you should wait before considering a transaction irreversible. For Ethereum for example the recommended time is 6 blocks or just over 1 minute. Following that you can say with relative confidence that the transaction has been a success. Of course, you can wait longer for even greater assurances.  
This is something to bear in mind when designing dapps, as it would be a poor user experience to misrepresent transaction information to your users. Especially if the transaction is high value.  
Remember, this timing doesn't include the wait times for having a transaction picked up by a miner.  


# Proof of Work compared to Proof of Stake

At a high level, proof-of-stake has the same end goal as proof-of-work: to help the decentralized network reach consensus, securely. But it has some differences in process and personnel:  

PoS switches out the importance of computational power for staked coins.  
PoS replaces miners with validators. Validators stake their coins to activate the ability to create new blocks.  
Validators don't compete to create blocks, instead they are chosen at random by an algorithm.  
Finality is clearer: at certain checkpoints, if 2/3 validators agree on the state of the block it is considered final. Validators must bet their entire stake on this, so if they try to collude down the line, they'll lose their entire stake.  


# Sources

[Proof of Work: How it works](https://ethereum.org/en/developers/docs/consensus-mechanisms/pow/)  
[Proof of Work: Wiki](https://en.wikipedia.org/wiki/Proof_of_work#:~:text=Proof%20of%20work%20(PoW)%20is,minimal%20effort%20on%20their%20part.)
[Proof of Work: How it works](https://www.investopedia.com/terms/p/proof-work.asp)  
[Bitcoin Whitepaper](https://bitcoin.org/bitcoin.pdf)  
[Energy Consumption Proof of Work](https://digiconomist.net/bitcoin-energy-consumption/)  
[Further Information: Majority Attack](https://en.bitcoin.it/wiki/Majority_attack)  
[Further Information: Finality](https://blog.ethereum.org/2016/05/09/on-settlement-finality/)  
[Proof of Work Cover Image](https://forkast.news/proof-of-work-what-is-it-bitcoin-halving/)  
