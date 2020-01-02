# Bell Number

## Definition

The Bell Number is the number of partitions of a set.

## Examples

### Empty Set
Set:
```

```
Partitions:
```

```
Bell Number: 1

### Set with 1 element
Set:
```
a
```
Partitions:
```
a
```
Bell Number: 1

### Set with 2 elements
Set:
```
ab
```
Partitions:
```
ab
a b
```
Bell Number: 2

### Set with 3 elements
Set:
```
abc
```
Partitions:
```
abc
ab c
ac b
bc a
a b c
```
Bell Number: 5

## All Bell Numbers

```
1, 1, 2, 5, 15, 52, 203, 877, 4140, 21147, 115975, 678570, 4213597, 27644437, 190899322, 1382958545, 10480142147, 82864869804, 682076806159, 5832742205057, ...
```

# Application to CoinJoin

Given a transaction with 100 inputs, assuming brute forcing, one would need to iterate through Bell Number of 100 elements number of partitions in order to find valid partitions. The Bell Number of 100 elements is `47585391276764833658790768841387207826363669686825611466616334637559114497892442622672724044217756306953557882560751`.

# References

- [1] https://www.comsys.rwth-aachen.de/fileadmin/papers/2017/2017-maurer-trustcom-coinjoin.pdf
