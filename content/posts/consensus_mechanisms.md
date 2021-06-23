---
title: Consensus Mechanisms
date: 2021-06-09T21:27:04+02:00
lastmod: 2021-06-23T16:27:04+02:00
author: Sebastian Brueckl
# avatar: /img/author.jpg
# authorlink: https://author.site
# https://www.c-sharpcorner.com/article/proof-of-work-vs-proof-of-stake/
cover: https://csharpcorner-mindcrackerinc.netdna-ssl.com/article/proof-of-work-vs-proof-of-stake/Images/Proof%20of%20Work%20Vs.%20Proof%20of%20Stake.gif

categories:
  - General
  - Introduction
  - Crypto Newcomer
tags:
  - Crypto Currency
  - Overview
  - Crypto Newcomer


# nolastmod: true
draft: false
---

Consensus Mechanisms are Mechanisms to proof the validity of transactions.

<!--more-->
------------

A consensus mechanism is a fault-tolerant mechansim that is used in computer and blockchain systems to achieve the necessary agreement on a single data value or a single state of the network among distributes process or multi-agent systems, such as with cryptocurrencies. It is useful in record-keeping, among other things.  
There are different concepts of the Consensus Mechanisms Proof of Work, Proof of Stake, Delegated Proof of Stake, Proof of Capicity, Proof of elapsed Time, Proof of Identity, Proof of Authority, Proof of Activity and Proof of Research.  
Most commonly used are the Proof of Work and Proof of Stake mechanisms.


# Proof of Work

Proof of Work POW is used by coins like Bitcoin, Litecoin etc. The Proof of Work Process is also called mining and the miners are known as nodes.  
The miners solve difficult mathematical puzzles that require extensive computional power. For this purpose miners use highly spezialized ASIC-Miners which are only build for the purpose of mining and can't be used for anything else. 
After solving mathematical puzzles which can only be solved by trial and error the miner recieves a block as a reward if they are the first to solve the puzzle.  
The level of difficulty for the puzzles changes according to the speed at which the blocks are being mined. In case the blocks are created quickly, then the puzzles would get more difficult and vice versa. Therefore, new blocks have to be created within a particular time frame to carefully adjust the difficulty level of puzzles.  
Despite being pretty popular there are big down sigths to the Proof of Work concept:  
The highly specialized ASIC-Miners can't work efficent forever caused of the increasing complexicity of the mining so there is lots of electronis waste every time a new generation of miners is released.  
Bitcoin's current estimated annual power consumption is 119 TWh which nearly equals to the electricity consumption of the netherlands.  

[Learn more about this topic](/science-communication-btc/posts/proof_of_work)

# Proof of Stake

Proof of Stake (POS) uses a randomized process to figure out who gets a chance to produce the next block. Blockchain users can lock up their tokens for a certain time for becoming a validator. After becoming a validator, users can be able to produce blocks. Validators can also be selected based on the design of blockchain. Generally, the user who owns the biggest stake or owns coins for the longest period of time has better odds of creating a new block.  
Validators usually get rewarded for their work with all or part of transaction fees of all the transactions carried out in the block they created.  
Alternatively, validators may receive a specific amount of coins due to inflation. With this approach, Proof of Stake method offers incentives to validators for maintaining the blockchain network. A big Advantage of Proof of Stake is the higher energy efficency compared to other consens mechanisms like Proof of Work.  
Also there is no specific hardware needed.  

[Learn more about this topic](/science-communication-btc/posts/proof_of_stake)

# Delegated Proof of Stake

In Delegated Proof of Stake process, users can stake their coins and vote for a particular number of delegates. The weight of a user’s vote is based on their stake.  
For instance, if a user ‘X’ stakes 20 coins for a delegate and another user ‘Y’ stakes 2, then X’s vote will have more weight compared to that of Y. The delegate that receives the highest number of votes gets a chance to produce new blocks. Delegates get rewarded with transaction fees or a specific amount of coins just like other blockchain consensus mechanisms such as Proof of Stake.  
Delegated Proof of Stake (DPOS) mechanism is one of the fastest blockchain consensus mechanisms. This mechanism can handle a higher number of transactions compared to Proof of Work mechanism. Due to its stake-weighted voting system, DPOS is often considered as a digital democracy.


# Proof of Capacity

In Proof of Capacity method, solutions to complex mathematical puzzles are stored in digital storages such as hard disks. This entire process is called plotting. After a storage device is filled with solutions for mathematical puzzles, users can utilize it for producing blocks. Users who are fastest in finding the solutions get a chance to create a new block. Hence, users with the highest storage capacity will have to higher chances of producing a new block.


