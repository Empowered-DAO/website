---
draft: false
title: "Unlimited Token Offer (UTO)"
snippet: "The UTO (Utility Token Offering) model offers a transparent, accountable, and fair alternative to traditional ICOs, allowing for real-time valuation and the ability for investors to cash out at any time, thereby addressing the pitfalls of ICOs such as lack of accountability and market manipulation."
image: {
    src: "https://images.unsplash.com/photo-1593720213428-28a5b9e94613?&fit=crop&w=430&h=240",
    alt: "full stack web development"
}
publishDate: "2023-09-09 11:39"
category: "Crypto"
author: "Adam Martin"
tags: [crypto, token]
---

A honest, fairer and safer alternative to launching via an ICO / ITO / ILO etc.

To be able to understand how a UTO works, we need to first look at how a typical ICO works. 

>We developed the UTO model at a time when ICO scams were commonplace and many people were losing millions of dollars. ICOs are no longer as common as they once were, being replaced by a number of different token launch models. However, fundamentally the same issues arise. 
>
>Note, that we will use ICO as a representative alternative model of raising initial funds. The mechanisms of which change a little, but the fundamental issues remain.

### What is an ICO?
An unregulated means by which funds are raised for a new cryptocurrency venture. An Initial Coin Offering (ICO) is used by startups to bypass the rigorous and regulated capital-raising process required by venture capitalists or banks. In an ICO campaign, a percentage of the cryptocurrency is sold to early backers of the project in exchange for legal tender or other cryptocurrencies.

### What does that really mean.
It seems these days, ICO's are being created almost daily and selling out even quicker. The "investors" are hoping that the value of these coins will increase in value. We use the term investors very loosely, as most people participating in an ICO sale are speculators.

There is no guarantee that the value of these tokens will increase, however almost immediately after the ICO has ended a large amount of these tokens are traded on various exchanges at some very high prices (as compared to the price to participate in the ICO).

The tokens are not being valued against the company that created them in the first place, but rather they are being valued against the current hype that is being generated and subsequently valued based on supply and demand on the exchange.

>Without the exchanges these tokens are essentially worthless!

### ...it gets worse.

As we already mentioned, most of these tokens are not tied to anything tangible. The value of the tokens are based completely on the hype of the ICO and the subsequent market exchange. The companies that launch the ICOs have no accountability to deliver upon any promises they make.

So, these companies launch an ICO to raise some funds. But not only that they also create or retain a large number of the same tokens for themselves. What are these tokens used for? There is only one purpose and that is to trade them on the exchange to make even more crypto.

You should ask yourself seriously why a company would be selling off their newly acquired (from thin air) tokens immediately on the exchanges when they have already raised such a large amount of funds from the ICO itself.

## How does the UTO model work?

At its core, the UTO is a smart contract that can accept funds in exchange of tokens. Additionally, it can also accept funds that are payment for products and services provided by the UTO operator.

UTO tokens are only created when another payment token (USDC for example) is received.

There are no time limits on how long the UTO can accept funds in exchange for tokens. However, the UTO itself can be "paused" by the UTO owner.

### Let's look at an example.

The UTO is launched with the following characteristics:
- 1 USDC = 100 UTO tokens
- Company offering the UTO retains 10% of the tokens created.

Buyer A sends 10 USDC to the contract, which results in 1000 tokens being created. 900 are assigned to Buyer A and 100 are assigned to the Company. The USDC itself is locked into the contract. The Company does not have access to the USDC, they can only get the USDC by selling their tokens at the same value as everyone else.

_At this point each token is worth 0.01 USDC - the same price as when the UTO launched._

However, the UTO contract can receive USDC that is not for token purchases. We refer to these as invoice payments. So carrying on with our example, let's assume that the UTO contract received an invoice payment of 90 USDC and so now holds 100 USDC in total. The cost of token purchase is formulated such that the current UTO token owners potential profit value is not decreased, that is we are guaranteeing that the price of a UTO token can not decrease due to supply. In fact, it can never go backwards in value.

We can calculate the current value of a single token with the following formula:

```
TUSDC / CS = TV
```
    
TUSDC = Total USDC in the contract  
CS = Circulating Supply of UTO tokens  
TV = Token Value  

so:

```
100 / 1000 = 0.1
```

That is, each token is now worth 0.1 USDC. Further purchases of UTO tokens need to ensure that this value is retained. So the formula for calculating further UTO token purchases is:

```
AMOUNT x (TUSDC/CS) = PRICE
```

where AMOUNT is the number of new tokens being purchased.

So, if a buyer wants to buy a further 5000 tokens then the cost is 500 USDC:

```
5000 x (100/1000) = 500 USDC
```

After this transaction, there would be:

**UTO Tokens** - 6000  
**USDC** - 600

Which means the token value is still 0.1 as it was before this new purchase. So anytime new tokens are bought, the price does not change. But when an invoice payment is made, then the price of every token in circulation goes up in price.

> Dip? What dip? The price of the UTO token can only ever increase.

## What are the benefits compared to ICO's?

**Fluidity**

You do not need to use a market exchange to cash out your UTO tokens. At anytime you can "sell" your tokens back to the UTO contract at the current token value without any extra fees (just pay for the gas).

Anytime UTO tokens are sold back to the contract, these tokens are destroyed and the equivalent USDC is sent to the user.

>The UTO company has to follow the exact same procedure to access the USDC as well. The USDC is locked into the contract. There is no way for the UTO company to access the USDC without selling tokens.

**More control in the hands of the contributors.**

Contributors can at any stage withdraw their investment less the tokens already assigned to the UTO Beneficiary.

With an ICO, when the token sale is complete, all of the money raised is handed over to the company that launched the ICO. At this point they can simply walk away with the money without producing anything. The incentive to implement the project is diminished when the company already has access to large amounts of money already. In some cases we are talking millions of dollars.

**No need for an exchange to buy and sell tokens.**
Because you can always sell your tokens back to the contract, there is no need for an exchange. This also means that the token is less prone to market manipulation.

_We say less prone because we can not stop anyone from putting the token up for trade, however, we would not be actively pushing to be listed on any exchanges._

**The valuation of the token is locked in.**
The token valuation is real and locked into the contract, auditing this valuation is simple and can be done by anyone at anytime. The valuation is not prone to large swings (the value can only ever increase), it is pegged to the USDC held within the contract.

**The company who launches a UTO is motivated to increase the value of the tokens.**
Because the company who owns the UTO contract has to sell the tokens they hold to access the USDC, they have a strong incentive to ensure that the people see value in what they are doing and continue to buy more UTO tokens.

We think that the UTO model is one of the fairer models currently. That does not mean it suits all use cases however. But, it is worth asking whether this model should be used more often. 

For ourselves, we will be launching our products & services using the UTO model as much as we can. Making it the basis for products where they have a need for their own token. 


