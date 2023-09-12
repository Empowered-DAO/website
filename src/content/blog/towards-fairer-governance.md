---
draft: false
title: "Towards Fairer Governance"
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

**The Future of Fair Governance is Here.**

We have always wanted to implement governance into a lot of what we do. In this, we are not unique.. just about every serious project offers some sort of governance as a way to support the idea of decentralization, openness and trust.

We have studied what others are doing, and over a year ago started to look at how we would operate our governance. There is a lot to consider, what should be governed, what is the process for putting forward a proposal, discussing it and ultimately voting on that proposal, and how do you apply the result of proposal.

However, the most important thing is how do we make it fair?

### Introducing Graphite

Graphite is our own governance platform built upon a smart contract that implements Quadratic Voting. Our governance token will of course be EPWR. When you vote on issues / proposals within Graphite, you will be rewarded for doing so.

### What is Quadractic Voting

Quadratic Voting is a method of collective decision making in which a participant votes not just for or against a proposal, but also expresses how strongly they feel about it. It can help protect the interests of small groups of voters that care deeply about particular proposals.

Typically, in Quadratic Voting, each participant is given a number of credits that can be used to vote with. However, the cost of casting more than one vote is quadratic, not linear. So, the marginal cost of each additional vote is far higher than that of the previous vote.

With Graphite, instead of credits, each participant can vote up to the amount of EPWR they have (typically most voters would vote with the minimum 1 EPWR).

To cast 1 vote costs you 1 EPWR, 2 votes would cost 4 EPWR, 3 votes 9 EPWR and so on. So, while you are increasing the chances of victory for your proposal with each additional vote, the quadratic nature of the voting ensures that only those who care deeply about certain proposals will cast additional votes for them.

```
Cost to the voter = (Number of votes)^2
```

### Tokenomics of a Proposal

Quadratic voting limits the power of your vote.. but if you have nothing on the line.. that is, if you get to keep the EPWR you used for voting, then you may as well vote with all your EPWR right?

This is where we introduce another feature, distribution of EPWR used in voting to all voters.

In the first place, there is a cost to put forward a proposal. That cost is paid in EPWR and half of the proposal fee is added to the pool of EPWR that is distributed at the end of the voting period. All votes cast are also added to this pool. The other 50% of the proposal fee is burned.

At the end of the proposal, the pool of funds (proposal fee and EPWR used for voting) is equally distributed amongst all voters.

**Let's look at an example.**
>This is a simplified example that does not include the proposal fee.

99 people vote in favor of a proposal with 1 EPWR each. A whale wants to vote against the 99 people. Because of the way quadratic voting works, the whale will have to vote with 10k EPWR. The whale gets what he wants and the funds are distributed. So 10099 EPWR are distributed amongst 100 people. Each person receives around 101 EPWR. A huge loss for the whale and a huge gain for the other voters.

Even though the whale got what they wanted, they had to distribute wealth to get it. And now, those passionate voters can put forward a new proposal and use their newly rewarded EPWR to vote with. Using the same example but with the 99 voters voting with 101 EPWR would mean that the whale is going to have to vote with 100million EPWR. 

**This is how we get fair community governance. True representation of what the community wants.**

### Summary

1. You are paid to participate in governance.
2. Every proposal will burn a portion of EPWR.
3. Whales will have to distribute their wealth to get what they want.
4. Votes can be cast for or against a proposal.

>We believe with Graphite, we can offer a fairer governance model that can be used to develop better products that serve the majority better.