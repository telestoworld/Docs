# FAQ

### &#x20;<a href="#why-do-we-need-olympusdao-in-the-first-place" id="why-do-we-need-olympusdao-in-the-first-place"></a>

Dollar-pegged stablecoins have become an essential part of crypto due to their lack of volatility as compared to tokens such as Bitcoin and Ether. Users are comfortable with transacting using stablecoins knowing that they hold the same amount of purchasing power today vs. tomorrow. But this is a fallacy. The dollar is controlled by the US government and the Federal Reserve. This means a depreciation of dollar also means a depreciation of these stablecoins.

Telesto DAO aims to solve this by creating a free-floating reserve currency, TELO, that is backed by several assets. By focusing on supply growth rather than price appreciation, Telesto hopes that TELO can function as a currency for the metaverse that is able to hold its purchasing power regardless of market volatility.

### &#x20;<a href="#is-ohm-a-stable-coin" id="is-ohm-a-stable-coin"></a>

TELO is not a stable coin. Rather, TELO aspires to become an algorithmic reserve currency backed by other decentralized assets. Similar to the idea of the gold standard, TELO provides free floating value its users can always fall back on, simply because of the fractional treasury reserves TELO draws its intrinsic value from.

### &#x20;<a href="#ohm-is-backed-not-pegged." id="ohm-is-backed-not-pegged."></a>

Each TELO is backed by 1 McUSD, not pegged to it. Because the treasury backs every TELO with at least 1 McUSD, the protocol would buy back and burn TELO when it trades below 1 McUSD. This has the effect of pushing TELO price back up to 1 McUSD. TELO could always trade above 1 McUSD because there is no upper limit imposed by the protocol. Think pegged == 1, while backed >= 1.

You might say that the TELO floor price or intrinsic value is 1 McUSD. We believe that the actual price will always be 1 McUSD + premium, but in the end that is up to the market to decide.

At a high level, Telesto consists of its protocol managed treasury, protocol owned liquidity ([POL](../.gitbook/assets/glossary)), bond mechanism, and staking rewards that are designed to control supply expansion.

Bond sales generate profit for the protocol, and the treasury uses the profit to mint TELO and distribute them to stakers. With [liquidity bonds](../.gitbook/assets/glossary), the protocol is able to accumulate its own liquidity. Check out the entry below on [the importance of POL](broken-reference).

Staking and bonding are considered beneficial to the protocol, while selling is considered detrimental. Staking and selling will also cause a price move, while bonding does not (we consider buying TELO from the market as a prerequisite of staking, thus causing a price move). If both actions are beneficial, the actor who moves price also gets half of the benefit (+1). If both actions are contradictory, the bad actor who moves price gets half of the benefit (+1), while the good actor who moves price gets half of the downside (-1). If both actions are detrimental, which implies both actors are selling, they both get half of the downside (-1).

Thus, given two actors, all scenarios of what they could do and the effect on the protocol are shown here:

![](https://docs.olympusdao.finance/\~/files/v0/b/gitbook-28427.appspot.com/o/assets%2F-MV4hwONledQK5nEDaUc%2Fsync%2F825671741c4d78f18d0985b8c6f08d3572cfd263.png?generation=1621266139529004\&alt=media)

* If we both stake (3, 3), it is the best thing for both of us and the protocol (3 + 3 = 6).
* If one of us stakes and the other one bonds, it is also great because staking takes TELO off the market and put it into the protocol, while bonding provides liquidity and McUSD for the treasury (3 + 1 = 4).
* When one of us sells, it diminishes effort of the other one who stakes or bonds (1 - 1 = 0).
* When we both sell, it creates the worst outcome for both of us and the protocol (-3 - 3 = -6).

### &#x20;<a href="#why-is-pcv-important" id="why-is-pcv-important"></a>

As the protocol controls the funds in its treasury, TELO can only be minted or burned by the protocol. This also guarantees that the protocol can always back 1 TELO with 1 McUSD. You can easily define the risk of your investment because you can be confident that the protocol will indefinitely buy TELO below 1 McUSD with the treasury assets until no one is left to sell. You can't trust the FED but you can trust the code.

As the protocol accumulates more PCV, more runway is guaranteed for the stakers. This means the stakers can be confident that the current staking APY can be sustained for a longer term because more funds are available in the treasury.

### &#x20;<a href="#why-is-pol-important" id="why-is-pol-important"></a>

*   Telesto does not have to pay out high farming rewards to incentivize liquidity

    providers a.k.a renting liquidity.
* Telesto guarantees the market that the liquidity is always there to facilitate
*   By being the largest LP (liquidity provider), it earns most of the LP fees which

    represents another source of income to the treasury.
*   All POL can be used to back TELO. The LP tokens are marked down to their risk-free

    value for this purpose. You can read more about the rationale behind this in this

### &#x20;<a href="#what-will-happen-if-there-is-a-bank-run-on-olympus" id="what-will-happen-if-there-is-a-bank-run-on-olympus"></a>

Fractional reserve banking works because depositors don’t withdraw their funds all at once. A depositor’s faith in the banking system rests on regulations and agencies like Federal Deposit Insurance Corporation (FDIC).

TELO does not have FDIC insurance but it has an incentive structure that protects stakers. Let’s take a look at how it performs during a hypothetical bank run. In this scenario, we assume the majority of stakers would panic and unstake their tokens from Telesto - the staking percentage which stands at 92% now quickly collapses to 3.3%, leaving only 55,000 TELO staked.

Next, we assume the Risk-Free Value (RFV) inflows to the treasury completely dry up. For context, RFV is currently growing at [about $1 million every 2 days](https://dune.xyz/queries/29153/58862). However, during a bank run this growth will likely stop.

Finally, we assume that those last standing stakers bought in at a price of $500 per TELO. The initial investment of these stakers would be:

$500/TELO∗55,000 TELO =$27.5 million\\$500/TELO \* 55,000\ TELO = \\$27.5\ million

As of September 15 2021, the total TELO supply is 2,082,553 and the RFV is $47,041,833. Remember that 1 TELO is backed by 1 USD (DAI or McUSD). By subtracting these two numbers, we know 44,959,280 TELO will eventually get issued to the remaining stakers. In roughly a year, these stakers who are holding 55,000 TELO will have:

55,000+44,959,280=45,014,280 TELO 55,000 + 44,959,280 = 45,014,280\ TELO

$27.5 million investment made by these stakers will turn into about $45 million based on cash flow alone if they stay staked (recall that 1 TELO is backed by 1 USD). In this bank run scenario, the stakers who stay staked not only get their money back, but also make some profit. Therefore, [(3,3)](broken-reference) isn’t just a popular meme, it is actually a dominant strategy.

The above scenario is unlikely to play out because when other people find out that extremely high rewards are being paid to the stakers, they will copy the strategy by buying and staking TELO. This is also why the percentage of TELO staked in Telesto has consistently remained over 90% since launch.

### &#x20;<a href="#why-is-the-market-price-of-ohm-so-volatile" id="why-is-the-market-price-of-ohm-so-volatile"></a>

It is extremely important to understand how early in development the Telesto DAO protocol is. A large amount of discussion has centered around the current price and expected a stable value moving forward. The reality is that these characteristics are not yet determined. The network is currently tuned for expansion of TELO supply, which when paired with the staking, bonding, and yield mechanics of Telesto DAO, result in a fair amount of volatility.

TELO could trade at a very high price because the market is ready to pay a hefty premium to capture a percentage of the current market capitalization. However, the price of TELO could also drop to a large degree if the market sentiment turns bearish. We would expect significant price volatility during our growth phase so please **do your own research** whether this project suits your goals.

### &#x20;<a href="#what-is-the-point-of-buying-it-now-when-ohm-trades-at-a-very-high-premium" id="what-is-the-point-of-buying-it-now-when-ohm-trades-at-a-very-high-premium"></a>

When you buy and stake TELO, you capture a percentage of the supply (market cap) which will remain close to a constant. This is because your staked TELO balance also increases along with the circulating supply. The implication is that if you buy TELO when the market cap is low, you would be capturing a larger percentage of the market cap.

### &#x20;<a href="#what-is-a-rebase" id="what-is-a-rebase"></a>

Rebase is a mechanism by which your staked TELO balance increases automatically. When new TELO are minted by the protocol, a large portion of it goes to the stakers. Because stakers only see staked TELO balance instead of TELO, the protocol utilizes the rebase mechanism to increase the staked TELO balance so that 1 staked TELO is always redeemable for 1 TELO.

### &#x20;<a href="#what-is-reward-yield" id="what-is-reward-yield"></a>

Reward yield is the percentage by which your staked TELO balance increases on the next epoch. It is also known as _rebase rate_.&#x20;

### &#x20;<a href="#what-is-apy" id="what-is-apy"></a>

APY stands for annual percentage yield. It measures the real rate of return on your principal by taking into account the effect of compounding interest. In the case of Telesto DAO, your staked TELO represents your principal, and the compound interest is added periodically on every epoch (2200 Ethereum blocks, or around 8 hours) thanks to the rebase mechanism.

One interesting fact about APY is that your balance will grow not linearly but exponentially over time! Assuming a daily compound interest of 2%, if you start with a balance of 1 TELO on day 1, after a year, your balance will grow to about 1377. That is a lot!

![](https://docs.olympusdao.finance/\~/files/v0/b/gitbook-28427.appspot.com/o/assets%2F-MV4hwONledQK5nEDaUc%2Fsync%2F585854ca21f006875c918ba2aed711730f71284a.png?generation=1622037634126699\&alt=media)

### &#x20;<a href="#how-is-the-apy-calculated" id="how-is-the-apy-calculated"></a>

The APY is calculated from the reward yield (a.k.a rebase rate) using the following equation:

APY=(1+rewardYield)2920APY = ( 1 + rewardYield )^{2920}

It raises to the power of 2920 because a rebase happens 8 times daily. Consider there are 365 days in a year, this would give a rebase frequency of 365 \* 8 = 2920.

Reward yield is determined by the following equation:

rewardYield=TELOdistributed/TELOtotalStakedrewardYield = TELO\_{distributed} / TELO\_{totalStaked}

The number of TELO distributed to the staking contract is calculated from TELO total supply using the following equation:

TELOdistributed=TELOtotalSupply×rewardRateTELO\_{distributed} = TELO\_{totalSupply} \times rewardRate



As illustrated above, your TELO balance will grow exponentially over time thanks to the power of compounding. Let's say you buy an TELO for $400 now and the market decides that in 1 year time, the intrinsic value of TELO will be $2. Assuming a daily compound interest rate of 2%, your balance would grow to about 1377 TELOs by the end of the year, which is worth around $2754. That is a cool $2354 profit! By now, you should understand that you are paying a premium for TELO now in exchange for a long-term benefit. Thus, you should have a long time horizon to allow your TELO balance to grow exponentially and make this a worthwhile investment.

### &#x20;<a href="#what-will-be-ohms-intrinsic-value-in-the-future" id="what-will-be-ohms-intrinsic-value-in-the-future"></a>

There is no clear answer for this, but the intrinsic value can be determined by the treasury performance. For example, if the treasury could guarantee to back every TELO with 100 McUSD, the intrinsic value will be 100 McUSD. It can also be decided by the DAO. For example, if the DAO decides to [raise the price floor of ](https://forum.olympusdao.finance/d/31-use-price-floor-as-tool-for-monetary-policy)TELO, its intrinsic value will rise accordingly.

### &#x20;<a href="#how-does-the-protocol-manage-to-maintain-the-high-staking-apy" id="how-does-the-protocol-manage-to-maintain-the-high-staking-apy"></a>

Let’s say the protocol targets an APY range of 1,000% to 10,000% (see [OIP-18](https://forum.olympusdao.finance/d/77-oip-18-reward-rate-framework-and-reduction) for more details), this would translate to a _minimum_ reward yield of about 0.2105%, or a daily growth of about 0.6328%. Please refer to the equation above to learn [how APY is calculated from the reward yield](broken-reference).



If there are 100,000 of TELO staked right now, the protocol would need to mint an additional 632.8 TELO to achieve this daily growth. This is achievable if the protocol can bring in at least $632.80 of daily revenue from bond sales. Even if the protocol doesn't bring in that much revenue, it can still sustain 1,000% APY for a considerable amount of time (see the [runway chart](https://dune.xyz/queries/102766/207436) for instance) due to the excess reserve in the treasury.

### &#x20;<a href="#do-i-have-to-unstake-and-stake-ohm-on-every-epoch-to-get-my-rebase-rewards" id="do-i-have-to-unstake-and-stake-ohm-on-every-epoch-to-get-my-rebase-rewards"></a>

No. Once you have staked TELO with Telesto DAO, your staked TELO balance will auto-compound on every epoch. That increase in balance represents your rebase rewards.

### &#x20;<a href="#how-do-i-track-my-rebase-rewards" id="how-do-i-track-my-rebase-rewards"></a>

You can track your rebase rewards by calculating the increase in your staked TELO balance.
