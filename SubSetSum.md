# SubSet Sum Problem

Given a set of numbers, is there a subset whose sum is zero? [1]

## Example [1]

Set:
```
-7, -3, -2, 5, 8
```
Solution:
```
-3, -2, 5
```

# Complexity

The complexity of the best known algorithms are exponential. [1]

# Application to CoinJoin

Take the positive numbers as inputs and the negative numbers as outputs. Disregarding the fees, in a transaction there must be at least one valid subset, the set we are starting out with:

```
21,12,36,28.1,-25,-8,-50,-14.1
```

If we find a valid subset: `21,12,-25,-8`, then the remaining set is also a valid subset: `36,28.1,-50,-14.1`, but we can also find valid subsets in the remeaning set too.  

With an optimized algorithm Knapsack paper assumes the complexity of the best cast scenario can not be lower than exponential: `O((2^n)∗m)`, where `m` is the time it takes to solve the subset sum problem for
each set.[2]

# References

- [1] https://en.wikipedia.org/wiki/Subset_sum_problem
- [2] https://www.comsys.rwth-aachen.de/fileadmin/papers/2017/2017-maurer-trustcom-coinjoin.pdf
