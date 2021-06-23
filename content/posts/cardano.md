---
title: Cardano
date: 2021-06-10T14:06:10+02:00
lastmod: 2021-06-21T21:06:10+02:00
author: Daniel Ostertag
# avatar: /img/author.jpg
# authorlink: https://author.site
# https://en.wikipedia.org/wiki/File:Cardano.svg
cover: https://upload.wikimedia.org/wikipedia/commons/f/f8/Cardano.svg
categories:
  - Advanced
tags:
  - Cardano
  - Crypto Currency
  - Smart Contract
  - Advanced
  
# nolastmod: true
draft: false
---

The next-gen Smart Contract [Proof-of-Stake](/science-communication-btc/posts/consensus_mechanisms) Blockchain Platform. 

<!--more-->
------------

# The Creation
Cardano was founded in 2014 by Charles Hoskinson, who was previously a member of the founding team of Ethereum. Shortly after he left the Ethereum project, he created Cardano to address some of Ethereums shortcomings.  
Nowadays Cardano is comprised of 3 organisations: 
- The Cardano Foundation: Oversees and supervises the advancement of Cardano and the ecosystem.
- IOHK: Designs, builds, and maintains the Cardano platform.
- EMURGO: Develops, supports, and incubates commercial opportunities and helps integrate businesses into the blockchain system.

# Peer-review process
Where Cardano differs from any other crypto project out there, is that they are more research oriented. For that they use a peer-review process. Other projects may rush to implement their, beforehand published, whitepapers and in the process suffer the consequences, by introducing security problems, or other bugs. Cardano on the other hand uses an elaborate peer review process. The papers are first submitted to well known conferences, where they are reviewed by world leading experts in Networking and Cryptography. Formal design specifications are then written, instead of jumping into coding hastily. The software is then written in accordance with those requirements. To play it extra safe, external auditors will review the code for vulnerabilities. Those reports are publicly accessible. Just as is the Source Code at: [github.com/input-output-hk](https://github.com/input-output-hk). This is crucial for *any* Crypto project, so that any one can review or build it themselves.  
The disadvantage to such a process however is, that development is fairly slow. Which is why it is barely half way through its roadmap, in contrast to Ethereum, which is in use for years now, despite development on Cardano starting not long after Ethereum. 

# The Roadmap

![test](/science-communication-btc/cardano_roadmap.png)


The development roadmap is split into 5 big eras with different main objectives.  
- **Byron**: The Byron era began with the first version in September 2017. It allowed users to buy sell and trade the ADA cryptocurrency (Currency of the Cardano network). 
- **Shelley**: Shelley was about decentralising the network and preparing it for the future. 
- **Goguen**: Goguen is the era, we are in right now. It will integrate Smart Contract capabilities, enabling developers to build dApps on Cardano, using the Plutus Programming language. 
- **Basho**: The Basho era is an era of optimisation, improving the scalability, interoperability and performance of the network. 
- **Voltaire**: The last era, will transform Cardano into a fully self sustaining system, where users can vote about future development goals. The funding of development will be made decentralised as well. 

# Ouroboros - Proof-of-Stake
Cardano uses the so-called Ouroboros system for their [pos](/science-communication-btc/posts/consensus_mechanisms). It was developed for Cardano and is, as always is the case with Cardano, based upon peer-reviewed papers.  
Ouroboros is mathematically secure, as long as 51% of the Network stake is held by honest participants, which is incentivized by the network as well.  
It incentivizes participation in the network, by rewarding either, the operation of a stake pool, or the delegation of ADA to a stake pool, with ADA.  
Ouroboros processes transaction blocks by dividing chains into epochs, which are further divided into time slots. For each slot, a stake pool is assigned as the slot leader, and is rewarded for adding a block to the chain. 

# Sources
[Medium: A Very Brief Overview of Cardano](https://medium.com/coinmonks/a-very-brief-overview-of-cardano-907a3c8d665e)  
[Cardano.org: Discover Cardano](https://cardano.org/discover-cardano)  
[Cardano.org: Cardano Partners](https://cardano.org/partners/)  
[Cardano.org: Ouroboros](https://cardano.org/ouroboros/)  
[roadmap.cardano.org](https://roadmap.cardano.org/en/)  

