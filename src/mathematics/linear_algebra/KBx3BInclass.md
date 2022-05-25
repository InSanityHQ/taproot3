---
title:   3B Inclass
context: linalg
author:  Huxley Marvit
date: 2021-11-08
---

#flo  #hw 

***

# Null Spaces and Ranges

### our terms!
nullspace, aka kernel :: subspaces of the domain
range, aka column space :: subspace of the codomain

T: V -> W
kernel goes to subspace of V, domain
range goes to subspace of W, codomain of V

nullspace and column spac :: vector space specific

### basis of null space 
non-trivial nullspace means ur not bijective, because ur losing info.
multiple things go to zero!

kernel is a subspace, so there exists a basis! multiple, potentially.

every transformation can be represented as a matrix
convert this to reduced row echelon to find free variables
don't need to worry about right hand elementary matricies because it's multiplied by all zeros!


LD rows mean u can't get to the identity matrix #extract into LD and identity matrix

$\begin{bmatrix} 
 1 & 0 & 5 \\
0 & 1 & -2 \\
 0 & 0 & 0   
 \end{bmatrix} 
 \begin{bmatrix} 
 -5a \\ 
 2a \\ 
 1a  
 \end{bmatrix} = \begin{bmatrix} 
 0 \\ 
 0 \\ 
 0  
 \end{bmatrix}$

because everything needs to cancel eachother -- start from the free var, all zeros, then go backwards

$\begin{bmatrix} 
 -5 \\ 
 2 \\ 
 1
 \end{bmatrix}$ is a basis vec

number of free vars is the amount of info u are missing to fully restrain ur system

if our map is injective, then our null space is zero! because you can only send one thing to zero.

functions are by definition injective. are they? only of theire domain? they can output undefined... right? #question

```ad-def
title: column space
In linear algebra, the column space of a matrix A is the span of its column vectors. The column space of a matrix is the image or range of the corresponding matrix transformation. -wiki
```



surjective: everything in A hits something in B. but, two things in A can hit one thing in B.

### fundemental theorem of linear maps!
![[KBxChapter3BReading#Fundemental theorem]]

amount of basis vecs in V 
can be divided into things that get sent to zero and things that don't get sent to zero
things that don't get sent to zero induce a basis of the range?

[to watch later.](https://www.youtube.com/watch?v=GWgj5rKBHOk)

*** 
*part 2!*

homogenous system of equations means the constant terms are all 0

therefore letting everything be 0 is always a solution
if it has another solution then it can't be injective

more variables than equations means u cant be injective

under-determined system, and over-determined system

injective and surjective -> bijective ^216fc0


