# Proof of Elapsed Time

Proof of Elapsed Time process randomly and fairly decides the producer of a new block based on the time they have spent waiting. For this purpose, the mechanism provides a random wait time for each user and the user whose wait time finishes the earliest will produce a new block. This consensus mechanism only works if the system can verify that no users can run multiple nodes and the wait time is truly random.


# Proof of Identity

Proof of Identity compares the private key of a user with an authorized identity. Basically, Proof of Identity is a piece of cryptographic evidence for a user’s private key that is cryptographically attached to a specific transaction. Any identified user from a blockchain network can create a block of data that can be presented to anyone in the network. Proof of Identity ensures integrity and authenticity of created data. Additionally, smart cities can use blockchain consensus mechanisms like Proof of Identity to verify the identity of their citizens.


# Proof of Authority

Proof of Authority mechanism is a modified version of Proof of Stake where the identities of validators in the network are at stake. In this scenario, the identity is the correspondence between validators’ personal identification and their official documentation to help verify their identity. These validators stake their reputation on the network.  
In Proof of Authority, the nodes that become validators are the only ones allowed to produce new blocks. Validators whose identity is at stake are incentivized to secure and preserve the blockchain network. Also, the number of validators is fairly small (i.e. 25 or less).


# Proof of Activity

Proof of Activity mechanism is the combination of Proof of Work and Proof of Stake. In Proof of Activity, miners try to find the solution to a puzzle and claim their reward.  
However, the blocks created in Proof of Activity mechanism are simple templates with mining reward address and header information. 
The header information is then used to choose a random group of validators for signing a block. The validators with larger stakes will have greater odds of being selected to sign a new block. Once the selected validators sign a new block, it becomes a part of the network. In case the block stays unsigned by some validators, it gets discarded and a new block is utilized. The network fees generated in the process are distributed between the winning miner and the validators.


# Proof of Research

A concept related in many ways to Proof of Work. However, unlike Proof of Work where the value associated with the production of a cryptocurrency is reliant on an arbitrary process of hashing, which despite its provable input cost has no other value output other than the creation of a cryptocurrency, Proof of Research aims to put the hash power of the decentralized network to work on problems that have demonstrable, real world value.  
There exists a number of companies that are attempting to build globally networked supercomputers, that harness the spare computing power of ordinary, non-technical users, and reward them in cryptocurrency for solving problems on their machines. These problems can range from analysis of weather systems and astronomy, to research into new drugs and artificial intelligence. By offsetting the spare hash power of their computers, participants in the network can benefit from the receipt of a publicly tradable asset, and scientific research teams can access an ad hoc network of computers. For the latter party, this is usually cheaper and easier to access than a traditional, centralized supercomputer, and arguably more dynamic in the ways in which hash power can be managed, making it possible for multiple research teams to use the network simultaneously.  


# Conclusion

Despite having similar goals, various blockchain consensus mechanisms ensure consensus with a varying approach. A single reliable consensus mechanism does not exist yet but the existing ones have evolved over time to meet the needs of blockchain technology.  
Additionally, predicting the type of blockchain consensus mechanism that will be popular and useful in the long run can be increasingly complex as the underlying technology is fairly new.  


# Sources

[Overview of different Consenus Mechanisms](https://www.allerin.com/blog/8-blockchain-consensus-mechanisms-you-should-know-about)  
[Energy Consumption Bitcoin](https://digiconomist.net/bitcoin-energy-consumption/)  
[Proof of Work](https://en.bitcoin.it/wiki/Proof_of_work)  
[Proof of Stake](https://www.investopedia.com/terms/p/proof-stake-pos.asp)  
[Delegated Proof of Stake](https://academy.binance.com/en/articles/delegated-proof-of-stake-explained)  
[Proof of Capacity](https://tokens-economy.gitbook.io/consensus/chain-based-proof-of-capacity-space/proof-of-capacity-poc)  
[Proof of Elapsed Time](https://medium.com/nerd-for-tech/whats-proof-of-elapsed-time-4f67cf3f45b3)  
[Proof of Authority](https://academy.binance.com/en/articles/proof-of-authority-explained)  
[Proof of Activity](https://www.investopedia.com/terms/p/proof-activity-cryptocurrency.asp)  
[Proof of Research](https://unblock.net/glossary/por-proof-of-research)  
