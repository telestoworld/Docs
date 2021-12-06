# Telesto Game Theory

> “If you are a leader or someone who works for the interest of a community, first make sure that you understand the interest of the people who make up that community. In this way, you will have a good chance of minimizing, perhaps, avoiding the us versus them mentality.”
>
> &#x20;― Duop Chak Wuol

​Telesto is an innovation in the way people interact with financial protocols. Our motivation is to delve deep into the Telesto protocol not from a technical or financial perspective but from the perspective of analysing human interaction.

There are many fields that have something to say about human interaction but the field of study we will focus on here will be game theory - the study of strategic interdependence.

It is our belief that Telesto is solving the problem of creating a new currency through internal coordination between different stakeholders within the protocol, without resorting to any policy enforced by a central entity. At its core this is an example of a [prisoner's dilemma](https://en.wikipedia.org/wiki/Prisoner's\_dilemma). A prisoner's dilemma is a situation where an individual's self interest is in conflict with a common goal, leading to the players within the game not cooperating despite it being in their best interests to cooperate.

In the case of currency, it is in each individual's best interest to use the most liquid, most widely used and most stable currencies. In crypto the assets that best meet these requirements have been dollar-denominated stablecoins. The ‘common goal’ in this context, is to maintain the individual’s purchasing power. This is something which stablecoins categorically do not achieve as most of them are pegged to fiat currencies, which are exposed to inflation risk. No individual acting alone can disentangle crypto from fiat. It takes mass coordination and alignment of incentives and this is what Telesto facilitates.

We will begin by outlining the essentials of game theory, and analysing the prisoner's dilemma from a purely abstract perspective. We will then delve into the specific components of Telesto. We will take no shortcuts. Telesto is a complex protocol that is the first of its kind and is deserving of deep and thorough analysis.

This is a collaborative piece of work that will be iterated on over time. It is aimed at a broad range of readers and if you would like to offer feedback or contribute to future sections, please join the Telesto DAO discord and reach out to the Community and Content team.



Game theory is the study of strategic interdependence. There are many situations in life where the best response to a situation depends on what other people in that situation do. Strategic situations are interesting because we can often get multiple outcomes, some of which are remarkably stable and yet sub-optimal for all people involved.

Consider a macroeconomic application of multiple stable outcomes under these conditions:

* Firms only invest if customers will buy goods.
* Customers only buy goods if they are paid wages.
* Customers are only paid wages by firms if customers buy goods.
* Firms think customers will buy goods and so expand production.
* Customers buy these goods because they think their wages are secure.
* The expanded profits allow firms to pay higher wages etc.
* Firms do not think customers will buy goods and so restrict production to save costs.
* Customers restrict their purchasing because they are uncertain about their wage security.
* Firms profits fall, leading to cost cutting in the form of wage cutting/laying off workers etc.

We can see that no one wants to be in the pessimistic outcome and yet still this outcome is very plausible. To understand why, we use game theory.

### &#x20;<a href="#the-model" id="the-model"></a>

In essence a game theoretic model has the following components:

**Players** They make choices based on information they hold about themselves, the other players and the structure of the game.

**Strategy** The full set of choices a player makes in a game.

**Payoffs** A payoff is the reward to each player, dependent on the outcome of the interaction. We decide payoffs by considering each player's preferences within the game.

**Payoff Matrix** A table that lists all the available strategies and their respective payoffs.

Game Theory is useful because it allows us to determine the optimal strategy which produces the best outcome for all the players involved.

The best way to get to grips with the power of game theory, is with an example.

### &#x20;<a href="#the-prisoners-dilemma-a-simultaneous-game" id="the-prisoners-dilemma-a-simultaneous-game"></a>

The first game any student of game theory learns is the prisoner's dilemma. This is due to its simplicity and it's applications to a wide variety of strategic situations. Once you see and understand this game, you will see it at play everywhere.

### &#x20;<a href="#context" id="context"></a>

The story goes like this; Two thieves plan to rob a store. As they approach the door, the police arrest them for trespassing. The police suspect that the pair planned to rob the store but they lack the evidence to prove it. They therefore require a confession to charge the suspects with the more serious crime. The interrogator separates the suspects and tells them each:

