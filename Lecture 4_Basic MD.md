## Definition (Mechanism) 
A (deterministic) mechanism (for a Bayesian game setting (N, O, Θ, p, u)) is a pair (A, M), where  
1. A: sets of __Actions__ for agents
2. M: A |→ O maps each __action__ profile to an __outcome__

## Quasilinear mechanism
A triple (A, _X_, p):  
1. A: set of actions
2. _X_(__choice function__): A -> _X_ action map to choice
3. p(__payment function__): action map to payment

## Bayesian game
**_A Baysian game setting + a mechanism_**  
Setting __(N, A, Θ, p, u)__ where u<sub>_i_</sub> : A × Θ |→ R. 

## Bayes-Nash equilibrium
a **mixed-strategy** profile s such that each s<sub>_i_</sub> is a best response to s<sub>_−i_</sub>


## Optimisation problem
1. The values of the inputs are __unknown__.
2. Design a game with a particular social choice function in equilibrium, the designer don't know __preference__ and agents might __lie__

## Social choice
1. O: sets of outcomes
2. N: a set of agents who have preferences over the outcomes
3. Goal: designing/picking a social choice function **_f_** that maps
from agents’ preferences to a particular outcome, which is
enforced.

## Dominant-strategy truthfulness
A direct mechanism is **dominant-strategy truthful** if, for every agent
i, telling the truth (i.e. revealing the true valuation) **maximises** i’s
utility, no matter what strategy the other players pick.

If Mechanism M is dominant-strategy truthful then
truth-telling is a **_(very weakly)_** dominant strategy for each agent
