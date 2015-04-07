# Subset Sum Algorithm

Implements the *Subset Sum Problem* using recursive backtracking. Implementation is provided as `SubsetSum` class contained in the package `io.gitbub.thehappybug.Algorithms`.

## Compiling

The project can be compiled using `make` tool:

```
$ make
javac io/github/thehappybug/Algorithms/SubsetSum.java
```

## Running

Run the class `SubsetSum`'s `main` method using:

```
$ java io.github.thehappybug.Algorithms.SubsetSum
[-7, -3, -2, -1, 5, 8]
[-7, -3, 10]
[-7, -2, -1, 10]
[-7, -2, 9]
[-7, -1, 8]
[-3, -2, 5]
```

The program requires no arguments.


## Documentation of `SubsetSum` (Public)

**`public class SubsetSum`**

Algorithm to generate all subsets of the current set that sum to zero.

**`public static void main(String[] args)`**

Main program to to generate all subsets of the current set that sum to zero.

 * **Parameters:** `args` — No argument required

**`public SubsetSum(int[] numbers)`**

Create a subset sum algorithm bound to this set.

 * **Parameters:** `numbers` — List

**`public ArrayList<ArrayList<Integer>> run()`**

Run the subset sum algorithm.

 * **Returns:** List of all eligible subsets
