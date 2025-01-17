---
title:   Chapter 2.A exercises
context: linalg
author:  Huxley Marvit
date: 2021-09-28
---

#ret #hw

***


# 2.A Exercises

```ad-abstract
Please reconsider the questions from Friday now that we have discussed them and part of Chapter 2.A. Do you have any questions about the proof of the Linear Dependence Lemma?? See if you can pin down any points where you lose the thread of the proof, and submit those questions and your updated answers for this assignment.

Be sure to try a few problems, so you have some ideas to share with your classmates on Thursday! Ideally consider at least three and complete at least one, but you don't have to submit those yet, just bring your ideas to class.

And if you haven't brought in your old quizzes, please be sure to do so!
```


### Linear Dependence Lemma

![[KBxLinearDependenceLemma]]

### A few problems
~Fibonacci! 
##### excr. 3
Find a number $t$ such that $(3, 1, 4), (2, -3, 5), (5, 9, t)$ is not linearly independent in $R^3$
***
Set up system of equations, 
$3a + 2b = 5$
$a - 3b = 9$
$4a + 5b = t$

solve, get $b=-2$ and $a=3$
plug it back in, $4(3)+5(-2)=2=t$

**answer: $t=2$**
*ah, 2.2 != 2.20 -- nice.*


##### Exercise 5
*from my personal notes:*

a. show that if we think of C as a vector space over **R**, then the list (1+i, 1-i) is linearly **independent.**

b. show that if we think of C as a vector space over **C**, then the list (1+i, 1-i) is linearly **dependent.**

Means: use scalars from R in the vector space C?
***


a. $a(1+i) + b(1-i) = 0$

prove that the only values of $a$ and $b$ are 0, thus satisfying the linear independence definition.

move i to only one side,
$a+b=i(b-a)$
since $a+b$ comes from R, and R is closed under addition, $a+b$ cannot have a complex component. 
$\therefore$ $a$ and $b$ must $=0$

***

b. $a(1+i) = b(1-i)$

let $b = i$
let $a = 1$

$i(1-i) = i-i^2 = 1+i$
$\therefore$ we can represent $(1-i)$ in terms of $(i+1)$ with scalars from C, and thus, it is linearly dependent.



##### Exercise 8
My personal notes on one of the exercises I solved:

Prove or give a counterexample: If $v_1, v_2,...,v_m$ is a linearly independent list of vectors in V and $\lambda \in F$ with $\lambda\ != 0$, then $\lambda v_1, \lambda v_2,...,\lambda v_m$ is linearly independent.
***

 $a_1 v_1 + a_2 v_2 + ... + a_m v_m = 0$ only if all scalars are equal to 0, as given in the definition
 
 $\lambda(a_1 v_1 + a_2 v_2 + ... + a_m v_m) = 0$
$\lambda \cdot 0 = 0$ 
 $\lambda a_1 v_1 +\lambda  a_2 v_2 + ... +\lambda  a_m v_m = 0$ only if all scalars are equal to 0
 $\therefore$  $\lambda v_1, \lambda v_2,...,\lambda v_m$ is linearly independent.

***

Draws from: [[KBxLinearIndependence]] [[KBxSpansLinAlg]]

***

In class review #extract

# In class after
### KBxDirectSum
[[KBxDirectSum]]

#question how do finite fields work?
field is just 0 and 1? but what about being closed under addition? ^319b41


**Trivial**: the simplest one? how do you quantify that? #question
Just about zeros?

Interesting concept: Step 1, to Step J. Represent algo's as an example first, then the final iteration?

Instead of just one generalized loop.
















