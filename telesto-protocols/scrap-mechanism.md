# 🔧 Scrap Mechanism

Scrap Mechanism

### What is SCRAP? <a href="#what-are-tbond-bonds" id="what-are-tbond-bonds"></a>

SCRAP's are unique tokens that can be utilized to help stabilize TELO price around peg (1 NEAR) by reducing circulating supply of TELO if the TWAP (time-weighted-average-price) goes below peg (1 NEAR).

### When can I buy SCRAP? <a href="#when-can-i-buy-tbond-bonds" id="when-can-i-buy-tbond-bonds"></a>

SCRAP can be purchased only on contraction periods, when TWAP of TELO is below 1 dollar.  Every new epoch on contraction periods, SCRAP tokens are issued in the amount of 3% of current TELO circulating supply, with a max debt amount of 35%. This means that if bonds reach 35% of circulating supply of TELO, no more bonds will be issued.Note: SCRAP TWAP (time-weighted average price) is based on TELO price TWAP from the previous epoch as it ends. This mean that TELO TWAP is real-time and SCRAP TWAP is not.

### Where can I buy SCRAP? <a href="#where-can-i-buy-tbond-bonds" id="where-can-i-buy-tbond-bonds"></a>

You can buy SCRAP if any are available, through the Scrap on telesto.finance, anyone can buy as many SCRAPs as they want as long as they have enough TELO to pay for them.There is a limit amount (3% of TELO current circulating supply) of available SCRAPs per epoch while on contraction periods, and are sold as first come first serve.

### Why should I buy SCRAP? <a href="#why-should-i-buy-tbond-bonds" id="why-should-i-buy-tbond-bonds"></a>

First and most important reason is SCRAP helps maintain the peg, but will not be the only measure use to keep the protocol on track, more on that on DAO Fund section [here](https://docs.tomb.finance/protocol/dao-fund). SCRAP does not have a expiration date, so you can view them as a investment on the protocol, because longterm you get benefits from holding SCRAP tokens.

#### Incentives for holding SCRAP <a href="#incentives-for-holding-tbond" id="incentives-for-holding-tbond"></a>

The idea is to reward SCRAP buyers for helping the protocol, while also protecting the protocol from being manipulated from big players.So after you buy SCRAP using TELO, you get 2 possible ways to get your TELO back:

1. Sell back your SCRAP for TELO while peg is between 1 - 1.1 (1 NEAR) with no redemption bonus. This to prevent instant dump after peg is recovered
2. Sell back your SCRAP for TELO while peg is above 1.1 (1 NEAR) with a bonus redemption rate

The longer you hold, the more both the protocol and you benefit from a SCRAP Example:

1. When TELO = 0.8, burn 1 TELO to get 1 SCRAP (SCRAP price = 0.8)
2. When TELO = 1.15, redeem 1 SCRAP to get 1.105 TELO (SCRAP price = 1.27)

So, which one is better?

If I buy TELO at 0.8, and hold it until 1.15 and then sell, I'm getting +0.35$ per TELO. But, if I buy TELO at 0.8, burn it for SCRAP, and redeem it at 1.15, I'm getting 1.105 TELO \* 1.15 (TELO current price) = 1,271 (+0.47$) per SCRAP redeemed.But what if getting back to peg is taking too long ?We are going to adjust our use cases, to have different behaviors on contraction and expansion periods to benefit TELO and SCRAP holders when needed.

### When can I swap SCRAP for a bonus? <a href="#when-can-i-swap-tbond-for-a-bonus" id="when-can-i-swap-tbond-for-a-bonus"></a>

SCRAP TWAP (time-weighted average price) is based on TELO price TWAP from the previous epoch as it ends. This mean that TELO TWAP is real-time and SCRAP TWAP is not. In other words, you can redeem SCRAP for a bonus when the previous epoch's TWAP > 1.1.