_“We are charging you with trespassing which will land you a one month jail sentence. I know you were planning to rob the store but I can’t prove it_ _without your testimony. Confess to me now, and I will dismiss your trespassing charge and set you free. Your friend will be charged for attempted_ _robbery and face 12 months in jail._ _I’m offering your friend the same deal. If you both confess, your testimony is no longer as valuable and you will both receive 8 months in jail.”_

Both players are self-interested and want to minimise their jail time. What should they do?

### &#x20;<a href="#payoff-matrix" id="payoff-matrix"></a>

Using a payoff matrix allows us to condense all the information into an easy-to-analyse diagram:

![](https://docs.olympusdao.finance/\~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F-MV4hwONledQK5nEDaUc-887967055%2Fuploads%2Fgit-blob-3d18a64ee34b85936eb4b83f3a2f864223e95890%2Fmatrix\_1.png?alt=media)

Player 1’s available strategies are the rows (Quiet or Confess) and their corresponding payoffs are the first numbers in each cell.

Players 2’s available strategies are the columns and their corresponding payoffs are the second numbers in the cells.

If player 1 stays Quiet and player 2 stays Quiet the game ends in the top left corner of the matrix. If both players Confess the game ends in the bottom right corner of the matrix and so on.

### &#x20;<a href="#strategies" id="strategies"></a>

To see which strategy each player will choose we should look at each move in isolation. From player 1’s perspective, what should he do if he thinks player 2 will stay Quiet?

![](https://docs.olympusdao.finance/\~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F-MV4hwONledQK5nEDaUc-887967055%2Fuploads%2Fgit-blob-f1f0d9bdaf4be0bda84e430c6418d11c26b564a2%2Fmatrix\_2\_correct.png?alt=media)

We can see that player 1 should Confess because if he stays Quiet he will get one month in jail and we have already stated that both players prefer less time in jail.

What about if player 1 thought that player 2 was going to Confess?

![](https://docs.olympusdao.finance/\~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F-MV4hwONledQK5nEDaUc-887967055%2Fuploads%2Fgit-blob-1361126d6e17ac65d7692f314db28d5a8a6f2e6e%2Fmatrix\_3.png?alt=media)

Again it seems that player 1 should Confess as it leads to 8 months jail time rather than the 12 on offer if player 1 stays Quiet.

Putting this together we reach an important conclusion: **Player 1 is better off confessing regardless of player 2’s strategy.**

Let’s look at player 2’s perspective, assuming he thinks player 1 will stay quiet:

![](https://docs.olympusdao.finance/\~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F-MV4hwONledQK5nEDaUc-887967055%2Fuploads%2Fgit-blob-ad25a418a10e9930d1bfd2fd2833b449cfb5c438%2Fmatrix\_4.png?alt=media)

Looking at the second numbers now we can see that like player 1, player 2 should confess as well: he will be set free instead of getting 1 month in jail.

![](https://docs.olympusdao.finance/\~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F-MV4hwONledQK5nEDaUc-887967055%2Fuploads%2Fgit-blob-b846d4d8faf3ab30a719196b9e7ce89f695d144e%2Fmatrix\_5.png?alt=media)

Once again it looks like Confess should be the chosen strategy even if player 2 thinks player 1 will also Confess.

**Player 2 is also better off confessing regardless of player 1’s strategy.**

### &#x20;<a href="#assumptions-and-conclusions" id="assumptions-and-conclusions"></a>

* We assumed that both players' preferences were to minimise their jail time
* We assumed both players were self-interested (i.e they don't care about their friends’ fate)
* We assumed only one interaction
* We assumed the players could not interact and plan their responses in advance

These assumptions led to a sub-optimal outcome in the game (Confess, Confess). We can see that had both players stayed Quiet, they would have received less jail time. This is an **unstable equilibrium** however, because (as we saw) both players are motivated to opt for Confess if they believe the other will stay Quiet.

Confess, Confess is therefore the only Nash equilibrium. A Nash equilibrium is a state in a game where no player wishes to deviate from their strategy, given what the other players are doing.

**The only dominant strategy in the prisoner's dilemma is Confess, Confess.** If both players were able to cooperate with each other and stay Quiet however, they would have achieved a better outcome. This is an important conclusion as it shows us that **two individuals may not cooperate, despite it appearing to be the best strategy for both.**
