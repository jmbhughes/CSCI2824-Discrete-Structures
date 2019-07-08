# The problem of frogs

## Problem 1
A row of n squares contains a frog in the leftmost square. 
By successive jumps the frog goes to the rightmost square and then back to the leftmost square. 
On the outward trip he jumps one, two or three squares to the right, and on the homeward trip he jumps to the left in a similar manner. 
He cannot jump outside the squares. He repeats the round-trip travel m times.

Let F(m, n) be the number of the ways the frog can travel so that at most one square remains unvisited.
For example, F(1, 3) = 4, F(1, 4) = 15, F(1, 5) = 46, F(2, 3) = 16 and F(2, 100) mod 109 = 429619151.

Find the last 9 digits of F(10, 1012).

## Problem 2
There are n stones in a pond, numbered 1 to n. Consecutive stones are spaced one unit apart.

A frog sits on stone 1. He wishes to visit each stone exactly once, stopping on stone n. However, he can only jump from one stone to another if they are at most 3 units apart. In other words, from stone i, he can reach a stone j if 1 ≤ j ≤ n and j is in the set {i-3, i-2, i-1, i+1, i+2, i+3}.

Let f(n) be the number of ways he can do this. For example, f(6) = 14, as shown below:
1 → 2 → 3 → 4 → 5 → 6 
1 → 2 → 3 → 5 → 4 → 6 
1 → 2 → 4 → 3 → 5 → 6 
1 → 2 → 4 → 5 → 3 → 6 
1 → 2 → 5 → 3 → 4 → 6 
1 → 2 → 5 → 4 → 3 → 6 
1 → 3 → 2 → 4 → 5 → 6 
1 → 3 → 2 → 5 → 4 → 6 
1 → 3 → 4 → 2 → 5 → 6 
1 → 3 → 5 → 2 → 4 → 6 
1 → 4 → 2 → 3 → 5 → 6 
1 → 4 → 2 → 5 → 3 → 6 
1 → 4 → 3 → 2 → 5 → 6 
1 → 4 → 5 → 2 → 3 → 6

Other examples are f(10) = 254 and f(40) = 1439682432976.

Let S(L) = ∑ f(n)3 for 1 ≤ n ≤ L.
Examples:
S(10) = 18230635
S(20) = 104207881192114219
S(1 000) mod 109 = 225031475
S(1 000 000) mod 109 = 363486179

Find S(1014) mod 109.

## Problem 3
Susan has a prime frog.
Her frog is jumping around over 500 squares numbered 1 to 500. 
He can only jump one square to the left or to the right, with equal probability, and he cannot jump outside the range [1;500].
(if it lands at either end, it automatically jumps to the only available square on the next move.)

When he is on a square with a prime number on it, he croaks 'P' (PRIME) with probability 2/3 or 'N' (NOT PRIME) with probability 1/3 just before jumping to the next square.
When he is on a square with a number on it that is not a prime he croaks 'P' with probability 1/3 or 'N' with probability 2/3 just before jumping to the next square.

Given that the frog's starting position is random with the same probability for every square, and given that she listens to his first 15 croaks, what is the probability that she hears the sequence PPPPNNPPPNPPNPN?

Give your answer as a fraction in reduced form.
