# README

## What are the files for?

The miniature instances are mainly for ensuring that your solution executes correctly. They shouldn't be too challenging to solve and check manually for correctness of your solution.

The benchmarking instances are the remaining four problems (i.e. first and large instances).

### Solution format

The solution you are expected to provide consists of exactly N-K coordinates from the provided dataset, followed by the reported score. For the reproducibility purposes, provide the score with 3 decimal places, rounded via round() function.


## Exemplary solution

For the example provided in the text, the expected output contents should look like:

```
1	0
0	1
1.414
```

The order of the points provided in the answer is not established, the only requirement is that each one of these points are in the problem description, so, for example, solution which looks like:

```
1	1
0	0
1.414
```

would be deemed incorrect, as the problem does not describe a tower placed at coordinates (1,1).

### Important caveat

This is an optimization problem. The solution is correct as long as it is feasible, properly formatted and the reported score is calculated correctly.
