---
draft: false
title: "Crypto Bonds"
snippet: "Bonds are debt instruments that companies issue to raise funds, offering investors a fixed interest over time, and Crypto Bonds add a layer of security and flexibility by using smart contracts and NFTs for ownership."
image: {
    src: "https://images.unsplash.com/photo-1593720213428-28a5b9e94613?&fit=crop&w=430&h=240",
    alt: "full stack web development"
}
publishDate: "2023-09-09 11:39"
category: "Crypto"
author: "Adam Martin"
tags: [crypto, defi, bonds]
---

### What are bonds? A quick overview.

Bonds are a source of funding that companies obtain through the public. The corporation creates the bonds, which are then available for purchase. The organisation has to pay back the bond purchasers plus a coupon, an annual interest payment.

Corporate bonds come with the flexibility that other financing options may not. That is because the issuer can decide how to use those bonds and the terms that go with them. So, matters like the bond's maturity and more are up to the company that creates it.

If they want to improve the appeal of their bonds, they can back them up with collateral. As a result, the bonds become more secure for investors to purchase.

For us investors, bonds are different from term deposits in that we can sell them. We don't have to hold them until 'maturity' – when we get our money back. However, the price we will get if we sell our bonds early can go up or down.

## Our vision

The idea for developing bonds on the blockchain came from a public discussion on our old carbon telegram page, which started with this comment from myself.

> Thinking out loud. I currently am carrying finance on my hotel and thought I would rather be paying interest to carbonauts instead. So, was thinking about creating an NFT that is purchased with zUSDT that would have a guaranteed return (I would need to calculate this). Each week, the nft contract would be funded with interest payments that any nft owners could withdraw.
>
> I would like to know if this sort of thing would be of interest to anyone? Of course there needs to be more research done.. just want to gauge basic idea first. Investing with a stablecoin to get a reasonable return on that investment.

This created quite a lot of interest and good discussion. There were problems to solve, how do we guarantee payments, how do we give confidence to purchasers etc. Questions to be answered, but the positive feedback we got meant we knew we were on to something. 

## Our Solution

Over the next few days, we continued discussing the idea with the Carbon community and came up with a basic concept of how Crypto Bonds would work.

It was essential to develop the fairest and safest Crypto Bond product that we could. Making sure we did as much as we could to protect any investments by bond purchasers. 

Every Crypto Bond is managed by its smart contract and issues its own unique NFT. The NFT represents ownership of the bond, and the owner of the NFT is the person that will be paid any interest earned. Because it is an NFT, it can be sold on a secondary market.

### Let's take a closer look.

Any bond issued using our model requires the following:

- Number of bonds to be issued.
- Token used to buy bond.
- Price of each bond.
- Collateral token.
- Collateral Coverage Ratio - how much collateral is provided per bond.
- Term Length.
- Minimum Term Length.
- APR - Annual Percentage Rate.

**A quick example.**

Someone wants to raise $100K in USDC and will use LINK as collateral. They have decided they will offer a Collateral Coverage Ratio of 150% - that is they will provide $150k worth of LINK as collateral. They are also offering a 10% APR, and they will have a maturity date of 1 year with a minimum term of 30 days. Each bond will be $100, so they will be issuing a total of 1000 bonds.

- Number of bonds: 1000
- Payment token: USDC
- Price: 100 USDC
- Collateral: LINK
- Collateral Coverage Ratio: 150%
- Term Length: 1 year
- Minimum Term Length: 30 days
- APR: 10%

>It is important to note that the amount of collateral is determined at the time of the contract being deployed. Because the value of the collateral can change, it can be that the Collateral Coverage Ratio changes.
>
>If the Collateral Coverage Ratio falls, the bond issuer is able to add more collateral into the contract to maintain the ratio. However, if they do not do so, the contract will not allow buying of any more bonds if there is not enough collateral.

**Using this example, the bond issuer would have to:**

1. Deposit $10k worth of USDC into the contract to cover all interest payable.
2. Deposit $150k worth of LINK into the contract to cover the collateral. They can deposit less, but doing so, will mean the contract will only allow the number of bonds covered by the collateral to be sold. 

One question you may have at this point is; What is the Minimum Term Length? This is where we have changed things a little from traditional bonds. We allow the bond issuer to buy back issued bonds at any time. The minimum term length gives the bond buyer a guaranteed return. In our example, this is set to 30days.

When a bond is bought back, the interest earned is returned to the bond owner along with the total price paid for the bond.

At the end of the term, there is a small window of time where the bond issuer can buy back the bonds. If they do not do this, the bond owner will be able to claim collateral instead.

At any time, the bond owner can claim any interest owed.

So, if you are looking for an alternative investment opportunity, keep a lookout for our Crypto Bonds.

