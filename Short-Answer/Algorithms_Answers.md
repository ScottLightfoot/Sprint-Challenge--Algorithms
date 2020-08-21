#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n^3)


b) O(n^2)


c) O(n)

## Exercise II


Akin to a binary search with left being break and right being non-break!

(Lets assume that we can drop it and ground floor and it doesn't break)
our min then becomes floor 0
we start at floor n/2 (current floor)
1. We drop an egg at current floor
2. If it breaks, we need to go lower - (half-way between min and current floor)
3. If it doesn't, let's go up!  (half-way between n & current floor + 1)

we repeat these steps until we've run out of splits to make!

given the nature of this problem, we will have a runtime complexity of O(log n)!
