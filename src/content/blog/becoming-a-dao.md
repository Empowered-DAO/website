---
draft: true
title: "Becoming a DAO"
snippet: ""
image: {
    src: "https://images.unsplash.com/photo-1593720213428-28a5b9e94613?&fit=crop&w=430&h=240",
    alt: "full stack web development"
}
publishDate: "2023-09-09 11:39"
category: "Crypto"
author: "Adam Martin"
tags: [crypto, token]
---

It has always been my goal to decentralise what we do at Carbon Labs as much as possible. That means building systems, products and services that allows the typical daily operations to simply work. But, these systems can not be rigid, they must be built in a way that changes can be made in a controlled but automated way. 

Those changes need to be instigated in different ways depending on different situations...

1. Fully Automated
2. Via Governance (community voting)
3. Manually

Before we take a look at these in a bit more detail, we need to chat briefly about what a DAO is...

### DAO? Decentralised Autonomous Organization
In traditional organizations, there’s typically a hierarchy. A formal board of directors, executives or upper management determine the structure and have the power to make changes.

DAOs, on the other hand, are decentralized, which means they aren’t governed by one person or entity. The rules and governance of each DAO is coded in smart contracts on the blockchain and cannot be changed unless voted upon by the DAO's members.

Instead of a select few having the majority of say, members of each DAO can vote on decisions together, typically on equal footing.

So, now we understand a bit more about what a DAO, let's have a look at how we can achieve some of the goals we have in moving towards operating as a DAO. At the start of this post we talked about 3 different ways that changes can be implemented. 

We want to reduce the 3rd option of "manually" as much as we can. There are situations where manual is the only option. But we will talk about those in another blog post. For now, I want to look at the other 2 options and how we are going to start this journey by automating a process of token management for our main token - EPWR.

### Introducing our BuyBack contract
In the traditional world, a buyback is a repurchase of outstanding shares by a company to reduce the number of shares on the market and increase the value of remaining shares.

Rather than shares, our buyback smart contract is programmed to repurchase our tokens from the open market.

To understand how our BuyBack contract works, I want to present a flow for one of services that will be available soon. That is the ability to mint exclusive NFTs from within Alchemy. The first one being CryptoKiwis. 

_image coming_

In the above, you can see 3 different income streams happening,

1. Purchase of an Avatar
2. Minting of a new NFT
3. Purchasing of an existing NFT that results in royalty payments being received.

All these payments get channeled through our BuyBack contract, which contains rules about what to do with any received funds.

Let's look at how we might set the rules, to achieve what is shown in the diagram above.

_TODO - walk through an example_

### Conclusion
Our BuyBack Smart Contract allows the automated control of our tokens. It just works, there is no need for anybody to do anything. But, if changes are needed, then they can be voted on and any passing votes will be automatically applied.

And so with this, we believe we get a step closer to further decentralisation. Where our governance token owners have control over their investment. Implementing changes as and when needed to ensure the ecosystem remains as healthy as possible.

For every product and service we offer, all payments received will be channeled through the BuyBack contract. Meaning every single purchase has a positive impact on EPWR. 