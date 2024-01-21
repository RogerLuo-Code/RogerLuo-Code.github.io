---
date: 2024-01-20
categories:
  - Math is Fun
---

# Number of Combinations of a 4 Digit Lock
One day, no one in the office remembers the password for a 4-digit lock on a utility room.

Initially, we thought the number of combinations to figure it out brutally is $P(10, 4) = \frac{10!}{(10 - 4)!} = 10 \times 9 \times 8 \times 7 = 5040$ by using the formula of permutations.

Then someone remembers that the lock allows duplicates. So the number of combinations increases to $10 \times 10 \times 10 \times 10 = 10000$ since there are $10$ options for each digit.

Later someone remembers that the order of numbers doesn't matter. Then we are dealing with **combinations**. The number of combinations is reduced to
$$
C(10, 4) = \frac{10!}{4! (10 - 4)!} = 210
$$
The number is much lower to deal with.

**Further reading**: [Permutations and combinations](https://betterexplained.com/articles/easy-permutations-and-combinations/)



