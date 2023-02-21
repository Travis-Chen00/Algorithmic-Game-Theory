# Lecture 3: Algorithmic Mechanism Design
## Auction
Any protocol that allows agents to indicate their interest in one or more resources, and uses these indications of interest to 
determine both the allocation of resources and a set of payments by the agents is an auction.
1. **Single-item auction** &nbsp;--> &nbsp;**_quasilinear utility model_** <br>
    + Sells **an** item -- antique book.<br>
    + **n** bidders.<br>
    + **$\theta$** i: Each bidder i has a private valuation(**willing to pay**)<br>
    + Utility:
        + If _i_ wins at price __p__, utility of p _Ui_($\theta$) = $\theta$ _i_ - P _i_
        + If _i_ loses, he has to pay pi, utility: - P _i_
        + Winners: 0
    + __independent private value model__, i.e. a bidder’s valuation does not depend on other bidders’ valuations.
    + bidders cannot collude.  
---
__Mechanism__: __Allocation rule__ + __payment rule__
---
2. Rules:
    + Allocation: Sells to the bidder with **Highest bid**
    + Payment: The winner is to pay the seller an amount ~~equal to his/her bid~~
## Vickrey Auction + Bidders = a Game
The **payoff (_utility_)** of each bidder i depends on the **_outcome_** (allocation + payment), which in turn depends on **_bi_**(bidders) and the
bids placed by the **_other_** bidders  
**Vickrey auction**: The highest bid wins and pays the second-highest bid.  
1. The __loser’s__ utility is zero
2. The __winner’s__ utility is: winner’s value - loser’s bid

## Bayesian Game
(N, A, $\theta$, p, u)
1. $\theta$: Type space
2. p: common-prior probability distribution 
3. u: Utility

