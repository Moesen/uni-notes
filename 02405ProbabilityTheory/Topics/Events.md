### Introduction
Events represented mathematically as subsets of an [[Outcome Space]]
The word event is used here for the kind of thing that has a probability, like getting a six when rolling a die.
An event A is represented by a subset of the outcome space $\Omega$. Could be a women in $\Omega=\{man, woman\}$ or $\{2, 4, 6\}$ in the set of even numbers of the outcome space of a die.

Number of outcomes in A is denoted $\#(A)$. Informally it is the number of chances for A to occur or the number of different ways $A$ can happen.

Assuming equally likely outcomes the probability of $A$, denoted $P(A)$, is defined to be the corrosponding proportion of outcomes.
Examples: $\frac{700}{1000}$,  $\frac{1}{2}$,  $\frac{3}{6}$

---
### Formula
$$P(A)=\frac{\#A}{\#(B)}$$
If all outcomes in a finite set $\Omega$ are equally likely, the probability of A is the number of outcomes in A divided by the total number of outcomes.

--- 
#### Examples
Box with 100 tickets marked 1..100. Ticket is drawn at random, what are the probabilities for different ticket types?
| Event              | Subset of $\{1,2,...,100\}$ | Probability |
| ------------------ | --------------------------- | ----------- |
| Number has 1 digit | $\{1, 2,...,9\}$            | 9%          |
| Two digits         | {10,11,...,99}              | 90%         |
| <=*k*              | {1,2,...,k}                 | k%          |
| k<                 | {k+1,...,100}               | (100-k)%    |
| Sum of digits = 3  | {3, 12, 21, 30}             | 4/100 = 4%            |

---
### Problems
#### Dice is rolled twice, top noted each time. 
**If fair dice, what is prob that the sum is 5**
There are two combinations that would yield five. (1,4) and (2,3). These combinations can be hit in both succession. $\Omega = 36$ and #(A)=4.
P(Sum of two numbers showing is 5) = 4/36 = 1/9.
$\surd$

**Prob that one dice shows 2 and other shows 4**
The subset A is (2, 4) and (4, 2). #(A)=2, $\Omega$ = 36, P(One 2 other 4) = 2/36 = 1/18
$\surd$

**Prob that second number is greater than first**

#(A)=#{2,3,4,5,6}+#{3,4,5,6}+{4,5,6}+{5,6}+{6}
P(Greater) = 15/36

**Prob second is lower than first**
Same as above

#### Rolling two n-sided dice
Two first same principle except instead of each time being 6 its now n. So its $\frac{4}{n^{2}}$ and $\frac{2}{n^{2}}$.

