# Lecture 3: Algorithmic Mechanism Design
## Auction
Any protocol that allows agents to indicate their interest in one or more resources, and uses these indications of interest to 
determine both the allocation of resources and a set of payments by the agents is an auction.
1. **Single-item auction** &nbsp; **_quasilinear utility model_** <br>
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
2. 
