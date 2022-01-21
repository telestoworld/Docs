# 🏦 Platform

## Trident Lounge

* Epoch duration: 6 hours
* Deposits / Withdrawal of MINERAL into/from the Vapor Pools will lock MINERAL for 6 epochs and TELO rewards for 3 epochs.&#x20;
* TELO rewards claim will lock staked MINERAL for 6 epochs and the next TELO rewards can only be claimed 3 epochs later
*   Distribution of TELO during Expansion

    **80%** as Reward for Boardroom MINERAL stakers\
    **18%** goes to DAO fund

    **2%** goes to DEV/ARTIST fund
* Epoch Expansion: Current expansion cap base on TELOsupply, if there are bonds to be redeemed, 65% of minted TELO goes to treasury until its sufficiently full to meet bond redemption. If there is no debt it will follow max capped expansion rate

### Masonry UI Available information

Next **Seigniorage** indicates a countdown timer to the next epoch. (Each epoch duration lasts for 6 hours)                                                                                                              &#x20;

**APR** refers to the simple returns in USD value relative to the amount of MINERAL staked (USD value).\
_Note: **** APR fluctuates from time to time and is dependent on certain factors such as:_

* Price of TELO
* Price of MINERAL
* Amount of MINERAL staked in Trident Lounge (Locked Value)

### Trident Lounge on Contraction Periods

Trident Lounge will **not** mint any TELO (_NO REWARDS ON TRIDENT LOUNGE_) while TWAP < 1.01

### Trident Lounge on Debt Phase

Debt Phase take place on the expansion epochs that start after a contraction period where there are still Tbonds to be redeemed.

65% of Expansion during Debt Phase is allocated to the Treasury Fund to prepare for the SCRAP Redemption. This amount is still reserved  whether or not SCRAP holders are redeeming bonds or not.

Once TELO in treasury is sufficiently full to meet all circulating bond redemption, expansion rates will resume to normal.

TELO emitted per epoch during contraction periods can be found on Regulations.



## Vapor Pools

Stake your LP to earn MINERAL tokens

Shares Pools (Mineral Reward) available for 12 months:

* TELO-NEAR LP: 35500 Shares
* MINERAL-NEAR LP: 24000 Shares

## Scrap

SCRAP (scrap tokens) are available for purchase when TELO falls below the 1 NEAR peg. If TELO's TWAP is between 1.00 and 1.01, neither SCRAP nor TELO will be issued.

e.g. if TELO's TWAP < 1, exchange TELO for SCRAP will be in a 1:1 ratio.

SCRAP (bond tokens) are available for redemption when TELO goes above the 1 NEAR peg.

To encourage redemption of SCRAP for TELO when TELO TWAP > 1.1 and incentivize users to redeem at a higher price, SCRAP redemption will be more profitable with a higher TELO TWAP value, of which SCRAP to TELO ratio will be 1:R, where R can be calculated in the formula as shown below:

&#x20;                       R=1+\[(TELO(​twapprice)−1)∗coeff)]

Where coeff = 0.7
