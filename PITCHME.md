## Motivation I
* Often, contracts are de-facto unenforceable due to high legal costs
* Yet, contracts like this are ubiquitious (you have one with UC Davis)
* A more through literature review would (hopefully) show that these contracts are under-therorized

---
## Motivation II
* Games with private information often have no efficient equilibrium
* Private information is common in the real world
* Perhaps these two stylized facts are related?

---
## Specific Research Question:
Are unenforceable contracts model-able as a coordination tool in a repeated game?

---
## The Model
---
### Players
1. Producer
    * Able to produce one unit of good each period, at cost $c \backsim U[0,1]$.
    * $c$ is private information
    * good is useless to producer
2. Consumer
    * Values good at 1 each period
---
### Mechanics
1. Before start, producer and consumer may write a contract, but there is no enforcement mechanism
2. Production Cost $c$ is revieled to producer
3. Consumer makes TIOLI offer to producer, who then chooses whetehr or not to produce ($q \in \{0, 1\}$)
4. repeat
---
### Objectives
1. Producer's objective function: $$\sum^{\infty}_{t = 0} \beta^t (p_t - c_t)q_t$$
2. Consumer's objective function: $$\sum^{\infty}_{t = 0} (1-p_t)q_t $$


---
### Equilibrium Concept

Equilibrium is 
Pricing rule for each period
$$p_t( p_s, q_s, ... , p_0, q_0) $$


$$p_t( p_s, q_s, ... , p_0, q_0$$
Quantity rule (production function) for each period 
$$q_t(p_t, c_t, p_s, c_s, q_s, ... , p_0, c_0, q_0$$ 

Such that $q_t(\cdot)$ optomizes the producesr's objective function given functions $p_t(\cdot)$, and $p_t(\cdot)$ optomizes the consumers objective function given functions $q_t(\cdot)$

--- 

## Solving
* Existance
* Uniqueness
* Optimiality

---
## Existance
* Call the one-shot equilibrium the "baseline" case
* $p_t = .5$, $q_t = {1 if c_t < p_t, 0 o.w.}$ 


---

## Uniqueness
* $p_t= 0$, $q_t = 0$ is also a (trivial) equilibrium, so not unique

---

## Optimality
* Can we do better?
* What if a contract lets us write a repeated game?

---

## A Better Equilibrium

* Contract: Consumer offers some $p> .5$  every time, and producer produces every time, even when $c > p$
* If the producer ever refuses, consumer offers $p = .5$ forever.

---
## Incentive Compatablity
### Consumer
* Baseline expected Consumer payoff = $\frac{1}{1-\beta} .25$
* Under this contract, Consumer payoff is $\frac{1}{1-\beta} (1-p)$
* Contract is incentive compatable for Consumer if $p \leq .75$
---
## Incentive Compatablity
### Producer
* After realization of $c$, producer chooses between $q= 0$ and $q=1$
* Expected payoff of $q=0$ is $\frac{B}{1-\beta} .125$
* Expected payoff of $q=1$ is $p = c +\frac{B}{1-\beta} (p-.5)$
---
## Incentive Compatablity
### Producer

* Contract is incentive compatable for producer if payoff of $q = 1$ is greater than or equal to payoff of $q = 0$ even when $c = 1$
* If $\beta > .663$, $p \geq .75$ is incentive compatable for producer
* if $\beta = .8 $, $p \geq .69$ is incentive compatable for producer
* if $\beta = .9 $, $p \geq .66$ is incentive compatable for producer
* if $\beta = 1.0 $, $p \geq .62$ is incentive compatable for producer

---
## Conclusions
For many plausible discount factors, we can write a contract that is completely non-binding, but facilitates an equilibrium that is welfare-improving for both players, and achieves the 1st best outcome

---
## Extensions
* In cases where it is not always efficient to produce, we would like a contract that lets producer choose $q=0$ sometimes
* Using the VF methods from 200D we can design a more sophisitcated strategy that allows us to examine more complicated strategy  space